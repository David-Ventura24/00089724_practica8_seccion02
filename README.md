<h1¿Cuál es la diferencia entre autenticación y autorización?</h1>
<h2>La autenticacion es como cuando el sistema te pregunta y vos quien sos? y vos le demostras quien ,  ejemplo
con usuario y contraseña. la autorizacion es lo que pasa después, una vez que ya saben quien sos, te dicen 
va, pero tenes permiso para hacer esto?. O sea, autenticación = identificarte, autorización = ver que podes hacer.</h2>

<h1¿Cuál es la función del token JWT en la guía?></h1>
<h2>El token JWT sirve para que despues de que el usuario inicie sesion, como Jerry con su email y contraseña, 
el servidor le de una especie de pase que debe incluir en cada peticion posterior. Ese token contiene informacion del usuario 
como su ID y esta firmado para que no se pueda falsificar. De esta forma los endpoints protegidos pueden saber si quien hace 
  la peticion ya se autentico  y si no lo hizo le bloquean el acceso y ya.</h2>
