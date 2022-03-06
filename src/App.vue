<template>

  <SideBar></SideBar>
  <WrapperTop></WrapperTop>
</template>

<script>

import SideBar from './components/SideBar.vue'
import WrapperTop from './components/WrapperTop.vue'

export default {
  name: 'App',
  components: {
    SideBar,
    WrapperTop
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
