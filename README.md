# README.md
# Curso de Sistemas Operativos
Yulianna Araya Sibaja
Universidad Latinoamericana de Ciencia y Tecnología
ULACIT
2022

# comandos_linux

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

# comandos_docker
