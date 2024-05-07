# Microservicio de Almacenamiento

Este es el repositorio del microservicio de almacenamiento para la aplicación XYZ. El microservicio está desarrollado en Python utilizando el framework FastAPI y se conecta a una base de datos MySQL.

## Requisitos

- Python 3.7 o superior
- MySQL 5.7 o superior

## Instalación

1. Clona este repositorio en tu máquina local.
2. Crea un entorno virtual utilizando `virtualenv` o `conda`.
3. Activa el entorno virtual.
4. Instala las dependencias utilizando el comando `pip install -r requirements.txt`.
5. Configura las variables de entorno necesarias, como la conexión a la base de datos.
6. Ejecuta el comando `python main.py` para iniciar el microservicio.

## Uso

El microservicio de almacenamiento proporciona una API RESTful para gestionar archivos y directorios. A continuación se muestran algunos ejemplos de cómo utilizar la API:

- Para subir un archivo, realiza una solicitud POST a `/files/upload` con el archivo adjunto.
- Para obtener la lista de archivos, realiza una solicitud GET a `/files`.
- Para descargar un archivo, realiza una solicitud GET a `/files/{file_id}`.
- Para eliminar un archivo, realiza una solicitud DELETE a `/files/{file_id}`.

## Contribución

Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1. Haz un fork de este repositorio.
2. Crea una rama con una descripción clara de la funcionalidad que vas a implementar.
3. Realiza tus cambios y asegúrate de que las pruebas pasen correctamente.
4. Envía una solicitud de extracción a la rama principal.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para obtener más información.
