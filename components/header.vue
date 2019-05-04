<template lang="pug">
div.header
  span.title Zilch Editor Community
  div.menu_container
    ul.menu
      li: nuxt-link(to='/') 首页
      li: nuxt-link(to='/download') 下载
      li: nuxt-link(to='/document') 文档
      li: nuxt-link(to='/plugin') 插件
      li: nuxt-link(to='/project') 作品
      li: nuxt-link(to='/me') 我
</template>

<style lang="stylus">
header_background_color = #42a5f5
title_font_color = #ffffff
menuitem_hover_backgouund_color = #90caf9

.header
  position sticky
  top 0px
  left 0px
  display flex
  width 100%
  font-weight 100
  color title_font_color
  background-color header_background_color

.title
  flex 1
  font-size 150%
  line-height 50px
  margin-left 3em

.menu_container
  flex 2

.menu
  float right
  display flex
  width 100%
  height 50px

.menu li
  float left
  display flex
  width 100%
  font-size 120%
  line-height 50px
  text-align center
  list-style none
  cursor pointer
  transition-duration 0.3s

.menu li:hover
  background-color menuitem_hover_backgouund_color

.menu li *
  width 100%
  height 100%
</style>


