# UmweltCampus Bau CH

Lern-App für Umweltschutz auf Schweizer Baustellen: vom Bau-Polier und Sicherheitsspezialisten zum leitenden Umweltbeauftragten.

**App öffnen:** https://knosli.github.io/umweltcampus/

Auf dem Handy lässt sich die App zum Startbildschirm hinzufügen (iPhone: Teilen → «Zum Home-Bildschirm»; Android: Menü → «Zum Startbildschirm hinzufügen» bzw. «App installieren»).

## Wichtig

- **Prüfstatus Entwurf.** Die Inhalte wurden mit KI-Unterstützung erstellt und teilweise extern KI-geprüft, aber nicht durch eine Fachperson freigegeben. Sie ersetzen weder Gesetzestexte, Normen, Bewilligungen noch eine fachliche oder behördliche Beurteilung.
- Die Kompetenzstufen der App sind interne Lernstände und keine anerkannten Qualifikationen.
- Der Lernstand wird nur im Browser des jeweiligen Geräts gespeichert. Sicherung und Übertragung über Einstellungen → Export / Import.

## Stand

Verfügbar: Module 1–4 und 8–10 (Umweltrecht, Gewässerschutz, Bauabfälle, Bodenschutz, Planung und AVOR, Umweltbaubegleitung, ISO 14001). In Entwicklung: Module 5–7, 11, 12.

## Entwicklung

React, TypeScript, Vite. Die App wird zu einer einzigen HTML-Datei gebaut.

```bash
npm install
```

```bash
npm test
```

```bash
npm run build && npm run e2e
```

```bash
npm run build:pages
```

`build:pages` erzeugt den Ordner `pages/` (HTML-Datei, Manifest, Icons, Service Worker). Sein Inhalt wird als Zweig `gh-pages` veröffentlicht; `main` enthält den Quellcode.

Dokumentation zu Umbau und Korrekturen: `docs/`.
