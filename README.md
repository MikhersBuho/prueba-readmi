# Encuesta-produccion-Bakend :cry:
## Proyecto Backend - Encuestas

**Para usar el proyecto hay que seguir los siguientes pasos:**


- Asegurarte de tener Python instalado en tu computadora.

-  Crear un entorno virtual de Python para el proyecto 

`$ python -m virtualenv venv`

- activamos el entorno virtual

`$ .\venv\Scripts\activate.ps1`

- Instalamos todas las dependencias requeridas para encuestas:

`$ pip install -r requirements.txt`

Creamos nuestro archivo `.env` para crear las variables de entrono (tiene que ser en en la carpeta donde esta el archivo `settings.py`)

- En el archivo `.env` agregamos las variables


    DEBUG=valor
    SECRET_KEY=valor
    DB_NAME=valor
    DB_USER=valor
    DB_PASSWORD=valor
    DB_HOST=valor
    DB_PORT=valor

## ya puedes correr el proyecto :innocent:

`$ python manage.py runserver`
