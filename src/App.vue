<template>
  <div>
    <HomeNavbar/>
    <PortofolioHome/>
    <AboutPortfolio/>
    <ProjectComponents/>
  </div>
</template>

<script>
import AboutPortfolio from './components/AboutPortfolio.vue'
import HomeNavbar from './components/HomeNavbar.vue'
import PortofolioHome from './components/PortofolioHome.vue'
import  ProjectComponents from './components/ProjectComponents.vue'

export default {
  name: 'App',
  components: {
    HomeNavbar,
    PortofolioHome,
    AboutPortfolio,
    ProjectComponents
    
  }
}
</script>

<style>

</style>./components/AboutPortofolio.vue
