### Configuración Previa

- Abrir la consola de comandos en la carpeta bin de Solr.
> solr.cmd start
- Crear un core (micoleccion) mediante el comando:
> solr.cmd create -c micoleccion
-  Cargar documentos a nuestro core:
>  java -Dc=micoleccion -Dauto -jar  
    ..\example\exampledocs\post.jar   ..\example\exampledocs\*.xml
