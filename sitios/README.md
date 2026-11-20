# Sitios de Cuatro Acuerdos

Cada carpeta es un Worker de Cloudflare con assets estáticos:

- `cuatroacuerdos/` → cuatroacuerdos.jardindegente.workers.dev (taller presencial)
- `cuatroacuerdos-online/` → cuatroacuerdos-online.jardindegente.workers.dev (taller online)

En Cloudflare, cada Worker está conectado a este repo con su carpeta como directorio raíz.
Para publicar un cambio: editar `public/index.html` y hacer push a `main`.
