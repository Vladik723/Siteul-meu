<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Marcu Vlad</title>
    <style>
* {
  box-sizing: border-box;
}

html,

body {
  background-color: #FEDCC8;
  display: flex;
}

.parallax {
  -webkit-perspective: 100px;
          perspective: 100px;
  height: 100vh;
  overflow-x: hidden;
  overflow-y: auto;
  position: absolute;
  top: 0;
  left: 50%;
  right: 0;
  bottom: 0;
  margin-left: -1500px;
}

.parallax__layer {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}
.parallax__layer img {
  display: block;
  position: absolute;
  bottom: 0;
}

.parallax__cover {
  background: #2D112B;
  display: block;
  position: absolute;
  top: 100%;
  left: 0;
  right: 0;
  height: 2000px;
  z-index: 2;
}
.parallax__layer__0 {
  -webkit-transform: translateZ(-300px) scale(4);
          transform: translateZ(-300px) scale(4);
}
.parallax__layer__1 {
  -webkit-transform: translateZ(-250px) scale(3.5);
          transform: translateZ(-250px) scale(3.5);
}
.parallax__layer__2 {
  -webkit-transform: translateZ(-200px) scale(3);
          transform: translateZ(-200px) scale(3);
}
.parallax__layer__3 {
  -webkit-transform: translateZ(-150px) scale(2.5);
          transform: translateZ(-150px) scale(2.5);
}
.parallax__layer__4 {
  -webkit-transform: translateZ(-100px) scale(2);
          transform: translateZ(-100px) scale(2);
}
.parallax__layer__5 {
  -webkit-transform: translateZ(-50px) scale(1.5);
          transform: translateZ(-50px) scale(1.5);
}
.parallax__layer__6 {
  -webkit-transform: translateZ(0px) scale(1);
          transform: translateZ(0px) scale(1);
}



.nume{
  width: 400px;
  height: 70px;
  border: 4px solid;
  color:rgb(0, 61, 110);
  font-weight: 700;
  font-size: 55px;
  position: absolute;
  text-align: center;
  top: 20%;
  left: 60%;
  text-emphasis: none;
  

}
.nume::before,.nume::after{
  content: "";
  position: absolute;
  width: 14px;
  height: 4px;
  background: rgb(247, 237, 193);
  transform: skewX(50deg);
  transition: .4s linear;
}
.nume::before{
  top: -4px;
  left: 10%;
}
.nume::after{
  bottom: -4px;
  right: 10%;
}
.nume:hover::before{
  left: 80%;
}
.nume:hover::after{
  right: 80%;}


    </style>
  </head>
  <body>
    <div class="parallax">
        <div class="parallax__layer parallax__layer__0">
            <img src="https://github.com/samdbeckham/blog/blob/master/dev/_assets/images/articles/firewatch/layer_0.png?raw=true" />
        </div>
        <div class="parallax__layer parallax__layer__1">
            <img src="https://github.com/samdbeckham/blog/blob/master/dev/_assets/images/articles/firewatch/layer_1.png?raw=true" />
        </div>
        <div class="parallax__layer parallax__layer__2">
            <img src="https://github.com/samdbeckham/blog/blob/master/dev/_assets/images/articles/firewatch/layer_2.png?raw=true" />
        </div>
        <div class="parallax__layer parallax__layer__3">
            <img src="https://github.com/samdbeckham/blog/blob/master/dev/_assets/images/articles/firewatch/layer_3.png?raw=true" />
        </div>
        <div class="parallax__layer parallax__layer__4">
            <img src="https://github.com/samdbeckham/blog/blob/master/dev/_assets/images/articles/firewatch/layer_4.png?raw=true" />
        </div>
        <div class="parallax__layer parallax__layer__5">
            <img src="https://github.com/samdbeckham/blog/blob/master/dev/_assets/images/articles/firewatch/layer_5.png?raw=true" />
        </div>
        <div class="parallax__layer parallax__layer__6">
            <img src="https://github.com/samdbeckham/blog/blob/master/dev/_assets/images/articles/firewatch/layer_6.png?raw=true" />
        </div>
        <div class="parallax__cover"></div>

        <div>
          <a class="nume">Vlad Marcu</a>
      </div>
    </div>
   
</body>
  </html>
