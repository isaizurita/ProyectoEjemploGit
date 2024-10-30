# Práctica 1: Introducción a Git

## Descripción
El programa `HolaMundo.py` contenido en este repositorio, simplemente imprime un mensaje en terminal (`"Hola Git"`).
El objetivo de esta práctica es aprender a utilizar las herramientas que nos ofrecen los 'Sistemas de Control de Versiones' como Git y GitHub, desde la creación de un repositorio hasta la gestión de cambios en archivoc mediante algunos comandos básicos.

## Instrucciones de uso
Para ejecutar el programa `HolaMundo.py` debemos tener instalado un compilador de Phyton en nuestro equipo, después abrir una terminal y navegar hasta el directorio donde se encuentre el archivo y ejecutar el comando:

```
python HolaMundo.py
```

Y la consola deberá mostrar el siguiente mensaje:

```
Hola Git
```

### Comandos utilizados

- **git init** Inicializa un nuevo repositorio
- **git add** Añade archivos al área de preparación de Git
- **git commit -m "mensaje"** Confirma y describe los cambios que se han hecho en el repositorio
- **git push** Sincroniza los nuevos cambios en el repositorio remoto

### Acerca de .gitignore
El archivo `.gitignore` es creado para evitar que ciertos archivos sean rastreados por Git. En este caso se ignoraron los archivos que tuvieran la extensión `.log`, que son archivos de registro que no son reelevantes para el código fuente. Esto con el fin de mantener el repositorio enfocado a los archivos de código fuente.

Al ejecutar `HolaMundo.py`, el programa imprimirá `"Hola Git"` en terminal. Para verificar que `debug.log` no se subió al repositorio remoto, se puede usar el comando **git status** antes de hacer un **git push**. Si `debug.log` no aparece en la lista de archivos no rastreados, significa que Git lo está ignorando correctamente. 
