# Ejercicio 2: Publica una imagen
1. Creo un repositorio en Docker Hub: https://hub.docker.com/repository/docker/odevincenti/ejercicio02
2. Me loggeo desde docker ejecutando:
```
docker login
```
3. Copio la imagen pero con un nombre que cumpla el formato 'nombre_de_usuario/nombre_del_repositorio:version' :
```
docker tag nicopaez/pingapp:3.0.0 odevincenti/ejercicio02:1.0.0
```
4. Subo la imagen a mi repositorio de Docker Hub:
```
docker push odevincenti/ejercicio02:1.0.0
```
5. Elimino la imagen de mi local:
```
docker image rm odevincenti/ejercicio02:1.0.0
```
6. Descargo la imagen desde Docker Hub
```
docker pull odevincenti/ejercicio02:1.0.0
```