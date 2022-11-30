# Ejercicio 4: creación de imagen PasswordAPI
1. Escribo el [dockerfile](Dockerfile)
2. Genero la imagen con:
```
docker build -t app.jar .
```
3. Ejecuto la imagen con:
```
docker run -d -p 8080:8080 app.jar
```
4. Chequeo que este funcionando bien en http://localhost:8080/
5. Creo un repositorio en Docker Hub: https://hub.docker.com/repository/docker/odevincenti/ejercicio04
6. Me loggueo desde Docker y cambio el nombre de la imagen:
```
docker tag app.jar odevincenti/ejercicio04:1.0.0
```
7. Publico la imagen en Docker Hub:
```
docker push odevincenti/ejercicio04:1.0.0
```
Imagen disponible en https://hub.docker.com/repository/docker/odevincenti/ejercicio04
