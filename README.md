<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Parfym</title>
</head>
<body>
	<header>
		<h2><em>LOGIN</em></h2>
	</header>
	<section>
		<form action="registro.jsp" method="POST">
			<label for="nombre">Nombre</label>
			<br>
			<input type="text" name="nombre" required/>
			<br>
			<label for="apellidos">Apellidos</label>
			<br>
			<input type="text" name="apellidos" required/>
			<br>
			<label for="fech_naci">Fecha Nacimiento</label>
			<br>
			<input type="date" name="fech_naci" required/>
			<br><br>
			<input name="submit" type="submit" value="Suscribirse" />
		</form>
		<br>
		<input onclick="window.location.href='inscritos.jsp'" name="submit" type="button" value="Inscritos"/>
	</section>
</body>
</html>
