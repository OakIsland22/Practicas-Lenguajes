# Práctica 8
## ¿Cómo se inicializa un repositorio en Git? 
Primero inicializa un repositorio, deberás abrir la terminal de comandos, ir al directorio donde deseas crear el repositorio utilizando el comando:
```
cd ruta/del/directorio
```
Una vez en el directorio deseado, ejecuta el siguiente comando para inicializar el repositorio:
```
git init
```
Esto creará un repositorio Git vacío en el directorio actual.

<br>

## ¿Cómo creas un repositorio en GitHub? 
Abres tu perfil en github y puedes darle en tu perfil después en repositorios y en **nuevo** y le pones un nombre a tu repositorio y despues **publicar**.

<br>

## ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub? 
Abres al terminal de comandos y utilizas el siguiente comando y el _URL del repositorio_ .
```
git remote add origin https://github.com/OakIsland22/Practicas-Lenguajes
``` 


<br>

## ¿Cuál es el flujo básico de trabajo en Git y GitHub? 
Inicias en el **Working directory**, después pasas al **Staged** _(index/staging)_, luego pasas al **Commit** _(HEAD/Local)_ y al final el **Remote** _(GitHub/Remote)_. Y el final que es para recibir cambios es _git pull_.

<br>

## ¿Para qué sirve el archivo .gitignore? 
Sirve para **ignorar** uno o muchos archivos ya sea con su extensión o su nombre y que no se suban al repositorio remoto.

<br>

## ¿Cuál es el propósito de una rama? 
Una rama nos permite separar una nueva funcionalidad en nuestro código, la cual luego podemos integrar en la versión principal.

Para crear una rama se utiliza el comando:
```
git branch nombre-rama
```

<br>

## ¿Qué es una fusión? 
Una fusión es fusionar una rama con otra para que se reflejen los cambios en la que se fusionó.

Para fusionar se utiliza el comando:
```
git merge rama-que-quieras-fusionar
```
<br>

## Explica los diferentes tipos de fusión que existen. 
Existen dos tipos de fusión las cuales son:
- Fast-Forward: La fusión se hace automática, no hay conflictos que se tengan que resolver.
- Manual Merge: La fusión hay que hacerla manual, hay conflictos para que se fusionen dos ramas.

<br>

## ¿Cómo puedes ver el historial de tu repositorio? 
Con el comando```git log```nos permite conocer todo el historial de un proyecto, con la información de la fecha, el autor y id de cada cambio.

Ejemplo:
```
git log
```

También sirve el comando ```git log –oneline``` que sirve para lo mismo pero lo resume en una línea y es más práctico.
```
git log --oneline
```
<br>

## ¿Cuál es el propósito de una etiqueta?
Sirve para **versionar el código** o proyecto.

Para generar una etiqueta se utiliza el comando:
```
git tag numero-versión
```