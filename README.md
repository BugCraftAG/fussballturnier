# ⚽ Fußballturnier

Kleine Web-Seite für unser Schul-Fußballturnier. Läuft komplett im Browser, ohne Server und ohne Anmeldung.

## Was sie kann

- Teams anlegen, mit Farbe und Spielern (Rückennummer, Kapitän). Spieler kann man auch als Liste einfügen, einer pro Zeile.
- Spielplan automatisch erstellen: entweder jeder gegen jeden oder Gruppen mit Halbfinale/Viertelfinale, Spiel um Platz 3 und Finale.
- Beginnzeit, Spieldauer, Pause und Anzahl der Spielfelder einstellen. Die Uhrzeiten rechnet die Seite selbst aus, und kein Team spielt zweimal gleichzeitig.
- Ergebnisse direkt beim Spiel eintragen. Bei Unentschieden in der K.-o.-Runde gibt's ein Feld fürs Elfmeterschießen.
- Tabelle (3 Punkte für Sieg, 1 für Remis, dann Tordifferenz) und Torschützenliste.
- Beamer-Anzeige mit nächsten Spielen, letzten Ergebnissen und Tabelle. Aktualisiert sich von selbst, wenn man im anderen Fenster was einträgt.
- Export/Import als JSON-Datei, Drucken.

## Speichern

Alles wird im Browser gespeichert (localStorage). Auf einem anderen Gerät sind die Daten also nicht automatisch da. Dafür unter „Speichern & mehr“ exportieren und am anderen Gerät importieren.

## Online stellen mit GitHub Pages

Im Repo auf **Settings → Pages** gehen, bei „Branch“ `main` und `/ (root)` auswählen und speichern. Nach ca. einer Minute ist die Seite unter `https://bugcraftag.github.io/fussballturnier/` erreichbar.
