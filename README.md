# README.md
# Curso de Sistemas Operativos
Yulianna Araya Sibaja
Universidad Latinoamericana de Ciencia y Tecnología
ULACIT
2022

# comandos linux

| Comando | Descripción | Ejemplo de uso |
| ------------- | ------------- | ------------- |
|  pwd | muestra la ruta del directorio de trabajo actual    |  $pwd -- /home/users |
|  cd  |   cd .. - sirve para ir un directorio hacia atrás, cd (nombre de la carpeta/ruta) - sirve para ir directamente a la carpeta o ruta en específico, cd - sirve para ir directamente a la carpeta de inicio. | cd desktop              |
| ls   |  Se usa para ver el contenido de un directorio. ls -R listará todos los archivos en los subdirectorios, ls -a mostrará los archivos ocultos, ls -al listará los archivos y directorios con información detallada como los permisos, tamaño, proprietario, etc. | $ ls -lr               |
| cat archivo  |  crea un nuevo archivo                   |  $ cat informacion.txt                        |
| cp   |  copia los archivos del directorio actual a un directorio diferente. |  cp imagen.jpg /home/folder1      |
| mv   |  su uso principal es mover archivos o  cambiar el nombre de los archivos |   mv imagen.jpg /home/folder2 -- mv nombreviejo.ext nombrenuevo.ext |
| mkdir | crea un nuevo directorio  | mkdir peliculas      |
| rm   |   se usa para elminar directorios y el contenido dentro de ellos  |  rm -r elmina el directorio          |
| touch |  permite crear un nuevo archivo en blanco.     |  touch archivo1 | 
| sudo  |  permite realizar tareas que requieren permisos administrativos o raíz    |   sudo nano /etc/hosts/                       |
| top                       |  mostrará una lista de los procesos en ejecución y la cantidad de CPU que utiliza cada proceso   |   $ sudo top                       |
| history         |   lista los comandos que ingresados anteriormente                                        |    $ history  grep update                     |
| clear  |   utilizado para limpiar la línea de comandos       |  $ clear                        |
| htop       | usado para monitorear los recursos vitales del sistema o los procesos en tiempo real.    |                          |
| su        |  se usa para obtener permisos de root para operaciones administrativas.   |  $ sudo su                        |
| stat       |  muestra información detallada sobre archivos o sistemas de archivos determinados    |   $ stat informacion.txt              |
| file       |  permite detectar el tipo y formato de un archivo   |                          |
| chown       | Es una abreviatura del 'Change owner',se utiliza en los sistemas operativos Unix y Unix-like para cambiar el propietario de archivos del sistema de archivos, directorios  |  sudo chown solvetic ./Solvetic3/       |
|  chmod      | permite cambiar o transferir la propiedad de un archivo al nombre de usuario especificado  |  $chmod  700 /user              |
| df     | es muy útil cuando necesitamos ver el espacio de disco disponible en cada una de las particiones de su sistema.   |   $ df -Th   |  
| kill    | si se tiene un programa que no responde, se puede cerrar manualmente utilizando el comando kill  |    $ kill -l                      |
| ps       |  es un comando que permite visualizar el estado de un Proceso. |  $ ps -e                        |
| du       | permite verificar cuánto espacio ocupa un archivo o un directorio. |  $ du -sh *                        |
| ping       | verifica el estado de conectividad a un servidor. |     ping 192.10.11.3                    |
| uname       |  imprimirá información detallada sobre el sistema Linux, como el nombre de la máquina, el sistema operativo, el núcleo, etc.  | $ uname _ a              |
| man    |  muestra el manual de un comando.   |  $ man free                        |
| echo        | se imprimen en la salida estándar. echo se usa comúnmente en scripts de shell para mostrar un mensaje o generar los resultados de otros comandos. | echo "Me llamo Yulianna"   |
| reboot        | comando para reiniciar la maquina o el servidor | sudo reboot   |

# comandos docker
| Comando | Descripción | Ejemplo de uso |
| ------------- | ------------- | ------------- |
| systemctl start       | iniciar el daemon | sudo systemctl start docker   |
| systemctl enable       | habilitar el daemon | sudo systemctl enable docker   |
| docker search       | buscar imagenes | docker search ubuntu   |
| docker run -i -t     | prueba del contenedor | docker run -i -t ubuntu /bin/echo  |
| docker images      | ver imagenes instaladas | sudo docker images   |
| docker run -it       | Iniciar una instancia | sudo docker run -it Ubuntu   |
| docker ps -a       | ver el estado de las imagenes | sudo docker ps -a    |
| docker stop     | detener un contenedor | docker stop container-id  |
| docker start    | iniciar un contenedor | docker start container-id  |
| docker login -u      | Iniciar sesión en la terminal con el usuario de docker hub | sudo docker login -u usuario_dockerhub   |
| docker push      | Hacer un push a la cuenta de DockerHub | sudo docker push docker-registry-username/docker-image-name   |
| docker rmi     | eliminar imagenes de docker | docker rmi Image Image |
| docker rm     | eliminar contenedores  | docker rm ID |
| docker run --rm    | eliminar contenedores despues de cerrado | docker run --rm image_name  |
| docker rm $(sudo docker ps -a -f status=exited -q)   | eliminar todos los contenedores con estado “Exited (0)”  | sudo docker rm $(sudo docker ps -a -f status=exited -q)   |
| docker pull      | obtener una imagen docker  | docker pull portainer/portainer-ce:latest |
| docker rm     | crear un volumen donde se almacenarán los datos de configuración  | docker rm ID |
| docker volume create     | eliminar todos los contenedores con estado “Exited (0)” | docker volume create portainer_data |
| docker run -d -p 8000:8000 -p 9443:9443      | ejecutar la aplicación con el puerto 9443 y el puerto 8000 expuesto  | docker run -d -p 8000:8000 -p 9443:9443 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest |
| add-apt-repository "deb [arch=amd64]      | agregar el repositorio oficial de Docker  | sudo add-apt-repository "deb [arch=amd64]  |
