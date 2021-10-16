# Ejercicio5
Detalle ejercicio 5 curso Kubernetes

HEALTHCHECK: 
En una instruccion que se utiliza para la verificación de estado de un contenedor en la definición de imagen. 
Puede suceder que el estado del contenedor sea Up pero la aplicacion que corre dentro este dando errores, es decir, el contenedor puede estar activo, pero no hay forma de que la aplicación dentro del contenedor proporcione un estado.
Esta instrucción sirve para eso, para poder informar un fallo de la aplicacion.

ONBUILD:
La instrucción ONBUILD agrega a la imagen una instrucción que se ejecutará en un momento posterior, cuando la imagen se use como base para otra construcción. 
El disparador se ejecutará en el contexto de la imagen que lo use como base, como si se hubiera insertado inmediatamente después de la instrucción FROM.

VOLUME:
Los contenedores Docker se utilizan para ejecutar aplicaciones en un entorno aislado. 
De forma predeterminada, todos los cambios dentro del contenedor se pierden cuando el contenedor se detiene. 
Los Volumenes se utilizan para mantener los datos entre ejecuciones.
Son sistemas de archivos montados en contenedores de Docker para conservar los datos generados por el contenedor en ejecución.
