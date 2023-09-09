<template>
  <NavBar navName="My Store"/>
  <HomePage />
  <SalePage />
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeroPage from './components/HeroPage.vue'
import SalePage from './components/SalePage.vue'
export default {
  components: {
    'NavBar': NavBar,
    'HomePage': HeroPage,
    'SalePage': SalePage
  },
  data() {
    return {
      navName: " "
    };
  }
};


</script>

<style>
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
</style>