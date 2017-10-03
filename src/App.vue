<template>
  <div id="app">
    <site-header>things</site-header>
    <router-view></router-view>
    <site-footer></site-footer>
  </div>
</template>

<script>
import siteHeader from '@/components/SiteHeader';
import siteFooter from '@/components/SiteFooter';
export default {
  name: 'app',
  components: {
    siteHeader,
    siteFooter,
  },
}
</script>

<style>
#app {
    height: 150vh;
    font-family: 'Nunito', sans-serif;
    margin: 0px;
    padding: 0px;
    min-height: 100vh;
    position: relative;
  }
</style>
