<template>
  <div class="container">
    <Nuxt/>
  </div>
</template>

<style lang="stylus">
html
  font-family 'Open Sans'
  font-size 16px
  word-spacing 1px
  -ms-text-size-adjust 100%
  -webkit-text-size-adjust 100%
  -moz-osx-font-smoothing grayscale
  -webkit-font-smoothing antialiased
  -webkit-tap-highlight-color rgba(0, 0, 0, 0)
  font-variant-ligatures no-common-ligatures
  box-sizing border-box
  color $green

*, *:before, *:after
  box-sizing border-box
  margin 0

.container
  min-height 100vh
  display flex
  justify-content center
  align-items center
  text-align center

.button--grey
  display inline-block
  border-radius 4px
  border 1px solid #2E495E
  color #2E495E
  text-decoration none
  padding 10px 30px
  margin-left 15px

  &:hover
    color #fff
    background-color #2E495E
</style>
