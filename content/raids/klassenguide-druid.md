---
title: 'Druid in den Raids'
image: 'https://i.imgur.com/xJasgah.jpeg'
description: 'Dieser Guide für Druid in Raids soll dir zeigen was als Druid geweils dein Job ist und wie du die Möglichkeiten deiner Klasse voll ausnutzen kannst.'
hidden: false
---

[[toc]]

Dieser Guide wurde mit Blick auf das Raid-Clearing und nicht auf Speedrunning geschrieben, daher werden Hardcore-Strategien nicht diskutiert.

# Boons & Buffs

## Spirits 

Waldläufer haben Zugriff zu 5 Spirits (Geistern). Jeder Geist gibt bis zu 10 Spielern alle 3 Sekunden einen einzigartigen Buff der 6 Sekunden anhält. Einige Spirits lösen einen Effekt aus wenn ein Spieler einen Gegner angreift. Diese Effekte haben einen internen Cooldown der von Spirit zu Spirit unterschiedlich ist und, außer beim <embed type="skills" id="12569" size="16">, von den Stats des auslösenden Spielers und nicht des Druids ausgehend. 

Spirits verlieren jede Sekunde HP und müssen so gemanaged werden das Sie nicht sterben und immer in der Nähe der Gruppe bleiben. Mit 600 Reichweite ist der Effekt des Spirits relativ weitreichend.  

Zudem geben alle Spirits bei Reaktivierung der Fähigkeit Buffs für 10 Spieler (skalierend auf der Boonduration vom Druid) durch den Trait <embed type="traits" id="1038" size="16"> und teleportieren sich zum Druid. 

### Passive Effekte der Spirits

| Spirit                                     | Effekt                                                              | Cooldown |
|--------------------------------------------|---------------------------------------------------------------------|----------|
| <embed type="skills" id="21773" size="16"> | Heilt um 863 (0.125) wenn ein Gegner angegriffen wird               | 10s      |
| <embed type="skills" id="12498" size="16"> | Fügt 2 x 2.5s Buring zu wenn ein Gegner angegriffen wird            | 8s       |
| <embed type="skills" id="12493" size="16"> | Fügt 3 x 6s Vulnerability zu wenn ein Gegner angegriffen wird       | 10s      |
| <embed type="skills" id="12497" size="16"> | Gibt einen permanenten 5% Bonus auf Power-Schaden                   | -/-      |
| <embed type="skills" id="12495" size="16"> | Gibt 3s <boon name="protection"> zu wenn ein Gegner angeriffen wird | 10s      |
| <embed type="skills" id="12569" size="16"> | Heilt 101 (0.035) skalierend mit der Healingpower des Druids        | 1s       |

### Aktive Effekte der Spirits

| Spirit                                     | Effekt                                                                 | Boons                                                     |
|--------------------------------------------|------------------------------------------------------------------------|-----------------------------------------------------------|
| <embed type="skills" id="21775" size="16"> | Heilt dich und dein Pet um 3865 (0.35) und deine Subgroup um 1940.     | 5s <boon name="regeneration"> für 10 Spieler.             |
| <embed type="skills" id="12592" size="16"> | Fügt 1 x 4s Burning und 5s Blindness auf 5 Gegner zu                   | 3s <boon name="vigor"> für 10 Spieler.                    |
| <embed type="skills" id="12594" size="16"> | Fügt 2232 (1.275) Schaden und 1s Daze auf 5 Gegner zu                  | 5s <boon name="fury"> für 10 Spieler.                     |
| <embed type="skills" id="12593" size="16"> | Fügt 3s Chill sofort und 5x1sec über Zeit auf 5 Gegner zu              | 8s <boon name="might"> für 10 Spieler.                    |
| <embed type="skills" id="12595" size="16"> | Fügt 2s Immobilize sofort und 4x4s Cripple auf 5 Gegner zu             | 3s <boon name="protection"> für 10 Spieler.               |
| <embed type="skills" id="12596" size="16"> | Cleanst 3 Zustände und belebt bis zu 5 Spieler wieder.                 | 3s <boon name="stability"> für 10 Spieler.                |

### Wann nimmt man was mit?

