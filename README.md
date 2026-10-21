# Práctica Docker Compose - [Tus Iniciales]

Este repositorio contiene la configuración para el despliegue de los servicios mediante Docker Compose.

## Comandos para gestionar los servicios

### 1. Iniciar los servicios
Para levantar los contenedores en segundo plano:

```bash
docker compose up -d

```

### 2. Comprobar el estado de los servicios

Para comprobar que los contenedores están activos y los puertos publicados:

```bash
docker compose ps

```

### 3. Ver los registros (logs)

Para visualizar la actividad y los registros de los contenedores en ejecución:

```bash
docker compose logs

```

### 4. Detener los servicios

Para apagar y eliminar los contenedores en ejecución:

```bash
docker compose down

