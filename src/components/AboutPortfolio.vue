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
    height: 500px;
    
}
.container{
    width: 80%;
    height: 400px;
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


</style>
