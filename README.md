
 <!DOCTYPE html>
<html lang="es">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Pachuca FC</title>

<style>

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #071b35;
    color: white;
}

header {
    background: #001b3a;
    text-align: center;
    padding: 25px;
    border-bottom: 3px solid #39a9ff;
}

header h1 {
    margin: 0;
    font-size: 32px;
}

.menu {
    background: #031329;
    padding: 10px;
    text-align: center;
    overflow-x: auto;
}

.menu button {
    background: #17436d;
    color: white;
    border: 0;
    padding: 11px;
    margin: 3px;
    border-radius: 8px;
    font-weight: bold;
}

.seccion {
    display: none;
    max-width: 650px;
    margin: auto;
    padding: 20px;
}

.activa {
    display: block;
}

.card {
    background: #102b4d;
    padding: 18px;
    margin-bottom: 15px;
    border-radius: 14px;
}

.jugador {
    background: #17436d;
    padding: 12px;
    margin: 7px 0;
    border-radius: 8px;
}

.partido {
    border-left: 5px solid #39a9ff;
}

.ganado {
    color: #48e08a;
}

.perdido {
    color: #ff7373;
}

.numero {
    font-size: 30px;
    font-weight: bold;
}

.tabla {
    width: 100%;
    border-collapse: collapse;
    font-size: 13px;
}

.tabla th {
    background: #06182d;
    padding: 8px;
}

.tabla td {
    padding: 8px 4px;
    border-bottom: 1px solid #315273;
    text-align: center;
}

.pachuca {
    background: #1767a5;
    font-weight: bold;
}

footer {
    text-align: center;
    padding: 30px;
    color: #aaa;
}

</style>

</head>


<body>


<header>

<h1>🔵⚪ PACHUCA</h1>

<p>Los Tuzos</p>

</header>


<div class="menu">

<button onclick="mostrar('inicio')">
🏠 Inicio
</button>

<button onclick="mostrar('jugadores')">
👥 Jugadores
</button>

<button onclick="mostrar('partidos')">
📅 Partidos
</button>

<button onclick="mostrar('tabla')">
📊 Tabla
</button>

<button onclick="mostrar('historia')">
📖 Historia
</button>

<button onclick="mostrar('titulos')">
🏆 Títulos
</button>

</div>


<!-- INICIO -->

<section id="inicio" class="seccion activa">

<h2>🏠 Pachuca FC</h2>


<div class="card">

<h2>🔵⚪ Club de Fútbol Pachuca</h2>

<p>
Bienvenido a la página de los Tuzos.
</p>

<p>
📍 Pachuca, Hidalgo, México
</p>

<p>
🏟️ Estadio Hidalgo
</p>

<p>
🇲🇽 Liga MX
</p>

</div>


<div class="card">

<h3>🔥 Último partido</h3>

<h2>
Pachuca 2 - 3 Puebla
</h2>

<p>
📅 Jornada 4 · Apertura 2026
</p>

<p class="perdido">
❌ Derrota
</p>

<p>
🏟️ Estadio Hidalgo
</p>

</div>


<div class="card">

<h3>📊 Pachuca en el torneo</h3>

<p>
Partidos: <strong>4</strong>
</p>

<p>
Victorias: <strong>1</strong>
</p>

<p>
Empates: <strong>0</strong>
</p>

<p>
Derrotas: <strong>3</strong>
</p>

<p>
Goles a favor: <strong>6</strong>
</p>

<p>
Goles en contra: <strong>6</strong>
</p>

<p>
Puntos: <strong>3</strong>
</p>

</div>

</section>


<!-- JUGADORES -->

<section id="jugadores" class="seccion">

<h2>👥 Jugadores</h2>

<p>
Jugadores utilizados en jornadas recientes.
</p>


<div class="card">

<h3>🧤 Porteros</h3>

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


<!-- PARTIDOS -->

<section id="partidos" class="seccion">

<h2>📅 Partidos</h2>


<div class="card partido">

<p>Jornada 1</p>

<h3>UNAM 0 - 3 PACHUCA</h3>

<p class="ganado">
✅ Victoria
</p>

</div>


<div class="card partido">

<p>Jornada 2</p>

<h3>PACHUCA 1 - 2 QUERÉTARO</h3>

<p class="perdido">
❌ Derrota
</p>

</div>


<div class="card partido">

<p>Jornada 3</p>

<h3>LEÓN 1 - 0 PACHUCA</h3>

<p class="perdido">
❌ Derrota
</p>

</div>


<div class="card partido">

<p>Jornada 4</p>

<h3>PACHUCA 2 - 3 PUEBLA</h3>

<p class="perdido">
❌ Derrota
</p>

</div>


<div class="card">

<h3>📌 Próximo partido</h3>

<p>
Aquí puedes agregar el siguiente partido
cuando esté confirmado.
</p>

</div>

</section>


<!-- TABLA -->

<section id="tabla" class="seccion">

<h2>📊 Tabla de posiciones</h2>

<p>
Liga MX · Apertura 2026 · Jornada 4
</p>


<div class="card">

<table class="tabla">

<tr>

<th>#</th>
<th>Equipo</th>
<th>J</th>
<th>G</th>
<th>E</th>
<th>P</th>
<th>DIF</th>
<th>PTS</th>

</tr>


<tr>
<td>1</td>
<td>América</td>
<td>4</td>
<td>3</td>
<td>1</td>
<td>0</td>
<td>+7</td>
<td>10</td>
</tr>


<tr>
<td>2</td>
<td>Tijuana</td>
<td>4</td>
<td>3</td>
<td>1</td>
<td>0</td>
<td>+4</td>
<td>10</td>
</tr>


