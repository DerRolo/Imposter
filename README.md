# Imposter

Ein werbefreies Imposter-Partyspiel für Android. Ein Handy wird herumgereicht, alle sehen heimlich ihr Wort, nur die Imposter kennen es nicht. Danach wird beschrieben, diskutiert und abgestimmt.

Die App läuft komplett im Browser und funktioniert nach der Installation auch ohne Internet.

## Spielablauf

1. Spieler, Regeln und Kategorien einstellen.
2. Handy herumreichen. Jeder Spieler hält seinen Namen gedrückt und sieht sein Wort. Loslassen verdeckt es wieder. Dann geht es mit „Weiter“ zum nächsten Spieler.
3. Ein zufälliger Spieler beginnt, nach einem Countdown von 3 Sekunden.
4. Diskussion mit Timer. Es werden Aufgaben angezeigt, zum Beispiel ein Wort oder einen Satz zum eigenen Wort zu nennen.
5. Abstimmung: Alle wählen die Verdächtigen aus. Danach folgt die Auflösung.

## Funktionen

- Spieleranzahl und Namen frei einstellbar, Spieler können jederzeit raus- und wieder reingenommen werden
- Anzahl der Imposter einstellbar oder zufällig, in jeder Runde neu
- Zeitlimit für die Diskussion einstellbar
- Hinweise für Imposter, auch ein eigener Hinweis pro Imposter
- Einstellbare Nähe der Hinweise zum Wort (sehr nah, mittel, weit)
- Option: Imposter wissen nicht, dass sie Imposter sind
- Option: Letzte Chance, bei der ein gefundener Imposter das Wort noch raten darf
- Option: Punktestand über mehrere Runden
- Missverständnismodus: Zivilisten und Imposter bekommen Wörter, die zur selben Frage passen, aber etwas völlig anderes meinen
- Über 1000 Wörter in mehr als 20 Kategorien, alle einzeln wählbar
- Wiederholungssperre: Wörter und Hinweise aus den letzten Runden werden vermieden
- Töne und Vibration, die Töne lassen sich abschalten
- Liste aller Wörter in der App

## Installation

Die App wird über GitHub Pages bereitgestellt.

1. Die Adresse der Seite in **Chrome auf dem Android-Handy** öffnen.
2. Menü (⋮) öffnen und **App installieren** oder **Zum Startbildschirm hinzufügen** wählen.
3. Die App einmal mit Internet öffnen, damit alles gespeichert wird.
4. Danach läuft sie auch im Flugmodus.

## Dateien

| Datei | Zweck |
| --- | --- |
| `index.html` | Das komplette Spiel in einer Datei |
| `manifest.json` | Angaben für die Installation als App |
| `sw.js` | Speichert die App für den Offline-Betrieb |
| `icon-192.png`, `icon-512.png` | App-Icons |

## Aktualisieren

Geänderte Dateien im Repository über **Add file → Upload files** hochladen. Dabei bleibt der Dateiname gleich, dann werden die alten Dateien ersetzt. Zum Auslösen des Offline-Updates in `sw.js` die Zeile mit `const CACHE = 'imposter-v…'` auf eine neue Nummer ändern. Danach die App einmal mit Internet öffnen und neu starten.

## Datenschutz

Die App sammelt, speichert oder sendet keine Daten an einen Server. Namen, Einstellungen, Punktestand und der Verlauf der zuletzt benutzten Wörter werden nur lokal im Browser des Geräts gespeichert. Es gibt keine Werbung und keine Tracker.

## Hinweise

- Alle Wörter, Markennamen und Titel dienen nur als Spielbegriffe. Sie gehören ihren jeweiligen Inhabern.
- Das Spiel ist für Erwachsene und Gruppen gedacht, der Missverständnismodus enthält bewusst zweideutige Begriffe.
