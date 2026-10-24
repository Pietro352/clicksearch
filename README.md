# clicksearch

Motore di ricerca con tre schede: **Tutti**, **Immagini**, **Video**. Pubblicato su GitHub Pages, alimentato da [Tavily](https://tavily.com).

## Chiave API

Nel repo vai su **Settings → Secrets and variables → Actions** e crea il secret `TAVILY_API_KEY`.
Ad ogni push la GitHub Action sostituisce il placeholder `__TAVILY_API_KEY__` in `index.html` e pubblica il sito.

Vai anche su **Settings → Pages** e imposta *Source* su **GitHub Actions**.

> Su un sito statico la chiave finisce nel codice pubblicato: nella dashboard Tavily conviene tenere il limite di utilizzo basso.
