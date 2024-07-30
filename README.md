<!DOCTYPE html>
<html lang = "en"> 
<head> 
     <meta charset=" UTF- 8">
     <meta http-equiv="x-UA-Compatible" content="IE=EDGE">
     <meta name = "viewport" content="width=device-width, initial-scale=1.0">
     <title>Personle Portofolio</title>
     <link rel=" stylesheet" href="style.css">
</head>
<body>
      <div class="hero">
          <nav>
               <img src="cccc.webp" alt ="logo">
               <ul>
                    <li><a href="#">HOME </a></li>
                    <li><a href="#">ABOUT </a></li>
                    <li><a href="#">PORTOFOLIO</a></li>
                    <li><a href="#">SERVICE </a></li>
                    <li><a href="#">HIRE ME </a></li>
               </ul>
          </nav>
          div <div class="detel">
            <h1>I'm Abdi <span>Alamsyah</span></h1>
            <p> This is my official portofolio website to showes all </p>
                   <br> Details and work exiprins web development
          </p>  
          <a href="#">DOWNLOAD CV</a>
          </div>
          <div class="images">
            <img src="IMG_20240418_002659.jpg" class="IMG_20240418_002659">
            <img src="cccc.webp" class="cccc.web" >
          </div>
      </div>
</body>
</html>



*{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}

.hero {
    position: relative;
    width: 100%;
    height: 100vh;
    background: #eff4fd;
}

 nav{
    display: flex;
    width: 84%;
    margin: auto;
    padding: 20px;
    align-items: center;
    justify-content: space-between;    
}

nav ul li {
    display: inline-block;
    list list-style: none;
    margin: 10px 20px;
}

nav ul li a {
    text-decoration: none;
    color: black;
    font-weight: bold;
}

nav ul li a  :hover{
     color : red;
}

.detel{
    margin-left: 8%;
    margin-top: 13%; 
}

.detel h1{
    font size: 50px;
    color: #212121;
    margin-bottom: 20px;
}

span{
    color: orange;
}

.detel p{
    color: : #555;
    line height:  22px;
}

.detel a{
    background: #212121;
    padding: 10px 18px;
    text-decoration: :none;
    font-weight:bold;
    color: #fff;
    display: inline-block; 
    margin: 30px 0;
    border radius:5px;
}

.images{
    width: 45%;
    height: 80px;
    position: absolute;
    bottom: 0;
    right: 100px;
}

.images img{
    height: 100px;
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    transition: bottom 1s,left 1s;
}

.images: :hover .IMG_20240418_002659.jpg{
    bottom : 40%;
}

.images :hover .cccc{
    left: 45;
}
