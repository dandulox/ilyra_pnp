# Kampagnenstruktur

## Ordnerstruktur

Standardstruktur für neue Kampagnen:

```text
Campaigns/
└── Kampagnenname/
    ├── 00 Kampagne.md
    ├── 01 Timeline.md
    ├── 02 Kanon-Index.md
    ├── 03 Offene Fragen.md
    ├── 04 Gerüchte.md
    ├── 05 Style Bible.md
    ├── 06 World Bible.md
    ├── 07 Progression Log.md
    ├── Charaktere/
    ├── NPCs/
    ├── Orte/
    ├── Fraktionen/
    ├── Quests/
    ├── Missionen/
    ├── Sessions/
    ├── Handouts/
    ├── Monster/
    ├── Bosse/
    ├── Items/
    ├── Bilder/
    │   ├── Charaktere/
    │   ├── NPCs/
    │   ├── Orte/
    │   ├── Karten/
    │   └── Fraktionen/
    └── Archiv/
```

## Dateibenennung

- nutze klare, stabile Namen
- verwende keine Zufalls- oder Arbeitsnamen
- halte Session- und Missionsdateien nummeriert

Beispiele:

```text
Cordelia Greaves.md
Kult des Blassen Mondes.md
Falkenruh.md
Session 01 - Stimmen aus der Kanalisation.md
Mission 03 - Das Puppentheater.md
```

## Frontmatter-Vorlagen

### Kampagne

```yaml
---
type: campaign
name: Kampagnenname
status: active
system: DnD 5e
tone:
  - dark-fantasy
  - gothic-horror
tags:
  - campaign
  - dnd
created_in: campaign-start
last_updated_in: campaign-start
---
```

### Spielercharakter

```yaml
---
type: player-character
name: Name
player: Spielername
status: active
first_appears_in: Kampagnenstart
current_location:
faction:
level:
class:
species:
tags:
  - character
canon_status: active
last_updated_in:
---
```

### NPC

```yaml
---
type: npc
name: Name
status: alive
first_appears_in:
current_location:
faction:
relationship_to_party: unknown
visibility: known
tags:
  - npc
canon_status: active
last_updated_in:
---
```

### Ort

```yaml
---
type: location
name: Name
region:
status: active
first_appears_in:
danger_level:
controlling_faction:
tags:
  - location
canon_status: active
last_updated_in:
---
```

### Fraktion

```yaml
---
type: faction
name: Name
status: active
first_appears_in:
leader:
headquarters:
relationship_to_party: unknown
tags:
  - faction
canon_status: active
last_updated_in:
---
```

### Quest

```yaml
---
type: quest
name: Questname
status: active
quest_type: main
giver:
first_appears_in:
resolved_in:
tags:
  - quest
canon_status: active
last_updated_in:
---
```

### Mission

```yaml
---
type: mission
name: Missionsname
status: planned
part_of_campaign:
starts_in:
ends_in:
tags:
  - mission
canon_status: active
last_updated_in:
---
```

### Session

```yaml
---
type: session
session_number:
title:
date_played:
campaign:
mission:
status: planned
tags:
  - session
---
```

## Kern-Dateien

### 00 Kampagne.md

```md
# Kampagnenname

## Kurzpitch

## Thema

## Ton

## Hauptkonflikt

## Startpunkt

## Zentrale Orte

## Zentrale Fraktionen

## Zentrale NPCs

## Kampagnenstruktur

## Aktueller Stand

Gültig ab: [[Kampagnenstart]]

## Offene Handlungsstränge

## Mögliche Enden
```

### 02 Kanon-Index.md

```md
# Kanon-Index

## Aktive Charaktere

## Aktive NPCs

## Tote / verschwundene NPCs

## Aktive Orte

## Veränderte Orte

## Aktive Fraktionen

## Zerschlagene Fraktionen

## Aktive Quests

## Abgeschlossene Quests

## Wichtige Enthüllungen

| Enthüllung | Bekannt ab | Bekannt für |
|---|---|---|
```

### 03 Offene Fragen.md

```md
# Offene Fragen

- Frage
```

### 04 Gerüchte.md

```md
# Gerüchte

- Gerücht
```

### 05 Style Bible.md

```md
# Style Bible

## Art Direction

## Architektur

## Farbpalette

## Kleidung

## Waffen

## Licht

## Symbole

## Fraktionsdesign

## Kartenstil

## Negativ-Prompts

## Wiederkehrende Motive
```

### 06 World Bible.md

```md
# World Bible

## Regionen

## Religionen

## Magie

## Geschichte

## Kalender

## Währungen

## Gesellschaft

## Monster

## Wiederkehrende Motive

## Kanonische Begriffe
```

### 07 Progression Log.md

```md
# Progression Log

| Datum / Session | Inhalt | Änderung | Datei |
|---|---|---|---|
| [[Session 04 - Der Blutmond]] | [[Cordelia Greaves]] | Kultmitgliedschaft enthüllt | [[Cordelia Greaves]] |
```
