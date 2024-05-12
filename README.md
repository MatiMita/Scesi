# Apuntes del Curso de Git

Este es mi repositorio de apuntes del curso para postulantes de la scesi

- **Repositorio**: Un lugar donde se almacena el código fuente y su historial de cambios.
- **Commit**: Una instantánea del código en un momento dado.
- **Branch (rama)**: Una línea independiente de desarrollo dentro del repositorio.
- **Merge (fusionar)**: Combinar los cambios de una rama en otra.

## Clase 1


## Comando git init
```bash
git init 
```
Este comando sirve para iniciar un nuevo proyecto

## Comando git status
```bash
git status
``` 
Este comando es para ver los cambios 

## Comando git addd
```bash
git add
```
Para subir y especificar que subir al main

## Comando Git Commit -m
```bash
git commit -m
```
El nombre de lo que estoy subiendo, "-m" me permite darle un nombre 
## Comando Git push
```bash
git push
```
Permite subir los cambios en la rama que estoy trabajando

## Comando Git Restore
```bash
git restore  
```
Permite poder restaurar algun archivo o proyectos por completo

## Comando Git Log
```bash
git log 
```
Permite mostrar todos los commits en el historial del repositorio

# Clase 2 
## GIT BRANCH
Permite crea,listar ,eliminar y renobar las ramas
```bash
git branch mi-rama
```
## GIT MERGE
Sirve para incorporar los cambios de una rama a la rama en la que nos encontramos
## GIT CHECKOUT
Cambia entre ramas y restura en el directorio de trabajo
## RESOLVER CONFLICTOS
Es una situacion en la que no es capaz de determinar que cambio es el tiene prevalecer una vez ocurra la fusion
```bash
git diff
```
## GIT CONFIG
Permite eitar lo que se utiliza en git
# CLASE 3
## Git remote origin<url>
permite crear y eliminar conexione de otros repositorios
## Git push origin<rama>
Nos permite sincronizar los cambios  de los repositorios  local con el remoto
 ## GIT RMEOTE PRUNE ORIGIN 
 Nos permite elimnar ramas que ya no existen en el remoto  y que podemos eliminar en el local
 ## Git branch
 Nos permite crear ramas desde nuestro codigo asi mismo visualizar
# CLASE 4
Pull Request : Es una peticion de cambios que se envia el repositorio original
