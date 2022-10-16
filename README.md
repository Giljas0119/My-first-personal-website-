# My-first-personal-website-
My first personal website made in HTML/CSS

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <script src="https://kit.fontawesome.com/f0afb4fc0d.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
    <title>https://www.jai.com.ph</title>
  </head>
  <body>
<div class="box">
  <img src="images/profilepicture.png" alt="" class="box-img">
  <h1>Giljas Jair R. Cariño</h1>
  <h4>ABOUT ME</h4>
  <h5>From:Casinglot, Tagoloan Mis, Or</h5><h5>Born in: CagayanDe Oro City</h5><h5>Language(s): Bisaya,English,Tagolog</h5>
  <h5.Ethnicity: Filipino</h5>
<p>BSIT Student I may not be sharp but I am willing to learn and take responsibility</p>
<ul>
  SOCIALS
  <li><a href="https://www.facebook.com/jai.carinew0119"><i class="fa fa-facebook-square" style="color:white"><! -- icon --></i></i></a></li>
  <li><a href="https://www.tiktok.com/@jairino0119"><i class="fa-brands fa-tiktok" style="color:black"<! -- icon --></i></a></li>
  <li><a href="https://twitter.com/Jai66503906"><i class="fa fa-twitter-square" style="color:skyblue"<! -- icon --></i></a></li>
</div>
</body>
</html>

body{
  margin: 0;
  padding: 0;
  background: url("images/IMG_20221016_221651.jpg") no-repeat;
  background-size: 600px;
  background-position: center;
}
.box{
  width: 350px;
  background: rgba(0,0,0,0,4);
  padding: 40px;
  text-align: center;
  margin: auto;
  margin-top: 5%;
  color: white;
  font-family: Times New Roman;
}
.box-img{
  border-radius: 100%;
  width: 200px;
  height: 200px;
}
.box h1{
  font-size: 40px;
  font-style: Arial;
  letter-spacing: 2px;
  font-weight: 100;
  -webkit-text-stroke: 1px black;
}
.box h4{
  font-family: Arial;
  font-size: 40px;
  letter-spacing: 3px;
  color: orange;
  -webkit-text-stroke: 1.5px black;
}
.box h5{
  font-family: Arial;
  font-size: 20px;
  letter-spacing: 3px;
  color: black;
}
.box p{
  text-align: center;
  font-family: Comic Sans MS;
  font-size: 38px;;
  letter-spacing: 3px; 
  font-family: Times New Roman; color: white;
  -webkit-text-stroke: 1.5px black;
}
ul{
  margin: 0;
  padding: 0;
  font-size: 89px;
}
.box li{
  font-size: 30px;
  display: inline-block;
  margin: 6px;
  list-style: none;
}
.box li a{
  text-decoration: none;
  font-size: 80px;
  transition: all ease-in-out 250ms;
}
.box li a:hover{
  color: #b9b9b9;
}
