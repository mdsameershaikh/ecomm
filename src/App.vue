<template>
  <div id="app">
    <page-head />

  </div>
</template>

<script>
import page_head from './components/page-head.vue'

export default {
  name: 'App',
  components: {
    'page-head': page_head
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
  margin-top: 60px;
}
</style>
