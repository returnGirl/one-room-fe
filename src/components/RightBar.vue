<template lang='jade'>
div.fr.right-bar
  Menu(theme='light')
    Menu-item(name='shoppingCar')
      Icon(type='ios-cart')
      购物车
    Menu-item(name='shoucang')
      Icon(type='document-text')
      我的收藏
    Menu-item(name='advice')
      Icon(type='document-text')
      反馈建议
    Menu-item(name='service')
      Icon(type='document-text')
      客服

  
</template>

<script>
export default {
  name: 'rightBar'
}
</script>

<style lang="sass" scoped>
.right-bar
  ul.ivu-menu
    border: 2px solid #d7d3d3
    border-right: none
    width: 150px !important
    margin-top: 20px
    li
      margin-bottom: 20px


</style>
