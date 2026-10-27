# Fokus – Deine Aufgaben

Eine einfache responsive To-do-App mit Aufgaben, Filtern und lokaler Speicherung im Browser.

## Dateien

- `dist/index.html`: Seitenstruktur
- `dist/style.css`: Design
- `dist/app.js`: Aufgaben und Speicherung mit localStorage
- `.openai/hosting.json`: Konfiguration für das bestehende Sites-Deployment

## Lokal starten

Im Projektverzeichnis mit Python:

```sh
python -m http.server 8000 --directory dist
```

Danach http://localhost:8000 öffnen. Es ist kein Build-Schritt erforderlich.

## Live-App

https://fokus-todo-sf-271026.sassy-chord-5940.chatgpt.site

Das Hosting erfolgt über Sites. Änderungen auf GitHub werden derzeit nicht automatisch deployt.

Aufgaben bleiben im jeweiligen Browser auf dem jeweiligen Gerät. Es gibt keine Synchronisierung zwischen Geräten.
