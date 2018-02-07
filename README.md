# HELLO WORLD PHP APP ENGINE FLEXIBLE ENVIROMENT

Aplicativo inicial en PHP para Google App Engine Flexible Enviroment

### Requerimientos

**Toda la configuracion se a realizardo para linux - ubuntu 16.04**

1. Instalar google cloud sdk. [Page Oficial Intalacion] (https://cloud.google.com/sdk/docs/?hl=es)
2. Instalar composer. [Page oficial Instalacion] (https://getcomposer.org/download/)
3. Volver Global composer. Ubicate en el directorio donde has descargado
 composer y ejecuta **sudo mv composer.phar /usr/local/bin/composer**
4. Puedes probar son SAPI (servidor interno de php) o con NGINX (yo recomiendo).Instalar NGINX
..1. cd /etc/apt/sources.list.d/
..2. sudo nano nginx.list
..3. Agrega estos repositorios:
...deb http://nginx.org/packages/ubuntu/ xenial nginx
...deb-src http://nginx.org/packages/ubuntu/ xenial nginx
..4. sudo apt-get update
..5. sudo apt-get install nginx
  
### Ejecucion del aplicativo en desarrollo

1. Dirigirte a la carpeta donde has clonado el codigo de la aplicacion
2. Ejecutar con SAPI:
	php -S localhost:8089 -t web
3. Tambien puedes ejecutar con nginx para ello
 [primero debes configurar php en nginx](https://www.youtube.com/watch?v=v_kqyIwj1FM)
4. Colocar en el browser http://localhost:8099.

### Ejecucion del aplicativo en GCP App Engine
1. Dirigirte a la carpeta donde has clonado el codigo de la aplicación
2. gcloud init (para configurar el proyecto al que vas a subir el aplicativo)
3. gcloud app deploy (subes el aplicativo a app engine, puede solicitar sociar cuenta para facturación si estas en modo free asocia esa cuenta)
4. gcloud browse (para que obtengas la URL de internet del aplicativo)

### Asesorias Privadas

**Contactate conmigo escribiendome a wilsonnm22@gmail.com**

