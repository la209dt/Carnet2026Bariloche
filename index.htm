<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Verificación Alumno</title>

<style>
body{
font-family:Arial;
text-align:center;
padding:40px;
background:#f4f6f9;
}

.caja{
border-radius:12px;
padding:25px;
display:inline-block;
background:white;
box-shadow:0 8px 20px rgba(0,0,0,0.15);
}

.ok{
color:green;
font-size:24px;
font-weight:bold;
margin-top:10px;
}

.deuda{
color:red;
font-size:24px;
font-weight:bold;
margin-top:10px;
}

h3{
margin-bottom:5px;
}

</style>
</head>

<body>

<h2>Estado del Alumno</h2>

<div class="caja" id="resultado">
Cargando...
</div>

<script>

const sheetURL="https://docs.google.com/spreadsheets/d/e/2PACX-1vToHCd9b22CYUpGzyfPB4g3n9BkJnezkKKmWwiHvcwNeZ2Cke83w9bnJ29CP9bMTvGqMQ4zTWOemF9Z/pub?output=csv";

const params=new URLSearchParams(window.location.search);
const dniBuscado=params.get("dni");

async function buscar(){

const res=await fetch(sheetURL);
const data=await res.text();

const filas=data.split("\n").slice(1);

for(let fila of filas){

const col=fila.split(",");

const nombre=col[1];
const dni=col[2];
const estado=col[3];

if(dni==dniBuscado){

let textoEstado="";

if(estado && estado.toLowerCase().includes("deudor")){
textoEstado='<div class="deuda">DEUDOR ❌</div>';
}else{
textoEstado='<div class="ok">NO DEUDOR ✅</div>';
}

document.getElementById("resultado").innerHTML=`
<h3>${nombre}</h3>
<p>DNI: ${dni}</p>
${textoEstado}
`;

return;

}

}

document.getElementById("resultado").innerHTML="Alumno no encontrado";

}

buscar();

</script>

</body>
</html>
