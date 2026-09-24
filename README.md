# Heimspielplaner V45.7 Offline

## Offline-Funktion
- Der letzte erfolgreich online geladene FuPa-Stand wird automatisch im Browser gespeichert.
- Ohne Internet wird dieser letzte Stand automatisch angezeigt.
- Sobald das Gerät wieder online ist, versucht die App automatisch eine Aktualisierung.
- Erst wenn neue FuPa-Daten erfolgreich erkannt wurden, ersetzt die App den alten gespeicherten Stand.
- Schlägt der Abruf fehl, bleibt der letzte funktionierende Stand erhalten.
- Manuelle Änderungen, Einstellungen, Importdaten, Kabinen- und Verkaufsplanung bleiben getrennt erhalten.

## Anzeige
- Grün: Online
- Rot: Offline
- Unter dem FuPa-Status steht der Zeitpunkt des letzten erfolgreichen Stands.

## GitHub
Alle Dateien dieses Pakets gemeinsam in denselben GitHub-Pages-Ordner hochladen und vorhandene Dateien ersetzen. Die App anschließend einmal vollständig online öffnen.

## Offline-Test
1. App online öffnen und warten, bis FuPa-Heimspiele geladen angezeigt werden.
2. App zum Home-Bildschirm hinzufügen.
3. Flugmodus aktivieren.
4. App vollständig schließen und neu starten.
5. Der letzte gespeicherte Stand muss mit rotem Offline-Status angezeigt werden.
