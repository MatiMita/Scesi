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
# CLASE 5
 ## GIT FLOW
 RAMAS PRINCIPALES
 MAIN: Su proposito es contener el codigo que encuentre en produccion  
 DEVELOP: Tienen caracteristicas que todavia tienen que ser probadas y validas        
 ## TRUNK BASED DEVELOPMENT
 Se deben hacer commits constantes para que los cambios sean mas faciles de integrar. Tambien hay redes que deshacen un pase a produccion en el caso que algo haya salido mal.
 ## Ship / Show / Ask
 - SHIP : Se fusiona en la rama principal sin revision 
 - SHOW : Se muestra los cambios paara que sea revisados por CI
 - ASK : Abre un PR para discutir  los cambios antes de funsionarlos 
# CLASE 6
## BUENAS PRACTICAS
- Usar los verbos imperativos  
add : Aniade un nuevo archivo
```bash
git commit -m "aniadimos un nuevo archivo."  # esta mal por el punto final
```
```bash
git commit -m "para arreglar un problema..." # esta mal por los puntos suspensivos 
```
```bash
git commit -m "cambiamos por defecto el sistema del color" # esta bien ya que no hay errores de sintaxis 
```
- Usar como maximo 50 caracteres para todos los mensajes de commit
- Usar los prefijos para los commits

feat : para una nueva caracteristica del usuario
fix : bug que afecta al usuario 
 perf : cambios que mejora los rendimientos     
 build : para cambios del sistema  
ci : para los cambios de integracion    
refactor : refactorizacion de codigo      
test : refactoriza un codigo ya  existente
