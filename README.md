# Orchestrator SaaS

## Descripción

Este proyecto corresponde a una aplicación Full Stack ejecutada completamente con Docker utilizando:

- Angular 21 para el Frontend
- Spring Boot para el Backend
- PostgreSQL como base de datos
- Docker y Docker Compose para la orquestación completa

La solución se encuentra completamente dockerizada y puede levantarse con un único comando.

---

# Tecnologías Utilizadas

## Frontend
- Angular 21
- TypeScript
- SCSS
- Nginx

## Backend
- Java 21
- Spring Boot
- Maven
- JPA / Hibernate

## Base de Datos
- PostgreSQL 15

## Infraestructura
- Docker
- Docker Compose

---

# Cómo Levantar el Proyecto

```bash
docker-compose up -d
```

# Cómo Detener el Proyecto

```bash
docker-compose down
```


---

# URLs de Acceso
- Frontend: http://localhost:4200/login

# Estructura del Proyecto

```txt
orchestrator_saas/
│
├── docker-compose.yml
├── README.md
│
├── db/
│   └── init.sql
│
├── saas/
│   ├── Dockerfile
│   ├── pom.xml
│   └── src/
│
└── saas_client/
    ├── Dockerfile
    ├── nginx.conf
    ├── package.json
    └── src/