- Bei Fights mit vielen Zuständen (Sloth, Matthias, Xera, Soulless Horror, Dhuum, Largos) kann <embed type="skills" id="12596" size="16"> nützlich sein, ansonsten nimm <embed type="skills" id="21773" size="16">.
- Wenn Power-Klassen dabei sind solltest du <embed type="skills" id="12497" size="16"> mitnehmen.
- <embed type="skills" id="12498" size="16"> kann genommen werden wenn ein Utility-Slot frei ist für mehr DPS, vorallem wenn Condi-Klassen dabei sind.
- Du solltest <embed type="skills" id="12493" size="16"> nehmen wenn deinem Squad <boon name="fury"> oder Vulnerability fehlt. Vulnerability-Uptime zu korrigieren bringt mehr als die offensiven Spirits!
- <embed type="skills" id="12495" size="16"> wird verwendet um <boon name="protection"> abzudecken. Diesen Spirit solltest du eigentlich immer mitnehmen außer jemand anderes übernimmt Protection (z.B. Tempest) oder Protection ist nicht nötig (z.B. Adina/Samarog/Gorseval)
- Als Elite ist meist <embed type="skills" id="12569" size="16"> am besten. Bei Fights mit Condi-Bursts ist <embed type="skill" id="31677" size="16"> sehr praktisch. Sie kann verwendet werden um die <condition name="confusion"> bei KC, den <condition name="blinded"> bei Zane oder die Condis vom Sloth-Shacke zu verhindern. Auch <embed type="skills" id="12580" size="16"> kann gut sein wenn <condition name="immobile"> benötigt wird wie bei Escort oder Vale Guardian.

## Spotter

Der Trait <embed type="traits" id="1016" size="16"> gibt einen einzigartigen Buff der bis zu 5 Spielern alle 3 Sekunden für 9 Sekunden 100 Präzision, also 4.76% Crit-Chance, gewährt. Die zusätzliche Präzision erlaubt einigen Klassen mehr offensive Stats mitzunehmen und trotzdem dank dem <profession name="druid"> auf 100% Crit-Chance zu kommen.

Alle Power-Klasse brauchen Spotter bis auf:
- Power <profession name="holosmith">
- Power <profession name="daredevil">
- Power <profession name="soulbeast">
- Power <profession name="dragonhunter"> (außer wenn Virtues oder Perfect Inscriptions gespielt wird)

**Wenn du dir unsicher bist frag einfach die Spieler ob ihre Klassen <embed type="traits" id="1016" size="16"> benötigen.**

Einige Condi-Klassen können auch von Spotter profitieren: 
- Condi <profession name="soulbeast"> dank <embed type="traits" id="1069" size="16">
- Condi <profession name="berserker"> dank <embed type="traits" id="1346" size="16">
- Condi <profession name="mirage"> dank <embed type="traits" id="710" size="16">
- Condi <profession name="weaver"> dank <embed type="traits" id="296" size="16">
- Condi <profession name="holosmith"> dank <embed type="traits" id="515" size="16">
- Condi <profession name="scourge"> dank <embed type="traits" id="802" size="16">

Trotzdem sollten immer zuerst die Power-Klassen Spotter erhalten! Sollte eine Klasse die eigentlich Spotter benötigt aus verschiedensten Gründen kein Spotter erhalten können, gib dieser Person Bescheid damit gegebenenfalls Gear oder Food angepasst werden können. Bis auf wenige Ausnahmen hast du als <profession name="druid"> Spotter überall dabei. Mehr zu den Ausnahmen findest du bei den einzelnen Bossen und bei den Traitlines.

## Boons

Als Druid bist du nicht nur für Heilung und Spirits verantwortlich sondern auch für einige Boons für 5 oder 10 Spieler.

### Might

Als Druid ist es deine Aufgabe 25 x <boon name="might"> auf deinem gesamten Squad aufrecht zu halten. Dafür ist der Trait <embed type="traits" id="2057" size="16"> essentiell. Dadruch geben deine Skills im <embed type="skills" id="31869" size="16"> auf 10 Spieler <boon name="might">. 

| Skill                                       | Effekt                          |
|---------------------------------------------|---------------------------------|
| <embed type="skills" id="31869" size="16">  | 2 x <boon name="might"> für 12s |
| <embed type="skills" id="32242" size="16">  | 2 x <boon name="might"> für 12s |
| <embed type="skills" id="32364" size="16">  | 2 x <boon name="might"> für 12s |
| <embed type="skills" id="32253" size="16">  | 10 x <boon name="might"> für 12s|
| <embed type="skills" id="34070" size="16">  | 8 x <boon name="might"> für 12s |

### Fury

Zudem musst du deine Subgroup, oder abhängig der Gruppenzusammenstellung dein gesamtes Squad, mit <boon name="fury"> versorgen. Deine <boon name="fury"> kommt hauptsächlich von <embed type="skills" id="12621" size="16"> mit den Traits <embed type="traits" id="964" size="16"> & <embed type="traits" id="1064" size="16">. Damit kannst du 100% <boon name="fury"> für deine Subgroup aufrecht erhalten.

