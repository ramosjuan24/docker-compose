# docker-compose
archivos de configuración docker-compose para instalación de herramientas de gestión y control QA


## URL DOCKER HUB
https://hub.docker.com/r/vimagick/mantisbt
https://hub.docker.com/r/bitnami/testlink/

## Comandos

## Ejecución:
docker-compose -f <nombrearchivo.yml> up -d

## Verificación de Logs
docker logs mariadb

## Verificación de Imagenes 
docker images

## Verificación de contenedores activos
docker ps

## Verificación de todos los contenedores
docker ps -a

## Eliminar contenedores
docker rm - f <idcontenedor>
  
## Eliminar imagenes 
docker rmi -f <idimagen>
  
  

