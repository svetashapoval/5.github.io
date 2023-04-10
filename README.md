<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<title>Caтypн</title>
<link rel="stylesheet" href="responsive.css" /> <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    {html font-size: 24px;}
    .header { text-align: center; }

nav ul { padding: 0;}

nav li {
  list-style: none;
  display: inline;
  font-size: 1.5rem;
  margin-right: 0.5rem;
}

.container {
  width: 100%;
  display: flex;
  justify-content: center;
}

.photo {
  max-width: 600px;
}

.photo img { width: 100%;}
.data {font-size: 1.5rem;}
.data ul { margin-top: 0;}
    @media (max-width: 600px) {
nav {
position: absolute;
top: 0px;
left: 5px;
}
nav img { display: block; }

nav ul { 
  display: none;
  background-color:white; 
  margin-top: -10px; 
  padding: 20px; 
  text-align: left;
    } 
    
    nav:hover ul { display: block; } 
    
    nav li { display: block; }
    
    h1 { font-size: 1.5rem; }

.data li { 
    font-size: 1.3rem;
   line-height: 1.5;
}
.header { height: 50px; }
    }
}
    
 nav img { display: none; }
    @media (max-width: 740px)
    {
.container { display: block;}
.photo { max-width: 100%;}
}   
    
    </style>
</head> 
  <body>
<div class="header"> 
  <nav>
    <img src="menu-icon.svg" alt="бутерброд меню" />
<ul>
<li><a href="#">Головна</a></li> <li><a href="#">Зоpi</a></li>
<li><a href="#">Coнцe</a></li> <li><a href="#">Планети</a></li>
<li><a href="#">Про проект</a></li>
<li><a href="#">Kонтакти</a></li>
</ul>
</nav>
<h1>Планета Сатурн</h1>>
</div>
<div class="container">
<div class="photo"> <img src="planet.jpg" />
</div>
<div class="data">
<ul>
<li>Сатурн друга за величиною планета сонячної системи.</li>
<li>Сатурн не має твердої поверхні.</li>
<li>Кільця сатурна можна побачити навіть в простий телескоп.</li>
<li>Рік на сатурні триває більше 29 земних років.</li>
</ul>
