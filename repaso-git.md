## Para que sirve GIT?

Para versionar nuestro proyecto

## Que es GitHub?

Es uno de los servicios que permite alojar (hostear) Nuestro repositorio en la nube

## Como creo un repositorio con git?

con el comando git init, inicializamos nuestro repositorio local

## Como podemos versionar nuestro codigo, es decir tengo unos cambios y quiero "guardar partida"?

git add . (Añade al area de preparacion de los cambios realizados en el codigo, el . hace referencia a traer todos los archivos en el directorio/ carpeta raiz)
git commit -m "comentario descriptivo del cambio" (Poder crear una "version/foto/checkpoint" de como esta el proyecto actualmente, toma en cuenta lo añadido por git add .)

#3 Como podemos subir nuestro commit al repositorio (asumiento que ya esta conectado)

depende:
    Si es la primera vez que pusheas git push -u origin main (para crear la mian remota)
    Si ya existe la main git push