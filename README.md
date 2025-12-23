<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      .container {
        border: 5px solid black;
     display: flex;
        height: 30vh;
        width: 40vw;
         
          
      }

      .container > div {
        width: 100px;
        color: white;
        height: 100px;
        
    
        
      }

      .box-1 {
        background-color: red;
        align-self: self-start;
      }

      .box-2 {
        background-color: green;
        align-self: self-end;
      }

      .box-3 {
        background-color: rgb(230, 230, 28);
         align-self: self-start;
      }

      .box-4 {
        background-color: blue;
        align-self: self-end;
      }

      .box-5 {
        background-color: blueviolet;
         align-self: self-start;
      }

      .box-6 {
        background-color: rgb(27, 161, 143);
        align-self: self-end;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="box-1">1</div>
      <div class="box-2">2</div>
      <div class="box-3">3</div>
      <div class="box-4">4</div>
      <div class="box-5">5</div>
      <div class="box-6">6</div>
    </div>
  </body>
</html>
