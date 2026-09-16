# Tag des Berufs – lokale Version

Diese Version ist als datensparsame Web-App/PWA aufgebaut.

## Speicherung

- Kurzbewerbungsdaten: `localStorage` auf dem jeweiligen Gerät
- Bewerbungsfoto: `localStorage` auf dem jeweiligen Gerät
- Messekontakte: `localStorage` auf dem jeweiligen Gerät
- Keine Datenbank
- Keine API und kein Login
- Export und Löschung erfolgen lokal

## Offline/PWA

`manifest.json` und `sw.js` sind enthalten. Nach dem ersten vollständigen Laden kann die App als PWA installiert und – sofern alle statischen Dateien gecacht wurden – offline verwendet werden.

## Noch erforderlich

Die ursprüngliche App nutzt `html2canvas` für den PNG-Export. In dieser Arbeitsumgebung konnte die Bibliothek nicht aus dem Internet geladen werden. Lege deshalb die originale Datei `html2canvas.min.js` (Version 1.4.1) neben `index.html`.

Außerdem gehört die bisherige `logo.png` neben `index.html`; sie war in der hochgeladenen Textdatei nicht enthalten.

## Datenschutz

Die technische Architektur reduziert die Datenübertragung erheblich, ersetzt aber nicht die schulische Datenschutzprüfung. Insbesondere sollte die Schule bzw. der Schulträger festlegen, ob der gewählte Hostingdienst für die Auslieferung der statischen App eingesetzt werden darf und welche Hinweise/Einwilligungen bzw. Rechtsgrundlagen für den konkreten Messebetrieb erforderlich sind.
