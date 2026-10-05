# Book Nook

Erste funktionsfähige Version der persönlichen Bücher-Web-App.

Enthalten:
- physische Bibliothek / Regal
- Kindle / E-Book / Hörbuch
- Markierung „Print fürs Regal“
- separate Kauf-Wunschliste
- ISBN-10 / ISBN-13 Suche
- Kamera-Barcode-Scanner mit ZXing
- Google Books + Open Library als Buchdatenquellen
- Lesestatus und Fortschritt
- Favoriten
- lokale Speicherung im Browser
- JSON Backup / Import
- PWA Manifest + Service Worker

Wichtig:
Der Kamera-Scanner benötigt auf iPhone/iPad eine HTTPS-Seite (oder localhost).
Wenn du index.html nur direkt als Datei öffnest, funktionieren Bibliothek und manuelle Eingabe,
aber die Kamera kann vom Browser blockiert werden.

Für eine echte iPhone-PWA die Dateien auf einen HTTPS-Webspace hochladen
(z. B. GitHub Pages, Netlify, Vercel oder einen eigenen Server) und dann in Safari
„Zum Home-Bildschirm“ wählen.
