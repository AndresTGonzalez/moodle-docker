# Repositorio de Moodle con Docker

Este repositorio contiene los archivos necesarios para levantar un entorno de Moodle utilizando Docker y la última versión de Bitnami.

## Archivos incluidos

- `Dockerfile`: Este archivo se utiliza para construir la imagen personalizada del contenedor de Moodle.
- `docker-compose.yml`: Este archivo se utiliza para definir y ejecutar los contenedores necesarios para ejecutar Moodle, incluyendo la base de datos.

## Uso

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener Docker y Docker Compose instalados en tu sistema.
3. Para levantar el entorno de desarrollo o testeo, simplemente ejecuta el siguiente comando en el directorio raíz del repositorio:

```bash
docker-compose build
docker-compose up
```
Este comando iniciará los contenedores de Moodle y la base de datos. Puedes acceder a Moodle desde tu navegador web visitando http://localhost.

Nota: Para el entorno de desarrollo y testeo, las contraseñas pueden dejarse en blanco.

## Configuración para producción
Para configurar Moodle en un entorno de producción, asegúrate de cambiar las variables de entorno en el archivo docker-compose.yml según las especificaciones de tu entorno. Esto incluye establecer contraseñas seguras y cualquier otra configuración necesaria para garantizar la seguridad y el rendimiento en producción.

## Contribuciones
¡Las contribuciones son bienvenidas! Si encuentras algún problema o tienes sugerencias para mejorar este repositorio, no dudes en abrir un issue o enviar un pull request.

