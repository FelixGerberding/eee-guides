---
title: 'Wie funktioniert ArcDPS?'
image: 'https://i.imgur.com/77rgXNw.jpeg'
description: 'ArcDPS ist ein mächtiges Werkzeug für Raider, aber wie funktioniert es eigentlich und wo bekommt man das her?'
hidden: false
priority: 3
---

# Was ist ArcDPS?

ArcDPS ist ein Drittanbieter-Addon für Guild Wars 2. Es erlaubt, vor allem im PvE, die strukturierte Analyse und Aufzeichung von Kämpfen, und ist daher vorallem bei Spielern in Raids und Fraktalen beliebt.

Über ArcDPS zeigt dir unter anderem:
- Kampfstatistiken von dir und allen Mitgliedern deiner Gruppe oder deines Squads
- Ein- und Ausgehenden Schaden
- Segenverteilung und CC

Die Echtzeit-Daten von ArcDPS (und die erstellten Logs) geben dir die grundlegenden Werkzeuge für Raids an die Hand und helfen dir, dich zu verbessern.

# Ist das erlaubt?

ArcDPS nutzt einen Hook mit Client-Netzwerkdaten, um Zugang zu einigen der nützlichsten Funktionen zu erhalten. Obwohl keine Änderungen an den Spieldateien vorgenommen werden, verstößt diese Methode der Datenextraktion direkt gegen die Guild Wars 2 AGB.

