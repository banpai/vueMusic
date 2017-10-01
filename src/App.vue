<template>
  <div id="app">
    <div class="m-header">地hi福啊好</div>
    <img src="./common/images/logo.png">
    <router-view></router-view> 
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
@import "~common/stylus/variable"
.m-header
    color: $color-background
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
