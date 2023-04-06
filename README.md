# Docker Compose para Postgres 4 y PgAdmin

Este sistema monta un servidor de Postgres y una aplicación web con PgAdmin para la gestión del servidor a través de contenedores Docker.

Las carpetas data/ y pgadmin/ estan destinadas para que el sistema alamacene ahí su configuración, de forma que si destruimos los contenedores y los volvemos a levantar seguiremos teniendo la información.

## Instalación

1. clonar el archivo `.env.example` a `.env`
2. Rellenar las variables de entorno necesarias en el nuevo archivo
3. Levantar el contenedor `docker-compose up -d `

