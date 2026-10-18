# Trazo

Editor de dibujo vectorial en una sola página (HTML, CSS y JavaScript sin dependencias).
Formas, pluma Bézier, edición de nodos, capas, alinear, agrupar, y exportación a SVG y PNG.

## Probarlo
Abrí `index.html` en el navegador.

## Docker
```bash
docker compose up -d --build
# http://localhost:8085  (cambiá el puerto con TRAZO_PORT)
```

## Portainer
Stacks > Add stack > Repository: URL de este repo, rama `main`, ruta `docker-compose.yml`.
En "Environment variables" podés definir `TRAZO_PORT`.
