# Programas necesarios para el funcionamiento del proyecto
1. [Composer](https://getcomposer.org/download/)
1. [Git](https://git-scm.com/downloads)
2. XAMPP ó LAMP


# Como instalar y ejecutar en este proyecto
1. Se ubican en el directorio donde puedan empezar a trabajar.
2. Clonar el repositorio desde su equipo local con la siguiente instrucción `git clone https://github.com/jjoselon/shopcar.git`.
3. Desde la carpeta raiz del proyecto ejecutar `composer install`
4. Ejecutar `php artisan serve`


# Flujo de trabajo para integrar los cambios
1. Ubicarnos en la rama `master` con `git checkout master`.
2. Obtener los últimos cambios del repositorio con `git pull origin master`.
3. Crear una rama a partir de `master` con la siguiente instrucción `git checkout -b [NOMBRE_RAMA]`. Como saber en que rama estamos: `git branch`.
4. Hacemos nuestros cambios :).
5. Agregar los cambios con `git add .`y confirmarlos con `git commit -m "Descripción de nuestros cambios. Ser lo mas claro posible"`. NOTA: Asegurar que se suben los cambios bien no subir archivos que no tienen nada que ver con el proyecto.
7. Subir la rama con nuestros cambios al repositorio remoto con `git push origin [NOMBRE_DE_LA_RAMA_QUE_CREAMOS]`


# Solicitud de integración de cambios desde GitHub

1. Creamos un [Pull Request](https://github.com/jjoselon/shopcar/pulls) de nuestros cambios.
2. Yo me encargo de revisarlos y aceptarlos :). 


#Modificaciones
1. Se modifica tabla personas
2. Ejecutar el comando php artisan migrate para actualizar la tabla.