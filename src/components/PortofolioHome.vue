<template>
   <div class="home" id="home">
     <div class="intro">
    <div class="present">Hello I'm</div>
    <div class="boula">Blaise Aganze pascal </div>
    <div class="present">Front-end Developer</div>

    <div class="btnn">
        <button><a href="ProjectComponents.vue">Visit My Projects</a></button>
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
    <div>
        <div class="wave"></div>
        <div class="wave"></div>
        <div class="wave"></div>
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
    /* background-color:#06171F; */
    
    margin: auto;
    font-family: -apple-system, BlinkMacSystemFont, sans-serif;
    overflow: auto;
    background: linear-gradient(315deg, rgba(21,70,107,1) 3%, rgba(12,45,61,1) 38%, rgba(6,23,31,1) 68%, rgba(6,23,31,1) 98%);
    animation: gradient 15s ease infinite;
    background-size: 400% 400%;
    background-attachment: fixed;
}
@keyframes gradient {
    0% {
        background-position: 0% 0%;
    }
    50% {
        background-position: 100% 100%;
    }
    100% {
        background-position: 0% 0%;
    }
}

.wave {
    background: rgb(255 255 255 / 25%);
    border-radius: 1000% 1000% 0 0;
    position: fixed;
    width: 200%;
    height: 12em;
    animation: wave 10s -3s linear infinite;
    transform: translate3d(0, 0, 0);
    opacity: 0.8;
    bottom: 0;
    left: 0;
    z-index: -1;
}

.wave:nth-of-type(2) {
    bottom: -1.25em;
    animation: wave 18s linear reverse infinite;
    opacity: 0.8;
}

.wave:nth-of-type(3) {
    bottom: -2.5em;
    animation: wave 20s -1s reverse infinite;
    opacity: 0.9;
}

@keyframes wave {
    2% {
        transform: translateX(1);
    }

    25% {
        transform: translateX(-25%);
    }

    50% {
        transform: translateX(-50%);
    }

    75% {
        transform: translateX(-25%);
    }

    100% {
        transform: translateX(1);
    }
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
