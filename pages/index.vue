<template>
  <section>
    <div>
      <Logo :width="350"/>
      <h1 class="title">
        NUXT
        <span class="green">JS</span>
      </h1>
      <h2 class="subtitle">Starter for CodeSandBox</h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--grey">Documentation
          <IconLink/>
        </a>
        <NLink to="/about" class="button--grey">About</NLink>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";
import IconLink from "~/components/IconLink.vue";

export default {
  components: {
    Logo,
    IconLink
  }
};
</script>

<style scoped lang="stylus">
@import '../assets/vars/*'

.title
  font-family 'Open Sans'
  display block
  font-weight 400
  font-size 100px
  letter-spacing 1px
  font-size 6em
  color $lightgreen

.green
  color $green

.subtitle
  font-weight 300
  font-size 3em
  color #2E495E
  word-spacing 5px
  padding-bottom 15px

.links
  padding-top 15px
</style>
