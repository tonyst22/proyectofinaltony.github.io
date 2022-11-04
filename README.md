# proyectofinaltony.github.io
proyecto final de primer año
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Inicio-Sesion</title>
  <link rel="stylesheet" href="iniciosision.css">
  <link rel="shortcut icon" href="img/htmlcode.png"  />
</head>

<body>

   <!--FORMULARIO---->
   <form class="form" action="inicio/inicio.html" method="POST">
        
    <!--TITULO------------------------>
    <h1 class="titulo">Inicio Sesion</h1>
    
    <!--CAJAS-DE-ENTRADA-DE-DATOS------------------------------------------------>
    
    <input class="cajas" type="email" placeholder="Email" maxlength="30" required>
    <input class="cajas" type="password" placeholder="Password" minlength="7" required maxlength="30">
    
    
    <!--BOTON-DE-REGISTRARSE-------------------------->
    <input type="submit" class="btn" value="Iniciar Sesion" required>
    
    <!--YA-TENGO-CUENTA----------------------------------------------------------->
    <p class="tengo-cuenta"><a href="registro.html" class="tengo-cuenta">crear cuenta</a></p>
    
</form>


</body>

</html>
