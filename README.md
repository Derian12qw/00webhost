<!DOCTYPE html>
<html>
<head>
<title>Contenido Diseño y Desarrollo Web</title>
<style>
h1::before {  
  transform: scaleX(0);
  transform-origin: bottom right;
}
h1:hover::before {
  transform: scaleX(1);
  transform-origin: bottom left;
}
h1::before {
  content: " ";
  display: block;
  position: relative;
  top: 0; right: 0; bottom: 0; left: 0;
  inset: 0 0 0 0;
  background:#CCD1D1 ;
  z-index: -1;
  transition: transform 1s ease;
}

h1{
  position: relative;
  font-size: 60px;
  font-family: Showcard Gothic;
}
h2{

  font-size: 40px;
  font-family: Showcard Gothic;
}
h3{

  font-size: 24px;
  font-family: Showcard Gothic;
}
body{
	margin:0.2;
	font-family: Segoe UI;
	font-size: 12px;
}
.menu-wrapper ul{
	padding: 0;
	list-style: none;
}
.principal-menu > li {
	display: inline-block;
}

.principal-menu > li > a{
	display: block;
	padding: 10px 5px;
	width: 200px;
}

li ul{
	position: absolute;
	display: none;
}

.sub-menu a{
	display: block;
	padding: 10px 5px;
	width: 130px;
}

li:hover ul{
	display: block;
}

.menu-wrapper, li ul{
	background:#212F3D  ; 
}

.principal-menu{
	width: 1300px;
	margin: 0 auto;
}

.principal-menu a{
	color:#7DCEA0   ;
	text-decoration: none;
	font-weight: bold;
        font-size: 13px;
}

.principal-menu li:hover{
	background:#212F3D ;
	text-shadow: 0 0 2px #000;
}


</style>
</head>
<body bgcolor="#D5DBDB   ">
<center>
<h2>PROYECTO TÉCNICO AREA INFORMATICA 2024-2025</h1>
<a href="proyectotecnico.html"><img src="C:\Users\USER1\Desktop\fnfan\images.jpg" width="150px" height="150px"></a>
<div class="menu-wrapper">
	<ul class="principal-menu">
	<li><a href="proyectotecnico.html">Inicio</a></li>
	<li><a href="">Soporte Técnico</a>
		<ul class="sub-menu">
			<li><a href="soporte1trimestre.html">Primer Trimestre</a></li>
			<li><a href="soporte2trimestre.html">Segundo Trimestre</a></li>
			<li><a href="soporte3trimestre.html">Tercer Trimestre</a></li>
		</ul>
	</li>
	<li><a href="#">Programación y Base de Datos</a>
		<ul class="sub-menu">
			<li><a href="programacion1trimestre.html">Primer Trimestre</a></li>
			<li><a href="programacion2trimestre.html">Segundo Trimestre</a></li>
			<li><a href="programacion3trimestre.html">Tercer Trimestre</a></li>
		</ul>
	</li>
<li><a href="#">Sistemas Operativos y Redes</a>
		<ul class="sub-menu">
			<li><a href="sistemas1trimestre.html">Primer Trimestre</a></li>
			<li><a href="sistemas2trimestre.html">Segundo Trimestre</a></li>
			<li><a href="sistemas3trimestre.html">Tercer Trimestre</a></li>
		</ul>
	</li>
	<li><a href="#">Diseño y Desarrollo Web</a>
		<ul class="sub-menu">
			<li><a href="diseño1trimestre.html">Primer Trimestre</a></li>
			<li><a href="diseño2trimestre.html">Segundo Trimestre</a></li>
			<li><a href="diseño3trimestre.html">Tercer Trimestre</a></li>
			<li><a href="contenido_d.html">Contenido</a></li>

	         </ul>
	</li>



<li><a href="#">FOL</a>
		<ul class="sub-menu">
			<li><a href="sistemas1trimestre.html">Primer Trimestre</a></li>
			<li><a href="sistemas2trimestre.html">Segundo Trimestre</a></li>
			<li><a href="sistemas3trimestre.html">Tercer Trimestre</a></li>
		</ul>

<img src="C:\Users\zumba\Downloads\images (1).zip" width="300px" height="200px"/>
