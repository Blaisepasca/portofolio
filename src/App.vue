<template>
  <div>
    <HomeNavbar/>
 <PortofolioHome/>
  </div>
</template>

<script>
import HomeNavbar from './components/HomeNavbar.vue'
import PortofolioHome from './components/PortofolioHome.vue'

export default {
  name: 'App',
  components: {
    HomeNavbar,
    PortofolioHome,
    
  }
}
</script>

<style>

</style>
