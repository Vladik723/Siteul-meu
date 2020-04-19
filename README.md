<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">
    <style>
        body{
    height: 100vh; 
    background-color:#F5DEB3;
}
*{
    margin: 0;
    padding: 0;
    font-family: "Courier New",sans-serif;
}
.team-section{
    height: 100vh;
    display: flex;
}
.s{
    flex: 1;
    overflow: hidden;
    cursor: pointer;
    position: relative;
    transition: .6s;
}
.s:hover{
    flex: 3;
}
.s-pic{
    position: absolute;
    height: 100%;
    left: 50%;
    transform: translateX(-50%);
    filter: grayscale(70%);
    transition: .3s;
}
.s:hover .s-pic{
    filter: grayscale(0);
}
.s-info{
    position: absolute;
    bottom: 10px;
    text-align: center;
    width: 100%;
    opacity: 0;
    transition: .2s;
}
.s:hover .s-info{
    opacity: 1;
    bottom: 60px;
    transition-delay: .3s;
}
.s-info h2{
    font-size: 50px;
    color: #008080;
}
.s-info p{
    color: #008080;
    font-style: arial;
    margin-top: 8px;
    margin-bottom: 20px;
    font-size: 20px;
}
    </style>
</head>
<body>
    <div class="team-section">
        <div class="s">
            <img src="images/1.jpg" alt="" class="s-pic" width="600px">
            <div class="s-info">
                <h2>Punguta cu doi bani</h2>
                <p>Punguta cu doi bani este un spectacol</p>
                <div class="socialmedia"></div>
            </div>
        </div>

        <div class="s">
            <img src="images/2.jpg" alt="" class="s-pic">
            <div class="s-info">
                <h2>Danila prepeleag</h2>
                <p>Danila prepeleag este un spectacol care<br> 
                    veti descoperi lumea dracilor, o lume<br>
                    misterioasaplina de haz si umor si smecherii</p>
                <div class="socialmedia"></div>
            </div>
        </div>

        <div class="s">
            <img src="images/3.jpg" alt="" class="s-pic" width="600px">
            <div class="s-info">
                <h2>Revizorul</h2>
                <p>COMING SOON</p>
                <div class="socialmedia"></div>
            </div>
        </div>        
    </div>
</body>
</html>
