<template>
  <div id="app">
    <reserve-modal v-show="false" @close="showModal=false"></reserve-modal>
    <site-header>things</site-header>
    <router-view></router-view>
    <site-footer></site-footer>
  </div>
</template>

<script>
import siteHeader from '@/components/SiteHeader';
import siteFooter from '@/components/SiteFooter';
import reserveModal from '@/components/ReserveModal';
export default {
  name: 'app',
  components: {
    siteHeader,
    siteFooter,
    reserveModal
  },
 data: {
    showModal: false
  }
}
</script>

<style>
@import './styles/main.scss';
@import './styles/_variables.scss';
  #app {
    min-height: 100vh;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    position: relative;
  }


.leftwave {
    width: 1440px;
    height: 701.2px;
    position: absolute;
    margin-top: 40rem;
    z-index: -1;
    /*object-fit: contain;*/
    background-image: linear-gradient(114deg, #835fdc, #4c31b5);
}
</style>
