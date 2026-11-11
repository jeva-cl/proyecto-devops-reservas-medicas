# SaludPlus - Reservas Médicas

## Descripción
Proyecto académico DevOps que simula una plataforma web de reserva de horas médicas mediante HTML, CSS, Docker y Nginx.

La aplicación es estática y no procesa reservas reales ni almacena información personal.

## Requisitos
- Docker Desktop.
- Docker Compose.

## Estructura del proyecto
- `src/`: contiene los archivos HTML y CSS.
- `Dockerfile`: define la construcción de la imagen Docker.
- `docker-compose.yml`: configura el servicio web.
- `.gitignore`: especifica los archivos que Git debe ignorar.
- `.env.example`: documenta variables de entorno de ejemplo.

## Instalación y ejecución

1. Clonar el repositorio:
   `git clone https://github.com/jeva-cl/proyecto-devops-reservas-medicas.git`

2. Entrar en la carpeta:
   `cd proyecto-devops-reservas-medicas`

3. Construir e iniciar el servicio:
   `docker compose up -d --build`

## Verificación

Consultar el estado del contenedor:
`docker compose ps`

Abrir la aplicación en el navegador:
`http://localhost:8080`

Consultar los registros:
`docker compose logs`

## Detener el servicio

`docker compose down`

## Tecnologías utilizadas
- HTML5
- CSS3
- Docker
- Docker Compose
- Nginx Alpine
- Git y GitHub

## Flujo de trabajo Git

El proyecto utiliza Git para registrar los cambios y GitHub para mantener el repositorio remoto. Se trabaja mediante ramas independientes y Pull Requests para revisar e integrar modificaciones en la rama principal.