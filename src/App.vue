<script>
import AppHeader from './components/AppHeader.vue';
import mainPage from './components/mainPage.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data(){
    return {

    }
  },

  components: {AppHeader, mainPage, AppFooter }
}
</script>

<template>
  <AppHeader />
  <MainPage />
  <AppFooter />
</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";
</style>
