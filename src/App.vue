<template>
  <div id="app">
    <Header/>
    <Content/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/macro/Header.vue'
import Content from './components/macro/Content.vue'
import Footer from './components/macro/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Footer
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
</style>
