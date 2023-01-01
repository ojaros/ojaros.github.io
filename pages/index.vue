<!-- To update code, commit and push changes on master then run 
yarn generate yarn deploy on master --> 

<template>
  <main class="main">
    <section class="section bg-hero">
      <Hero />
    </section>

    <section class="section bg-about">
      <Introduction />
    </section>

    <section class="section bg-experience">
      <Experience />
    </section>

    <section class="section bg-projects">
      <Projects />
    </section>

    <Footer />
  </main>
</template>

<script>
import Introduction from '~/components/Introduction.vue'
import Experience from '~/components/Experience.vue'
import Footer from '~/components/Footer.vue'

export default {}
</script>

<style lang="scss">
@import '~/assets/styles.scss';

.main {
  height: 100vh;
  perspective: 2px;
  overflow-x: hidden;
  overflow-y: auto;
  scroll-behavior: smooth;
}

.section {
  position: relative;
  height: auto;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: center;
  padding-top: 70px;
  padding-bottom: 70px;
}

.static-three {
  background-color: #c06c84;
}

.parallax::after {
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-size: cover;
  transform: translateZ(-1px) scale(1.5);
  z-index: -1;
}

.bg-hero {
  background-image: url('/images/lib.jpg');
  background-attachment: fixed;
  background-size: cover;
}
.bg-about {
  background: #f0f2f2;
}
.bg-experience {
  background-color: #fff;
}
.bg-projects {
  background-color: #f0f2f2;
}
</style>
