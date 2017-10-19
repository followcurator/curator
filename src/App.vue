<template>
  <div id="app">
    <reserve-modal v-show="true" @close="showModal=false"></reserve-modal>
    <site-header>things</site-header>
    <router-view></router-view>
      <div class="left-wave"></div>
      <div class="right-wave"></div>
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
    position: relative;
  }
.right-wave {
  position: absolute;
  z-index: -1;
  left: 0;
  width: 100%;
  height: 75%;
  top: 25%;
  background-size: cover;
  background-image: linear-gradient(114deg, #835fdc, #4c31b5);
  background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/rightwave.svg');
}

.left-wave {
  position: absolute;
  z-index: -1;
  left: 0;
  width: 100%;
  top: 39.1%;
  height: 60.9%;
  background-size: cover;
  background-image: linear-gradient(114deg, #835fdc, #4c31b5);
  background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/leftwave.svg');
}
</style>
