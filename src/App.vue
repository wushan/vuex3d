<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
@import 'assets/styles/normalize';
html {
  font-size: 100%;
  line-height: 1.4;
  font-family: 'Proxima Nova', 'Avenir', Helvetica, Arial, sans-serif;
}
#app {
  font-family: 'Proxima Nova', 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
