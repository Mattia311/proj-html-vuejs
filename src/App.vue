<template>
  <div id="app">
    <SiteHeader/>
    <SiteMain/>
    <SiteFooter/>
    
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue';
import SiteMain from './components/SiteMain.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
  }
}
</script>

<style lang="scss">
@import "../node_modules/bootstrap/scss/bootstrap.scss";
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css');
</style>
