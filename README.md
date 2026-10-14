# tv-web-launcher-module

TizenBrew-Modul (Typ *Site Modification*) für den [TV-Web-Launcher](../tv-web-launcher).

- `websiteURL` → Kachelseite `tv.html`, von TizenBrew lokal ausgeliefert (127.0.0.1:8081); sie lädt die Liste vom NAS
- `loader.js` → wird von TizenBrew in **jede** geladene Seite injiziert und enthält das Fernbedienungs-Skript `tv.js` (eingebettet, weil viele Seiten das Nachladen per CSP/Mixed-Content blockieren).

**Nicht von Hand ändern** – erzeugt mit `node tools/build-module.js` im Repo `tv-web-launcher`.

## Auf dem TV hinzufügen
TizenBrew → Module Manager → *Add GitHub Module* → `Schnitzelbrot6969/tv`.
