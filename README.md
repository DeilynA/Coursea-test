# Coursea-test
Coursea test repository

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Our Menu</title>
<style>

/.......... Base styles ........../
. {
box-sizing: border-box;
}
h1 {
margin-bottom: 15px;
}

p {
border: 1px solid black;
background-color: #d3d3d3;
width: 90%;
height: 150px;
margin-right: auto;
margin-left: auto;
font-family: cursive;
color: solid black;
}

/* simple responsive framework */
.row {
  width:100%;
  }
  
  /********** large devices only **********/
  @media (min-width: 1200px) {
    .col-lg-1, .col-lg-2, .col-lg-3{
      float: left;
    }
    .col-lg-1 {
      width: 33.3%;
    }
    .col-lg-2 {
      width: 50% ;
    }
    .col-lg-3{
      width: 100%;
    }

    /********** Medium devices only **********/
    @media (min-width: 970px) and (max-width: 1199px) {
      .col-md-1, .col-md-2, .col-md-3 {
        float: left;
      }
      .col-md-1{
        width: 33.3px;
      }
      .col-md-2{
        width: 50%;
      }
      .col-md-3{
        width: 100%;
      }

  </style>
</head>
<body>
  <h1>Our Menu</h1>

  <div class="row">
    <div class="col-lg-3 col-md-3"><p> Chicken             Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
    <div class="col-lg-2 col-md-2"><p> Beef                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>
    <div class="col-lg-1 col-md-1"><p>Sushi                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></div>   
  </div>


</body>
</html>

    
