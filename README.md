# Apache SOLR, creando un mini buscador de peliculas

Archivos de configuración base para SOLR y docker que acompañan el artículo publicado en [Apache SOLR, creando un mini buscador de peliculas](https://blog.irontec.com/introduccion-a-apache-solr-paso-a-paso-2-de-2/)

## Contenido

* *filscore_dataset*: Archivo .csv con información sobre unas 5042 peliculas.
* *filmscore_final*: Archivos de configuración base para SOLR, contiene los resultados finales para utilizar como referencia.
* *filmscore_start_here*: Archivos de configuración base para SOLR, sin los cambios en managed-schema. A utilizar como punto de partida.
* *docker-compose.yml*: Archivo de docker-compose para levantar un contenedor SOLR.

## Levantar el contenedor

* Ejecutar desde el directorio principal donde se encuentra el archivo docker-compose.yml: `docker-compose up -d`
* Para detener el contenedor y continuar luego: `docker-compose stop`
* Para iniciar el contenedor: `docker-compose start`

Más detalles --> [Apache SOLR, creando un mini buscador de peliculas](https://blog.irontec.com/introduccion-a-apache-solr-paso-a-paso-2-de-2/).
