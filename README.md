<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>AutoLux — автосалон</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#0f0f0f;
color:white;
}

/* HEADER */

header{
height:100vh;
background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.8)),
url("https://images.unsplash.com/photo-1492144534655-ae79c964c9d7");
background-size:cover;
background-position:center;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

header h1{
font-size:60px;
margin-bottom:20px;
}

header p{
font-size:22px;
opacity:0.9;
}

header button{
margin-top:30px;
padding:15px 35px;
border:none;
background:#e00000;
color:white;
font-size:18px;
border-radius:5px;
cursor:pointer;
transition:0.3s;
}

header button:hover{
background:#ff2e2e;
}

/* NAVBAR */

nav{
position:fixed;
top:0;
width:100%;
background:#111;
display:flex;
justify-content:center;
padding:15px;
z-index:1000;
}

nav a{
color:white;
text-decoration:none;
margin:0 20px;
font-size:18px;
transition:0.3s;
}

nav a:hover{
color:red;
}

/* SECTIONS */

section{
padding:80px 10%;
}

h2{
text-align:center;
font-size:36px;
margin-bottom:50px;
color:#ff2e2e;
}

/* ABOUT */

.about{
text-align:center;
max-width:900px;
margin:auto;
font-size:18px;
line-height:1.6;
}

/* CAR CARDS */

.cars{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px;
}

.card{
background:#1a1a1a;
border-radius:10px;
overflow:hidden;
transition:0.4s;
box-shadow:0 0 15px rgba(0,0,0,0.6);
}

.card:hover{
transform:translateY(-10px) scale(1.03);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.card-content h3{
margin-bottom:10px;
}

.card-content p{
opacity:0.8;
font-size:15px;
}

/* BRANDS */

.brands{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:30px;
}

.brand{
background:#1a1a1a;
padding:25px;
border-radius:8px;
width:200px;
text-align:center;
transition:0.3s;
}

.brand:hover{
background:#222;
transform:scale(1.05);
}

/* GALLERY */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
border-radius:8px;
transition:0.3s;
}

.gallery img:hover{
transform:scale(1.05);
}

/* FOOTER */

footer{
background:#111;
padding:30px;
text-align:center;
margin-top:60px;
}

</style>
</head>

<body>

<nav>
<a href="#about">О нас</a>
<a href="#cars">Автомобили</a>
<a href="#brands">Бренды</a>
<a href="#gallery">Галерея</a>
</nav>

<header>

<h1>AutoLux</h1>
<p>Премиальный автосалон современных автомобилей</p>

<button onclick="document.getElementById('cars').scrollIntoView()">Смотреть автомобили</button>

</header>

<section id="about">

<h2>О нашем автосалоне</h2>

<div class="about">
<p>
AutoLux — современный автосалон, где представлены лучшие автомобили
мировых брендов. Мы предлагаем спортивные автомобили, внедорожники
и современные электромобили.
</p>

<p>
Автомобиль сегодня — это не просто транспорт, а сочетание технологий,
дизайна, комфорта и безопасности. Именно поэтому мы выбираем только
лучшие модели для наших клиентов.
</p>
</div>

</section>

<section id="cars">

<h2>Популярные автомобили</h2>

<div class="cars">

<div class="card">
<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70">
<div class="card-content">
<h3>Спортивный автомобиль</h3>
<p>Мощный двигатель, аэродинамика и высокая скорость.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1502877338535-766e1452684a">
<div class="card-content">
<h3>Внедорожник</h3>
<p>Надежный автомобиль для города и бездорожья.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1549921296-3a6b1c52b0b7">
<div class="card-content">
<h3>Электромобиль</h3>
<p>Экологичный транспорт будущего с современными технологиями.</p>
</div>
</div>

</div>

</section>

<section id="brands">

<h2>Популярные бренды</h2>

<div class="brands">

<div class="brand">BMW</div>
<div class="brand">Mercedes</div>
<div class="brand">Audi</div>
<div class="brand">Tesla</div>
<div class="brand">Toyota</div>
<div class="brand">Porsche</div>

</div>

</section>

<section id="gallery">

<h2>Галерея автомобилей</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70">
<img src="https://images.unsplash.com/photo-1511919884226-fd3cad34687c">
<img src="https://images.unsplash.com/photo-1542362567-b07e54358753">
<img src="https://images.unsplash.com/photo-1494976388531-d1058494cdd8">

</div>

</section>

<footer>

<p>© 2026 AutoLux — автосалон автомобилей</p>

</footer>

</body>
</html>
