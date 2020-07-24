# Laboratorio 01 - Preparando nuestro entorno

## Introducción

El objeto de este laboratorio es sumamente simple, prepararemos nuestras computadoras para tener un ambiente local de desarrollo. En concreto, prepararemos los siguientes componentes dentro de nuestra máquina:

- __Node.js__ : Plataforma para ejecución de programas en el lenguage javascript.
- __Visual Studio Code__ : Editor de texto avanzado, pensado para el desarrollo de programas.
- __Docker__ : Entorno de contenedores, encargado de la gestión de herrmientas de software para la creación de ambientes.
- __Hyperledger Fabric__ : Plataforma de Blockchain basada en el proyecto de código abierto Hyperledger Fabric.
- __IBM Blockchain Visual Studio Code Extension__ componente accesorio grtuito para visual studio code para controlar y desplegar código a la plaraforma de Hyperledger Fabric.

## 1 - Acceder a la línea de comando

Todas nuestras máquinas cuentan con una terminal desde donde podemos controlar y ejecutar programas desde la linea de comando. Para usar la terminal debemos hacer lo siguiente, dependiendo de nuestro sistema operativo:

1. En __Windows__ en nuestra barra de programas, seleccionar la opción "ejecutar" (opcionalmente tecleear _cmd+r__) y en el campo que se muestra escribir la instrucción __cmd__ y teclar la tecla de __Intro__
2. Bajo __OS X__ tienes dos opciones
    1. Haz clic en el ícono de Launchpad en el Dock, escribe Terminal en el campo de búsqueda y haz clic en Terminal.
    2. En el Finder , abre la carpeta /Aplicaciones/Utilidades, y haz doble clic en Terminal.

## 2 - Instalar Node.js

Lo primero que haremos, será revisar si ya tenemos Node.js instalado, escribiendo la siguiente instrucción y finalizando con la tecla de __Intro__

```
node -v
```
En caso de que Node se encuentre instalado, esto mostrará la versión instalada. Para ejecutar los ejercicios necesitamos tener la versión 8.16 o superior.

En caso de que esta instrucción muestre un error o bien que la versión sea una versión anterior, deberemos ir a la siguiente dirección https://nodejs.org/en/download/ en donde seleccionaremos el instalador correspondiente a nuestro sistema operativo. Una vez descargado el instalador lo ejecutamos con sus opciones por omisión.

## 3 - Instalar Visual Studio Code

El Visual Studio Code es un editor de texto ideal para la creación de programas. Para poder descargarlo debemos entrar a https://code.visualstudio.com/ y seleccionar nuestro sistema operativo. Descargamos el instalador y ejecutamos la instalación por omisión.

## 4 - Instalar Docker 

Docker es una plataforma de contenedores que sirve para desplegar plataformas de desarrollo y ejecución de soluciones. Para instalarlo debemos de seguir las siguientes instrucciones dependiendo de nuestra plataforma:

- __Windows 10 Home__
    - Debemos navegar a https://hub.docker.com/editions/community/docker-ce-desktop-windows/ y una vez ahí dar click en el botón ![get stable](../imagenes/getstable.png)
    - Luego de descargarlo, debemos ejecutar el instalador, si se nos pregunta, debemos asegurarnos de habilitar las opciones para habilitar las opciones de __WSL 2__
    - Una vez ejecutada y finalizada la instalación, __Docker Desktop__ debe ejecutar, esto lo podemos saber pues aparecerá el siguiente icono en la barra de notificaciones ![whale](../imagenes/whale-x-win.png)
    - Si al finalizar la instalación __Docker Desktop__ no inicia automáticamente, debemos iniciarlo manualmente buscando docker entre nuestras aplicaciones y seleccionando la opción __Docker Desktop__ entre nuestros resultados como se muestra a continuacion : ![whale](../imagenes/docker-app-search.png)
- __Windows 10 Pro, Enterprise, o Education__
    - Debemos navegar a https://hub.docker.com/editions/community/docker-ce-desktop-windows/ y una vez ahí dar click en el botón ![get stable](../imagenes/getstable.png)
    - Luego de descargarlo, debemos ejecutar el instalador, si se nos pregunta, debemos asegurarnos de habilitar las opciones para habilitar las opciones de __Hyper-V__
    - Una vez ejecutada y finalizada la instalación, __Docker Desktop__ debe ejecutar, esto lo podemos saber pues aparecerá el siguiente icono en la barra de notificaciones ![whale](../imagenes/whale-x-win.png)
- __OS X__ 


![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")