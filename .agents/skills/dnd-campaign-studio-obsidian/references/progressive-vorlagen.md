# Progressive Vorlagen

## Gemeinsame Grundstruktur

Nutze für Charaktere, NPCs, Orte, Fraktionen und Quests mindestens diese Struktur:

```md
# Name

## Kurzprofil

## Aktueller Stand

Gültig ab: [[Mission X - Name]] oder [[Session XX - Name]]

## Bekannter Stand für Spieler

## DM-Geheimnisse

## Entwicklung / Progression

| Gültig ab | Änderung | Auslöser | Sichtbarkeit |
|---|---|---|---|
| [[Session 01 - Beispiel]] | Erste Begegnung | Gruppe trifft Figur | Spielerwissen |
| [[Mission 02 - Beispiel]] | Wahre Loyalität enthüllt | Untersuchung | DM/Spielerwissen |

## Frühere Versionen / Archiv

## Beziehungen

- [[Name]]: Art der Beziehung

## Offene Fragen

- Frage
```

## Spielercharakter

```md
# Charaktername

## Basisdaten

## Aktueller Stand

Gültig ab: [[Session XX - Name]]

## Hintergrund

## Motivation

## Innerer Konflikt

## Beziehungen

## Charakterbogen

| Gültig ab | Entwicklung | Auslöser | Notizen |
|---|---|---|---|
| [[Kampagnenstart]] | Ausgangszustand | Charaktererstellung |  |
| [[Mission 01 - Name]] | Neue Angst / neues Ziel | Ereignis |  |

## Fähigkeiten / Besonderheiten

| Gültig ab | Fähigkeit / Merkmal | Quelle | Spielrelevanz |
|---|---|---|---|

## Geheimnisse

## Bekannte Informationen für andere Spieler

## DM-Hooks

## Bildkanon

Siehe auch: [[Charaktername - Bildprompt]]
```

## NPC

Beobachte besonders:

- Statusänderungen
- Loyalitätswechsel
- enthüllte Geheimnisse
- Beziehungen zur Gruppe
- Tod, Verschwinden oder Verstümmelungen
- neue visuelle Merkmale

Beispiel für Progression:

```md
## Entwicklung / Progression

| Gültig ab | Änderung | Auslöser | Sichtbarkeit |
|---|---|---|---|
| [[Session 01 - Ankunft in Falkenruh]] | Wirkt wie eine hilfreiche Gelehrte | Erstkontakt | Spielerwissen |
| [[Session 04 - Das verbotene Archiv]] | Ist Mitglied des Kultes | Fund alter Briefe | Spielerwissen |
| [[Mission 03 - Das Puppentheater]] | Verliert ihr linkes Auge | Angriff durch Marionette | Spielerwissen |
```

## Ort

Orte verändern sich durch Ereignisse wie Belagerung, Seuche, Zerstörung oder Machtwechsel.

```md
## Zustand des Ortes

| Gültig ab | Zustand | Ursache | Sichtbarkeit |
|---|---|---|---|
| [[Kampagnenstart]] | Neblige Handelsstadt | Ausgangslage | Spielerwissen |
| [[Mission 02 - Die roten Glocken]] | Quarantänezone | Ausbruch der Seuche | Spielerwissen |
```

## Fraktion

```md
## Fraktionsentwicklung

| Gültig ab | Veränderung | Ursache | Sichtbarkeit |
|---|---|---|---|
| [[Kampagnenstart]] | Agiert im Verborgenen | Ausgangslage | DM-Geheimnis |
| [[Session 06 - Die Masken fallen]] | Öffentlich bekannt | Enthüllung | Spielerwissen |
```

## Quest

Statuswerte:

- planned
- active
- paused
- failed
- completed
- abandoned

```md
## Questverlauf

| Stand | Gültig ab | Beschreibung | Konsequenz |
|---|---|---|---|
| Offen | [[Session 02 - Auftrag der Gelehrten]] | Quest erhalten | Neuer Hinweis |
| Aktiv | [[Session 03 - Blut im Brunnen]] | Erster Hinweis gefunden | Zugang zum Archiv |
| Abgeschlossen | [[Session 05 - Der Keller der Puppen]] | Kind gefunden | Fraktion reagiert |
```

## Session

```md
# Session XX - Titel

## Metadaten

- Kampagne: [[Kampagnenname]]
- Mission: [[Mission XX - Name]]
- Datum:
- Spieler:
- Charaktere:

## Vorbereitung

## Zusammenfassung

## Wichtige Ereignisse

## Neue NPCs

- [[Name]]

## Neue Orte

- [[Ort]]

## Neue Quests

- [[Quest]]

## Geänderte bestehende Inhalte

| Datei | Änderung | Gültig ab |
|---|---|---|
| [[Cordelia Greaves]] | Geheimnis teilweise enthüllt | [[Session XX - Titel]] |

## Spielerwissen

## DM-Geheimnisse, die weiterhin geheim bleiben

## Offene Fragen

## Nächster Einstieg
```

## Mission

```md
# Mission XX - Titel

## Kurzbeschreibung

## Ziel der Mission

## Startbedingungen

## Beteiligte Charaktere

## Beteiligte NPCs

## Orte

## Quests

## Mögliche Szenen

## Eskalationsstufen

| Stufe | Bedingung | Folge |
|---|---|---|

## Abschlussbedingungen

## Konsequenzen

## Kanonänderungen

| Inhalt | Änderung | Gültig ab |
|---|---|---|
```

## Enthüllungen und Wahrheit

Trenne bei geheimnislastigen Inhalten sauber zwischen:

- Spielerwissen
- DM-Geheimnissen
- Gerüchten
- Wahrheit

Wenn Wahrheiten bekannt werden, dokumentiere das sichtbar:

```md
## Enthüllungen

| Wahrheit | Enthüllt ab | Enthüllt durch |
|---|---|---|
```

## Retcons

Retcons sind erlaubt, müssen aber sichtbar bleiben.

```md
## Retcons

| Datum | Alte Version | Neue Version | Grund |
|---|---|---|---|
```

Bei kleinen Präzisierungen genügt auch ein Hinweis:

```md
> Hinweis: Diese Information wurde ab [[Session XX]] präzisiert.
```
