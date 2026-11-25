# clicksearch

Motore di ricerca con tre schede: **Tutti**, **Immagini**, **Video**. Pubblicato su GitHub Pages, alimentato da [Serper](https://serper.dev) per il web e da [Wikimedia Commons](https://commons.wikimedia.org) per molte più immagini (gratis, senza chiave).

## Chiave API

Nel repo vai su **Settings → Secrets and variables → Actions** e crea il secret `SERPER_API_KEY`.
Ad ogni push la GitHub Action sostituisce il placeholder `__SERPER_API_KEY__` in `index.html` e pubblica il sito.

Vai anche su **Settings → Pages** e imposta *Source* su **GitHub Actions**.

> Su un sito statico la chiave finisce nel codice pubblicato: nella dashboard Serper conviene tenere il limite di utilizzo basso.
