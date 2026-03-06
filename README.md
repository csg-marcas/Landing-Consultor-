<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Consultoría de Imagen Comercial | Filadelfia Paraguay</title>

<style>

body{
margin:0;
font-family:Arial, Helvetica, sans-serif;
background:#0f0f0f;
color:white;
}

header{
background:#000;
padding:20px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

header h1{
font-size:22px;
letter-spacing:2px;
}

nav a{
color:white;
margin-left:20px;
text-decoration:none;
font-size:14px;
}

.hero{
height:90vh;
background-image:url("https://images.unsplash.com/photo-1555529669-e69e7aa0ba9a");
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:20px;
}

.hero h2{
font-size:42px;
max-width:700px;
}

.hero button{
margin-top:20px;
padding:15px 30px;
border:none;
background:#c8a96a;
color:black;
font-weight:bold;
cursor:pointer;
}

.section{
padding:80px 10%;
text-align:center;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
margin-top:40px;
}

.card{
background:#1a1a1a;
padding:30px;
border-radius:8px;
}

.card img{
width:100%;
border-radius:6px;
margin-bottom:15px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
margin-top:40px;
}

.gallery img{
width:100%;
border-radius:8px;
}

.contact{
background:#111;
}

form{
max-width:500px;
margin:auto;
display:flex;
flex-direction:column;
gap:15px;
margin-top:30px;
}

input, textarea{
padding:12px;
border:none;
border-radius:4px;
}

button.submit{
background:#c8a96a;
border:none;
padding:14px;
font-weight:bold;
cursor:pointer;
}

footer{
padding:40px;
text-align:center;
background:black;
margin-top:40px;
}

</style>
</head>

<body>

<header>

<h1>MEJORA TU MARCA</h1>

<nav>
<a href="#servicios">Servicios</a>
<a href="#trabajo">Proyectos</a>
<a href="#contacto">Contacto</a>
</nav>

</header>

<section class="hero">

<div>
<h2>Transformo comercios comunes en experiencias de marca que venden más</h2>
<button onclick="document.getElementById('contacto').scrollIntoView()">Solicitar consultoría</button>
</div>

</section>

<section class="section" id="servicios">

<h2>Servicios</h2>

<div class="services">

<div class="card">
<img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36">
<h3>Imagen del comercio</h3>
<p>Optimización visual de locales para generar impacto y atraer clientes.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
<h3>Organización del espacio</h3>
<p>Distribución estratégica de productos para mejorar circulación y ventas.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1507209696998-3c532be9b2b5">
<h3>Experiencia del cliente</h3>
<p>Creación de ambientes que aumentan la permanencia y la percepción de valor.</p>
</div>

</div>

</section>

<section class="section" id="trabajo">

<h2>Inspiración de proyectos</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1556742049-0cfed4f6a45d">
<img src="https://images.unsplash.com/photo-1441986300917-64674bd600d8">
<img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36">

</div>

</section>

<section class="section contact" id="contacto">

<h2>Solicitar una consultoría</h2>

<form>

<input type="text" placeholder="Nombre">

<input type="email" placeholder="Email">

<textarea placeholder="Cuéntame sobre tu negocio"></textarea>

<button class="submit">Enviar</button>

</form>

</section>

<footer>

<p>Filadelfia, Boquerón – Paraguay</p>
<p>Consultoría en imagen comercial y experiencia del cliente</p>

</footer>

</body>

</html>
