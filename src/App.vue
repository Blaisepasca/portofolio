<template>
  <div>
    <HomeNavbar/>
    <PortofolioHome/>
    <AboutPortfolio/>
    <ProjectComponents/>
    <ContactComponent/>
  </div>
</template>

<script>
import AboutPortfolio from './components/AboutPortfolio.vue'
import HomeNavbar from './components/HomeNavbar.vue'
import PortofolioHome from './components/PortofolioHome.vue'
import  ProjectComponents from './components/ProjectComponents.vue'
import ContactComponent from './components/ContactComponent.vue'

export default {
  name: 'App',
  components: {
    HomeNavbar,
    PortofolioHome,
    AboutPortfolio,
    ProjectComponents,
    ContactComponent
    
  }
}
</script>

<style>

</style>./components/AboutPortofolio.vue
