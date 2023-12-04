<script>
import AppHeader from './components/AppHeader.vue';
import mainPage from './components/mainPage.vue';
import AppFooter from './components/AppFooter.vue';
import AppMarketing from './components/AppMarketing.vue';

export default {
  data(){
    return {
        
    }
  },

  components: {AppHeader, mainPage, AppFooter, AppMarketing },
}
</script>

<template>
  <AppHeader />
  <mainPage />
  <AppMarketing />
  <AppFooter />
</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";
</style>
