# i2bit Website

Statische Unternehmenswebsite für **i2bit** — digitale Innovation und Software-Produkte.

## Seiten

| Datei | Beschreibung |
|---|---|
| `index.html` | Startseite mit Hero-Bereich, Produktübersicht und Scroll-Animationen |
| `product.html` | i2bit Analytics Platform — Datenanalyse-Produkt |
| `secure.html` | i2bit Secure Cloud — Cloud-Dienste |
| `enterprise.html` | i2bit Enterprise Suite — Business Software |
| `contact.html` | Kontaktformular |
| `dynamic.html` | Dynamischer Inhalt |

## Assets

- `blacklodge/catalog.pdf` — Produktkatalog Blacklodge
- `chronize/logo.png` — Logo Chronize
- `gm-connect/logo.jpeg`, `logo.png` — Logo GM Connect
- Diverse `.jpeg`/`.png` Bilder für Produkte und Hero-Bereich

## Lokal starten

```bash
python3 -m http.server 8080
```

Dann im Browser: [http://localhost:8080](http://localhost:8080)

Alternativ mit Node.js:

```bash
npx serve .
```

## Technologien

- Reines HTML/CSS/JS — kein Build-Schritt, keine Dependencies
- Apple-inspiriertes Design (SF Pro Display, Glassmorphism-Header)
- Scroll-basierte Fade/Scale-Animationen via IntersectionObserver
- Responsiv für Desktop und Mobile

## Deployment

Da es sich um statische Dateien handelt, kann die Website auf jedem Webserver oder CDN gehostet werden (Netlify, Vercel, GitHub Pages, Apache/Nginx).
