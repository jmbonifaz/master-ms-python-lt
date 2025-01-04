# master-ms-python-lt

Proyecto del Master en microservicios con Python

## Description

Sistema de gestion de ordenes de compra.

### Details

Este sistema permite gestionar ordenes de compra, junto con los usuarios y productos asociados a estas. Tambien debera
gestion el manejo de sesiones de usuario, las cuales se usaran durante todo el flujo de la aplicacion.

El sistema tambien debera de emitir eventos de sobre las ordenes las cuales deberan ser notificadas a un sistema externo
para ser procesadas.

### Tecnologias

- Python >=3.12
- FastAPI
- Docker
- Docker Compose
- RabbitMQ
- PostgreSQL
- ElasticSearch
- Kibana
- Grafana
- Prometheus
- Kubernetes
- Traefik (opcional)
- Nix (opcional)
- PKL (opcional)

### Distribucion de directorios

- `students/<name>`: Directorio de estudiantes en el cual cada carpeta contendra el codigo fuente de cada estudiante.
- `class`: Directorio de clases en el cual se encontrara el codigo fuente de las clases.