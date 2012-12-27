diseno-twitter
==============
<!DOCTYPE html>
<html lang="es">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<script language="javascript" src="http://code.jquery.com/jquery-1.8.3.min.js"></script>
<script>
$(document).ready(function(e) {
	var alto = $("#contenedor").css("height");
	$("#footer").css("height",alto);
    $("#inner2").mouseenter(function(){
		$("#inner").animate({"opacity":"0"},3000);
		})
	 $("#inner2").mouseleave(function(){
		$("#inner").animate({"opacity":"1"},2000);
		})	
});
</script>
<link rel="stylesheet" href="css/css.css" />
<title>Untitled Document</title>
</head>

<body>
<div id="contenedor">

    <div id="menu">     
        <div id="inner2"></div>
        <div id="inner"></div>
    </div>
	<div id="contenido"><h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3>
    <h3><--- Pasen el Mouse Por encima del borde de la imagen</h3></div>
    <div id="header"><!--este es el menu-->
    	<ul>
        	<li><a href="">Inicio</a></li>
           	<li><a href="">Contactos</a></li>
            <li><a href="">B&uacute;squeda</a></li>
            <li><a href="">Tendencias</a></li>
            <li><a href="">Configurar</a></li>
        </ul>
    </div>
<div id="footer"></div>

</div>
</body>
</html>
