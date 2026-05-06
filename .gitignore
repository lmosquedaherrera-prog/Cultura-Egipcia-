<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cultura Egipcia</title>

<link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;scroll-behavior:smooth;}

body{
    font-family:'Segoe UI',sans-serif;
    background:#0c0c0c;
    color:white;
}

/* FONDO ANIMADO */
body::before{
    content:"";
    position:fixed;
    width:100%;
    height:100%;
    background: radial-gradient(circle, #ffd70022 1px, transparent 1px);
    background-size: 40px 40px;
    animation: moveBg 20s linear infinite;
    z-index:-1;
}

@keyframes moveBg{
    from{transform:translateY(0);}
    to{transform:translateY(-200px);}
}

/* NAV */
header{
    position:fixed;
    width:100%;
    background:rgba(0,0,0,0.7);
    backdrop-filter:blur(8px);
    z-index:1000;
}

nav{
    display:flex;
    justify-content:center;
    gap:30px;
    padding:15px;
}

nav a{
    color:#ffd700;
    text-decoration:none;
    font-weight:bold;
    position:relative;
}

nav a::after{
    content:"";
    position:absolute;
    width:0%;
    height:2px;
    background:#ffd700;
    left:0;
    bottom:-5px;
    transition:.3s;
}

nav a:hover::after{
    width:100%;
}

/* HERO */
#inicio{
    height:100vh;
    background:url('https://images.unsplash.com/photo-1549893079-842e7c7db4a3') center/cover fixed;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

#inicio h1{
    font-size:70px;
    text-shadow:0 0 20px #000;
}

/* SECCIONES */
section{
    padding:100px 20px;
    text-align:center;
}

.contenido{
    max-width:900px;
    margin:auto;
}

/* CARDS */
.cards{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:30px;
}

.card{
    background:#111;
    border:1px solid #ffd70033;
    width:260px;
    padding:25px;
    border-radius:15px;
    transition:.4s;
}

.card:hover{
    transform:translateY(-10px) scale(1.05);
    box-shadow:0 0 20px #ffd70055;
}

/* BOTÓN FLOTANTE */
.btn-top{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#ffd700;
    color:black;
    padding:10px 15px;
    border-radius:50%;
    font-weight:bold;
    cursor:pointer;
    box-shadow:0 0 10px #ffd700;
}

/* FOOTER */
footer{
    background:#000;
    padding:20px;
}
</style>
</head>

<body>

<header>
<nav>
<a href="#inicio">Inicio</a>
<a href="#historia">Historia</a>
<a href="#dioses">Dioses</a>
<a href="#monumentos">Monumentos</a>
<a href="#contacto">Contacto</a>
</nav>
</header>

<section id="inicio">
<div data-aos="zoom-in">
<h1>Cultura Egipcia</h1>
<p>Explora el misterio del Antiguo Egipto</p>
</div>
</section>

<section id="historia">
<div class="contenido" data-aos="fade-up">
<h2>Historia</h2>
<p>El Antiguo Egipto floreció alrededor del río Nilo durante miles de años.</p>
</div>
</section>

<section id="dioses">
<h2 data-aos="fade-up">Dioses</h2>
<div class="cards">
<div class="card" data-aos="flip-left">
<h3>Ra</h3>
<p>Dios del sol</p>
</div>

<div class="card" data-aos="flip-left" data-aos-delay="150">
<h3>Osiris</h3>
<p>Dios del inframundo</p>
</div>

<div class="card" data-aos="flip-left" data-aos-delay="300">
<h3>Anubis</h3>
<p>Dios de la momificación</p>
</div>
</div>
</section>

<section id="monumentos">
<div class="contenido" data-aos="fade-right">
<h2>Monumentos</h2>
<p>Las pirámides siguen siendo un misterio fascinante.</p>
</div>
</section>

<section id="contacto">
<div class="contenido" data-aos="fade-up">
<h2>Contacto</h2>
<p>correo@ejemplo.com</p>
</div>
</section>

<footer>
<p>© 2026 Cultura Egipcia</p>
</footer>

<div class="btn-top" onclick="window.scrollTo({top:0,behavior:'smooth'})">↑</div>

<script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
<script>
AOS.init({duration:1200,once:true});
</script>

</body>
</html>
