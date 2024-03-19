<template>
   <div class="home">
     <div class="intro">
    <div class="present">Hello I'm</div>
    <div class="boula">Blaise Aganze pascal </div>
    <div class="present">Front-end Developer</div>

    <div class="btnn">
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
    padding-top: 150px;
    background-color:#06171F;
    
   
}
.intro{
    height: 350px;
    width: 600px;
    margin-left: 100px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    
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
    margin-bottom: 1px;
}
button{
    background-color: #7A1B13; 
    margin-top: 10px;
    padding-top:10px;
    padding-bottom: 10px;
    padding-right: 15px;
    padding-left: 15px;
    border-radius: 35px;
    border: none;   

}
button a{
    text-decoration: none;
    color: white;
    text-transform: uppercase;
}
button:hover{
    background-color: #FC3727;
}
 

</style>
