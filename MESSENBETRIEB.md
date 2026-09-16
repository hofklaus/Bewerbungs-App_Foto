# Tag des Berufs – Einsatz auf der Messe

## Empfohlener Ablauf

1. Die Schule veröffentlicht die statischen Dateien über den von ihr freigegebenen Webhoster.
2. Aus der öffentlichen App-Adresse wird ein QR-Code erzeugt.
3. Schüler scannen den QR-Code mit ihrem eigenen Smartphone.
4. Die App wird einmal vollständig geladen.
5. Optional: Die App wird auf dem Startbildschirm installiert.
6. Die Schüler tragen ihre Bewerbungsdaten und Messekontakte ein.
7. Die Daten bleiben lokal auf dem jeweiligen Gerät.
8. Die Bewerbung wird als Bild geteilt/gespeichert.
9. Nach der Messe können die Schüler ihre lokalen Daten exportieren oder vollständig löschen.

## Wichtig vor dem Einsatz

- Die Schule sollte den gewählten Hostingdienst durch die zuständige Datenschutzstelle/den Schulträger freigeben lassen.
- Vor dem Messebetrieb sollte geprüft werden, welche externen Ressourcen die veröffentlichte Seite lädt.
- Für den Offline-Betrieb müssen alle App-Dateien einschließlich `html2canvas.min.js` und `logo.png` vorhanden sein.
- Auf iOS und Android sollte jeweils ein Testgerät verwendet werden.
- Das Löschen der Browserdaten bzw. das Deinstallieren der App kann ebenfalls lokale Daten entfernen. Schüler sollten deshalb wichtige Exporte selbst sichern.

## QR-Code

Der QR-Code muss ausschließlich auf die veröffentlichte `index.html`/Startseite der App zeigen. Er sollte nicht auf das GitHub-Repository zeigen.

## Datenschutz-Hinweis

Diese technische Architektur verhindert die zentrale Speicherung der in der App eingegebenen Schülerdaten. Sie ist keine rechtliche Freigabe. Die Schule bzw. der Schulträger muss die konkrete Verarbeitung, den Hostingdienst, die Information der Betroffenen und die erforderlichen organisatorischen Maßnahmen prüfen.
