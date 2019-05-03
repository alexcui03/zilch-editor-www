<template lang="pug">
div.header
  div.header_c
    span.title Zilch Editor Community
    ul.menu
      li: nuxt-link(to='/') 首页
      li: nuxt-link(to='/download') 下载
      li: nuxt-link(to='/plugin') 插件
      li: nuxt-link(to='/project') 作品
      li: nuxt-link(to='/me') 我
</template>

<style lang="stylus">
header_background_color = #ffb11b

.header
  width 100vw
  background-color header_background_color

.title
  font-size 150%
  margin-left 15%
  line-height 2em
  vertical-align middle

.menu
  position absolute
  right 15%
  display inline-block
  vertical-align middle

.menu li
  list-style none
  float left
  padding 0.5em

</style>


