<template>
    <div class="project">
      <div class="projectimage">Image</div>
      <div class="projectdescrp">
        <div class="titles">
            project title
        </div>
        <div class="description">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad perspiciat</div>
        <div class="language">
            <div class="langue">PHP</div>
            <div class="langue">js</div>

        </div>

      </div>
    </div>
  </template>
  
  <script>

  
  export default {
    name: 'ProjectComponents',
    components: {
      
      
    }
  }
  </script>
  
  <style>
  .project{
    width: 100%;
    height: 400px;
    background-color: red;
    display: inline-flex;
    height: 300px;
    
    
  }
  .projectimage{
    width: 30%;
    height:300px;
    background-color: blue;
  }
  .projectdescrp{
    width: 70%;
    height:300px;
    background-color: yellow;
  }
  
  </style>
  