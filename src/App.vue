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
@import './styles/main.scss';
#app {
    min-height: 100%;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    position: relative;
  }
</style>
