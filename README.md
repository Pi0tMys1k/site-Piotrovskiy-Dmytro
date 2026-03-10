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
background:#0f0f0f;
color:white;
line-height:1.6;
}

header{
background:#b30000;
padding:40px;
text-align:center;
}

header h1{
margin:0;
font-size:40px;
}

nav{
background:#1c1c1c;
display:flex;
justify-content:center;
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

section{
padding:50px;
max-width:1100px;
margin:auto;
}

h2{
text-align:center;
margin-bottom:30px;
color:#ff4d4d;
}

.cars{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:30px;
}

.card{
background:#1a1a1a;
padding:20px;
border-radius:10px;
width:300px;
text-align:center;
box-shadow:0 0 10px rgba(0,0,0,0.6);
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.card img{
width:100%;
border-radius:8px;
}

.brands{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
text-align:center;
}

.brand{
background:#1a1a1a;
padding:20px;
border-radius:8px;
}

footer{
background:#1c1c1c;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>

</head>

<body>

<header>
<h1>🚗 Мир автомобилей</h1>
<p>Информация о современных автомобилях, технологиях и брендах</p>
</header>

<nav>
<a href="#about">О автомобилях</a>
<a href="#types">Типы автомобилей</a>
<a href="#brands">Популярные бренды</a>
</nav>

<section id="about">

<h2>Что такое автомобиль</h2>

<p>
Автомобиль — это транспортное средство, предназначенное для перевозки людей или грузов. 
Современные автомобили оснащены сложными технологиями безопасности, системами помощи водителю 
и мощными двигателями.
</p>

<p>
Первый автомобиль с двигателем внутреннего сгорания был создан в конце XIX века. 
С тех пор автомобильная индустрия стала одной из самых крупных и технологичных отраслей 
в мире.
</p>

</section>

<section id="types">

<h2>Типы автомобилей</h2>

<div class="cars">

<div class="card">
<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70">
<h3>Спортивные автомобили</h3>
<p>
Спортивные автомобили созданы для высокой скорости и динамики. 
Они обладают мощными двигателями и аэродинамическим дизайном.
</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1502877338535-766e1452684a">
<h3>Внедорожники</h3>
<p>
SUV или внедорожники предназначены для поездок по сложным дорогам. 
Они имеют высокий клиренс и полный привод.
</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1549921296-3a6b1c52b0b7">
<h3>Электромобили</h3>
<p>
Электромобили работают на электричестве и не выделяют выхлопных газов. 
Это одно из самых перспективных направлений развития транспорта.
</p>
</div>

</div>

</section>

<section id="brands">

<h2>Популярные автомобильные бренды</h2>

<div class="brands">

<div class="brand">
<h3>BMW</h3>
<p>Немецкий бренд, известный спортивным характером и высоким качеством.</p>
</div>

<div class="brand">
<h3>Mercedes-Benz</h3>
<p>Один из самых престижных автомобильных брендов в мире.</p>
</div>

<div class="brand">
<h3>Tesla</h3>
<p>Компания, специализирующаяся на инновационных электромобилях.</p>
</div>

<div class="brand">
<h3>Toyota</h3>
<p>Японский производитель, известный надежностью и экономичностью.</p>
</div>

</div>

</section>

<footer>
<p>© 2026 Мир автомобилей | Информационный сайт</p>
</footer>

</body>
</html>
