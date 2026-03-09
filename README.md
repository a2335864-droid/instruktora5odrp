
<!-- Иконки -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Montserrat', sans-serif;
}

body{
background: radial-gradient(circle at top,#6b4cff,#1d103b 60%,#090012);
color:white;
min-height:100vh;
}

/* меню */

nav{
display:flex;
justify-content:center;
gap:20px;
padding:30px;
}

nav a{
text-decoration:none;
color:white;
padding:12px 24px;
border-radius:30px;
background:rgba(255,255,255,0.08);
border:1px solid rgba(255,255,255,0.2);
transition:0.3s ease; /* Плавная анимация */
display:flex;
align-items:center;
gap:8px;
}

/* Игровое свечение кнопок */
nav a:hover {
    background: #6be7ff;
    color: #001b22;
    box-shadow: 0 0 15px rgba(107, 231, 255, 0.8), /* Основное свечение */
                0 0 30px rgba(107, 231, 255, 0.6), /* Более размытое свечение */
                0 0 45px rgba(107, 231, 255, 0.4); /* Еще более размытое */
    transform: translateY(-3px); /* Небольшой подъем */
}


/* заголовок */

header{
text-align:center;
margin-top:40px;
}

header h1{
font-size:48px;
font-weight:700;
}

/* контейнер */

.container{
max-width:900px;
margin:auto;
padding:20px;
}

/* блоки */

.block{
background:rgba(255,255,255,0.06);
border:1px solid rgba(255,255,255,0.15);
border-radius:18px;
padding:25px;
margin-top:20px;
backdrop-filter:blur(12px);
transition:0.3s ease; /* Плавная анимация */
}

.block.highlight{
border:1px solid #6be7ff;
background:rgba(107,231,255,0.12);
}

/* заголовок раздела */

.section-title{
text-align:center;
font-size:34px;
margin:70px 0 30px 0;
display:flex;
justify-content:center;
align-items:center;
gap:10px;
}

/* карточки */

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:25px;
}

.card{
width:260px;
padding:28px;
border-radius:18px;
background:rgba(255,255,255,0.05);
border:1px solid rgba(255,255,255,0.15);
transition:0.3s ease; /* Плавная анимация */
text-align:center;
}

.card i{
font-size:28px;
margin-bottom:10px;
color:#6be7ff;
}

.card:hover{
transform:translateY(-6px);
background:rgba(107,231,255,0.15);
border:1px solid #6be7ff;
box-shadow: 0 0 15px rgba(107, 231, 255, 0.8),
            0 0 30px rgba(107, 231, 255, 0.6),
            0 0 45px rgba(107, 231, 255, 0.4);
}

.card a{
display:inline-block;
margin-top:12px;
text-decoration:none;
color:#6be7ff;
font-weight:600;
display:inline-block; /* Для применения трансформаций */
transition:0.3s ease; /* Плавная анимация */
}

.card a:hover {
    color: #ffffff; /* Изменение цвета текста */
    transform: scale(1.1); /* Немного увеличить ссылку */
    text-shadow: 0 0 8px rgba(107, 231, 255, 0.7); /* Свечение текста */
}


/* футер */

footer{
margin-top:90px;
text-align:center;
padding:40px;
background:rgba(0,0,0,0.35);
}

footer h2{
color:#B197FC; /* Светло-фиолетовый */
transition:0.4s ease;
}

footer p{
color:#B197FC; /* Светло-фиолетовый */
transition:0.4s ease;
}


</style>
</head>

<body>

<nav>
<a href="#"><i class="fa-solid fa-house"></i> Главная</a>

<a href="https://docs.google.com/document/d/1GPLUaJWW2Ma8nIZwG6jXK4-g2AAGqrFYDQT25bCjM48/edit?tab=t.0#heading=h.twssduvwxag" target="_blank">
<i class="fa-solid fa-book-open"></i> Методичка Инструкторов
</a>

<a href="https://docs.google.com/document/d/1GPLUaJWW2Ma8nIZwG6jXK4-g2AAGqrFYDQT25bCjM48/edit?tab=t.0#heading=h.9k9acbm4k0le" target="_blank">
<i class="fa-solid fa-book"></i> Обучение кадетов
</a>
</nav>

<header>
<h1><i class="fa-solid fa-user-graduate"></i> Инструктора ОДРП №5</h1>
</header>

<div class="container">

<div class="block">
Инструктор - это Администратор, ответственный за проведение обучения Кадетам и помощи при необходимости.
</div>

<div class="block">
Цель Инструкторов - обучение новых кадров, проведение тестов для повышения и поддержка знаний у кадетов 5 сервера.
</div>

<div class="block highlight">
Помните! Инструктора - это ответственные за кадетов Администраторы. Вся ответственность насчёт знаний интернов - на вас! Старайтесь обучать кадетов не поверхостно, а углубленно.
</div>

<h2 class="section-title">
<i class="fa-solid fa-clipboard-check"></i> Тесты
</h2>

<div class="cards">

<div class="card">
<i class="fa-solid fa-file-circle-check"></i>
<h3>Тест №1</h3>
<a href="https://docs.google.com/forms/d/e/1FAIpQLSeEMZcwY5Y--6v4YsEn29P183xmQyZsiCueRZJRKWI2CjxIiA/viewform" target="_blank">Пройти</a>
</div>

<div class="card">
<i class="fa-solid fa-file-pen"></i>
<h3>Тест №2</h3>
<a href="https://docs.google.com/forms/d/e/1FAIpQLSfrAUqgZDG_API64myLkaIK9Doi_Jx_RXsfC2tTUMBOCXxDAg/viewform" target="_blank">Пройти</a>
</div>

<div class="card">
<i class="fa-solid fa-list-check"></i>
<h3>Тест №3</h3>
<a href="https://docs.google.com/forms/d/e/1FAIpQLScwhcdcYzW10jNkHrez3uUvZL481dZ5H1eQKeuzu_OxyZXu_A/viewform" target="_blank">Пройти</a>
</div>

</div>

</div>

<footer>
<h2>Инструктора 5 сервера</h2>
<p>by Алекс Уэйнрайт</p>
</footer>

</body>
</html>

