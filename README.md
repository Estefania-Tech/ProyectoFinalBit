*Proyecto Final*

Desarrollar una aplicación web funcional que integre un frontend en Angular 
con un backend construido con Node.js, Express y MongoDB, aplicando buenas prácticas de desarrollo full stack.

*Enrutamiento de Angular*

se implementaron tres vistas de navegación, las cuales son:

**Iniciar sesión**
http://localhost:4200/login
Se implementan validaciones básicas como lo son el correo, contraseña
si los credenciales exiten será redirigido a notas de manera satisfactoria

**Registrarse**
http://localhost:4200/register
Se requieren de campos requeridos como el nombre, correo y contraseña,
al dar clic en el botón de Registrarse será redireccionado automaticamente a Iniciar sesión

**Notas**
http://localhost:4200/notas
en esta vista de navegación se verán las listas actuales en el momento, deberá permitir la 
eliminación de estas, así como el de modificar o añadir una nueva nota, a su vez en la parte superior
se encontrará el botón de Cerrar sesión que lo redireccionara a iniciar sesión vista principal del 
proyecto.

**Errores en el proyecto**
en la vista **Notas**, no permite añadir una nueva nota, ni modificarla
el localhost arroja uyn error en la que no se encuentra el ID del usuario 
que ha iniciado sesión y para  realizar dichas acciones es necesaria un id para poder identificar 
las notas añadidas de cada usuario.
