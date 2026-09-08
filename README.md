# Makler-Insider-Treff

Landingpage für den Makler-Insider-Treff am 30. Juni 2026 auf Gut Neuenhagen.

Eine Veranstaltung des VersicherungsJournal-Verlags, inhaltlich durchgeführt von ibras® GmbH & Co. KG.

## Struktur

- `index.html` — die Landingpage (vollständig eigenständig, keine externen Schriftaufrufe)
- `christian-lueth.jpg` — Porträt Christian Lüth
- `finn-lueth.jpg` — Porträt Finn Lüth
- `kompass-landkarte.jpg` — Hintergrundbild im Hero-Bereich
- `fonts/` — lokal gehostete Lato- und Newsreader-Schriftschnitte (aus Datenschutzgründen statt Google Fonts CDN, analog zur Orientierungsberatung-Seite)

Alle Bilder und Fonts werden über relative Pfade eingebunden und müssen im selben Verzeichnis wie `index.html` liegen.

## Veröffentlichung über GitHub Pages

1. Im Repository unter **Settings → Pages**
2. Bei **Source** den Branch `main` und den Ordner `/ (root)` wählen
3. Speichern — die Seite ist nach kurzer Zeit unter `https://ibras2004.github.io/Makler-Insider-Treff/` erreichbar

## Eigene Domain

Für die Domain `makler-insidertreff.de`: unter **Settings → Pages → Custom domain** eintragen und beim Domain-Registrar die DNS-Einträge auf GitHub Pages setzen.
