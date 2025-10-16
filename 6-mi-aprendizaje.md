# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado o utilizó otros comandos que no se mencionan al realizar la práctica también se debe documentar.

En esta practica 3 se aprendí de los volumenes, segun entedi son tipo una caja de herramientas que no dependen de un contenedor, aun si borraramos el contenedor el volumen sigue ahí.

En la parte de bind mount, se realizo correctamente todo, pero al momento de hacer el contenedor con la ruta como en el directoria html no habia archivos me salio error, pero luego al poner el template, como al descomprimir ya habia archivos, ya funciono correctamente.

En el ejercicio, al crear los directorios y hacer con ellos los contenedores se creaba todos los archivos necesarios de esa imagen en este caso mysql y wordpress, luego de hacer una configuración en wordpress le elimine el contenedor de wordpress, y al volver a crear otra vez el contenedor la pagina al cargar aparecio con todas las modificación, esto debido a que los datos están almacenados en la carpeta www del host.

En la parte de volumen nombrado solo tuve problema en la parte de la instalación del drupal, esto debido a que no puse correctamente el servidor el de postgres, luego como todo estaba en la red net-drupal, no se tuvieron que mapear los puertos, solo el del server-drupal para la instalación.

En cuanto a los volumenes anonimos entiendo que se crea automaticamente cuando se crea un contenedor, y que se guardan datos temporalmenten mientras existe el contenedor.
