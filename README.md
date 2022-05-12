Para el fichero de Dockfile:
	- FROM httpd:latest *este comando sirve para indifcar donde se encuentra la imagen*

terminal:
	- docker pull * permite descargar la imagen mas reciente de ese repositorio.
	- docker build -t *para crear la imagen*
	- docker run -p puerto:puerto *ya teniendo el contenedor sirve para ponerlo en funcionamiento y debemos poner tambien el puerto*.
	- docker stop *este comando detendrá el contenedor que se está ejecutando, debemos poner el nombre/ID para hacer esto posible*
	- docker ps *muestra los contenedores que están en ejecución y te da algo de información sobre ellos como el nombre, el estado o cuando se creó.*
	- docker rm *elimina un contenedor*
	- docker container cp *copia archivos*
	- docker ps -a detalla los contenedores y los enumera*
	- docker rmi *remueve la imagen*
	- docker restart *reinicia el contenedor*
	- -d *modo demonio*

