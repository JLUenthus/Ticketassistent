🎫 Ticketassistent

KI-gestützter Ticketassistent für den telefonischen IT-Support – enthus GmbH.

Was ist das?

Ein Webinterface das Techniker während eines Supportgesprächs entlastet. Stichworte eingeben, KI strukturiert daraus ein fertiges Ticket – nur noch copy-pasten.

Features


Tab-System – mehrere Gespräche gleichzeitig offen, max. 20 Sessions (localStorage)
Anruf-Timer – Start/Stop mit Gesprächsdauer-Anzeige
Notizen → KI – Stichworte übertragen, Claude analysiert und gibt aus:

Kurzzusammenfassung
Fehlende Informationen (Rückfragen)
Priorität + Zeiteinschätzung
Auswirkung



Mehrere Runden – Antworten ergänzen, nächste KI-Auswertung anfragen
Abschlussbericht – Statistik-Block + fertiger Tickettext, ein Klick zum Kopieren
Kein Backend – alles lokal im Browser, kein Server, kein Cloud-Sync
DSGVO-konform – keine personenbezogenen Daten an die KI, nur technische Stichworte


Setup


Repo klonen / ZIP entpacken
index.html direkt im Browser öffnen oder über GitHub Pages deployen
Oben rechts auf „Nicht verbunden" klicken → Claude API-Key eintragen
Fertig


GitHub Pages Deploy

Repository Settings → Pages → Source: Deploy from branch → main / root

Die .nojekyll Datei ist bereits enthalten.

Datenschutz


API-Key wird nur in localStorage des eigenen Browsers gespeichert
Kontaktdaten (Name, Telefon, E-Mail) werden nicht an die Claude API gesendet
Nur technische Stichworte werden verarbeitet
Cache jederzeit über „Cache leeren" vollständig löschbar


Stack


Vanilla HTML/CSS/JS – keine Abhängigkeiten
Claude API (claude-sonnet-4-6)
localStorage für Persistenz
