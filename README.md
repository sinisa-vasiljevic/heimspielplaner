## Heimspielplaner V45.9 Offline

### Fehlerbehebungen
- Die zuvor fehlende `manifest.webmanifest` ist jetzt vollständig im GitHub-Paket enthalten.
- Der Manifest-Verweis in der `index.html` wurde von V45.7 auf V45.9 aktualisiert.
- Der Offline-Cache wurde auf `heimspielplaner-v45.9-offline` angehoben.
- Service Worker, Manifest, Versionsdatei und sichtbarer Versionsstand sind konsistent.

### Freie Zeitfenster für Testspiele
- Die Einstellung heißt weiterhin eindeutig „Puffer vor Spielbeginn“.
- Der Puffer wird ausschließlich vor dem Spielbeginn berücksichtigt.
- Nach dem offiziellen Spielende wird kein zusätzlicher Puffer addiert.
- Beispiel: Anstoß 15:30 Uhr, 60 Minuten Puffer, offizielles Ende 16:50 Uhr. Der Platz ist von 14:30 bis 16:50 Uhr belegt und ab 16:50 Uhr wieder frei.

### Unverändert
- Kabinenbelegung, Verkaufsplanung, SGV-Filter, Spielplananzeige und alle übrigen Funktionen bleiben unverändert.

### Installation auf GitHub
Alle Dateien aus der ZIP gemeinsam in denselben GitHub-Pages-Ordner hochladen und vorhandene Dateien ersetzen. Danach die App einmal vollständig online öffnen und neu laden.
