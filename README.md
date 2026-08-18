<!DOCTYPE html>
<html lang="es">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Pachuca FC</title>

<style>

body{
margin:0;
font-family:Arial,sans-serif;
background:#071b35;
color:white;
}

header{
background:#001b3a;
text-align:center;
padding:25px;
}

h1{
margin:0;
font-size:32px;
}

.menu{
display:flex;
overflow:auto;
background:#031329;
padding:10px;
gap:8px;
}

.menu button{
background:#17436d;
color:white;
border:0;
border-radius:10px;
padding:12px;
font-weight:bold;
}

.seccion{
display:none;
padding:20px;
max-width:600px;
margin:auto;
}

.activa{
display:block;
}

.card{
background:#102b4d;
padding:18px;
margin:15px 0;
border-radius:15px;
}

.jugador{
background:#17436d;
padding:12px;
margin:7px 0;
border-radius:9px;
}

.numero{
font-size:30px;
font-weight:bold;
}

footer{
text-align:center;
padding:30px;
color:#aaa;
}

</style>

</head>

<body>

<header>

<h1>🔵⚪ PACHUCA</h1>

<p>Los Tuzos</p>

</header>


<div class="menu">

<button onclick="abrir('inicio')">
🏠 Inicio
</button>

<button onclick="abrir('jugadores')">
👥 Jugadores
</button>

<button onclick="abrir('partidos')">
📅 Partidos
</button>

<button onclick="abrir('datos')">
📊 Datos
</button>

<button onclick="abrir('titulos')">
🏆 Títulos
</button>

</div>


<section id="inicio" class="seccion activa">

<h2>🏠 Pachuca FC</h2>

<div class="card">

<h2>🔵⚪ Club de Fútbol Pachuca</h2>

<p>
Bienvenido a la página de los Tuzos.
</p>

<p>📍 Pachuca, Hidalgo</p>

<p>🏟️ Estadio Hidalgo</p>

<p>🇲🇽 Liga MX</p>

</div>

<div class="card">

<h3>🔥 Último partido</h3>

<p>Pachuca 1 - 2 Querétaro</p>

<p>⚽ Gol: Salomón Rondón</p>

</div>

</section>


<section id="jugadores" class="seccion">

<h2>👥 Jugadores</h2>

<div class="card">

<h3>🧤 Portero</h3>

<div class="jugador">
#25 Carlos Moreno
</div>

</div>


<div class="card">

<h3>🛡️ Defensas</h3>

<div class="jugador">
#22 Alan Mozo
</div>

<div class="jugador">
#4 Eduardo Bauermann
</div>

<div class="jugador">
#2 Sergio Barreto
</div>

<div class="jugador">
#15 Francisco Venegas
</div>

</div>


<div class="card">

<h3>🎯 Mediocampistas</h3>

<div class="jugador">
#16 Christian Rivera
</div>

<div class="jugador">
#10 Elías Montiel
</div>

<div class="jugador">
#7 Rodolfo Pizarro
</div>

</div>


<div class="card">

<h3>🔥 Atacantes</h3>

<div class="jugador">
#11 Oussama Idrissi
</div>

<div class="jugador">
#29 Robert Kenedy
</div>

<div class="jugador">
#23 Salomón Rondón
</div>

</div>

</section>


<section id="partidos" class="seccion">

<h2>📅 Partidos</h2>

<div class="card">

<h3>Pachuca 1 - 2 Querétaro</h3>

<p>🇲🇽 Liga MX</p>

<p>⚽ Salomón Rondón</p>

</div>

<div class="card">

<h3>Próximos partidos</h3>

<p>📅 Aquí puedes agregar los siguientes partidos.</p>

</div>

</section>


<section id="datos" class="seccion">

<h2>📊 Datos</h2>

<div class="card">

<h3>⚽ Estadísticas</h3>

<p>Partidos: 2</p>

<p>Victorias: 1</p>

<p>Empates: 0</p>

<p>Derrotas: 1</p>

</div>

<div class="card">

<h3>🔥 Goleador</h3>

<p class="numero">Salomón Rondón</p>

<p>⚽ 1 gol</p>

</div>

<div class="card">

<h3>🌎 Competiciones</h3>

<p>🇲🇽 Liga MX</p>

<p>🌎 Concacaf</p>

<p>🇺🇸 Leagues Cup</p>

</div>

</section>


<section id="titulos" class="seccion">

<h2>🏆 Títulos</h2>

<div class="card">

<h3>🇲🇽 México</h3>

<p>🏆 Liga MX</p>

<p>🏆 Copa MX</p>

<p>🏆 Campeón de Campeones</p>

</div>

<div class="card">

<h3>🌎 Internacional</h3>

<p>🏆 Concacaf Champions Cup</p>

</div>

<div class="card">

<h3>📖 Historia</h3>

<p>
Pachuca es uno de los clubes históricos
del fútbol mexicano.
</p>

</div>

</section>


<footer>

🔵⚪ PACHUCA FC

<br><br>

Página hecha por un aficionado

</footer>


<script>

function abrir(nombre){

let secciones =
document.querySelectorAll(".seccion");

secciones.forEach(function(seccion){

seccion.classList.remove("activa");

});

document.getElementById(nombre)
.classList.add("activa");

window.scrollTo(0,0);

}

</script>

</body>

</html>
