# Neufurt und Dornufer Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Eine erste spielbare Obsidian-Kampagnenbasis für [[Neufurt]] und [[Campaigns/Neufurt/Orte/Das Grenzland von Dornufer|Das Grenzland von Dornufer]] mit Kernnotizen, NSCs, Orten, Storyaufbau und Auftaktmission anlegen.

**Architecture:** Die Kampagne wird als verlinktes Obsidian-Wiki unter `Campaigns/Neufurt/` aufgebaut. Kernnotizen `00` bis `07` bilden die zentrale Übersicht; NSCs, Orte, Fraktionen, Missionen und Sessions werden als Einzeldateien mit YAML-Frontmatter, Wikilinks, `Gültig ab`-Markern und Progressionsabschnitten angelegt.

**Tech Stack:** Obsidian Markdown, YAML Frontmatter, Wikilinks

---

### Task 1: Kampagnenstruktur und Kernverzeichnis anlegen

**Files:**
- Create: `Campaigns/Neufurt/`
- Create: `Campaigns/Neufurt/Charaktere/`
- Create: `Campaigns/Neufurt/NPCs/`
- Create: `Campaigns/Neufurt/Orte/`
- Create: `Campaigns/Neufurt/Fraktionen/`
- Create: `Campaigns/Neufurt/Quests/`
- Create: `Campaigns/Neufurt/Missionen/`
- Create: `Campaigns/Neufurt/Sessions/`
- Create: `Campaigns/Neufurt/Handouts/`
- Create: `Campaigns/Neufurt/Monster/`
- Create: `Campaigns/Neufurt/Bosse/`
- Create: `Campaigns/Neufurt/Items/`
- Create: `Campaigns/Neufurt/Bilder/Charaktere/`
- Create: `Campaigns/Neufurt/Bilder/NPCs/`
- Create: `Campaigns/Neufurt/Bilder/Orte/`
- Create: `Campaigns/Neufurt/Bilder/Karten/`
- Create: `Campaigns/Neufurt/Bilder/Fraktionen/`
- Create: `Campaigns/Neufurt/Archiv/`

- [ ] **Step 1: Ordnerstruktur erzeugen**

Run: `New-Item -ItemType Directory -Force -Path '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Charaktere', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\NPCs', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Orte', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Fraktionen', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Quests', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Missionen', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Sessions', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Handouts', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Monster', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Bosse', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Items', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Bilder\Charaktere', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Bilder\NPCs', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Bilder\Orte', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Bilder\Karten', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Bilder\Fraktionen', '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Archiv'`
Expected: Alle Ordner existieren ohne Fehler.

- [ ] **Step 2: Ordnerstruktur verifizieren**

Run: `Get-ChildItem -Recurse '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt' | Select-Object FullName`
Expected: Die Unterordner `NPCs`, `Orte`, `Fraktionen`, `Missionen`, `Sessions` und `Bilder` sind sichtbar.

### Task 2: Kernnotizen der Kampagne schreiben

**Files:**
- Create: `Campaigns/Neufurt/00 Kampagne.md`
- Create: `Campaigns/Neufurt/01 Timeline.md`
- Create: `Campaigns/Neufurt/02 Kanon-Index.md`
- Create: `Campaigns/Neufurt/03 Offene Fragen.md`
- Create: `Campaigns/Neufurt/04 Gerüchte.md`
- Create: `Campaigns/Neufurt/05 Style Bible.md`
- Create: `Campaigns/Neufurt/06 World Bible.md`
- Create: `Campaigns/Neufurt/07 Progression Log.md`

- [ ] **Step 1: Kampagnenkern in `00` bis `07` formulieren**

Content requirements:
- `00 Kampagne.md` beschreibt Pitch, Thema, Hauptkonflikt, Startpunkt, zentrale Orte, Fraktionen und NSCs.
- `01 Timeline.md` enthält Vorgeschichte vom Aufbruch der Siedler bis kurz nach dem ersten Winter.
- `02 Kanon-Index.md` enthält verlinkte Listen für Orte, NSCs, Quests und Enthüllungen.
- `03 Offene Fragen.md` hält Rohstoff-, Vermissten- und Dornufer-Mysterien fest.
- `04 Gerüchte.md` legt erste spielbare Gerüchte in Neufurt an.
- `05 Style Bible.md` definiert frontierhafte, hoffnungsvolle Bildsprache.
- `06 World Bible.md` beschreibt Dornufer, Siedlerherkunft, Magie und Rohstofflogik.
- `07 Progression Log.md` startet den sichtbaren Kanonverlauf ab [[Kampagnenstart]].

- [ ] **Step 2: Kernnotizen querverlinken**

Run: `Get-Content '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\00 Kampagne.md'`
Expected: Wikilinks zu `[[Neufurt]]`, `[[Campaigns/Neufurt/Orte/Das Grenzland von Dornufer|Das Grenzland von Dornufer]]`, dem Rohstoff und ersten Missionen sind vorhanden.

### Task 3: Erste NSCs und Fraktionsachsen aufbauen

