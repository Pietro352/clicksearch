# clicksearch

Motore di ricerca con tre schede: **Tutti**, **Immagini**, **Video**. Pubblicato su GitHub Pages, alimentato da [Tavily](https://tavily.com) per il web e da [Wikimedia Commons](https://commons.wikimedia.org) per molte più immagini (gratis, senza chiave).

## Chiave API

Nel repo vai su **Settings → Secrets and variables → Actions** e crea il secret `TAVILY_API_KEY`.
Ad ogni push la GitHub Action sostituisce il placeholder `__TAVILY_API_KEY__` in `index.html` e pubblica il sito.

Vai anche su **Settings → Pages** e imposta *Source* su **GitHub Actions**.

> Su un sito statico la chiave finisce nel codice pubblicato: nella dashboard Tavily conviene tenere il limite di utilizzo basso.
