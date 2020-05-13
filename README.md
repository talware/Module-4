<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>module4-Assignments</title>
<style>
 
  *{
    box-sizing:content-box;
  }

    h1{
        text-align: center;
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        padding-top: 20px;
        /* padding-bottom: 20px; */
    }
  
    .row{
        width: 100%;
    }

    .border1{
      float: right;
      margin-top: -30px;
      margin-right: -10px;
      text-align: center;
      border: 1px solid black;
      background-color:yellowgreen;
      width: 80px;
      height: 20px;
    
    }
    .border2{
      float: right;
      margin-top: -30px;
      margin-right: -10px;
      text-align: center;
      border: 1px solid black;
      background-color: brown;
      color: cornsilk;
      width: 80px;
      height: 20px;
    
    }
    .border3{
      float: right;
      margin-top: -30px;
      margin-right: -10px;
      text-align: center;
      border: 1px solid black;
      background-color:teal;
      width: 80px;
      height: 20px;
    
    }

    @media (min-width: 992px){
        .col-lg-1, .col-lg-2, .col-lg-3 
        {
        float: left;
        border: 2px solid black;
        background-color:tomato;
        padding-top: 30px;
        padding-left: 10px;
        padding-right: 10px;
        margin-left: 20px;
        /* margin-right: 5px;  */
        margin-top: 30px; 
      }
        .col-lg-1 {
        width: 28.875%;
      }
        .col-lg-2 {
        width: 28.875%;
      }
        .col-lg-3 {
        width: 28.875%;
      }
    }

    @media (min-width: 768px) and (max-width: 991px) {
        .col-md-1, .col-md-2, .col-md-3 
        {
        float: left;
        border: 2px solid black;
        background-color: tomato;
        padding-top: 30px;
        padding-left: 10px;
        padding-right: 10px;
        margin-left: 10px;
        margin-top: 30px;
      }
      .col-md-1 {
        width: 45.37%;
      }
      .col-md-2 {
        width: 45.37%;
      }
      .col-md-3 {
        width: 95%;
      }
    }

    @media (max-width: 767px) {
        .col-sm-1, .col-sm-2, .col-sm-3 
        {
        float: left;
        border: 2px solid black;
        background-color: tomato;
        padding-top: 30px;
        padding-left: 10px;
        padding-right: 10px;
        margin-left: 10px;
        margin-top: 30px;
      }
      .col-sm-1 {
        width: 95%;
      }
      .col-sm-2 {
        width: 95%;
      }
      .col-sm-3 {
        width: 95%;
      }
    }
    

</style>

</head>
<body>
    <div>
        <h1 >Our Menu</h1>
    </div>

    <!-- <div id="container"> -->
      <div class="row">
        <div class="col-lg-1 col-md-1 col-sm-1">
          <p class="border1">Chicken</p>
            <p>What is Lorem Ipsum Lorem Ipsum is simply dummy 
               text of the printing and typesetting industry                  
                Ipsum has been the industry's standard dummy  
                ever since the 1500s when an unknown printer  
                galley of type and scrambled it to make a type 
                specimen book it has?
            </p>
        </div>

        <div class="col-lg-2 col-md-2 col-sm-2">
          <p class="border2">Beef</p>
            <p>What is Lorem Ipsum Lorem Ipsum is simply dummy 
               text of the printing and typesetting industry                  
               Ipsum has been the industry's standard dummy  
               ever since the 1500s when an unknown printer  
               galley of type and scrambled it to make a type 
               specimen book it has?
            </p>
        </div>

        <div class="col-lg-3 col-md-3 col-sm-3">
          <p class="border3">Sushi</p>
            <p>What is Lorem Ipsum Lorem Ipsum is simply dummy 
               text of the printing and typesetting industry                  
               Ipsum has been the industry's standard dummy  
               ever since the 1500s when an unknown printer  
               galley of type and scrambled it to make a type 
               specimen book it has?
            </p>
        </div>
      </div>  
    <!-- </div> -->
    
</body>
</html>
