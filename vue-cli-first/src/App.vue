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
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  margin-top: 60px;
}
</style>
