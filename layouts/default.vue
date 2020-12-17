<template>
  <main id="__body">
    <NavBar />
    <nuxt id="__content" />
    <!-- <Footer id="__footer" /> -->
  </main>
</template>

<script>
import Vue from 'vue'
import NavBar from '~/components/NavBar.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    NavBar,
    Footer,
  },
}
</script>

<style lang="scss">
@import '~/assets/styles.scss';
// #__content {
//   margin-top: 80px;
// }
</style>
