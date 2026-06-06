<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>El Sendero Interactivo</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
body{
    font-family: Arial, sans-serif;
}

.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
    url("https://images.unsplash.com/photo-1441974231531-c6227db76b6e");
    background-size:cover;
    background-position:center;
    color:white;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.section-title{
    color:#198754;
    font-weight:bold;
    margin-bottom:30px;
}

.gallery img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card:hover{
    transform:translateY(-5px);
    transition:.3s;
}

footer{
    background:#198754;
    color:white;
    padding:20px;
}
</style>
</head>
<body>

<!-- MENU -->
<nav class="navbar navbar-expand-lg navbar-dark bg-success fixed-top">
<div class="container">

<a class="navbar-brand fw-bold" href="#">
🌿 El Sendero Interactivo
</a>

<button class="navbar-toggler"
type="button"
data-bs-toggle="collapse"
data-bs-target="#menu">

<span class="navbar-toggler-icon"></span>

</button>

<div class="collapse navbar-collapse" id="menu">

<ul class="navbar-nav ms-auto">

<li class="nav-item">
<a class="nav-link" href="#inicio">Inicio</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#acerca">Acerca</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#objetivos">Objetivos</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#galeria">Galería</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#contacto">Contacto</a>
</li>

</ul>

</div>
</div>
</nav>

<!-- PORTADA -->
<section id="inicio" class="hero">

<div class="container">

<h1 class="display-2 fw-bold">
EL SENDERO INTERACTIVO
</h1>

<p class="lead">
Proyecto educativo y ecológico enfocado en el aprendizaje,
la conservación ambiental y la interacción con la naturaleza.
</p>

<a href="#acerca" class="btn btn-success btn-lg">
Conocer más
</a>

</div>

</section>

<!-- ACERCA -->
<section class="py-5" id="acerca">

<div class="container">

<h2 class="text-center section-title">
¿Qué es El Sendero Interactivo?
</h2>

<div class="row align-items-center">

<div class="col-md-6">

<img src="c:\Users\cristo\OneDrive\Documents\imagen1.jpeg"
class="img-fluid rounded shadow">

</div>

<div class="col-md-6">

<p>
El Sendero Interactivo es un espacio diseñado para fomentar
el aprendizaje mediante experiencias prácticas y actividades
relacionadas con el medio ambiente.
</p>

<p>
A través de recorridos guiados y estaciones informativas,
los visitantes descubren la importancia de conservar los
ecosistemas y proteger la biodiversidad.
</p>

<p>
Este proyecto busca fortalecer la educación ambiental y
promover una cultura de respeto hacia la naturaleza.
</p>

</div>

</div>

</div>

</section>

<!-- OBJETIVOS -->
<section class="bg-light py-5" id="objetivos">

<div class="container">

<h2 class="text-center section-title">
Objetivos
</h2>

<div class="row">

<div class="col-md-4 mb-4">

<div class="card shadow h-100">

<div class="card-body text-center">

<h4>📚 Educación</h4>

<p>
Promover el aprendizaje interactivo mediante experiencias
significativas.
</p>

</div>
</div>
</div>

<div class="col-md-4 mb-4">

<div class="card shadow h-100">

<div class="card-body text-center">

<h4>🌱 Conservación</h4>

<p>
Fomentar el cuidado y respeto por el medio ambiente.
</p>

</div>
</div>
</div>

<div class="col-md-4 mb-4">

<div class="card shadow h-100">

<div class="card-body text-center">

<h4>🤝 Participación</h4>

<p>
Impulsar la integración de estudiantes y comunidad.
</p>

</div>
</div>
</div>

</div>

</div>

</section>

<!-- CARRUSEL -->
<section class="py-5">

<div class="container">

<h2 class="text-center section-title">
Recorrido Fotográfico
</h2>

<div id="carouselExample" class="carousel slide">

<div class="carousel-inner">

<div class="carousel-item active">
<img src="c:\Users\cristo\OneDrive\Documents\imagen2.jpg" class="d-block w-100 rounded">
</div>

<div class="carousel-item">
<img src="c:\Users\cristo\OneDrive\Documents\imagen3.jpg" class="d-block w-100 rounded">
</div>

<div class="carousel-item">
<img src="img/foto5.jpg" class="d-block w-100 rounded">
</div>

</div>

<button class="carousel-control-prev"
type="button"
data-bs-target="#carouselExample"
data-bs-slide="prev">

<span class="carousel-control-prev-icon"></span>

</button>

<button class="carousel-control-next"
type="button"
data-bs-target="#carouselExample"
data-bs-slide="next">

<span class="carousel-control-next-icon"></span>

</button>

</div>

</div>

</section>

<!-- GALERIA -->
<section id="galeria" class="bg-light py-5">

<div class="container">

<h2 class="text-center section-title">
Galería de Imágenes
</h2>

<div class="row gallery g-4">

<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen4.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen5.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen6.jpg" class="rounded shadow"></div>

<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen7.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen8.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen9.jpg" class="rounded shadow"></div>

<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen10.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen11.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen12.jpg" class="rounded shadow"></div>

<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen2.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen3.jpg" class="rounded shadow"></div>
<div class="col-md-4"><img src="c:\Users\cristo\OneDrive\Documents\imagen4.jpg" class="rounded shadow"></div>

</div>

</div>

</section>

<!-- BENEFICIOS -->
<section class="py-5">

<div class="container">

<h2 class="text-center section-title">
Beneficios del Proyecto
</h2>

<div class="row text-center">

<div class="col-md-3">
<h4>🌳</h4>
<p>Contacto con la naturaleza.</p>
</div>

<div class="col-md-3">
<h4>🎓</h4>
<p>Aprendizaje práctico.</p>
</div>

<div class="col-md-3">
<h4>♻️</h4>
<p>Conciencia ambiental.</p>
</div>

<div class="col-md-3">
<h4>👨‍👩‍👧</h4>
<p>Participación comunitaria.</p>
</div>

</div>

</div>

</section>

<!-- CONTACTO -->
<section id="contacto" class="bg-success text-white py-5">

<div class="container">

<h2 class="text-center mb-4">
Contacto
</h2>

<div class="row justify-content-center">

<div class="col-md-8">

<form>

<div class="mb-3">
<input type="text"
class="form-control"
placeholder="Nombre">
</div>

<div class="mb-3">
<input type="email"
class="form-control"
placeholder="Correo electrónico">
</div>

<div class="mb-3">
<textarea
rows="5"
class="form-control"
placeholder="Escribe tu mensaje"></textarea>
</div>

<div class="text-center">

<button class="btn btn-light">
Enviar
</button>

</div>

</form>

</div>

</div>

</div>

</section>

<footer class="text-center">

<h5>El Sendero Interactivo</h5>

<p>
Proyecto Escolar 2025
</p>

</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
