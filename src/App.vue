<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style rel="stylesheet/scss" lang="scss" scoped>
  @import "assets/scss/reset";
  #app {
    color: #333;
  }
</style>
