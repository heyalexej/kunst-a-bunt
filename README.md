# kunst-a-bunt am Kollwitzplatz

Website des Galerieladens **kunst-a-bunt am Kollwitzplatz** (Antiquitäten, Lampen,
Kunst & Grafik) im Prenzlauer Berg, Berlin.

Statische, mobil-responsive Neuumsetzung der ursprünglichen Seite – im gleichen
optischen Stil (oranger Kasten auf dunklem Grund), aber technisch modernisiert:

- responsiv (Mobile/Tablet/Desktop), `viewport`-Meta, wischbare Navigation auf Mobil
- vollständige SEO-Basis: `<title>`/Descriptions je Seite, Open Graph, `sitemap.xml`,
  `robots.txt`, JSON-LD `ArtGallery` (Adresse, Öffnungszeiten, Geo)
- echter Text statt Bild-Text, korrektes UTF-8, beschreibende `alt`-Texte
- optimierte Bilder (WebP + JPG-Fallback), `loading="lazy"`
- privacy-by-design: keine Cookies, kein Tracking, keine externen Web Fonts,
  Karte nur als Link statt Embed
- Ausstellungsübersicht 2000–2020 als HTML-Seite (zusätzlich als PDF)

## Lokal ansehen

```bash
python3 -m http.server 8080
# http://localhost:8080/
```

## Struktur

| Datei | Inhalt |
|-------|--------|
| `index.html` | Startseite |
| `antiquitaeten.html`, `lampen.html`, `kunst-grafik.html` | Sortimentsbereiche |
| `geschichte.html` | Geschichte des Ladens |
| `ausstellungen.html` | Ausstellungen seit 2000 |
| `kontakt.html` | Kontakt, Öffnungszeiten, Anfahrt |
| `impressum.html`, `datenschutz.html` | Rechtliches |
| `assets/` | CSS und optimierte Bilder |
| `downloads/` | Ausstellungen.pdf |

Kontakt: Wörther Straße 39, 10435 Berlin · Mo–Fr 11–19 Uhr, Sa 11–17 Uhr
