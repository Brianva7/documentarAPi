## Al loguear con el usuario amdnistrador (ADMINCODER) es posible acceder al endpoint localhost:8080/users, la vista desde la cual es posible modificar el rol del usario (no permitiendo la modificacion del usuario administrador)

## Rol PREMIUM agregado y los permisos fueron modificados directamente desde el middleware de auth

## Para recuperar la contraseña agregue un enlace en /login. el mail sera enviado por defecto a la direccion statica del transport.sendmail desde la funcion forgotPassword() [./src/controllers/sessions.controller.js]

![transporterConfig](/src/public/img/transport.PNG)

## modificar para recibir el endpoint! :D

## /apidocs GET: products (como ejemplo)

![swaggerUi](/src/public/img/swaggerUi.PNG)
