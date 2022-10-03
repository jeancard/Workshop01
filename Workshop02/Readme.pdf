[Perfil de Github](https://github.com/jeancard)

# Configuración de vagrant

## Configurando de la llave:

1. Se realizó la creación de la llave publica mediante el siguiente comando: `ssh-keygen -t rsa`.
![Keygen](images/keygen.png)

2. Se copió la llave pública a vagrant, utilizando el siguiente comando: `cp ~/.ssh/isw811-322-g1.pub`

![Publickey](images/Publickey.png)

3. Se inicializó vagrant en modo ssh, con el siguiente comando: `vagrant ssh`

![Publickey](images/Vagrant ssh.png)

4. Se relizó la configuración de la llave publica en vagrant, mediante el siguiente comado: `cat /vagrant/isw811-322-g1.pub >> .ssh/authorized_keys`.


## Configuración apache:

1. Se realizó la configuración del archivo lfts.isw811.xyz.conf en la carpeta de sitios disponibles para Apache, se utilizó el siguiente comando: `sudo cp /vagrant/lfts.isw811.xyz.conf /etc/apache2/sites-available/`

![Apache_config](images/Apache_config.png)

2. Se habilitaron 3 modulos requeridos en apache, con el siguiente comando: `sudo a2enmod vhost_alias rewrite ssl`.

![Apache_config](images/Apache_config2.png)

3. Se creó estructura del archivo html para visualizarlo desde al navegador, se crea en la carpeta publica, se utiliza el siguiente comando: `echo "¡Hola Mundo!" > ~/sites/lfts.isw811.xyz/public/index.html`.
  
4. Se realizó una prueba de sintaxis de la configuración realizada, con el siguiente comando: `sudo apache2ctl -t`.

5. Se habilitó la configuración realizada, haciendo uso del siguiente comando: `sudo a2ensite lfts.isw811.xyz.conf`.

6. Se reinició apache para que se ejecuten los cambios aplicados en la configuración, se utilizó el siguiente comando: `sudo systemctl reload apache2`.


# Por último se accede desde el navegador, debe verse algo así:
![Hola_mundo](https://www.quanticbyte.com/wp-content/uploads/2017/12/wordpress_0_3.jpg)

![linkedin-url](https://www.linkedin.com/in/jean-carlos-rodr%C3%ADguez-d%C3%ADaz-899141226/)