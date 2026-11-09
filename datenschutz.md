---
title: Datenschutz
permalink: /datenschutz/
---

# Datenschutz

Stand: 9. November 2026

Kurz: Ich bekomme als Autor nichts, was dich erkennbar macht: keinen Namen, keine Noten, keine Dateien. Es gibt kein Konto,
keinen Server des Autors, keine Werbung und kein Tracking. Mit deinem Uni-Login meldet sich die App direkt von deinem Gerät bei
der Universität Tübingen an. Sonst holt sie öffentliche Daten von GitHub und ihre Updates von Expo; Expo merkt sich dabei eine
zufällige Nummer dieser Installation (mehr unten).

Studium Autopilot ist kein offizielles Angebot der Universität Tübingen.

## Wer verantwortlich ist

Philip Walter, der Autor der App. E-Mail: [studiumautopilot@duck.com](mailto:studiumautopilot@duck.com). Bei Fragen zum
Datenschutz schreib mir dort.

## Was die App abruft

| Was | Woher | Wann |
|---|---|---|
| Zentrale Daten (von mir gepflegt, für alle gleich): Termine, Fristen, Semesterdaten, Lehrveranstaltungen, Vorträge, Kapitel für den Lernplan | GitHub Pages (`studium-autopilot.github.io`) | beim Start und beim Öffnen (höchstens alle 15 Minuten), beim Aktualisieren und im Hintergrund |
| Deine Kursdateien und Kursseiten | ILIAS (`ovidius.uni-tuebingen.de`), Anmeldung über `idp.uni-tuebingen.de` | nur mit Uni-Login: wie oben |
| Abgabetermine deiner Übungen | dein ILIAS-Kalender (`ovidius.uni-tuebingen.de`) | nur mit Uni-Login: wie oben |
| Dein Stundenplan | Alma (`alma.uni-tuebingen.de`) | nur mit Uni-Login: wie oben |
| Updates der App (Fehlerbehebungen und neue Funktionen) | Expo (`u.expo.dev`, `assets.eascdn.net`) | bei jedem Start der App |

- Bei jedem Abruf sieht der Server deine IP-Adresse, wie beim Öffnen einer Webseite. Mit den zentralen Daten schickt die App
  nichts über dich mit: keinen Namen, keine Module, keine Noten.
- Expo bekommt bei jeder Update-Abfrage eine zufällige Nummer dieser Installation, die Version der App und das Betriebssystem.
  Die Nummer entsteht beim ersten Start auf deinem Gerät und hat nichts mit deinem Namen zu tun. Ist die App beim Start
  abgestürzt, schickt sie beim nächsten Mal einmal die Fehlermeldung mit.
- Dein Uni-Passwort geht nur an die Anmeldeseiten der Uni (`idp.uni-tuebingen.de` für ILIAS, `alma.uni-tuebingen.de` für
  Alma), verschlüsselt und ohne Server dazwischen. Der Uni gegenüber nennt sich die App „StudiumAutopilot“; die Uni kann also
  sehen, dass du sie benutzt.
- Den Uni-Login musst du nicht eingeben. Ohne ihn lädt die App keine Unterlagen, keine Abgabetermine und keinen Stundenplan.
- Im **Demo-Modus** (Benutzername `demo`) spricht die App mit keiner Uni und holt keine zentralen Daten; Kurse, Dateien und
  Abgaben sind erfunden. Nur die Update-Abfrage bei Expo läuft wie sonst.

## Was auf deinem Gerät bleibt

- **Uni-Login:** Benutzername, Passwort und die Links zu deinem ILIAS-Kalender und deinem Alma-Stundenplan liegen nur im
  Schlüsselbund dieses Geräts, vom Betriebssystem verschlüsselt. Sie werden nicht synchronisiert und nicht auf ein anderes Gerät
  übertragen; auf jedem Gerät gibst du den Uni-Login selbst ein.
- **Deine Unterlagen** liegen im Ordner der App, den du in der Dateien-App siehst. Sie sind nicht im Backup deines Geräts
  (iCloud oder Computer), weil die App sie jederzeit neu laden kann: nach einer Wiederherstellung von selbst, auf einem neuen
  Gerät, sobald du dich wieder anmeldest.
- **Deine Angaben, Noten, To-dos, eigenen Termine, der Lernplan, deine Karteikarten mit deiner Lernhistorie** und was die App
  aus ILIAS und Alma geholt hat (Kursliste, Abgabetermine, Stundenplan) liegen in der Datenbank der App auf diesem Gerät. Die
  Datenbank ist Teil des Backups deines Geräts (iCloud oder Computer), wie bei jeder App.
- **Mitteilungen** plant die App auf dem Gerät selbst, ohne Server. Auf dem Sperrbildschirm stehen keine Kurs- oder
  Abgabetitel aus ILIAS, weil Kurstitel Beitrittspasswörter enthalten können; die Titel deiner eigenen und der zentralen
  Termine schon. **Widgets** zeigen nur Modulkürzel, Art, Uhrzeit und Raum, keine Titel.

## Wer Daten bekommt

