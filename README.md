# BillBar

Buchhaltung für Selbständige, Freiberufler und Kleinunternehmer in Deutschland, als Programm für den Mac. Rechnungen schreiben, Belege sammeln, Bankumsätze zuordnen, Umsatzsteuer-Voranmeldung und Einnahmenüberschussrechnung vorbereiten.

**Alles bleibt auf deinem Mac.** Kein Konto, keine Anmeldung, kein Server.

## Laden und installieren

1. Unter [Releases](https://github.com/janisnicolai/billbar/releases/latest) die Datei `BillBar-….zip` laden und auspacken.
2. Das Programm in den Ordner „Programme“ ziehen.
3. Beim ersten Öffnen meldet macOS, dass es den Entwickler nicht prüfen kann. Das liegt daran, dass BillBar ohne kostenpflichtiges Apple-Entwicklerkonto herausgegeben wird. So gibst du es frei:
   - Systemeinstellungen → „Datenschutz & Sicherheit“ öffnen.
   - Nach unten zum Hinweis auf BillBar gehen und „Dennoch öffnen“ wählen.
   - Das ist nur beim ersten Start nötig.

Die Programmdatei heißt aus der Entstehung noch `Buchhaltung.app`, im Programm steht überall BillBar.

Voraussetzung: ein Mac mit Apple-Chip (M1 oder neuer) und macOS 13 oder neuer.

## Updates

BillBar fragt einmal am Tag hier nach, ob es eine neue Fassung gibt, und meldet sie. Installiert wird erst nach deinem Klick. Jede Fassung ist vom Herausgeber unterschrieben; ohne gültige Unterschrift installiert BillBar nichts. Die Abfrage lässt sich im Menü „BillBar“ abschalten.

## Was ins Internet geht

- Die tägliche Frage nach Updates (ein Abruf der Datei `aktuell.json` in diesem Repo, ohne Angaben über dich).
- Nur wenn du es anstößt: das Laden eines KI-Modells für das Auslesen von Belegen. Das Modell selbst läuft danach auf deinem Mac.

Sonst nichts. Keine Nutzungsstatistik, keine Fehlerberichte.

## Ehrlich gesagt

- BillBar ist ein privates Projekt und kein geprüftes Steuerprogramm. Es ersetzt keine Steuerberatung. Prüfe die Zahlen, bevor du sie ans Finanzamt gibst.
- Die Voranmeldung und die Anlage EÜR trägst du selbst in ELSTER ein. Für die Voranmeldung erzeugt BillBar eine Datei zum Hochladen in Mein ELSTER.
- Bilanzierung (doppelte Buchführung) kann BillBar nicht.
- Deine Daten liegen in `~/Library/Application Support/Buchhaltung/`. Richte in den Einstellungen eine Datensicherung auf eine externe Platte oder einen Cloud-Ordner ein.
- Der Quelltext ist derzeit nicht öffentlich. In diesem Repo liegen nur die fertigen Programme.

Nutzung auf eigene Verantwortung, ohne Gewähr.
