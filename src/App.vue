<template>
  <div id="app">
    <ParentComponent />
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    ParentComponent: () => import('./components/ParentComponent.vue')
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
