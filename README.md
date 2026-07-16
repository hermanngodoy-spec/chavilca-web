# chavilca-web

Landing page pública del **Grupo Chavilca** (chavilca.cl). Sitio estático: solo HTML y CSS, **sin build, sin backend, sin login**. Hermano corporativo de [amaru-web](https://amaruspa.cl).

## Contenido

| Archivo | Qué es |
|---|---|
| `index.html` | La página completa (hero con el rombo, la raíz diaguita, las 3 empresas, el estándar, contacto). Todo el CSS va embebido. |
| `favicon.svg` | El rombo diaguita del grupo. |
| `404.html` | Página de error con el rombo. |
| `robots.txt` / `sitemap.xml` | SEO básico (dominio chavilca.cl). |

## Las empresas del grupo

- **AMARU** — Lavandería industrial + aseo y mantención (amaruspa.cl, operando).
- **TAMANGO** — Insumos (h.godoy@tamangospa.cl) — tarjeta "PRÓXIMAMENTE" hasta definir su oferta pública.
- **COLQUE** — Cafetería (h.godoy@colquespa.cl) — tarjeta "PRÓXIMAMENTE" hasta definir su oferta pública.

Contacto del grupo: h.godoy@chavilca.cl

## Deploy

Cloudflare Pages conectado a este repo (igual que amaru-web): cada push a `main` publica solo. Sin paso de build (framework preset: *None*).

## Editar

Los textos de TAMANGO y COLQUE están marcados "PRÓXIMAMENTE"; cuando exista la oferta real, reemplazar la tarjeta en `index.html` (sección `#empresas`) y la caja de contacto (`#contacto`).

© 2026 Grupo Chavilca · Atacama, Chile