Allerdings hat ArenaNet in einem Reddit-AMA [hier](https://web.archive.org/web/20170917193052/https://www.reddit.com/r/Guildwars2/comments/5svug8/the_head_of_the_snake_devs_here_ask_us_anything/ddi77u2/) die Nutzung von DPS-Metern wie ArcDPS explizit erlaubt. In seinem jetzigen Zustand ist ArcDPS eine weit verbreitete Anwendung, die zwar theoretisch gegen die offiziellen Terms of Service verstößt, allerdings von ArenaNet gedulded wird. Das ging so lange gut, bis der Entwickler von ArcDPS Funktionen hinzufügte, die über das hinausgingen, was ArenaNet tolerieren wollte. Von dort an bestand ein enger Kontakt zwischen ArenaNet und dem Entwickler von ArcDPS, der sich jedes zusätzliche Feature durch ArenaNet absegnen ließ.

Daher ist sehr unwahrscheinlich, dass ein Account aufgrund der Nutzung von ArcDPS gesperrt wird. Trotzdem kann sich ArenaNets Standpunkt natürlich jederzeit ändern. Solltest du ArcDPS lieber nicht nutzen wollen, kannst du andere Nutzer in deiner Gruppe bitten, die fertigen Logs mit dir zu teilen und so ebenfalls alle Informationen erhalten.

# Installation

Die [offizielle Website](https://www.deltaconnected.com/arcdps/) ist ziemlich kurz und bündig, enthält aber eine Menge nützlicher Informationen, sodass du dir sich eine Minute Zeit nehmen sollten, um sie durchzulesen.

1. Wie die Website sagt: Sei kein Arschloch. Schimpfe nicht über DPS oder benutze es, um Spieler zu flamen. Du solltest es benutzen, um zu sehen, wie gut du im Vergleich zu Benchmarks und anderen abschneidest.
2. Klicken Sie auf den Download-Link unten auf der Seite und klicken Sie auf 'd3d11.dll'. Sie brauchen die anderen Downloads nicht. Wenn dein Browser beim Herunterladen der .dll-Datei eine Warnung ausgibt, musst du den Download trotzdem zulassen.
3. Nach dem Download musst du die Datei in den '...\Guild Wars 2'-Ordner verschieben. Dies ist der Ort, an dem du GW2 installiert hast, normalerweise in "Programme" oder "Programme (x86)".
4. Starte das Spiel und du solltest sehen, dass ArcDPS läuft. Wenn du ArcDPS nicht siehst, kannst du versuchen, mit 'Alt' + 'Umschalt' + 'T' das Menü aufzurufen oder mit 'Alt' + 'Umschalt' + 'H' das Menü ein- und auszublenden.

## Logs

Sobald du ArcDPS installiert hast, kannst du die Einstellung zum Speichern von Logs aktivieren, indem du das Menü öffnest ('Alt' + 'Shift' + 'T') und unter "Logging" das Kästchen "save after boss encounter" aktivierst. Die Logs werden nach Fraktal-/Strike-/Raid-Bosskämpfen und dem Trainingsgolem gespeichert. Die Logs befinden sich standardmäßig in 'Users\DEIN_USER_NAME\Documents\Guild Wars 2\addons\arcdps\arcdps.cbtlogs' und du kannst diesen Ordner über das Menü ändern oder öffnen.

Um die Logs anzusehen, musst du sie analysieren. Dafür kannst du die Logs auf [dps.report](https://dps.report) hochladen, damit du einen Link zum Teilen und alle Details erhältst. Du kannst auch den Offline Elite Insights Parser verwenden, wenn du das bevorzugst. Es gibt auch den [Log-Manager von Gw2Scratch](https://gw2scratch.com/tools/manager), mit dem du alle Log-Dateien auf deinem Computer durchsehen und hochladen kannst, was du willst.

## Weitere Einstellungen

Area Stats ist das Hauptfenster und zeigt die DPS der Gruppe/des Squads an. Wenn ihr mit der rechten Maustaste auf das Fenster klickt, könnt ihr die Einstellungen ändern, einschließlich "Anzeige", mit der ihr die gewünschte Formatierung einstellen könnt.

| Platzhalter | Angezeigte Daten |
|-------------|-----------------------------------------------------------|
| '@1' | Gesamt an allen Gegnern verursachter Schaden (Cleave) |
| '@2' | Schaden pro Sekunde auf allen Gegnern (Cleave) |
| '@3' | Prozentualer Anteil am Schaden an allen Gegnern (Cleave) |
| '@4' | Gesamt am Target verursachter Schaden |
| '@5' | Schaden pro Sekunde auf dem Target |
| '@6' | Prozentualer Anteil am Schaden am Target |

Daraus kannst du dir dein gewünschtes Anzeigeformat zusammenstellen, zum Beispiel so: '@5, @6 (@2, @3)'.

Self-Stats können zur Überprüfung der Heilung verwendet werden, aber diese Metrik ist in Bosskämpfen nicht wirklich nützlich (gute Gruppen erleiden weniger Schaden, sodass ihr möglicherweise weniger heilt als erwartet und umgekehrt bei schlechteren Gruppen).

Mit Metriken kannst du dir folgendes anzeigen lassen:
- FPS - F, je höher, desto besser 60+ ist großartig, fällt aber bei starker Belastung ab
- Ping - P, je niedriger, desto besser, über 300 beginnt eine problematische Verzögerung
- Server-Lag - R, sollte 25 sein viel niedrigere oder hohe Zahlen zeigen ein Problem mit Server-Ticks, die von Server-Last oder verworfenen Paketen stammen können

## Tastenkombinationen

| Platzhalter | Angezeigte Daten |
|-----------------------|---------------------------------------------|
| 'Alt' + 'Shift' + 'T' | Einstellungen |
| 'Alt' + 'Shift' + 'C' | Area Stats |
| 'Alt' + 'Shift' + 'B' | Boon-Table |
| 'Alt' + 'Shift' + 'H' | Versteckt alle Fenster |
| 'Alt' + 'Shift' + 'S' | Zeigt Details über das ausgewählte Target |
| 'Alt' + 'Shift' + 'K' | Legt das Target fest (in Raids automatisch) |

## Addons

ArcDPS hat einige Addons, die es noch besser machen. Zur Installation lege einfach deren DLLs in denselben Ordner wie ArcDPS ab. Diese sind ebenfalls von Dritten entwickelt und nicht mit ArcDPS oder Guild Wars 2 affiliiert.

- [Boon Table](https://github.com/knoxfighter/GW2-ArcDPS-Boon-Table/releases) - Zeigt die Verteilung von Boons in einem einfach lesbaren und anpassbaren Format)
- [killproof.me Plugin](https://github.com/knoxfighter/arcdps-killproof.me-plugin/releases) - Zeigt die Killproofs, LI und weitere Infos von killproof.me für Nutzer in der Gruppe an
- [Healing Stats](https://github.com/Krappa322/arcdps_healing_stats/releases) - Erweitert die Darstellung im Spiel und die Logs um Details zum (persönlichen) Healing-Output
- [Unofficial Extras](https://github.com/Krappa322/arcdps_unofficial_extras_releases/releases) - Ermöglich anderen Addons Zugriff auf zusätzliche Informationen aus dem Spiel

# Analyse von Logs

<alert color="red" icon="❗" text="Wenn du mit dem Mauszeiger über die Spalten oder Zahlen auf dps.report fährst, werden dir in der Regel zusätzliche Informationen angezeigt!">

Sobald Sie ein Protokoll analysiert haben, sollten Sie es verstehen können. Hier sind einige kurze Tipps, worauf Sie achten sollten.

## General Stats

=== Logs lesen ===
Wenn du ein Log analysiert hast, willst du es verstehen. Hier sind ein paar kurze Tipps, was du dir ansehen solltest.

* Schadensstatistiken - Schöner Überblick über die DPS auf einen Blick
* Defensiv-Statistiken - Zeigt Tode und Niederlagen auf einen Blick an, nützlich, wenn du nach Runs suchst, in denen du nicht untergegangen bist.

## Buffs

Beachte die Optionen "Phase duration" und "Phase active duration", bei letzterer werden tote Spieler nicht auf die Uptimes und Durchschnittswerte angerechnet

- Boons
* **Uptime** - Zeigt die durchschnittlichen Stacks und die Gesamtdauer an, es kann sich lohnen, bestimmte Bossphasen auszuwählen (direkt über den Gruppenmitgliedern), wenn der Boss Phasen hatte. Gibt einen guten Überblick darüber, ob die Boons gut oder schlecht waren und schlüsselt sie nach Sub-Squad auf. In einer perfekten Welt hättest du 25 Macht und 100% Uptime für alle erwarteten Boons.
* Generation Self - Nützlich, um zu sehen, welche Boons man selbst erhält, aber normalerweise nicht so wichtig.
* Generation Group - Die Boons, die jeder Spieler an seine Untergruppe (normalerweise 5 Spieler) gegeben hat.
* Generation Squad - Die Boons, die der gesamte Squad erhalten hat. Mittlerweile nicht mehr besonders wichtig, früher konnten einige Klassen Boons für 10 Spieler geben.
- Offensiv-Buffs - Mit Bannern, Geistern und anderen Schadens-Buffs.
- Defensiv-Buffs - Mehr Geister und Utility-Buffs.
- Persönliche Buffs - Klassen- und spezialisierungsspezifische Buffs und Effekte. Einige interessante Details, aber nichts allzu Wichtiges.

## Damage Modifier (Schadensmodifikatoren)

Zeigt den Schadensbonus an, den du mit jeder bestimmten Rune oder Nahrung erhalten würdest(!). Wenn du z.B. eine Gelehrtenrune benutzt (5% Schaden bei über 90% Lebenspunkten), aber nur 87% deiner Treffer über 90% Lebenspunkte liegen, beträgt der Gesamtschaden 4,4%.

## Mechanics

Zeigt wichtige bossspezifische Mechaniken und wie oft Spieler von ihnen getroffen wurden. Wenn niemand getroffen wurde, wird die Mechanik in der Liste nicht angezeigt.

## Graph

Zeigt den DPS aller Spieler für den gesamten Kampf sowie die HP des Endgegners und die Verluste/Todesfälle in einer schönen Grafik an.

## Target Summary
* Outgoing Damage - Zeigt an, welchen Schaden der Boss verursacht hat und welche Angriffe er benutzt hat.
* Incoming Damage - Eingehender Schaden des Bosses.
* **Buff-Status** - Zeigt die auf den Boss angewendeten Bedingungen an. Das ist sehr wichtig, um zu überprüfen, wie lange es dauert, bis er verwundbar ist, oder um sicherzustellen, dass du die Bedingungen auf den Golem angewendet hast.

## Player Summary

Du musst einen Spieler im Gruppenabschnitt oben auswählen.

* Outgoing Damage - Persönliche DPS aufgeschlüsselt nach Fertigkeiten. Das hilft dir auch dabei, die Anzahl der Einsätze der Fähigkeit mit der Anzahl der Treffer zu vergleichen.
* Incoming Damage - Übersicht über alles, was dem Spieler Schaden zugefügt hat.
* **Simple Rotation** - Skills, die in der Reihenfolge verwendet werden, einschließlich Waffenwechsel, Ausweichen, abgebrochene Skills, Wiederbelebungszeit usw. Wichtig ist, dass nicht alle sofort gewirkten Fertigkeiten (Fertigkeiten ohne Wirkzeit) erfasst werden können, wie z. B. Shatter, Mantras und Legendenwechsel. Sehr nützlich, wenn du an deinem Golem-Bench arbeitest, und einer der detailliertesten Bereiche, die du dir ansehen kannst.
* Verbrauchsmaterialien - Hier kannst du nachsehen, welche Lebensmittel/Verbrauchsmaterialien ein Spieler hat und ob sie aufgebraucht sind.

Es gibt auch eine tolle Option für die Kampfwiederholung oben, mit der du alle Positionen sehen und den gesamten Kampf aus der Draufsicht wiederholen kannst. Du kannst auch die Details einschalten, um jederzeit die Gesundheit und Gaben zu sehen. Im Detailmenü gibt es auch Optionen für Ziele (Boss) und Mechaniken. Auf der linken Seite siehst du die DPS und kannst jeden Spieler auswählen, um ihn in einem grünen Kasten zu umreißen (Spieler in ihrem Unterbereich erhalten einen blauen Umriss), außerdem kannst du Kreise um sie herum ziehen, um zu sehen, wie nah sie an Verbündeten oder Feinden sind.