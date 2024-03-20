<template>
    <div class="About">
        <div class="container">
            <div class="img">
                <img src="../assets/bl.jpeg" width="300" alt="">
            </div>
            <div class="infos">
                <div class="names">Blaise Aganze pascal</div>
                <div class="description">Front-end Developer</div>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nobis animi, at reprehenderit
                     illo atque eveniet aut ullam natus molestiae nam optio
                     sapiente deserunt. Consequuntur dolore vero voluptate numquam debitis hic.</p>

                     <button class="btn"><a href="#">DOWNLOAD CV</a></button>
            </div>
        </div>
        <div class="skills" >
            <div class="logoss">
            <img src="../assets/html_5_30px.png" >
            <img src="../assets/css3_30px.png" >
            <img src="../assets/javascript_30px.png" >
            <img src="../assets/vue_js_30px.png">
            <img src="../assets/php_logo_30px.png">
            <img src="../assets/mysql_logo_30px.png">
            </div>
        </div>
       
    </div>
 
</template>

<script>



export default {
  name: 'AboutPortfolio',
  components: {
   
    
  }
}
</script>



<style>
.About{
    width: 100%;
    height:auto;
    padding-bottom: 30px;
   
    
}
.container{
    width: 80%;
    height: 200px;
    margin-left: 10%;
    padding-top: 80px;
    display: inline-flex;
      
}
img{
    box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3) ;
    
}
.infos{
    margin-left: 30px;
}
.names{
    font-size: 30px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.description{
    font-size: 17px;
    color: #B0B0B0;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.btn{
    background-color: #7A1B13;
}
.btn a{
    text-decoration: none;
}
.btn:hover{
    background-color: #FC3727;
}
.skills{
    width: 100%;
    height: 50px;
    
}
.logoss{
    width: 30%;
    margin: auto;
    margin-top: 15px;
    
}




</style>
