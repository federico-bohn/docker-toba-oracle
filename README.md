# docker-toba-oracle

Proyecto basado en [docker-toba](https://github.com/SIU-Toba/docker-toba)

Contenedor Docker para instalar un entorno de desarrollo Toba, listo para crear o cargar un nuevo proyecto que se conecte con base de datos Oracle. 

## Requerimientos
 * Se debe tener instalado [Docker](https://docs.docker.com/installation/)

## Build
Hay un archivo `toba.sh` que contiene el script de instalación de toba, ante cualquier cambio a este script (o al Dockerfile), ejecutar lo siguiente para re-generar la imagen 
```
docker build -t="federicobohn/docker-toba-oracle" .
```
Una vez hecho el push a github automáticamente se va a actualizar la imagen en el índice de [hub.docker.com](hub.docker.com)
