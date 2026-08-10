# Kundendatenbank

Einfache Eingabemaske für Kundendaten (Objekte, Hausverwaltungen).

## Funktionen
- Erfassung: Kundennummer, Objektbezeichnung, Straße/Hausnummer, PLZ, Ort, Hausverwaltung, Gültig von/bis
- Autofill: bei bereits bekannter Hausverwaltung werden Adressdaten vorgeschlagen (editierbar)
- Liste mit Suche, Filter nach Ort/Hausverwaltung, Sortierung per Klick auf Spaltenkopf
- Duplikatserkennung (Fuzzy-Matching via Levenshtein-Distanz) für ähnliche Adressen/Objektbezeichnungen

## Verwendung
`index.html` im Browser öffnen. Keine Installation nötig, Daten werden im `localStorage` des Browsers gespeichert.

## Tech-Stack
Reines HTML/CSS/JavaScript, keine Abhängigkeiten.
