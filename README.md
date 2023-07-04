# Desafio 6 - Implementación de login
** LEIBLICH Ezequiel Gaston
** Comisión 43345

El proyecto consistió en ajustar nuestro servidor principal para trabajar con un sistema de login completo. Se realizaron todas las vistas necesarias, siguiendo las instrucciones del hands-on lab, para gestionar el registro y el login de los usuarios. Además, se implementaron las correspondientes rutas de router para procesar dichas acciones.

Una vez que el login se completaba con éxito, se realizaba una redirección automática a la vista de productos. En esta vista, se añadió un mensaje de bienvenida personalizado que mostraba los datos del usuario que había iniciado sesión.

Un aspecto importante que se agregó al sistema fue la implementación de un sistema de roles. Si el correo ingresado en el login era "adminCoder@coder.com" y la contraseña correspondiente era "adminCod3r123", el usuario de la sesión tenía acceso a un campo adicional en su perfil. Por otro lado, todos los usuarios que no tuvieran el rol de administrador automáticamente se les asignaba el rol de "usuario".

Adicionalmente, se implementó un botón de "logout" en todas las vistas. Al hacer clic en este botón, se destruía la sesión del usuario y se redirigía de manera segura a la vista de login, donde podrían iniciar sesión nuevamente si así lo deseaban.

Durante el desarrollo del proyecto, se tuvo en cuenta que, si bien el diseño no era prioritario, las vistas debían ser claras y funcionales. Se puso especial atención en las redirecciones entre las diferentes vistas, asegurándose de que los usuarios fueran guiados de manera adecuada y fluida en su experiencia.

En resumen, el trabajo consistió en ajustar el servidor principal para trabajar con un sistema de login completo, incluyendo todas las vistas necesarias y las rutas de router correspondientes. Se implementó una redirección directa a la vista de productos después del login, junto con un mensaje de bienvenida personalizado. Además, se agregó un sistema de roles en el que los usuarios con el correo y contraseña específicos tenían acceso a un campo adicional, mientras que los demás usuarios tenían asignado el rol de "usuario". Por último, se incluyó un botón de "logout" para destruir la sesión y redirigir al usuario a la vista de login. Se tuvo en cuenta la funcionalidad de las sesiones sobre el diseño, pero se mantuvo un enfoque claro y eficiente en las vistas y las redirecciones.
