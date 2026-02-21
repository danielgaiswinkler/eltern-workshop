# Eltern-Workshop: "Das erste Smartphone"

## Projekt-Info
- **Erstellt:** 2026-02-21
- **Typ:** HTML-Präsentation + Handout für Elternabend
- **Veranstaltung:** Eschenburgschule + Das Projekt e.V. (Familienzentrum)
- **Ort:** Lahn-Dill-Kreis, Hessen
- **Referent:** Daniel Gaiswinkler
- **Dauer:** 90 Minuten
- **Notion-Projekt:** Projekt e.V. Karin Ziegler KI Integration

## Dateien
| Datei | Beschreibung |
|-------|-------------|
| `index.html` | Reveal.js Präsentation (30 Folien, Speaker Notes) |
| `handout.html` | Print-optimiertes Eltern-Handout (A4, 2-3 Seiten) |
| `CLAUDE.md` | Diese Projekt-Dokumentation |

## Technologie
- Reveal.js via CDN (https://cdn.jsdelivr.net/npm/reveal.js)
- Google Fonts via CDN
- QR-Codes als SVG (qrcode.js via CDN)
- Keine lokalen Dependencies
- Funktioniert offline + online

## Design
- Warme Farben: Orange/Amber, Petrol, sanftes Grün, Anthrazit
- Display-Font Headlines, Sans-Serif Body
- Responsive (Laptop, Beamer, Tablet)
- Speaker Notes, Fortschrittsbalken, Touch-Support

## Deployment
- Kann auf GitHub Pages, Netlify oder lokalem Server gehostet werden
- `npx serve .` oder direkte HTML-Datei öffnen
- Alle Assets via CDN geladen

## Workshop-Struktur (5 Phasen)
1. Ankommen & Eisbrecher (10 Min) - Folien 1-4
2. Die Realität (25 Min) - Folien 5-13
3. Praktische Werkzeuge (25 Min) - Folien 14-20
4. Eltern als Vorbilder (15 Min) - Folien 21-24
5. Zusammenfassung & Ressourcen (15 Min) - Folien 25-30

## TODOs
- [ ] Hosting einrichten (GitHub Pages?)
- [ ] QR-Code auf Handout mit finaler URL aktualisieren
- [ ] Datum des Elternabends eintragen
- [ ] Optional: Kontaktdaten von Das Projekt e.V. ergänzen
