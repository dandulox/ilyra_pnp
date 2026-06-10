# Bildkanon und Prompts

## Globaler Stil

Standardrichtung, sofern die Kampagne nichts Präziseres vorgibt:

- Dark Fantasy
- Gothic Horror
- viktorianische Architektur
- Verfall
- Nebel
- Mondlicht
- entsättigte Farben
- realistische Proportionen
- cinematic lighting
- hoher Detailgrad
- kein Anime
- kein Comicstil
- kein Chibi
- keine modernen Gegenstände

## Style Bible

Prüfe vor jedem Bildprompt, ob `05 Style Bible.md` existiert. Wenn ja, hat diese Datei Vorrang vor allgemeinen Stilannahmen.

Empfohlene Struktur:

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

## Bildprompt-Dateien

Lege für wichtige Inhalte eigene Prompt-Dateien an:

```text
Bilder/NPCs/Cordelia Greaves - Bildprompt.md
Bilder/Orte/Falkenruh - Bildprompt.md
Bilder/Karten/Falkenruh Stadtkarte - Bildprompt.md
Bilder/Fraktionen/Kult des Blassen Mondes - Symbolprompt.md
```

## Bildkanon-Vorlage

```md
# Name - Bildprompt

## Zugehöriger Inhalt

- Hauptdatei: [[Name]]
- Typ:
- Gültig ab: [[Session XX - Name]]

## Visueller Kanon

| Gültig ab | Merkmal | Ursache | Sichtbarkeit |
|---|---|---|---|
| [[Kampagnenstart]] | Dunkler Mantel, silberne Augen | Ausgangsdesign | Spielerwissen |
| [[Mission 03 - Das Puppentheater]] | Linkes Auge vernarbt | Verletzung | Spielerwissen |

## Aktueller Bildprompt

```text
...
```

## Negativprompt

```text
anime, cartoon, chibi, modern clothing, sci-fi, bright colors
```

## Frühere Bildversionen

### Version 1

Gültig von: [[Kampagnenstart]]
Gültig bis: [[Mission 03 - Das Puppentheater]]

```text
...
```
```

## Prompt-Vorlagen

### Charakter

```text
Dark fantasy gothic horror character concept art of [Name], [Rolle], [Alter], [Kleidung], [besondere Merkmale], [Fraktionselemente], standing in [Ort], moonlit fog, victorian dark fantasy, cinematic lighting, highly detailed, realistic proportions, muted colors, no anime, no cartoon, no modern objects.
```

### Ort

```text
Dark fantasy gothic horror environment concept art of [Ort], [Architektur], [Stimmung], [Wetter], [wichtige Merkmale], moonlit fog, victorian decay, cinematic lighting, muted colors, highly detailed, no modern objects, no cartoon.
```

### Karte

```text
Hand-drawn dark fantasy map of [Ort/Region], parchment texture, black ink, gothic cartography, readable labels, north at top, consistent symbols, old world map style, muted sepia tones, no satellite view, no modern map icons, no bright colors.
```

### Fraktionssymbol

```text
Dark fantasy faction emblem for [Fraktion], [Symbolik], gothic heraldry, engraved metal, black ink version, parchment version, simple readable silhouette, no modern logo style, no bright colors.
```
