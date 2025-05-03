# 📦 Odoo 18 + PostgreSQL con Docker

Este proyecto levanta un entorno completo de Odoo 17 con PostgreSQL usando Docker, con persistencia de datos en el disco local y soporte para módulos personalizados.

## 🚀 Características

- Odoo 18 en contenedor Docker
- PostgreSQL 15 como base de datos
- Persistencia de datos en disco local
- Soporte para módulos adicionales (`./addons`)
- Accesible desde navegador web en `http://localhost:8069`

## 🧱 Estructura del Proyecto

odoo-docker/
├── docker-compose.yml
├── addons/ # Módulos personalizados
├── postgresql/ # Datos persistentes de PostgreSQL
└── odoo-data/ # Datos persistentes de Odoo


## 📦 Requisitos

- Docker
- Docker Compose

## ⚙️ Cómo usar

1. **Clonar el repositorio:**

```bash
git clone https://github.com/tuusuario/odoo-docker.git
cd odoo-docker

2 **Clonar el repositorio:**

mkdir addons postgresql odoo-data

3. Luego levantar el entorno usando 

Docker compose up

acceder al lochalhost:8069
