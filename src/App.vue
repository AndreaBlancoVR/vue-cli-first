<template>
  <div id="app">
    <TitleSample />
    <JumboSample />
  </div>
</template>

<script>
import TitleSample from './components/TitleSample.vue'
import JumboSample from './components/JumboSample.vue'

export default {
  name: 'App',
  components: {
    TitleSample,
    JumboSample
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