<tr>
<td>3</td>
<td>Monterrey</td>
<td>4</td>
<td>3</td>
<td>0</td>
<td>1</td>
<td>+7</td>
<td>9</td>
</tr>


<tr>
<td>4</td>
<td>Atlas</td>
<td>4</td>
<td>3</td>
<td>0</td>
<td>1</td>
<td>+1</td>
<td>9</td>
</tr>


<tr>
<td>5</td>
<td>Toluca</td>
<td>4</td>
<td>2</td>
<td>1</td>
<td>1</td>
<td>+3</td>
<td>7</td>
</tr>


<tr>
<td>6</td>
<td>Pumas</td>
<td>4</td>
<td>2</td>
<td>1</td>
<td>1</td>
<td>+2</td>
<td>7</td>
</tr>


<tr>
<td>7</td>
<td>Puebla</td>
<td>4</td>
<td>2</td>
<td>1</td>
<td>1</td>
<td>+1</td>
<td>7</td>
</tr>


<tr>
<td>8</td>
<td>Querétaro</td>
<td>4</td>
<td>2</td>
<td>1</td>
<td>1</td>
<td>+1</td>
<td>7</td>
</tr>


<tr>
<td>9</td>
<td>Guadalajara</td>
<td>4</td>
<td>2</td>
<td>1</td>
<td>1</td>
<td>0</td>
<td>7</td>
</tr>


<tr>
<td>10</td>
<td>Cruz Azul</td>
<td>4</td>
<td>2</td>
<td>0</td>
<td>2</td>
<td>0</td>
<td>6</td>
</tr>


<tr>
<td>11</td>
<td>León</td>
<td>4</td>
<td>2</td>
<td>0</td>
<td>2</td>
<td>0</td>
<td>6</td>
</tr>


<tr>
<td>12</td>
<td>Necaxa</td>
<td>4</td>
<td>2</td>
<td>0</td>
<td>2</td>
<td>-1</td>
<td>6</td>
</tr>


<tr>
<td>13</td>
<td>Atlante</td>
<td>4</td>
<td>1</td>
<td>2</td>
<td>1</td>
<td>0</td>
<td>5</td>
</tr>


<tr class="pachuca">
<td>14</td>
<td>🔵 Pachuca</td>
<td>4</td>
<td>1</td>
<td>0</td>
<td>3</td>
<td>0</td>
<td>3</td>
</tr>


<tr>
<td>15</td>
<td>Atl. San Luis</td>
<td>4</td>
<td>0</td>
<td>2</td>
<td>2</td>
<td>-4</td>
<td>2</td>
</tr>


<tr>
<td>16</td>
<td>Tigres</td>
<td>4</td>
<td>0</td>
<td>1</td>
<td>3</td>
<td>-4</td>
<td>1</td>
</tr>


<tr>
<td>17</td>
<td>Santos</td>
<td>4</td>
<td>0</td>
<td>0</td>
<td>4</td>
<td>-6</td>
<td>0</td>
</tr>


<tr>
<td>18</td>
<td>Juárez</td>
<td>4</td>
<td>0</td>
<td>0</td>
<td>4</td>
<td>-11</td>
<td>0</td>
</tr>

</table>

</div>

</section>


<!-- HISTORIA -->

<section id="historia" class="seccion">

<h2>📖 Historia del Pachuca</h2>


<div class="card">

<h3>📅 1892</h3>

<p>
El Pachuca Football Club fue fundado
el 1 de noviembre de 1892.
</p>

<p>
Es considerado el club más antiguo
del fútbol mexicano.
</p>

</div>


<div class="card">

<h3>🏟️ Estadio Hidalgo</h3>

<p>
El Pachuca disputa sus partidos como
local en el Estadio Hidalgo.
</p>

<p>
El estadio fue inaugurado en 1993.
</p>

</div>


<div class="card">

<h3>🌎 Copa Sudamericana 2006</h3>

<p>
Pachuca ganó la Copa Sudamericana
en 2006.
</p>

<p>
Fue un título histórico para el fútbol
mexicano.
</p>

</div>


<div class="card">

<h3>🏆 Concacaf</h3>

<p>
Pachuca conquistó su sexta Copa de
Campeones de la Concacaf en 2024.
</p>

<p>
Derrotó 3-0 al Columbus Crew
en la final.
</p>

</div>


<div class="card">

<h3>🌎 Mundial de Clubes</h3>

<p>
Pachuca ha participado en diferentes
ediciones del Mundial de Clubes.
</p>

<p>
Su mejor actuación histórica en el
torneo fue el tercer lugar de 2017.
</p>

</div>

</section>


<!-- TITULOS -->

<section id="titulos" class="seccion">

<h2>🏆 Títulos</h2>


<div class="card">

<h3>🇲🇽 México</h3>

<p>
🏆 7 títulos de Liga MX
</p>

<p>
🏆 Copa MX
</p>

<p>
🏆 Campeón de Campeones
</p>

</div>


<div class="card">

<h3>🌎 Internacionales</h3>

<p>
🏆 6 Copas de Campeones de Concacaf
</p>

<p>
🏆 Copa Sudamericana 2006
</p>

<p>
🏆 Derbi de las Américas
</p>

<p>
🏆 Copa Challenger
</p>

</div>

</section>


<footer>

🔵⚪ PACHUCA FC

<br><br>

Página de aficionado

</footer>


<script>

function mostrar(nombre) {

    var secciones =
    document.getElementsByClassName("seccion");

    for (var i = 0; i < secciones.length; i++) {

        secciones[i].style.display = "none";

    }

    document.getElementById(nombre).style.display = "block";

    window.scrollTo(0, 0);

}

</script>


</body>

</html>
