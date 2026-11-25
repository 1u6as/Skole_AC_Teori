# AC Theory – første version

## Indhold
- `index.html`: Selve appen.
- `manifest.json`: Gør appen installerbar som PWA.
- `sw.js`: Offline-cache til appens filer.

## Hurtig test på computer
Åbn `index.html` i en browser. Appens funktioner virker lokalt.

## Installation på Android og computer
For at installere den som en rigtig PWA skal filerne ligge på en HTTPS-webadresse.
En nem gratis mulighed er GitHub Pages:
1. Opret/log ind på GitHub.
2. Opret et nyt repository (fx `ac-theory`).
3. Upload alle tre filer (`index.html`, `manifest.json`, `sw.js`) til repository'ets rod.
4. Gå til Settings → Pages.
5. Vælg deploy fra branch `main` og folder `/ (root)`, og gem.
6. Når GitHub viser din webadresse, åbn den på computeren og Android-telefonen.
7. På Android: Chrome-menuen (⋮) → Installer app / Føj til startskærm.
8. På computer: brug installationsikonet i adresselinjen eller browsermenuen → Installer AC Theory.

## Vigtigt
Appen foretager ingen beregninger. Den hjælper kun med at finde formler og viser symboler/krav.
Dette er en startversion med et udvalg af almindelige AC-formler. Få formlerne kontrolleret mod dit undervisningsmateriale, især for parallelle AC-kredsløb, før du bruger appen til afleveringer eller prøver.
