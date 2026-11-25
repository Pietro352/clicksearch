# clicksearch

Motore di ricerca con tre schede: **Tutti**, **Immagini**, **Video**. Pubblicato su GitHub Pages, alimentato da [Serper](https://serper.dev) per il web e da [Wikimedia Commons](https://commons.wikimedia.org) per molte più immagini (gratis, senza chiave).

## Chiave API

La chiave Serper **non è nel sito né nel repository**: sta come secret del worker Cloudflare `api-gateway` (rotta `/serper`). Il sito chiama il gateway, che aggiunge la chiave lato server.

Per cambiarla: `cd api-gateway && npx wrangler secret put SERPER_API_KEY`.

Vai su **Settings → Pages** e imposta *Source* su **GitHub Actions**.

