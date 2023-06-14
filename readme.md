# Git y github clase inicial

## Comandos basicos de git

```sh
git init # Inicia un repositorio en la carpeta actual

git add nombre_de_archivo o * # git add agrega al staging area los elementos deseados

git status # Nos devuelve la informacion sobre el commit a realizar o nuestro espacio de trabajo

git commit -m "" #

git checkout nombre_rama # Cambiarme a una rama nombre_rama

git checkout -b nombre_rama # -> Creo una rama nombre_rama
```

> Cuando creas una rama la creas a partir de donde estas parado

## Merge de ramas

Un merge es la union de una rama x en un commit x hacia otra rama x en un commit x

```sh
git checkout rama_a_donde_quiero_mergear # cambiarme a la rama donde quiero los cambios

git merge nombre_de_la_rama_donde_Estan_los_cambios # Se une la rama nombre_... a rama_a_donde quieres
```
