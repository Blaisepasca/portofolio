<template>
    <div class="project">
      <div class="projectimage">Image</div>
      <div class="projectdescrp">
        <div class="titles">
            project title
        </div>
        <div class="descript">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad perspiciat
        </div>
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
    width: 80%;
    height: 400px;
    display: inline-flex;
    height: 300px;
    margin-left: 10%;
    border-radius: 10px;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
    background-color: #E6E6E6;
    font-family: Verdana;
  }
  .projectimage{
    width: 30%;
    height:300px;
    background-color: blue;
    border-radius: 10px;
  }
  .projectdescrp{
    width: 70%;
    height:300px;
    border-radius: 10px;
    padding: 10px;
  }
  .titles{
    font-size: 25px;
    margin-bottom: 10px;
  }
  .language{
    width: 100%;
    display: inline-flex;
    padding-top: 20px;
  }
  .langue{
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 10px;
    padding-right: 10px;
    border: 2px solid #ABABAB;
    border-radius: 5px;
    margin-right: 10px;
  }
  .descript{
    color: #3B3B3B;
    font-size: 16px;
  }
  
  </style>
  