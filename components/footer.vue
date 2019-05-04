<template lang="pug">
div.footer
  p.copyright
    | Copyright © 2019&nbsp;
    a(href='blog.alexcui.top') Alex Cui
    | . All rights reserved.
  ul.link_list
    li: a(href='https://github.com/alexjason/zilch-editor-www') Github
  ul.link_list
    li: a(href='#') Clip社区
    li: a(href='#') SS社区网络
    li: a(href='#') 别针团队
    li: a(href='#') 蓝柠工作室
</template>

<style lang="stylus">
footer_background_color = #42a5f5
text_font_color = #ffffff

.footer
  width 100%
  height 90px
  padding-top 10px
  color text_font_color
  background-color footer_background_color
  text-align center
  font-weight 100

.copyright
  margin-bottom 5px

.link_list
  padding 0px

.link_list li
  list-style none
  display inline

.link_list li:after
  content ' | '

.link_list li:last-child:after
  content ''
</style>
