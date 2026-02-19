<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CAN MEDYA</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#111;
color:white;
}

header{
background:#000;
padding:20px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:22px;
font-weight:bold;
color:#00ff88;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(135deg,#000,#1a1a1a);
}

.hero h1{
font-size:40px;
margin-bottom:15px;
}

.hero p{
color:#aaa;
margin-bottom:25px;
}

.btn{
padding:12px 25px;
background:#00ff88;
color:black;
border:none;
border-radius:8px;
cursor:pointer;
font-weight:bold;
}

.btn:hover{
background:#00cc6a;
}

footer{
background:#000;
text-align:center;
padding:15px;
}
</style>

</head>
<body>

<header>
<div class="logo">CAN MEDYA</div>
<nav>
<a href="#">Ana Sayfa</a>
<a href="#">Projeler</a>
<a href="#">İletişim</a>
</nav>
</header>

<section class="hero">
<h1>CAN MEDYA</h1>
<p>Dijital Projeler ve Web Çözümleri</p>
<button class="btn" onclick="alert('Hoşgeldin Dayı 🚀')">Başla</button>
</section>

<footer>
© 2026 CAN MEDYA
</footer>

</body>
</html>
