# Comandos para Docker

1. Actualiza tu terminal:

```shell
pip install --upgrade pip
```

2. Verificar si Docker esta instalado (Está instalado por default):

```shell
docker -v
```
**PD: Para sacar las imagenes, puedes meterte a la página "**Docker Hub".****

**En este caso, ocuparemos la imagen de **Ubuntu****

3. Descargar la imagen:

```shell
docker pull nombrepropietario/nombreimagen:version
```
o

```shell
docker pull nombre:version
```

4. Revisar si la imagen se ha descargado:

```shell
docker imagen
```

5. Empezar la imagen (estar dentro de nuestra imagen):

```shell
docker run -it -p 8080:8080 imagen
```

6. Revisar los procesos de los contenedores que se estén usando en Docker (o esten activos):

```shell
docker ps
```
Para revisar los contenedores que se han creado:

```shell
docker ps -a
```

7. Para iniciar un contenedor que ya se ha creado :

NOTA: no estarás dentro del contenedor, pero si lo inicias.

```shell
docker start container_name
```

8. Para cerrar o parar el contenedor activo

```shell
docker stop container_name
```

9. Para borrar el contenedor:

```shell
docker rm container_name
```
