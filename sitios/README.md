# Sitios de Jardín de Gente

Cada carpeta es un Worker de Cloudflare con assets estáticos:

- `cuatroacuerdos/` → cuatroacuerdos.jardindegente.workers.dev (taller presencial)
- `cuatroacuerdos-online/` → cuatroacuerdos-online.jardindegente.workers.dev (taller online)
- `algomas/` → algomas.jardindegente.workers.dev (taller "Algo más", traído desde Netlify)

En Cloudflare, cada Worker está conectado a este repo con su carpeta como directorio raíz.
Para publicar un cambio: editar `public/index.html` y hacer push a `main`.

Conectado a Cloudflare el 20/11/2026.
