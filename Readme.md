# Iniciar proyecto con Django + Postgres

Este proyecto se puede utilizar para iniciar un proyecto desde cero.

## Requisitos
- docker
- docker-compose

## Configuración
Cambi el nombre del fichero .env.sample por .env

## Configuración para desarrollo
```docker-compose up --build```

## Configuración para producción
```docker-compose -f docker-compose.prod.yml up --build```


Este proyecto es un fork de: alicmp/djnago-postgres-docker-starter
