# cursoDocker_modulo3
Ejercicios del curso de docker modulo3

# Ejercicios Curso de Docker

Como ya hemos visto en el curso hemos aprendido como utilizar Docker.

# Environment - Entorno

Maquina virtual Linux en Vmware o VirtualBox. Instancia en cualquier provider cloud o uso de la terminal Linux con Docker en su computadora. <br>
Necesario tener instalado Docker y docker-compose mediante la documentación oficial.

# Prueba de herramienta docker y docker-compose

Una vez instalado ejecutando ``` docker run -ti -p 80:80 httpd:latest ``` puede comprobar como se puede desplegar un servidor httpd.

# Envio de los ejercicios

Los ejercicios estan subidos Modulo por modulo, y tienen que subirlo tal en su fichero, en el caso de que tenga que crear un script, introducir los comandos dentro, en caso de que sea un docker-compose.yaml o Dockerfile subir estos ficheros.

# Acceso a Documentacion

Hay documentacion tanto en mis repositorios en github/crcasis o gitlab/crcasis. <br>
Hay documentacion en las páginas oficiales y siempre es interesante apoyarse en hub.docker.io

# Como subir el contenido al repositorio

```
repository="https://repository.example.git" 
git clone $repository
git add . 
git commit -m "ejercicios curso de docker"
git push
```

