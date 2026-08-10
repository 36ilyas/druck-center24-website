# Druck-Center24 — Website

Statische Website für **Druck-Center24** (Inh. Markus Lehmann) — Druckerei, Copyshop, Textildruck & Bestickung, Druckerpatronen und Zubehör mit Standorten in **Düren, Rheydt und Hückelhoven**.

Aufgebaut auf einem eigenständigen, abhängigkeitsfreien Layout (kein Framework) und ausgeliefert über **GitHub Pages**.

## Struktur

| Datei | Zweck |
|-------|-------|
| `index.html` | Startseite |
| `404.html` | Markenkonforme Fehlerseite (GitHub Pages nutzt sie automatisch) |
| `assets/logo.png` | Logo von druck-center24.de |

## Design

- **Akzentfarbe:** `#cc3366` (Magenta, übernommen von druck-center24.de)
- **CMYK-Signatur:** feine C/M/Y/K-Leiste am Seitenkopf und in den „Warum"-Kacheln — als Nod an die Druck-/CMYK-Identität
- **Neutrale Grautöne:** `#26262b` (Überschriften) / `#4b4b52` (Text) / `#f7f7f8` (Hintergrund)
- **Schriften:** Space Grotesk (Headlines), Hanken Grotesk (Text), Space Mono (Labels)
- Responsiv (Desktop / Tablet / Mobile), Scroll-Reveal mit `prefers-reduced-motion`-Support

## Lokale Vorschau

```bash
python -m http.server 8000
# dann http://localhost:8000 öffnen
```

## Hinweise

- Die Inhalte (Standorte, Kontakt, USt-IdNr) stammen aus den öffentlichen Angaben auf druck-center24.de (Impressum & Standorte). Marketing-Texte sind neu formuliert.
- Die Navigationspunkte springen zu Abschnitten auf der Startseite (One-Pager). „Anfrage" verweist auf die Kontaktdaten der Standorte; Impressum/Datenschutz verlinken auf druck-center24.de.