- **GitHub** (GitHub, Inc., USA) liefert die zentralen Daten aus und speichert dabei IP-Adressen zur Sicherheit. GitHub ist
  nach dem EU-US Data Privacy Framework zertifiziert, für das ein Angemessenheitsbeschluss der EU-Kommission gilt (Art. 45
  DSGVO), und verarbeitet die Daten nach seiner eigenen
  [Datenschutzerklärung](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- **Expo** (650 Industries, Inc., USA) liefert die Updates in meinem Auftrag aus (Auftragsverarbeitung, Art. 28 DSGVO). Expo
  speichert Installationsnummer und IP-Adresse, um Updates zu verteilen und zu zählen, wie viele Installationen ein Update
  haben und wo es nicht startet; es nutzt sie nicht für Werbung und verknüpft sie nicht mit Daten aus anderen Apps. Für die
  Übermittlung in die USA gelten die EU-Standardvertragsklauseln (Art. 46 DSGVO), vereinbart in
  [Expos Nutzungsbedingungen](https://expo.dev/terms), Abschnitt 3.2.
- Expo und GitHub bekommen nur die hier genannten Daten und sind vertraglich oder durch ihre Zertifizierung an einen Schutz
  gebunden, der dem dieser Erklärung entspricht.
- Die **Universität Tübingen** bekommt nur, was du ihr auch im Browser schicken würdest; für ILIAS und Alma gilt ihr
  Datenschutz.
- **Apple:** Hast du in den iOS-Einstellungen „Mit App-Entwicklern teilen“ an, gibt Apple mir Absturzberichte und
  Nutzungsstatistiken ohne deinen Namen weiter.
- Teilst du eine Datei mit einer anderen App (zum Beispiel GoodNotes) oder öffnest du einen Link („Quelle öffnen“, „In ILIAS
  öffnen“), gilt der Datenschutz dieser App oder Webseite.

## Warum das erlaubt ist

- Die Abrufe bei GitHub und der Uni braucht die App, um zu tun, was du von ihr willst (Art. 6 Abs. 1 lit. b DSGVO).
- Die Update-Abfrage bei Expo mit Installationsnummer und Fehlermeldung: mein berechtigtes Interesse, Fehler schnell zu beheben
  und Updates sicher zu verteilen (Art. 6 Abs. 1 lit. f DSGVO).
- Absturzberichte und Statistiken von Apple: mein berechtigtes Interesse, Fehler zu finden (Art. 6 Abs. 1 lit. f DSGVO); ob
  Apple sie schickt, entscheidest du in den iOS-Einstellungen.
- Was die App auf deinem Gerät speichert und liest, auch die Installationsnummer für Updates, braucht sie für ihre Funktionen
  (§ 25 Abs. 2 Nr. 2 TDDDG).

## Wie lange

- Auf deinem Gerät: bis du dich abmeldest oder die App löschst (siehe Löschen).
- Expo löscht die Fehlermeldung nach drei Tagen. Für Installationsnummer und IP-Adresse nennt Expo keine feste Frist; sie
  bleiben dort, solange Expo sie für die Updates braucht. GitHub nach seiner eigenen Datenschutzerklärung.

## Löschen

- **Uni-Login entfernen:** Einstellungen → Uni-Login → Abmelden. Das löscht auf diesem Gerät Benutzername, Passwort, die
  Kalender-Links, die Termine aus ILIAS und Alma und den ganzen Ordner der App in der Dateien-App, auch Dateien, die du selbst
  hineingelegt hast; die App fragt vorher. Deine eigenen Angaben, Karteikarten und To-dos bleiben.
- **Alles löschen:** Melde dich ab und lösch dann die App. iOS entfernt dabei ihre Datenbank und ihre Dateien. Den Uni-Login
  im Schlüsselbund lässt iOS beim Löschen einer App stehen, deshalb zuerst abmelden; installierst du die App wieder, löscht sie
  ihn beim ersten Start. In älteren Backups deines Geräts bleibt die Datenbank, bis du diese Backups löschst.

## Deine Rechte

Du kannst Auskunft, Berichtigung, Löschung, Einschränkung und die Herausgabe deiner Daten verlangen (Art. 15–20 DSGVO); schreib
mir dafür an die Adresse oben. Weil ich nicht weiß, wer du bist, finde ich Daten über dich nur mit deiner Hilfe (Art. 11 DSGVO).
Du kannst dich auch bei einer Datenschutz-Aufsichtsbehörde beschweren (Art. 77 DSGVO), zum Beispiel beim Landesbeauftragten für
den Datenschutz und die Informationsfreiheit Baden-Württemberg.

**Widerspruch (Art. 21 DSGVO):** Was ich auf mein berechtigtes Interesse stütze (die Update-Abfrage bei Expo, die Berichte von
Apple), dem kannst du jederzeit widersprechen; schreib mir dafür an die Adresse oben. Apples Berichte schaltest du selbst ab:
Einstellungen → Datenschutz & Sicherheit → Analyse & Verbesserungen → „Mit App-Entwicklern teilen“. Die Update-Abfrage lässt
sich in der App nicht einzeln abschalten; dann bleibt nur, die App zu löschen.
