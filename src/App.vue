<template>
  <div id="app">
    <Header1 />
    <Header />
    <Main />
    <Footer />
    <Footer2 />
  </div>
</template>

<script>
import Header1 from '@/components/Header1.vue';
import Header from '@/components/Header.vue';
import Main from '@/components/Main.vue';
import Footer from '@/components/Footer.vue';
import Footer2 from '@/components/Footer2.vue';

export default {
  name: 'App',
  components: {
    Header1,
    Header,
    Main,
    Footer,
    Footer2,
  }
}
</script>

<style lang="scss">
* {
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
  font-family: sans-serif;
}

#app {
  cursor: crosshair;
  height: 100%;
}
</style>
