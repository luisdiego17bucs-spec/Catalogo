<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Catálogo de Ropa</title>
<style>
body { font-family: Arial, sans-serif; margin: 0; padding: 0; background:#f4f4f4; }
header { background:#111; color:white; padding:15px; text-align:center; position:sticky; top:0; }
nav { display:flex; justify-content:center; gap:20px; margin-top:10px; }
nav a { color:white; text-decoration:none; font-weight:bold; font-size:14px; }
.container { padding:20px; max-width:1000px; margin:auto; }
h2 { margin-top:50px; }
.filtros { background:white; padding:15px; border-radius:12px; box-shadow:0 2px 5px rgba(0,0,0,0.1); margin-bottom:30px; }
.filtros select { padding:8px; border-radius:8px; border:1px solid #ccc; margin-right:10px; }
.prenda { background:white; padding:15px; border-radius:12px; box-shadow:0 2px 5px rgba(0,0,0,0.1); margin-bottom:20px; }
.fotos { display:grid; grid-template-columns:repeat(auto-fit,minmax(150px,1fr)); gap:10px; margin-top:10px; }
.fotos img { width:100%; border-radius:10px; }
.talla { font-weight:bold; margin-top:10px; }
footer { background:#111; color:white; text-align:center; padding:20px; margin-top:40px; }
</style>
</head>
<body>
<header>
<h1>Mi Catálogo de Ropa</h1>
<nav>
<a href="#playeras">Playeras</a>
<a href="#pantalones">Pantalones</a>
<a href="#sudaderas">Sudaderas</a>
<a href="#contacto">Contacto</a>
</nav>
</header>

<div class="container">
<div class="filtros">
<h3>Filtros</h3>
<select>
<option>Todas las tallas</option>
<option>S</option>
<option>M</option>
<option>L</option>
<option>XL</option>
</select>
<select>
<option>Todas las categorías</option>
<option>Playeras</option>
<option>Pantalones</option>
<option>Sudaderas</option>
</select>
</div>

<h2 id="playeras">Playeras</h2>
<div class="prenda">
<h3>Playera Blanca Clásica</h3>
<p class="talla">Tallas: S, M, L, XL</p>
<div class="fotos">
<img src="foto1.jpg">
<img src="foto2.jpg">
<img src="foto3.jpg">
<img src="foto4.jpg">
</div>
</div>

<h2 id="pantalones">Pantalones</h2>
<div class="prenda">
<h3>Pantalón Negro Slim</h3>
<p class="talla">Tallas: 30, 32, 34, 36</p>
<div class="fotos">
<img src="foto1.jpg">
<img src="foto2.jpg">
<img src="foto3.jpg">
<img src="foto4.jpg">
</div>
</div>

<h2 id="Sueteres">Sueteres</h2>
<div class="prenda">
<h3>Sueter navideño</h3>
<p class="talla">Talla: S</p>
<div class="fotos">
<img src="img-ropa/sueter_navidad_f.JPEG">
<img src="img-ropa/sueter_navidad_a.JPEG">
<img src="img-ropa/sueter_navidad_e.JPEG">
<img src="img-ropa/sueter_navidad_x.JPEG">
</div>
</div>

<h2 id="contacto">Contacto</h2>
<div class="prenda">
<h3>Haz tu pedido</h3>
<p>Envíame un mensaje por WhatsApp:</p>
<p><strong>55 0000 0000</strong></p>
</div>
</div>

<footer>
<p>Catálogo creado por mí 😎</p>
</footer>

</body>
</html>
