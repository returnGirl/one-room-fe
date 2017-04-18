<template lang='jade'>
footer(class='footer')
  Row
    Col(span='8').tl
      h1 关于一室
      p Lorem ipsum dolor sit amet.Lorem ipsum dolor sit ametLorem ipsum dolor sit ametLorem ipsum dolor sit ametLorem ipsum dolor sit ametLorem ipsum dolor sit amet
      h2 地址
      p 文本标签
      h2 邮箱
      p 文本标签
    Col(span='8').tl
      h1 帮助中心
      h2 了解我们
      h2 常见问题
      h2 联系我们
      h2 用户协议
    Col(span='8').tl
      h1 商业合作
      h2 商业合作
      h2 加入我们
  
</template>

<script>
export default {
  name: 'footer'
}
</script>

<style lang="sass" scoped>
footer
  border-top: 2px solid #bdbaba
  padding: 10px 40px 30px 40px
  background-color: #D7D7D7
  h1, h2
    margin-top: 20px
</style>
