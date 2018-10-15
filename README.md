Taller de Docker
================

dockerfile-tarea-1
---------

Dentro de esta carpeta encontraran una simple aplicacion escrita en NodeJS, y dentro del archivo READNE encontraran
las instrucciones especificadas por el desarrollador de la aplicacion, para que puedan proceder a Dockerizar la misma.

El objetivo de esta tarea es entonces :

1. Escribir el archivo Dockerfile en base a las instrucciones dadas por el desarrolaldor
2. Contruir la imagen de la aplicacion NodeJS
3. Subir la imagen a un repositorio Docker Hub personal
4. Ejecutar la aplicacion y mostar evidencia de su ejecucion y correcto funcionamiento
5. Subir a un repositorio github personal, el archivo Dockerfile asi como evidencia de la correcta ejecucion de la aplicacion.

Solucion
---------
[Docker Hub Link](https://hub.docker.com/r/jpoh97/udea_tarea1/ "jpoh97 docker hub")

docker build: 
![alt text](https://github.com/jpoh97/udea_docker_taller_1/blob/master/dockerfile-tarea-1/evidences/Docker%20build.PNG "docker build")

docker run: 
![alt text](https://github.com/jpoh97/udea_docker_taller_1/blob/master/dockerfile-tarea-1/evidences/Docker%20run.PNG "docker run")

docker run from dockerhub: 
![alt text](https://github.com/jpoh97/udea_docker_taller_1/blob/master/dockerfile-tarea-1/evidences/Docker%20run%20from%20dockerhub.PNG "docker run from dockerhub")

app running: 
![alt text](https://github.com/jpoh97/udea_docker_taller_1/blob/master/dockerfile-tarea-1/evidences/Running.PNG "nodejs app running")

dockerfile-tarea-2
---------

Dentro de esta carpeta encontraran un diagrama simple de arquitectura de alto nivel, de una aplicacion que debe ser desarrollada con patron de microservicios y desplegada usando Docker Compose.

El objetivo de esta tarea es entonces :

1. Escribir el archivo docker-compose.yml usando las instrucciones dadas dentro de la carpeta
2. Para el microservicio de frontend y backend se puede seleccionar el lenguaje de programacion preferido
3. El motor de de Base de Datos usado debe ser MySQL
4. La logica/caso de uso a desarrollar en el microservicio queda a discrecion del estudiante
5. Para facilidad en la resolucion del taller, el estudiante puede usar los microservicios desarrollados en el curso anterior.