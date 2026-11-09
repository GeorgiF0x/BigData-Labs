# BigData Labs

Laboratorios y ejercicios de clase del curso de Big Data. El proyecto del curso (SmartTour) vive en su propio repositorio, `SmartTour-BigData`.

## Ejecución

Requisitos: Git y Docker Desktop.

```bash
docker compose up
```

- JupyterLab: http://localhost:8888
- pgAdmin: http://localhost:5050
- PostgreSQL: `localhost:5432`, base `labs_db`, usuario `labs`, contraseña `labs123`

Usa los mismos puertos que SmartTour, así que no se pueden levantar los dos entornos a la vez.

## Estructura

laboratorios:
Enunciados, presentaciones y guiones de cada laboratorio (lab01, lab02, ...).

notebooks:
Notebooks de cada laboratorio y ejercicios de clase (`ej1_clase`).

datasets:
Datos de cada laboratorio. `labPstgrades` se monta en Postgres en `/datos`.

docs:
Referencias de diseño para las presentaciones.
