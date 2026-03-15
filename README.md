<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<title>Clube de Patas</title>

<style>

body{
font-family: Arial;
margin:0;
background:#f4f4f4;
}

header{
background:#ff914d;
color:white;
text-align:center;
padding:30px;
}

header h1{
margin:0;
}

.container{
display:flex;
justify-content:center;
gap:30px;
padding:40px;
flex-wrap:wrap;
}

.card{
background:white;
width:220px;
border-radius:10px;
box-shadow:0 4px 8px rgba(0,0,0,0.2);
text-align:center;
padding:20px;
}

.card img{
width:100%;
border-radius:10px;
}

.card h2{
margin:10px 0;
}

button{
background:#ff914d;
border:none;
padding:10px 20px;
color:white;
border-radius:5px;
cursor:pointer;
}

button:hover{
background:#ff6b1a;
}

footer{
text-align:center;
padding:20px;
background:#333;
color:white;
}

</style>
</head>

<body>

<header>
<h1>🐾 Clube de Patas</h1>
<p>Adote um amigo para a vida</p>
</header>

<section class="container">

<div class="card">
<img src="https://placedog.net/300/200">
<h2>Rex</h2>
<p>Cão brincalhão e muito amigável.</p>
<button>Adotar</button>
</div>

<div class="card">
<img src="https://placekitten.com/300/200">
<h2>Mimi</h2>
<p>Gata carinhosa que gosta de dormir.</p>
<button>Adotar</button>
</div>

<div class="card">
<img src="https://placedog.net/301/200">
<h2>Bob</h2>
<p>Cão fiel e ótimo companheiro.</p>
<button>Adotar</button>
</div>

</section>

<footer>
<p>© 2026 Clube de Patas</p>
</footer>

</body>
</html>
