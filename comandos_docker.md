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

5. Empezar la imagen:

```shell
docker run -it -p 8080:8080 imagen
```

6. Revisar los procesos de los contenedores que se estén usando en Docker:

```shell
docker ps
```
o si quieres que aparezca en forma de lista:

```shell
docker ps -a
```
