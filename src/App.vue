<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Header'
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
app {
  display: flex;
  flex-direction: row;
}
</style>
