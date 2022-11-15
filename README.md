## Contenedor Node Básico en Docker

Este proyecto crea un servidor basico en NodeJs, el cual al ingresar por navegador muestra un "Hello Pablo"

## Instalación de Docker

En sistemas windows se puede instalar de manera sencilla usando [Docker Desktop](https://www.docker.com/products/docker-desktop/), un ejecutable que instala docker y los componentes necesarios.

En sistemas Linux, se puede usar los siguientes comandos
<code> $ curl -fsSL https://get.docker.com -o get-docker.</code>
######
<code> $ sh get-docker.sh </code>

## Instalación de NodeJs

Para la instalación de NodeJs, pueden ingresar a este [link](https://nodejs.org/en/download/) y descargar el paquete acorde al sistema operativo e instalarlo de manera tradicional.

## Preparación de la imagen

Una vez clonado el repositorio, desde terminal ubicate en la raiz de este proyecto y ejecuta la siguiente instrucción:
<code>docker build . -t [nombreImagen]</code>
Donde este comando crea una imagen partir del Dockerfile incluido.

## Creación y ejecución del contenedor

Para crear y correr el contenedor, basta ejecutar el comando docker run de la siguiente manera:
<code>docker run -d --name node -p 8082:8080 [nombreImagen]</code>

Para corroborar el correcto levantamiento, debes abrir tu navegador e ingresara la url http://localhost:8082

## Construido con 🛠️

* [NodeJs]() Lenguaje utilizado NodeJs v16
* [VsCode]() Editor Utilizado
* [Docker]() 

## Autor ✒️

* **Pablo Perez** - *Trabajo Inicial* - [pprezp](https://github.com/pprezp)

---
⌨️ con ❤️ por [pprezp](https://github.com/pprezp) 😊