Wenn du aus verschiedensten Gründen ohne Warhorn spielst kannst du <embed type="traits" id="965" size="16"> statt <embed type="traits" id="964" size="16"> nehmen und dein Pet immer wechseln wenn möglich um ~80% <boon name="fury"> Uptime für deine Subgroup zu generieren. Solltest du keine andere <boon name="fury"> Quelle in deiner Subgroup haben kannst du die restlichen 20% mit dem **roten Moa** und <embed type="skills" id="1064" size="16"> oder <embed type="skills" id="12493" size="16"> abdecken. 

Wenn du **Marksmanship** statt **Skirmishing** läufst kannst du zusätzlich <embed type="traits" id="986" size="16"> verwenden für noch mehr <boon name="fury">.

### Regeneration

Da <profession name="druid"> durch Traits, Runen, Sigille und Food sehr viele Healing-Modifier hat ist <boon name="regeneration"> besonders wichtig und effektiv um dein Squad passiv am Leben zu halten und deinen <embed type="skills" id="31869" size="16"> aufzuladen. Bei 10 Spielern im Squad läd sich dein Avatar nur durch <boon name="regeneration"> um 15% pro Sekunde auf. Wenn mehrere Spieler <boon name="regeneration"> geben wird die mit der stärksten Heilung priorisiert. Um das zu erreichen ist es wichtig das so viele Healing-Modifier wie möglich aufrechterhalten werden.

Healing-Modifier:
| Quelle                                     | Modifier                                 |
|--------------------------------------------|------------------------------------------|
| <embed type="items" id="24842" id="16">    | 20%                                      |
| <embed type="items" id="68634" id="16">    | 10%                                      |
| <embed type="items" id="67528" id="16">    | 10%                                      |
| <embed type="items" id="74326" id="16">    | ~17%                                     |
| <embed type="traits" id="1992" id="16">    | 20%                                      |
| **Gesamt**                                 | ~77%                                     |

Skills die <boon name="regeneration"> geben:
| Skill                                                                                               | Spieler                                 |
|-----------------------------------------------------------------------------------------------------|-----------------------------------------|
| <embed type="skills" id="31496" size="16">                                                          | <tag color="yellow" text="Kein Limit">  |
| <embed type="skills" id="21775" size="16"> dank <embed type="traits" id="1038" size="16">           | <tag color="green" text="Squad">        |
| <embed type="skills" id="12620" size="16"> mit <embed type="traits" id="964" size="16">             | <tag color="blue" text="Subgroup">      |
| <embed type="skills" id="12621" size="16"> mit <embed type="traits" id="964" size="16">             | <tag color="blue" text="Subgroup">      |
| <embed type="skills" id="12489" size="16">                                                          | <tag color="blue" text="Subgroup">      |
| Pet-Wechsel mit <embed type="traits" id="986" size="16"> & <embed type="traits" id="964" size="16"> | <tag color="blue" text="Subgroup">      |

### Protection

Die Schadensreduktion von <boon name="protection"> ist enorm stark und hift Spieler mit <embed type="items" id="24836" size="16"> Uptime, verhindert Tode durch Mechaniken und erlaubt es dir weniger Zeit mit Heilung zu verbringen. Abhängig des Erfahrungslevels deiner Gruppe ist Protection nicht immer bei allen Encoutern nötig. 

Als <profession name="druid"> gibst du <boon name="protection"> mit <embed type="skills" id="12495" size="16"> und dessen Skill <embed type="skills" id="12595" size="16">. Wenn <embed type="skills" id="12595" size="16"> durchgängig aktiviert wird erhält man etwa 67% <boon name="protection"> Uptime. Grundsätzlich ist 60% ein gutes Ziel. Der Grund dafür ist das die <boon name="protection"> die Spieler von passiven Effekt des <embed type="skills" id="12495" size="16"> erhalten mit der Boonduration des jeweiligen Spieler skaliert, nicht mit der des <profession name="druid">.

### Swiftness

Deine einzige Quelle für <boon name="swiftness"> ist <embed type="skills" id="12621" size="16"> mit den Traits <embed type="traits" id="964" size="16"> & <embed type="traits" id="1064" size="16">. Einige Klassen wie <profession name="berserker"> mit <embed type="traits" id="1413" size="16" color="warrior"> benötigen <boon name="swiftness">.