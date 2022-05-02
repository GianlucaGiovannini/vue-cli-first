<template>
  <div id="app">
  <Titolo/>
  <JumboTron/>
  </div>
</template>

<script>
import Titolo from './components/TitleComponent.vue'
import JumboTron from './components/JumboComponent.vue'

export default {
  name: 'App',
  components: {
    Titolo,
    JumboTron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
