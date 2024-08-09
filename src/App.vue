<template>
  <div id="app">
    <NavigationBar />
    <JumboTron/>
    <CTA/>
    <CardMultiple/>
    <FootSite/>
  </div>
</template>

<script>

import CTA from './components/CTA.vue'
import NavigationBar from './components/NavigationBar.vue'
import JumboTron from './components/JumboTron.vue'
import CardMultiple from './components/Cards.vue'
import FootSite from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavigationBar,
    JumboTron,
    CTA,
    CardMultiple,
    FootSite,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
