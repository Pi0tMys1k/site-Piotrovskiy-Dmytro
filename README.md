# site-Piotrovskiy-Dmytro
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Мир автомобилей</title>

<style>

body{
font-family: Arial, sans-serif;
margin:0;
background:#111;
color:white;
}

header{
text-align:center;
padding:40px;
background:#c40000;
}

nav{
display:flex;
justify-content:center;
background:#222;
padding:15px;
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

.cars{
display:flex;
justify-content:center;
gap:30px;
padding:40px;
flex-wrap:wrap;
}

.car-card{
background:#1c1c1c;
padding:20px;
border-radius:12px;
width:260px;
text-align:center;
transition:0.3s;
box-shadow:0 0 10px rgba(0,0,0,0.5);
}

.car-card:hover{
transform:scale(1.07);
}

.car-card img{
width:100%;
border-radius:10px;
}

footer{
text-align:center;
padding:20px;
background:#222;
margin-top:40px;
}

</style>

</head>

<body>

<header>
<h1>🚗 Мир автомобилей</h1>
<p>Лучшие автомобили современности</p>
</header>

<nav>
<a href="#">Главная</a>
<a href="#">Галерея</a>
<a href="#">Контакты</a>
</nav>

<section class="cars">

<div class="car-card">
<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70" alt="Спортивный автомобиль">
<h2>Спортивный автомобиль</h2>
<p>Быстрый, мощный и создан для скорости.</p>
</div>

<div class="car-card">
<img src="https://images.unsplash.com/photo-1549921296-3a6b1c52b0b7" alt="Электромобиль">
<h2>Электромобиль</h2>
<p>Современные технологии и экологичность.</p>
</div>

<div class="car-card">
<img src="https://images.unsplash.com/photo-1511919884226-fd3cad34687c" alt="Суперкар">
<h2>Суперкар</h2>
<p>Максимальная скорость и роскошный дизайн.</p>
</div>

</section>

<footer>
<p>© 2026 Мир автомобилей</p>
</footer>

</body>
</html>
