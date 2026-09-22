# Mining Empire V6 – PWA

## Online stellen
Die Dateien müssen über HTTPS ausgeliefert werden. Einfachste Möglichkeiten:
- GitHub Pages
- Netlify
- Vercel

Wichtig: `index.html`, `manifest.json`, `sw.js` und die beiden PNG-Dateien müssen im selben Ordner liegen.

## Smartphone installieren

### Android / Chrome
1. Öffne die HTTPS-Adresse des Spiels.
2. Im Browser-Menü „App installieren“ / „Zum Startbildschirm hinzufügen“ wählen.
3. Die App erscheint auf dem Homescreen.

### iPhone / Safari
1. Öffne die HTTPS-Adresse in Safari.
2. Teilen → „Zum Home-Bildschirm“.
3. „Hinzufügen“.

Der Service Worker ermöglicht anschließend die Nutzung auch ohne Internet, sobald die App einmal geladen wurde.

## Hinweis
Ein lokales `file://`-Öffnen reicht für eine installierbare PWA nicht aus. Für Installation und Offline-Cache braucht das Spiel eine HTTPS-Webadresse (localhost ist für Entwicklung ebenfalls erlaubt).
