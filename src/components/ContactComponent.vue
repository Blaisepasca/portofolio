<template>
    <div class="contact" id="contact">
        <div class="itemsContact">
            <a href="#" class="c-item" title="Facebook"><img src="../assets/facebook.png"></a>
            <a href="mailto:blaiseaganzepascal10@gmail.com" class="c-item" title="Email"><img src="../assets/email.png"></a>
            <a href="#" class="c-item" title="Github"><img src="../assets/github.png"></a>
            <a href="#" class="c-item" title="Instagram"><img src="../assets/instagram.png"></a>
        </div>
        
    </div>
    <div class="footer">
          Make with love by Blaise Pascal &copy; 2024
      </div>
  </template>
  
  <script>
    export default {
    name: 'ContactComponent',
    components: {
  
  
    }
  }
  </script>
  
  <style>
 .contact{
    width: 100%;
    height: 300px;
    background-color: #06171F;
    margin-top: 30px;
    position: relative;
    padding-top: 300px;
 }
 .itemsContact{
    width: 400px;
    height: 50px;
    margin: auto;
 }
 .footer{
  width: 100%;
  height: 40px;
  text-align: center;
  line-height: 40px;
  color: white;
  background-color: #06171F;
 }
  </style>