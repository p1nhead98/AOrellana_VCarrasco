Integrantes: 
Vicente Carrasco
Alfredo Orellana

Cuenta del admin:
Nombre de usuario: admin
Contrase�a: supercontra

Cuenta de user:
Nombre de usuario: matgo98
contrase�a: contrase�a123

Esta pagina consiste en un portal dirigido a los desarrolladores de videojuegos independientes, para ellos poder subir sus creaciones
tanto como juegos, o cualquier tipo de material que sirva de apoyo para el desarrollo de estos, en la web
se puede iniciar sesion, registrar una cuenta, crear publicaciones, modificarlas y eliminarlas, el proyecto
contiene pruebas unitarias, views, templates, forms y modelos, todos los datos ingresados se almacenan
en la base de datos incorporada en Django.

Este proyecto esta sujeto a futuras actualizaciones ya sea con mayor cantidad de opciones y/o funcionalidades
o mejoras en el codigo del proyecto mismo



Intrucciones de uso:

-------------------------------------------------------------------------------------------------------------------
Indice de Pagina: 
Lo primero que se puede apreciar es una breve descripcion de lo que trata el sitio web, 
seguido a esto se muestra el listado de juegos que ya se encuentran alojados en el sitio.

Al seleccionar el titulo de uno de los juegos en el listado este te llevara a la pagina del post del juego, con 
mas informacion y boton de descarga del juego.

En el baner de la pagina esta el nombre de esta con las opciones "Inicio" y "Nuevo Proyecto", al 
seleccionar inicio este lleva al index y al seleccionar nuevo proyecto este llevara al formulario para 
ingresar un juego nuevo dentro de la pagina.
-------------------------------------------------------------------------------------------------------------------------
Iniciar sesi�n:
Se tienen dos campos, el primero es de ingresar el username, y el segundo la contrase�a, junto a un boton de aceptar
tambien dentro del login esta la opcion para registrarse en la pagina web
-------------------------------------------------------------------------------------------------------------------------
Registrar:
Se tienen varios campos, de los cuales ni el nombre ni el apellido son obligatorios, no se puede ingresar username ni correos 
que ya se encuentren registrados en la pagina web
da opcion a iniciar sesion en caso de tener cuenta
------------------------------------------------------------------------------------------------------------------------
Cerrar sesion: 
Al ser seleccionado cerrara la sesion y rederigira a la pagina de incio de la web
-------------------------------------------------------------------------------------------------------------------------
Perfil:
Muestra los datos de la cuenta de user que se encuentra con la sesion iniciada, tambien tiene un enlace para ver los post filtrados
para mostrar los post realizados por el usuario que inicio sesion
-------------------------------------------------------------------------------------------------------------------------
Nuevo Proyecto:
dentro del formulario se encuentran distintos campos, tres de estos son obligatorios los cuales son "titulo", "Descripcion General" y "Juego"
las demas son optativas, pero les dan mas estilo y personalizan mejor cada post de algun juego
-------------------------------------------------------------------------------------------------------------------------
Pagina de los post:
Al seleccionar un juego en el listado de juegos del index este redireccionara a una pagina con mas detalles del juego,
este esta compuesto por las descripciones, imagenes subidas en el formulario, fecha de subida, boton de descarga,
y al principio de la pagina se encuentran dos botones "Editar Post" y "Eliminar Post".
-------------------------------------------------------------------------------------------------------------------------
Editar Post: 
Esta pagina es seleccionada a traves del boton de "Editar Post" en la pagina de algun juego subido, es igual al formulario para
subir un nuevo proyecto, y cualquier campo puede ser modificado, tiene el boton de "Subir" para guardar los cambios como el de "Cancelar"
que redireccionara a la pagina de index. Esta pagina solo puede ser usado por la cuenta del user que haya subido el post, los usuarios 
que no sean los autores del post no pueden acceder, mientras que las cuentas de tipo admin, pueden editar cualquier post de cualquier usuario
--------------------------------------------------------------------------------------------------------------------------
Eliminar Post:
Esta pagina es seleccionada a traves del boton "Eliminar Post" en la pagina de algun juego subido, esta solo es un texto 
preguntando si se desea eliminar el proyecto, con los botones "Si, Eliminar" y "Cancelar", el primero eliminara
el post de los registros y redireccionara a la pagina index, mientras el segundo sol redireccionara al index sin eliminar
el post. Esta pagina solo puede ser usado por la cuenta del user que haya subido el post, los usuarios 
que no sean los autores del post no pueden acceder, mientras que las cuentas de tipo admin, pueden eliminar cualquier post de cualquier usuario
