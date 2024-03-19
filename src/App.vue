<template>
  <div>
    <HomeNavbar/>
    <PortofolioHome/>
    <AboutPortfolio/>
  </div>
</template>

<script>
import AboutPortfolio from './components/AboutPortfolio.vue'
import HomeNavbar from './components/HomeNavbar.vue'
import PortofolioHome from './components/PortofolioHome.vue'

export default {
  name: 'App',
  components: {
    HomeNavbar,
    PortofolioHome,
    AboutPortfolio,
    
  }
}
</script>

<style>

</style>./components/AboutPortofolio.vue
