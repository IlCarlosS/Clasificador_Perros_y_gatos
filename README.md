# Clasificación de imágenes (perros y gatos)

Este proyecto y código fuente sirve para creación de un clasificador de perros y gatos usando Python y Tensorflow, del canal de YouTube [Ringa Tech](https://youtube.com/RingaTech)

Este código representa el sitio web, una vez que se crea y entrena el modelo de inteligencia artificial con Python y Tensorflow, el cual es exportado a los archivos "json" y "bin".

## Cómo utilizarlo

### Inicia un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso puedes usar cualquier servidor, pero aquí hay una forma de hacerlo:
- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000
