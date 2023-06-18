<template>
  <div>
    <HeaderApp />
    <JumboTron />
    <MainApp />
    <FooterApp />
  </div>
</template>


<script>

import HeaderApp from './components/HeaderApp.vue';
import JumboTron from './components/JumboTron.vue';
import MainApp from './components/MainApp.vue';
import FooterApp from './components/FooterApp.vue';

export default {
  name : 'App',

  components : {
    HeaderApp,
    JumboTron ,
    MainApp,
    FooterApp,




  }


}
</script>


<style lang="scss">
  @import './styles/general.scss';
</style>