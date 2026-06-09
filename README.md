# Practica8_Normalizacion
Proyecto: Normalización de Bases de Datos con Docker

Este proyecto automatiza la normalización de datasets y carga los resultados en una base de datos PostgreSQL, ejecutándose íntegramente dentro de contenedores Docker.

## Prerrequisitos
* Tener instalado **Docker** y **Docker Compose**.
* [cite_start]Colocar los datasets originales en la carpeta `data/raw/`[cite: 181, 182].
* [cite_start]Colocar los scripts DDL en la carpeta `sql/ddl/` (estos se ejecutarán automáticamente al iniciar la base de datos por primera vez)[cite: 199, 200, 229].

## Instrucciones de Uso

1. **Construir y levantar los contenedores:**
   Ejecuta el siguiente comando en la raíz del proyecto para descargar las imágenes, construir la aplicación y levantar los servicios en segundo plano:
   ```bash
   docker-compose up -d --build
