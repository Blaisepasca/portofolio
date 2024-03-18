<template>
   <div class="home">
    <p>Hello I'm</p>
    <h1>Blaise Aganze pascal </h1>
    <p>Front-end Developer</p>

    <div class="btn">
        <button>Visit My Projects</button>
    </div>
    <div class="sociauxmedia">
        <div>
            <img src="../assets/facebook_30px.png" >
        </div>
        <div>
            <img src="../assets/github_30px.png" >
        </div>
        <div>
            <img src="../assets/Gmail Logo_30px.png">
        </div>
        <div>
            <img src="../assets/instagram_30px.png">
        </div>
        
    
    </div>
   </div>
  
 
</template>

<script>



export default {
  name: 'PortofolioHome',
  components: {
   
    
  }
}
</script>

<style>
.home{
    width: 100%;
    height: 80vh;
    background-color:#5D5E5E;
   
}

.sociauxmedia{
    display: flex;
    margin-top: 200px;
   
}
 

</style>
