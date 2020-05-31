<!DOCTYPE html>
<html>
    <head>
         <title> Responsive Layout </title>
        <style>
           *{
              box-sizing:border-box;
          }
          h1{
              text-align:center;
              margin-bottom:70px;
          }
          p{
            border:1px solid black;
            background-color:gray;
            width:90%;
            height:150px;
          margin-left:auto;
          color:white;
          }
          @media(min-width:120px;){
           .col-lg-1,.col-lg-2,.col-lg-3{
            float:left;
            border:1px solid black;
          
  } 
  .col-lg-1{
                    width:33.33%;
          }
  .col-lg-2{
                  width:66.66%;
  }
  .col-lg-3{
                  width:99.99%;
  }
   @media(min-width:120px;){
           .col-md-1,.col-md-2,.col-md-3{
            float:left;
            border:1px solid black;
          
  } 
  .col-md-1{
                    width:33.33%;
          }
  .col-md-2{
                  width:66.66%;
  }
  .col-md-3{
                  width:99.99%;
  }
  
  .ram{
        text-align:right;
        width:15px;
        background-color:pink;
        color:black;
  }
   }
  </style>
   </head>
   
<body>
  
  <h2>our menu</h2>
  <div class="row"> 
  <div class="col-lg-2 col-md-6">
  <p> lorem ipsum dolar sit amet,consectur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore manga aliqua. Ut enim ad minim veniam, qquis nostrud exercitation.</p>
    </div>
   <div class="col-lg-2 col-md-6">
     <p class="ram">Chicken </p>
  <p> lorem ipsum dolar sit amet,consectur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore manga aliqua. Ut enim ad minim veniam, qquis nostrud exercitation.</p>
    </div>
   <div class="col-lg-2 col-md-6">
  <p> lorem ipsum dolar sit amet,consectur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore manga aliqua. Ut enim ad minim veniam, qquis nostrud exercitation.</p>
    </div>
  </div>
</body>
  </html>
