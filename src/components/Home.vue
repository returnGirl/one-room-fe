<template lang='jade'>
div.home
  div.main
    RightBar
    div.pt-80.pb-100
      h1 一室|一种个性化的生活方式
      div(class='search').mt-30
        Input(v-model='keyword' placeholder="请输入..." id='keyword')
        Button(type='primary' icon='ios-search') SEARCH
  div.images.mt-40.pb-100
    Row
      Col(span='6')
        img(src='../assets/placehold.png')
      Col(span='6')
        img(src='../assets/placehold.png')
      Col(span='6')
        img(src='../assets/placehold.png')
      Col(span='6')
        img(src='../assets/placehold.png')
    //- Carousel(v-model='value1' autoplay)
    //-   Carousel-item
    //-     div.demo-carousel 1
    //-   Carousel-item
    //-     div.demo-carousel 2
    //-   Carousel-item
    //-     div.demo-carousel 3
    //-   Carousel-item
    //-     div.demo-carousel 4
  div.jiaju
    div.tc.p-30.bw.title
      h1 家具分类
    div.image.pt-40.pb-40
      Row
        Col(span='12')
          img(src='../assets/placehold.png')
        Col(span='6')
          img(src='../assets/placehold.png')
        Col(span='6')
          img(src='../assets/placehold.png')
      Row
        Col(span='6')
          img(src='../assets/placehold.png')
        Col(span='6')
          img(src='../assets/placehold.png')
        Col(span='12')
          img(src='../assets/placehold.png')  
  div.recommend
    div.tc.p-30.bw.title
      h1 热门推荐
    Row.pt-40.pb-40
      Col(span='8')
        img(src='../assets/placehold.png')
      Col(span='8')
        img(src='../assets/placehold.png')
      Col(span='8')
        img(src='../assets/placehold.png')
  div.cooperation
    div.tc.p-30.bw.title
      h1 品牌合作
    div.image.pt-40.pb-40
      Row
        Col(span='8')
          img(src='../assets/placehold.png')
        Col(span='8')
          img(src='../assets/placehold.png')
        Col(span='8')
          img(src='../assets/placehold.png')
      Row.pt-20
        Col(span='8')
          img(src='../assets/placehold.png')
        Col(span='8')
          img(src='../assets/placehold.png')
        Col(span='8')
          img(src='../assets/placehold.png')
</template>

<script>
import RightBar from './RightBar'
export default {
  name: 'home',
  data () {
    return {
      keyword: '',
      value1: 1
    }
  },
  components: {
    RightBar
  }
}
</script>

<style lang="sass" scoped>
.title
  border: 2px solid #d7d3d3
.home
  background-color: #F2F2F2
.main
  overflow: auto
#keyword
  width: 400px
  margin-right: 10px
.demo-carousel
  height: 200px
  background-color: #506b9e
  width: auto
</style>
