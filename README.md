# Práctica 6: servidor web Nginx con Docker

Servidor web local con Nginx, una página HTML y un volumen administrado mediante Docker Compose.

## Estructura

```text
.
├── docker-compose.yml
└── src/
    └── index.html
```

## Ejecución

```bash
docker compose up -d
docker compose ps
```

Abrir `http://localhost:8080` en el navegador.

Para detener el servicio:

```bash
docker compose down
```