**Files:**
- Create: `Campaigns/Neufurt/NPCs/Mara Venn.md`
- Create: `Campaigns/Neufurt/NPCs/Edric Vale.md`
- Create: `Campaigns/Neufurt/NPCs/Sera Kestel.md`
- Create: `Campaigns/Neufurt/Fraktionen/Rat von Neufurt.md`
- Create: `Campaigns/Neufurt/Fraktionen/Die Freischürfer von Dornufer.md`

- [ ] **Step 1: Drei Ratsfiguren mit klaren Rollen schreiben**

Content requirements:
- `Mara Venn` verkörpert Gemeinschaft, Versorgung und Stabilität.
- `Edric Vale` verkörpert Ehrgeiz, Erschließung und riskante Wachstumslogik.
- `Sera Kestel` verkörpert Freiheitsdrang, Misstrauen gegen Kontrolle und Widerstand gegen Notstandsregeln.
- Jede Datei enthält Kurzprofil, aktueller Stand, bekannter Stand für Spieler, DM-Geheimnisse, Beziehungen, Entwicklung/Progression und offene Fragen.

- [ ] **Step 2: Politische Struktur verlinken**

Content requirements:
- `Rat von Neufurt.md` beschreibt Zusammensetzung, Ziele, Konfliktlinien und Entscheidungsstil.
- `Die Freischürfer von Dornufer.md` bildet unabhängige Sucher und Schürfer als Druckgruppe außerhalb des Rates ab.

- [ ] **Step 3: NSC-Verweise prüfen**

Run: `Get-Content '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Fraktionen\Rat von Neufurt.md'`
Expected: Alle drei Ratsmitglieder sind als Wikilinks referenziert.

### Task 4: Neufurt, Dornufer und den ersten Fundort als Story-Orte schreiben

**Files:**
- Create: `Campaigns/Neufurt/Orte/Neufurt.md`
- Create: `Campaigns/Neufurt/Orte/Das Grenzland von Dornufer.md`
- Create: `Campaigns/Neufurt/Orte/Die Glimmernarbe.md`

- [ ] **Step 1: Siedlung und Region definieren**

Content requirements:
- `Neufurt.md` beschreibt Aufbau, Stimmung, Probleme nach dem ersten Winter, wichtige Bezirke und Alltagsdruck.
- `Das Grenzland von Dornufer.md` beschreibt Geografie, Routen, Gefahren und das Versprechen des neuen Lands.
- `Die Glimmernarbe.md` wird als erster wichtiger Fundort des Rohstoffs etabliert und mit den Vermissten verbunden.

- [ ] **Step 2: Ortseinträge progressiv absichern**

Run: `Get-Content '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Orte\Die Glimmernarbe.md'`
Expected: Der Ort enthält `Gültig ab: [[Kampagnenstart]]`, Spielerwissen, DM-Geheimnisse und Zustand des Ortes.

### Task 5: Auftaktstory, Quest, Mission und erste Session anlegen

**Files:**
- Create: `Campaigns/Neufurt/Quests/Was von der Glimmernarbe ruft.md`
- Create: `Campaigns/Neufurt/Missionen/Mission 01 - Stimmen an der Glimmernarbe.md`
- Create: `Campaigns/Neufurt/Sessions/Session 01 - Stimmen im Tau.md`

- [ ] **Step 1: Quest und Mission formulieren**

Content requirements:
- Die Quest startet aktiv und verknüpft Vermisste, Visionen und Rohstofffundort.
- Die Mission beschreibt Ziel, Startbedingungen, beteiligte NSCs, Orte, Eskalationsstufen und Konsequenzen.

- [ ] **Step 2: Session-Auftakt als spielbaren Einstieg schreiben**

Content requirements:
- `Session 01 - Stimmen im Tau.md` enthält Vorbereitung, Zusammenfassung, wichtige Ereignisse, neue NSCs, neue Orte, Spielerwissen, DM-Geheimnisse und nächsten Einstieg.
- Die Session beginnt in Neufurt mit ersten Berichten über tröstende Visionen und einer Ratsansprache oder Bitte.

- [ ] **Step 3: Kanondateien aktualisieren**

Run: `Get-Content '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\02 Kanon-Index.md'`
Expected: NSCs, Orte, Fraktionen und die Auftaktquest sind eingetragen.

### Task 6: Konsistenzprüfung und Abschluss

**Files:**
- Modify: `Campaigns/Neufurt/00 Kampagne.md`
- Modify: `Campaigns/Neufurt/02 Kanon-Index.md`
- Modify: `Campaigns/Neufurt/07 Progression Log.md`

- [ ] **Step 1: Link- und Kanonprüfung durchführen**

Run: `Get-ChildItem -Recurse '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt' -Filter *.md | Select-Object -ExpandProperty FullName`
Expected: Alle geplanten Markdown-Dateien sind vorhanden.

- [ ] **Step 2: Startkonsistenz prüfen**

Review checklist:
- Alle Kernfiguren, Orte und Storyelemente verwenden dieselben Namen.
- `Gültig ab`-Marker sind in zentralen Dateien gesetzt.
- `Spielerwissen`, `DM-Geheimnisse` und `Gerüchte` sind sauber getrennt.
- `00 Kampagne.md`, `02 Kanon-Index.md` und `07 Progression Log.md` referenzieren die neu angelegten Inhalte.
