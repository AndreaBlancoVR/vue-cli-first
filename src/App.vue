<template>
  <div id="app">
    <TitleSample />
  </div>
</template>

<script>
import TitleSample from './components/TitleSample.vue'

export default {
  name: 'App',
  components: {
    TitleSample
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
