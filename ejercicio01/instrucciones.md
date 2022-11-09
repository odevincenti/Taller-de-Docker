# Ejercicio 1: Contenedor nginx
1. Abrir powershell y ejecutar:
```
docker run -it --rm -d -p 8080:80 --name ej1 -v ~/Repos/Taller-de-Docker/ejercicio01:/usr/share/nginx/html nginx
```
2. Navegar a http://localhost:8080/