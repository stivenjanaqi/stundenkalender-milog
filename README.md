# Stundenkalender - MiLoG

Ein einfacher, browserbasierter Stundenkalender für die Arbeitszeiterfassung nach MiLoG. Arbeitszeiten werden automatisch berechnet; das offizielle PDF wird mit einem Klick erzeugt.

## Live

https://catalyst-al.github.io/stundenkalender-milog/

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
   - Unten eine Schicht wählen: 🌙 Nacht 22:30–07:00, 🌅 Früh 06:30–14:00, 🌄 Früh lang 06:30–15:00, 🌇 Spät 14:30–22:30, 🌆 Spät lang 14:30–23:00 – oder 🏖️ Urlaub bzw. 🧽 Frei.
   - Tage antippen oder mit Finger/Maus über mehrere Tage ziehen. Nochmals tippen = Tag löschen.
   - **➕ 2. Schicht** einschalten, um an einem Tag eine zweite Schicht hinzuzufügen (wird automatisch zeitlich sortiert; Überschneidungen werden gemeldet).
   - 🏖️ Urlaub markiert den Tag im Kalender, zählt keine Arbeitsstunden und erscheint nicht im MiLoG-PDF.
   - Lange drücken bzw. Rechtsklick öffnet die Details (eigene Zeiten, Entlohnungsart).
   - **🔁 Erste Woche wiederholen** überträgt Tag 1–7 auf alle leeren Tage des Monats; **↶ Rückgängig** macht jeden Schritt rückgängig.
   - Tastatur: Pfeiltasten wählen den Tag, `1`–`5` tragen die Schicht ein, `U` Urlaub, `0` löscht, `+` schaltet die 2. Schicht um, `Strg`+`Z` macht rückgängig.
3. Einzelne Tage genau anpassen im Modus **✏️ Detail** (Tagesliste):
   - Jeder Tag ist eine Zeile mit Zeitleiste (04:00 bis 08:00 am Folgetag). Tag antippen öffnet die Bearbeitung darunter.
   - **Schnell tippen** und mit `Enter` zum nächsten Tag: `630-15` (06:30–15:00), `2230-7 p3` (Pause ab 03:00), `630-14 / 1430-2230` (zwei Schichten), `u` = Urlaub, `0` = frei. Ohne `p` wird die Pause automatisch gesetzt (30 Min. ab 6 Std., 45 Min. ab 9 Std.; bei bekannten Schichten deren Pause).
   - In der Leiste die **Enden ziehen** = Beginn/Ende, den **gestreiften Block ziehen** = Pause verschieben (15-Min.-Schritte).
   - Knöpfe **−15 / +15 / +30** für Beginn, Ende und Pause; Schicht-Chips; **➕ 2. Schicht**; **⧉ Wie Vortag**; **⋯ Details** öffnet den bisherigen Tagesdialog (z. B. für die Entlohnungsart).
   - ⚠️ Hinweise bei mehr als 10 Std. Arbeitszeit, zu kurzer Pause, weniger als 11 Std. Ruhezeit oder überschneidenden Schichten (nur Hinweise, keine Rechtsberatung).
4. Unter **Formular (Druck / PDF)** auf **Offizielles PDF erzeugen** klicken.
5. Das fertige MiLoG-PDF herunterladen und an die Buchhaltung weitergeben.

## Datenschutz und Sicherung

Die Daten werden nur im Browser auf dem jeweiligen Gerät gespeichert. Sie werden nicht an GitHub übertragen. Für einen Gerätewechsel oder als Sicherung bitte regelmäßig die JSON-Backup-Funktion in der Anwendung verwenden.
