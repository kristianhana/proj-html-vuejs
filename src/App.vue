<script>
import AppHeader from './components/AppHeader.vue';
import mainPage from './components/mainPage.vue';
import AppMarketing from './components/AppMarketing.vue';
import TipsTricks from './components/TipsTricks.vue';
import AppFooter from './components/AppFooter.vue';



export default {
  data(){
    return {
        
    }
  },

  components: {AppHeader, mainPage, AppMarketing, TipsTricks,  AppFooter },
}
</script>

<template>
  <AppHeader />
  <mainPage />
  <AppMarketing />
  <TipsTricks />
  <AppFooter />
</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";
</style>
