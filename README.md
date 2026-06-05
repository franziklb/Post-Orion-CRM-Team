# Programm Orion — Programmleitung

Begleitendes Video-Format zur Offerte von **BearingPoint** für die
Gesamtprogrammleitung des CRM-Transformationsvorhabens **Orion** der
Schweizerischen Post.

Statische HTML-Site, deployed via Vercel.

## Inhalt

- `index.html` — Single-Page-Layout (kein Navigation, gemäss Briefing)
- `styles.css` — BearingPoint CI: sharp corners, Rot als Akzent, Inter als Aptos-Ersatz
- `assets/` — Logos (BearingPoint, Die Schweizerische Post)
- `videos/` — beide Vorstellungsvideos (werden ergänzt)

## Lokale Vorschau

```sh
python3 -m http.server 8000
# http://localhost:8000
```

## Deployment

Static site, deployed on Vercel via GitHub integration. Pushes to `main`
trigger automatic production deploys.
