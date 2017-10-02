<template>
  <div id="app">
    <!-- <contact-modal></contact-modal> -->
    <!-- <site-header></site-header> -->
    <router-view></router-view>
    <!-- <site-footer></site-footer> -->
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
    height: 150vh;
    font-family: 'Nunito', sans-serif;
    margin: 0px;
    padding: 0px;
    /*min-height: 100vh;*/
    position: relative;
    /*padding-bottom: 14.8rem;*/
  }
</style>
