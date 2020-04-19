<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Marcu Vlad</title>
    <style>
*{
  margin: 0;
  padding: 0;
  font-family: "montserrat",sans-serif;
}

body{
  background: #353b48;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.btn{
  width: 500px;
  height: 90px;
  background: none;
  border: 4px solid;
  color: #ffffff;
  font-weight: 700;
  text-transform: uppercase;
  cursor: pointer;
  font-size: 55px;
  position: relative;

}

.btn::before,.btn::after{
  content: "";
  position: absolute;
  width: 14px;
  height: 4px;
  background: #353b48;
  transform: skewX(50deg);
  transition: .4s linear;
}

.btn::before{
  top: -4px;
  left: 10%;
}

.btn::after{
  bottom: -4px;
  right: 10%;
}

.btn:hover::before{
  left: 80%;
}

.btn:hover::after{
  right: 80%;
}
    </style>
  </head>
  <body>
    <button class="btn">Vlad Marcu</button>
  </body>
</html>
