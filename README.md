# Hatze Notizen – Downloads

Notiz-App für Windows (mit Android-Begleiter): Rich-Text-Editor mit Stift-Ebene
(OneNote-Prinzip), Wikilinks mit Graph, Aufgaben, Kalender und Tagesnotiz,
Vorlagen, Verschlüsselung, Versionshistorie und automatischen Backups.

Alle Daten liegen als Dateien in einem frei wählbaren Ordner („Vault") auf
deinem Rechner – **ohne Cloud-Zwang und ohne Konto**. Sync ist optional über
OneDrive, Dropbox oder Syncthing möglich.

## Download

**[➜ Neueste Version herunterladen](https://github.com/KilianHatze/hatze-notizen-releases/releases/latest)**

| Datei | Für wen |
|---|---|
| `HatzeNotizen_Setup.exe` | Windows-Installation (empfohlen) |
| `HatzeNotizen.zip` | Windows portabel – entpacken und starten, keine Installation |
| [`HatzeNotizen.apk`](https://github.com/KilianHatze/hatze-notizen-releases/releases/tag/v2.0.1) | Android-Begleit-App – vorerst weiter Version 2.0.1 ([Download bei v2.0.1](https://github.com/KilianHatze/hatze-notizen-releases/releases/tag/v2.0.1); Installation aus unbekannten Quellen erlauben) |

### Hinweis zur SmartScreen-Meldung

Beim ersten Start des Installers kann Windows „Der Computer wurde durch Windows
geschützt" anzeigen, weil die Datei (noch) nicht signiert ist. In dem Fall:
**„Weitere Informationen" → „Trotzdem ausführen"**.

## Systemvoraussetzungen

- Windows 10/11 (64-Bit). Die nötigen Microsoft-Laufzeitbibliotheken bringt
  der Installer mit.
- Android 8.0 oder neuer für die Begleit-App.

## Automatische Update-Prüfung

Ab Version 2.0.2 fragt die App beim ersten Start einmal, ob sie beim Start
nach neuen Versionen suchen soll. Bei „Ja" fragt sie nur die aktuelle
Versionsnummer aus der Datei `version.json` in diesem Repository ab – GitHub
sieht dabei wie bei jedem Webseitenaufruf die IP-Adresse. Sie meldet sich nur,
wenn eine neue Version bereitliegt; „Anzeigen" öffnet dann die Download-Seite.
Bei „Nein" fragt die App nie von sich aus nach.

Ändern lässt sich das jederzeit unter **Einstellungen → Updates**.

In Version 2.0.1 gibt es diese Frage noch nicht. Dort lässt sich die Prüfung
unter **Einstellungen → Updates** einschalten, indem man diese Adresse als
Update-Quelle einträgt:

```
https://raw.githubusercontent.com/KilianHatze/hatze-notizen-releases/main/version.json
```

## Handbuch

Das vollständige Benutzerhandbuch ist in der App eingebaut: Taste **F1** oder
das ?-Symbol in der Leiste.
