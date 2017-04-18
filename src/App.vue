<template>
  <div id="app">
    <Navbar></Navbar>
    <div class='main-content'>
      <router-view></router-view>
    </div>
    <Foot></Foot>
  </div>
</template>

<script>
import Navbar from './components/Nav'
import Foot from './components/Footer'
export default {
  data () {
    return {
      radio: true
    }
  },
  name: 'app',
  components: {
    Navbar,
    Foot
  }
}
</script>

/*测试*/
<style lang='sass'>
#app
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

//原子类
.bw
  background-color: white
.tc
  text-align: center
.tl
  text-align: left
.tr
  text-align: right

.fl
  float: left
.fr
  float: right

@for $i from 1 through 20
  .p-#{5*$i}
    padding: (5 * $i) + px
  .pl-#{5*$i}
    padding-left: (5 * $i) + px
  .pr-#{5*$i}
    padding-right: (5 * $i) + px
  .pb-#{5*$i}
    padding-bottom: (5 * $i) + px
  .pt-#{5*$i}
    padding-top: (5 * $i) + px
  .m-#{5*$i}
    margin: (5 * $i) + px
  .ml-#{5*$i}
    margin-left: (5 * $i) + px
  .mr-#{5*$i}
    margin-right: (5 * $i) + px
  .mb-#{5*$i}
    margin-bottom: (5 * $i) + px
  .mt-#{5*$i}
    margin-top: (5 * $i) + px
</style>
