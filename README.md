
Esta es una prueba tecnica para proceso de reclutamiento. Los requisitos que cumple esta prueba se encuentran en los siguientes documentos ubicados en la raiz del directorio.

-PruebaPractica_LAPI.pdf

-PruebaPractica_Singh.pdf

Para realizar el despliegue de la aplicion es necesario seguir los siguientes pasos

1. Correr el comando: `composer install `
2. Una vez instalas las dependencias Composer se deben instalar las paqueterias JS con: `npm insall`
3. Ahora es necesario crear una base de datos (latin1, latin1_swedish_ci) con el nombre de: `examen_reclutamiento`
4. Para configurar las crecenciales de acceso apra la base de datos. Copiar el contenido del archivo .env.example en un nuevo fichero llamado .env
5. Una vez duplicado el contenido del paso anterior, realizar el cambio de las credenciales de la base de datos con: `DB_USERNAME` y `DB_PASSWORD`
6. Realizar las migraciones de la base de tatos con el comando: `php artisan migrate`
7. Para sembrar los datos de los primeros 100 empleados se debe correr el siguiente comando `php artisan db:seed`
8. Para finalizar se deben activar las tareas programadas con el comando: `php artisan schedule:work`
