<template>
  <div id="app">
    <app-header></app-header>
    <router-view />
  </div>
</template>
<script>
import AppHeader from "@/components/common/AppHeader";
export default {
  components: {
    AppHeader
  }
};
</script>
<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
</style>
