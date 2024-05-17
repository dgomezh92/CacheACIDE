# CacheACIDE con Redis y PostgreSQL en Python

Este proyecto demuestra cómo implementar una caché ACIDE (Atomicidad, Consistencia, Aislamiento, Durabilidad, Eficiencia) utilizando Redis como caché y PostgreSQL como base de datos en Python. El proyecto incluye las operaciones básicas de lectura, escritura y eliminación, asegurando que las transacciones sean manejadas de manera adecuada para mantener la consistencia entre Redis y PostgreSQL.

## Requisitos

- Docker y Docker Compose instalados.
- Python 3.6 o superior.
- Las siguientes bibliotecas de Python:
  - `psycopg2-binary`
  - `redis`

## Instalación

### Paso 1: Clonar el repositorio

```sh
git clone https://github.com/dgomezh92/CacheACIDE.git
cd CacheACIDE

