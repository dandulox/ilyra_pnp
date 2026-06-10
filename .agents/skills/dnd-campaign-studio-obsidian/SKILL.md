---
name: dnd-campaign-studio-obsidian
description: Unterstützt beim Erstellen, Erweitern und Pflegen von D&D- und anderen Pen-&-Paper-Kampagnen als verlinktes Obsidian-Markdown-Wiki. Verwenden, wenn Codex Kampagnen, Welten, Charaktere, NPCs, Orte, Fraktionen, Quests, Missionen, Sessions, Handouts, Kanon-Updates oder Bildprompts mit YAML-Frontmatter, Wikilinks und progressivem Kanonmanagement strukturieren oder aktualisieren soll.
---

# D&D Campaign Studio für Obsidian

## Überblick

Arbeite Obsidian-first. Denke jeden wichtigen Inhalt als eigene Markdown-Datei mit YAML Frontmatter, Wikilinks und klarer Kanon-Historie.

Optimiere auf Spielbarkeit und Langzeitpflege:

- schreibe nutzbar statt nur atmosphärisch
- vermeide lange Lore ohne Spielzweck
- halte Informationen erweiterbar und querverlinkt
- aktualisiere bestehenden Kanon sichtbar statt still zu überschreiben

## Kernregeln

1. Prüfe zuerst, ob passende Dateien bereits existieren oder erwähnt wurden.
2. Erweitere bestehende Dateien bevorzugt, statt Duplikate zu erzeugen.
3. Markiere neue oder geänderte Informationen immer mit `Gültig ab:`.
4. Trenne konsequent zwischen `Spielerwissen`, `DM-Geheimnissen`, `Gerüchten` und bestätigter Wahrheit.
5. Pflege bei relevanten Änderungen auch abhängige Dateien wie `02 Kanon-Index.md`, `07 Progression Log.md` und Bildprompt-Dateien.
6. Schreibe Dateinamen klar, stabil und Obsidian-freundlich.
7. Verwende für wichtige Namen immer Wikilinks wie `[[Cordelia Greaves]]`.

## Arbeitsablauf

### Neue Kampagne

- Lege die Kampagnenstruktur aus [references/kampagnenstruktur.md](references/kampagnenstruktur.md) an.
- Erstelle mindestens die Kern-Dateien `00` bis `07`.
- Richte Ton, Stil, Weltlogik und offenen Kanon früh ein.

### Neue oder geänderte Inhalte

- Lies für Ordnerstruktur, Dateinamen und Frontmatter zuerst [references/kampagnenstruktur.md](references/kampagnenstruktur.md).
- Lies für progressive Inhaltsvorlagen [references/progressive-vorlagen.md](references/progressive-vorlagen.md).
- Wenn eine grobe Idee vorliegt, liefere einen spielbaren Entwurf plus passende Ziel-Dateien.
- Wenn eine bestehende Entität geändert wird, ergänze die Änderung als neuen Stand statt alte Aussagen unsichtbar zu ersetzen.

### Session- oder Missionsnotizen

- Fasse Rohnotizen in spielrelevante Ereignisse zusammen.
- Erkenne neue NPCs, Orte, Quests, Geheimnisse und Kanonverschiebungen.
- Aktualisiere betroffene Entitäten, den Kanon-Index, das Progression Log und offene Fragen.

### Bildkanon und Prompts

- Prüfe vor jedem Bildprompt, ob `05 Style Bible.md` existiert.
- Übernimm Stil, Motive und Negativ-Prompts aus der Style Bible.
- Lies für visuelle Regeln und Prompt-Vorlagen [references/bildkanon-und-prompts.md](references/bildkanon-und-prompts.md).

## Ausgabeformat

Wenn konkrete Dateien erstellt oder aktualisiert werden sollen, antworte in dieser Reihenfolge:

1. Bei mehreren Dateien zuerst eine Übersicht:

```md
## Dateien

- `Campaigns/Kampagnenname/NPCs/Name.md` - erstellen
- `Campaigns/Kampagnenname/07 Progression Log.md` - aktualisieren
```

2. Danach pro Datei:

```text
Pfad: Campaigns/Kampagnenname/NPCs/Name.md
Aktion: erstellen
```

3. Direkt darunter der vollständige Markdown-Inhalt.

Wenn der Nutzer nur Ideen, Verbesserungsvorschläge oder Strukturhilfe will, liefere trotzdem:

- die wahrscheinlich betroffenen Dateien
- klare Annahmen
- Anschlussvorschläge für Kanon- und Progressionspflege

## Kanon und Sichtbarkeit

Behandle jede relevante Information als zeitgebunden.

Nutze Formulierungen wie:

```md
Gültig ab: [[Kampagnenstart]]
Gültig ab: [[Mission 02 - Das Puppentheater]]
Gültig ab: [[Session 04 - Der Blutmond]]
Sichtbarkeit: Spielerwissen
Sichtbarkeit: DM-Geheimnis
Sichtbarkeit: Gerücht
```

Retcons sind erlaubt, aber nie unsichtbar. Dokumentiere sie in einer eigenen `Retcons`-Sektion oder als klaren Hinweis mit Bezug auf die auslösende Session oder Mission.

## Qualitätsmaßstab

Liefere nicht nur einen einzelnen Inhalt, sondern einen wartbaren Kampagnenstand. Denke also immer auch an:

- Beziehungen zwischen Dateien
- sichtbare Entwicklungsverläufe
- Konsequenzen von Quests und Szenen
- anschließbare Plot-Hooks
- visuellen Kanon

## Referenzen

- Lies [references/kampagnenstruktur.md](references/kampagnenstruktur.md) für Ordnerstruktur, Kern-Dateien, Dateibenennung und Frontmatter.
- Lies [references/progressive-vorlagen.md](references/progressive-vorlagen.md) für Templates von Charakteren, NPCs, Orten, Fraktionen, Quests, Missionen und Sessions.
- Lies [references/bildkanon-und-prompts.md](references/bildkanon-und-prompts.md) für Style Bible, Bildkanon und Prompt-Vorlagen.
