# Arenero para gatos inteligente

¡Bienvenido al repositorio del Arenero para gatos inteligente!

## Descripción del proyecto

Este proyecto tiene como objetivo brindar una solución innovadora y práctica para el manejo de datos de un arenero inteligente para gatos. El sistema consta de dos componentes principales:

1. **Servidor**: El servidor se encarga de recibir los datos del arenero inteligente, procesarlos y almacenarlos en una base de datos. Está desarrollado en Node.js y se comunica con el arenero a través de una API REST.

2. **Página web de control**: La página web proporciona una interfaz intuitiva y amigable para visualizar y gestionar los datos recopilados por el arenero inteligente. Utiliza tecnologías web modernas como HTML, CSS y JavaScript.

## Requisitos previos

Antes de utilizar la página web, asegúrese de tener instalado XAMPP en su computadora. Puede descargarlo e instalarlo desde [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).

## Configuración y puesta en marcha

Siga los siguientes pasos para comenzar a utilizar la página web:

1. Descargue el archivo **proyecto_arenero.zip** y descomprímalo en una ubicación de su elección.

2. Ubique la carpeta resultante dentro de la carpeta **htdocs** de su instalación de XAMPP. Esta carpeta se encuentra en la ubicación donde instaló XAMPP en su disco local.

3. Asegúrese de tener instalado Node.js en su computadora. Si aún no lo ha hecho, puede descargarlo desde [https://nodejs.org](https://nodejs.org) e instalarlo.

4. Abra Visual Studio Code (u otro editor de su preferencia) y abra la carpeta **servidor_iot** que descomprimió previamente.

5. Abra una terminal en Visual Studio Code y ejecute el siguiente comando para iniciar el servidor:

   ```bash
   node src/indexrest.js
   ```

6. ¡Listo! Ahora puede acceder a la página web del arenero inteligente desde su navegador favorito utilizando la siguiente URL:

   [http://localhost/proyecto_arenero/index.php](http://localhost/proyecto_arenero/index.php)

## Características de la página web

La página web de control del arenero inteligente ofrece diversas funcionalidades para que pueda interactuar con el sistema de forma eficiente:

- Visualización de datos en tiempo real: Podrá ver en tiempo real la información recopilada por el arenero, como el peso del gato y la frecuencia de uso.

- Configuración del arenero: A través de la página web, podrá ajustar ciertos parámetros del arenero, como el nivel de la arena o la frecuencia de limpieza automática.

- Historial de datos: Explore el historial de datos almacenados en la base de datos para analizar el comportamiento de su gato a lo largo del tiempo.

- Notificaciones: El sistema puede enviar notificaciones a su correo electrónico o teléfono móvil para alertar sobre eventos importantes o situaciones que requieran su atención.

## Contribuciones

¡Estamos emocionados de recibir contribuciones de la comunidad! Si desea colaborar con el proyecto, puede hacerlo a través de pull requests. También puede informar problemas o sugerir mejoras en la sección de "Issues" del repositorio.

Esperamos que este proyecto sea útil y atractivo para todos los amantes de los gatos y la tecnología. ¡Diviértase explorando y mejorando la vida de nuestros queridos felinos! 🐱🚀
