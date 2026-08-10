# Kundendatenbank

Einfache Eingabemaske für Kundendaten (Objekte, Hausverwaltungen).

## Funktionen
- Erfassung/Bearbeitung über Pop-up: Kundennummer, Objektbezeichnung, Objektadresse, Hausverwaltung (inkl. eigener Adresse + Rechnungsmail), Gültig von/bis
- Autofill: bei bereits bekannter Hausverwaltung werden deren Adresse und Rechnungsmail vorgeschlagen (bleiben editierbar)
- Liste mit Suche, Filter nach Ort/Hausverwaltung, Sortierung per Klick auf Spaltenkopf
- Duplikatserkennung (Fuzzy-Matching via Levenshtein-Distanz) ausschließlich auf Basis von Objektadresse + Objektbezeichnung – die Hausverwaltungsadresse fließt nicht in die Duplikatsprüfung ein
- Beim ersten Öffnen werden automatisch Beispieldatensätze aus Vorarlberg geladen (inkl. zweier bewusst angelegter Duplikatspaare)

## Verwendung
`index.html` im Browser öffnen. Keine Installation nötig, Daten werden im `localStorage` des Browsers gespeichert.

## Tech-Stack
Reines HTML/CSS/JavaScript, keine Abhängigkeiten.
