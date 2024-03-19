<template>
      <div class="navbar">
        <div class="items">
            <li class="item"><a href="#">Home</a></li>
            <li class="item"><a href="#">About</a></li>
            <li class="item"><a href="#">Projects</a></li>
            <li class="item"><a href="#">Contacts</a></li>
        </div>
      </div>
   
  </template>
  
  <script>
  
  
  
  export default {
    name: 'HomeNavbar',
    components: {
     
      
    }
  }
  </script>
  
  <style>
  .navbar{
    width: 100%;
    height: 80px;
    background-color: #06171F;
    display: flex;
    justify-content: end;
    
  }
  .items{
    width:'40%';
    display: inline-flex;
    padding-right: 80px;
    height: 80px;
    line-height: 80px;
    
  }
  .items li {
    list-style: none;
    margin-right: 35px;
   
    
  }
  .items li a{
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 15px;
  }
  .items li a:hover {
    color: #FC3727;
  }
  
  </style>
  