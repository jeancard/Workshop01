# Workshop 01

1. Se requiere VirtualBox, se instala la versión 6.1
2. Se requiere Vagrant, se descarga e instala la versión Amd64 del siguiente link: [Download Vagrant] (https://www.vagrantup.com/downloads)
3. Se crea una carpeta donde se mantienen los archivos de configuración vagrant (VMs).
4. Se crea un archivo de configuración inicial mediante el comando: vagrant init debian/buster6
5. Se realiza la configuracion en el archivo vagrantfile, se ve como la siguiente imagen: ![alt text](https://www.redeszone.net/app/uploads-redeszone.net/2019/02/Vagrant_Terminal-1.png "Logo Title Text 1")
6. Se ingresa a la máquina virtual mediante SSH
7. Al ingresar a la máquina se deben actualizar los paquetes mediante el comando: sudo apt-get update
8. Se deben instalar los paquetes necesarios para el servidor, con el siguiente comando: sudo apt-get install vim vim-nox curl git apache2 mariadb-server mariadb-client php7.4 php7.4-bcmath php7.4-curl php7.4-json php7.4-mbstring php7.4-mysql php7.4-xml.
9. Probar el acceso al servidor virtual, debería verse algo así: ![alt text](https://servidordebian.org/_media/es/stretch/internet/http/apache2.png "Logo Title Text 1")