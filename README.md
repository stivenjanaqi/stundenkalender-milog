# Stundenkalender - MiLoG

Ein einfacher, browserbasierter Stundenkalender für die Arbeitszeiterfassung nach MiLoG. Arbeitszeiten werden automatisch berechnet; das offizielle PDF wird mit einem Klick erzeugt.

## Für GitHub Pages veröffentlichen

1. Bei GitHub ein neues Repository erstellen, zum Beispiel `stundenkalender-milog`.
2. Das Repository bei Bedarf auf **Public** setzen.
3. Diese Dateien in die oberste Ebene des Repositories hochladen:
   - `index.html`
   - `README.md`
   - `.gitignore`
4. Im Repository **Settings** -> **Pages** öffnen.
5. Bei **Build and deployment** `Deploy from a branch` auswählen.
6. Den Branch `main` und den Ordner `/(root)` auswählen und speichern.
7. Nach kurzer Zeit erscheint dort der öffentliche Link, zum Beispiel:
   `https://BENUTZERNAME.github.io/stundenkalender-milog/`

## Nutzung

1. Monat auswählen und die Mitarbeiterdaten einmal eintragen.
2. Schichten eintragen – am schnellsten im Modus **⚡ Schnell**:
   - Unten eine Schicht wählen (🌙 Nacht, 🌅 Früh, 🌃 Lange Nacht, 🌆 Langer Sa oder 🧽 Frei).
   - Tage antippen oder mit Finger/Maus über mehrere Tage ziehen. Nochmals tippen = Tag löschen.
   - Lange drücken bzw. Rechtsklick öffnet die Details (zweite Schicht, eigene Zeiten, Entlohnungsart).
   - **🔁 Erste Woche wiederholen** überträgt Tag 1–7 auf alle leeren Tage des Monats; **↶ Rückgängig** macht jeden Schritt rückgängig.
   - Tastatur: Pfeiltasten wählen den Tag, `N` `F` `L` `S` tragen ein, `0` löscht, `Strg`+`Z` macht rückgängig.
   - Im Modus **✏️ Detail** öffnet ein Klick wie bisher den Tagesdialog.
3. Unter **Formular (Druck / PDF)** auf **Offizielles PDF erzeugen** klicken.
4. Das fertige MiLoG-PDF herunterladen und an die Buchhaltung weitergeben.

## Datenschutz und Sicherung

Die Daten werden nur im Browser auf dem jeweiligen Gerät gespeichert. Sie werden nicht an GitHub übertragen. Für einen Gerätewechsel oder als Sicherung bitte regelmäßig die JSON-Backup-Funktion in der Anwendung verwenden.
