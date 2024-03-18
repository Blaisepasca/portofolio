<template>
   <div class="home">
     <div class="intro">
    <div class="present">Hello I'm</div>
    <div class="boula">Blaise Aganze pascal </div>
    <div class="present">Front-end Developer</div>

    <div class="btn">
        <button><a href="#">Visit My Projects</a></button>
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
.intro{
    height: 350px;
    width: 600px;
    margin-left: 100px;
    background-color: red;
}

.sociauxmedia{
    display: flex;  
}
img{
    margin: 15px;
}
.boula{
    font-size: 50px;
    color: white;
}
.present{
    font-size: 20px;
    color: white;
    margin-bottom: 10px;
}
button{
    background-color: blue; 
    margin-top: 5px;
    padding-top:5px;
    padding-bottom: 5px;
    padding-right: 10px;
    padding-left: 10px;
    border-radius: 35px;
    border: none;   

}
button a{
    text-decoration: none;
    color: white;
}
 

</style>
