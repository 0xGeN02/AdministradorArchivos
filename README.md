# Gestor de Archivos con Usuarios

## Descripción

Este proyecto es un gestor de archivos con usuarios, diseñado para trabajar con bases de datos y Big Data.
Construido con ***Django*** y ***PostgreSQL***.

## Funcionalidades

1. **Autenticación de usuarios**: Los usuarios pueden registrarse, iniciar sesión y cerrar sesión.
2. **Gestión de archivos**: Los usuarios pueden subir, descargar, eliminar y renombrar archivos.
3. **Gestión de permisos**: Los usuarios pueden compartir archivos con otros usuarios y establecer permisos de lectura/escritura.
4. **Búsqueda de archivos**: Los usuarios pueden buscar archivos por nombre, tipo, tamaño, etc.
5. **Soporte para Big Data**: La aplicación es capaz de manejar grandes volúmenes de datos y realizar análisis en tiempo real.

## Requisitos

- Python 3.8 o superior
- Django 3.2 o superior
- PostgreSQL 13 o superior

## Instalación

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias del proyecto con el comando `pip install -r requirements.txt`.
3. Configura tu base de datos PostgreSQL.
4. Ejecuta las migraciones con el comando `python manage.py migrate`.
5. Inicia el servidor con el comando `python manage.py runserver`.

## Uso

Una vez que el servidor esté en funcionamiento, puedes acceder a la aplicación a través de tu navegador web en `localhost:8000`.

## Contribución

Las contribuciones son bienvenidas. Por favor, abre un problema para discutir lo que te gustaría cambiar.

## Licencia

MIT
