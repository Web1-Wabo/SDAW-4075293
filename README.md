# Proyecto SDAW_XXXX

Este proyecto contiene una estructura básica orientada a mostrar un
mensaje mediante JavaScript y ejecutarse en un servidor local con
Node.js.

------------------------------------------------------------------------

## 📌 Archivos incluidos

-   **index.html** → Contiene un botón que muestra "Hola Alvaro
    Sanchez".
-   **script.js** → Contiene la función que muestra el mensaje.
-   **server.js** → Servidor Node.js usando Express.
-   **package.json** → Dependencias y script de arranque.
-   **README.md** → Información del proyecto.

------------------------------------------------------------------------

## ▶️ Cómo ejecutar el servidor local

### 1. Instalar dependencias

``` bash
npm install
```

------------------------------------------------------------------------

## 📘 Comandos Git utilizados

-   **git init** → Inicializa un repositorio Git en la carpeta del
    proyecto.
-   **git add** → Añade archivos al área de preparación (staging area).
-   **git commit** → Registra los cambios en el historial de Git.
-   **git status** → Muestra el estado de los archivos modificados/no
    rastreados.
-   **git branch** → Lista y crea ramas nuevas.
-   **git checkout** → Cambia entre ramas.
-   **git merge** → Fusiona ramas.
-   **git log --oneline** → Muestra el historial resumido.
-   **git push** → Envía los commits al repositorio remoto.
-   **git pull** → Sincroniza cambios desde el repositorio remoto.
-   **git restore** → Restaura archivos a una versión anterior.
-   **git revert** → Crea un commit que deshace otro commit.

------------------------------------------------------------------------

## 📦 Comandos Node.js utilizados

-   **npm init** → Crea un package.json (ya incluido).
-   **npm install express** → Instala el framework Express.
-   **npm start** → Ejecuta el servidor Node definido en package.json.


--------------------------------------------------------------------------
## Información técnica añadida desde rama 1
En esta sección se describen los principales comandos de Git utilizados durante la práctica:

- git init: Inicializa un repositorio vacío.
- git add: Añade archivos al staging area.
- git commit: Registra los cambios en el historial del repositorio.
- git branch: Crea o lista ramas dentro del repositorio.
- git merge: Fusiona ramas entre sí.
- git push: Envía los cambios locales al repositorio remoto.
## Información técnica añadida desde rama 2
7ab702c (HEAD -> master) Primer commit del proyecto

## Información técnica añadida desde rama 4
Para conectar el repositorio local con GitLab se añadió un remoto adicional 
con el comando `git remote add`. Después se verificó con `git remote -v` que 
GitHub y GitLab estaban correctamente configurados. Finalmente, se subieron 
los cambios al nuevo remoto con `git push gitlab main`.
