---
title: 'Wie funktioniert ArcDPS?'
image: 'https://i.imgur.com/77rgXNw.jpeg'
description: 'ArcDPS ist ein mächtiges Werkzeug für Raider, aber wie funktioniert es eigentlich und wo bekommt man das her?'
hidden: false
priority: 3
---

# Was ist ArcDPS?

ArcDPS ist ein Drittanbieter-Addon für Guild Wars 2. Es erlaubt, vor allem im PvE, die strukturierte Analyse und Aufzeichung von Kämpfen, und ist daher vorallem bei Spielern in Raids und Fraktalen beliebt. 

Über ArcDPS kannst zeigt dir unter anderem:
- Kampfstatistiken von dir und allen Mitgliedern deiner Gruppe oder deines Squads
- Ein- und Ausgehenden Schaden
- Segenverteilung und CC

Die Echtzeit-Daten von ArcDPS (und die erstellten Logs) geben dir die grundlegenden Werkzeuge für Raids an die Hand und helfen dir dich zu verbessern.

# Ist das erlaubt?

ArcDPS nutzt einen Hook mit Client-Netzwerkdaten, um Zugang zu einigen der nützlichsten Funktionen zu erhalten. Obwohl keine Änderungen an den Spieldateien vorgenommen werden, verstößt diese Methode der Datenextraktion direkt gegen die Guild Wars 2 AGB. 

Allerdings hat ArenaNet in einem Reddit-AMA [hier](https://web.archive.org/web/20170917193052/https://www.reddit.com/r/Guildwars2/comments/5svug8/the_head_of_the_snake_devs_here_ask_us_anything/ddi77u2/) die Nutzung von DPS-Metern wie ArcDPS explizit erlaubt. In seinem jetzigen Zustand ist ArcDPS eine weit verbreitete Anwendung die zwar theoretisch gegen die offiziellen Terms of Service verstößt, allerdings von ArenaNet gedulded wird. Das ging so lange gut, bis der Entwickler von ArcDPS Funktionen hinzufügte, die über das hinausgingen, was ArenaNet tolerieren wollte. Von dort an bestand ein enger Kontakt zwischen ArenaNet und dem Entwickler von ArcDPS, der sich jedes zusätzliche Feature durch ArenaNet absegnen ließ. **Daher ist sehr unwahrscheinlich das ein Account aufgrund der Nutzung von ArcDPS gesperrt wird. Trotzdem kann sich ArenaNets Standpunkt natürlich jederzeit ändern.** Solltest du ArcDPS lieber nicht nutzen wollen kannst du andere Nutzer in deiner Gruppe bitten die fertigen Logs mit dir zu teilen und so ebenfalls alle Informationen erhalten.

# Installation

Die [offizielle Website](https://www.deltaconnected.com/arcdps/) ist ziemlich kurz und bündig, enthält aber eine Menge nützlicher Informationen, so dass du dir sich eine Minute Zeit nehmen sollten, um sie durchzulesen. 

1. Wie die Website sagt: Sei kein Arschloch. Schimpfe nicht über DPS oder benutze es, um Spieler zu flamen. Du solltest es benutzen, um zu sehen, wie gut du im Vergleich zu Benchmarks und anderen abschneidest.
2. Klicken Sie auf den Download-Link unten auf der Seite und klicken Sie auf `d3d11.dll`. Sie brauchen die anderen Downloads nicht. Wenn dein Browser beim Herunterladen der .dll-Datei eine Warnung ausgibt, müsst du den Download trotzdem zulassen.
3. Nach dem Download musst du die Datei in den `...\Guild Wars 2`-Ordner verschieben. Dies ist der Ort, an dem du GW2 installiert hast, normalerweise in "Programme" oder "Programme (x86)".
4. Starte das Spiel und du solltest sehen, dass ArcDPS läuft. Wenn du ArcDPS nicht siehst, kannst du versuchen, mit `Alt` + `Umschalt` + `T` das Menü aufzurufen oder mit `Alt` + `Umschalt` + `H` das Menü ein- und auszublenden.

## Logs

Sobald du ArcDPS installiert hast, kannst du die Einstellung zum Speichern von Logs aktivieren, indem du das Menü öffnest (`Alt` + `Shift` + `T`) und unter "Logging" das Kästchen "save after boss encounter" aktivierst. Die Logs werden nach Fraktal-/Strike-/Raid-Bosskämpfen und dem Trainingsgolem gespeichert. Die Logs befinden sich standardmäßig in `Users\DEIN_USER_NAME\Documents\Guild Wars 2\addons\arcdps\arcdps.cbtlogs` und du kannst diesen Ordner über das Menü ändern oder öffnen.

Um die Logs anzusehen, musst du sie analysieren. Dafür kannst du die Logs auf [dps.report](https://dps.report) hochladen damit du einen Link zum Teilen und viele Details erhältst. Du kannst auch den Offline Elite Insights Parser verwenden, wenn du das bevorzugst. Es gibt auch den [Log-Manager von Gw2Sratch](https://gw2scratch.com/tools/manager), mit dem du alle Log-Dateien auf deinem Computer durchsehen und hochladen kannst, was du willst.

## Weitere Einstellungen

Area Stats ist das Hauptfenster und zeigt die DPS der Gruppe/des Squads an. Wenn ihr mit der rechten Maustaste auf das Fenster klickt, könnt ihr die Einstellungen ändern, einschließlich "Anzeige", mit der ihr die gewünschte Formatierung einstellen könnt.

| Platzhalter | Angezeigte Daten                                          |
|-------------|-----------------------------------------------------------|
| `@1`        | Gesamt an allen Gegnern verursachter Schaden (Cleave)     |
| `@2`        | Schaden pro Sekunde auf allen Gegnern (Cleave)            |
| `@3`        | Prozentualier Anteil am Schaden an allen Gegnern (Cleave) |
| `@4`        | Gesamt am Target verursachter Schaden                     |
| `@5`        | Schaden pro Sekunde auf dem Target                        |
| `@6`        | Prozentualier Anteil am Schaden am Target                 |

Daraus kannst du dir dein gewünschtes Anzeigeformat zusammenstellen, zum Beispiel so: `@5, @6 (@2, @3)`. 

Self-Stats können zur Überprüfung der Heilung verwendet werden, aber diese Metrik ist in Bosskämpfen nicht wirklich nützlich (gute Gruppen erleiden weniger Schaden, so dass ihr möglicherweise weniger heilt als erwartet und umgekehrt bei schlechteren Gruppen). 

Mit Metriken kannst du dir folgendes anzeigen lassen:
- FPS - F, je höher, desto besser 60+ ist großartig, fällt aber bei starker Belastung ab
- Ping - P, je niedriger, desto besser, über 300 beginnt eine problematische Verzögerung
- Server-Lag - R, sollte 25 sein viel niedrigere oder hohe Zahlen zeigen ein Problem mit Server-Ticks, die von Server-Last oder verworfenen Paketen stammen können

## Tastenkombinationen


| Platzhalter           | Angezeigte Daten                            |
|-----------------------|---------------------------------------------|
| `Alt` + `Shift` + `T` | Einstellungen                               |
| `Alt` + `Shift` + `C` | Area Stats                                  |
| `Alt` + `Shift` + `B` | Boon-Table                                  |
| `Alt` + `Shift` + `H` | Versteckt alle Fenster                      |
| `Alt` + `Shift` + `S` | Zeigt Details über das ausgewählte Target   |
| `Alt` + `Shift` + `K` | Legt das Target fest (in Raids automatisch) |

## Addons

