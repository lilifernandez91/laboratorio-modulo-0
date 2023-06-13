# Laboratorio-Módulo-0

## Pasos a seguir

1. Para crear un repositorio en local:

- Abrir la terminal y navegar hasta el directorio donde deseas crear el repositorio.
- Crear una carpeta con el nombre del repositorio.

> mkdir nombredelrepositorio

- Inicializar el repositorio

> git init

<img src="./images/terminal.png">

- Abrir la carpeta en Visual Studio Code.
- Crear un primer archivo (En este caso fue el archivo *readme-md*)
- Ejecutar los siguientes comandos:

> git add .

> git commit -m "mensaje"

<img src="./images/vscode.png">

***

2. Subir el repositorio a GitHub.

- Crear un repositorio en GitHub.
- Ejecutar en la terminal de Visual Studio Code los comandos para conectar el repositorio local con el repositorio de GitHub:

> git remote add origin urldelrepositoriodegithub

> git push origin main

- Verificar que la conexión se haya establecido correctamente con el comando:

> git remote -v

<img src="./images/connection.png">

<img src="./images/repo.png">
    
3. Commit y push

- Como anteriormente ya se había creado un archivo llamado *readme.md*