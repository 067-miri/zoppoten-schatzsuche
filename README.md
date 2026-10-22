# Das Geheimnis von Zoppoten

Ein statischer Prototyp für eine historische Schatzsuche. Die App benötigt keinen Build-Schritt und keine externen Abhängigkeiten.

## Inhaltlicher Stand

Die referenzierte Unterhaltung lieferte nur zwei Screenshots, keine zugänglichen CSV-Dateien. Geschichte, Verdächtige und Stationsorte sind deshalb Beispieldaten. Die bisherige Ortskulisse orientiert sich am Seebad Sopot und ist keine geprüfte Route für Zoppoten. Vor einem Einsatz vor Ort müssen die Originaldaten eingesetzt werden. Es sind keine Codes vor Ort angebracht; die unten stehenden Codes dienen zum Testen bzw. zum Ausdrucken durch die Spielleitung. Die Aufgaben sind Gesprächsimpulse; geprüft wird jeweils der Stationscode.

## Auf dem iPhone

Die entpackte HTML-Datei in der Dateien-Vorschau ist kein zuverlässiger App-Start. Nach Veröffentlichung den GitHub-Pages-Link in Safari öffnen. Vorlesen benötigt eine verfügbare deutsche Systemstimme und einen Tastendruck. Der Fortschritt bleibt im selben Browser auf demselben Gerät erhalten, sofern dessen Speicher erlaubt ist. Eine gespeicherte lokale HTML-Datei benötigt keine Internetverbindung; für erneutes Offline-Laden der veröffentlichten Website gibt es keinen Service Worker.

## Auf GitHub Pages veröffentlichen

1. Den Inhalt dieser ZIP-Datei entpacken.
2. `index.html` (und optional `README.md`) in ein neues GitHub-Repository hochladen.
3. Unter **Settings → Pages** als Quelle **Deploy from a branch**, Branch **main** und Ordner **/(root)** wählen.
4. Nach wenigen Minuten zeigt GitHub die öffentliche Adresse an.

## Stationscodes zum Testen

`DAMPF`, `MOEWE`, `WALZER`, `LICHT`, `ECHO`, `ZIMMER`, `GARTEN`, `BERNSTEIN`

Alle Inhalte und Codes stehen direkt im Array `stations` am Ende der `index.html` und lassen sich dort austauschen.
