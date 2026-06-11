# Brasselmark Setup Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** `Brasselmark` als zweiten ausgearbeiteten Kanton von `Velis` mit Zentralort, Abgabelogik und Einbindung in den Universumskanon anlegen.

**Architecture:** Ein neues Regionsdossier für `Brasselmark` und ein neues Siedlungsdossier für `Kornwacht` bilden den Kern. `Velis`, `Haus Vaelren`, der Siedlungsindex, der Kanon-Index und das Glossar werden ergänzt, damit der Kanton als materieller Gegenpol zu `Aurenhal` direkt lesbar wird.

**Tech Stack:** Obsidian-Markdown, YAML Frontmatter, Wikilinks, bestehende Universumsstruktur

---

### Task 1: Brasselmark und Kornwacht als Dossiers anlegen

**Files:**
- Create: `Universe/Regionen/Brasselmark.md`
- Create: `Universe/Städte und Siedlungen/Kornwacht.md`

- [ ] **Step 1: Kantondossier `Brasselmark` schreiben**

Lege Brasselmark als fruchtbaren, aber ausgezehrten Abgabekanton mit Speicher- und Sammelplatzlogik an.

- [ ] **Step 2: Stadtdossier `Kornwacht` schreiben**

Lege Kornwacht als harten Zentralort der Erfassung, Lagerung und Weiterleitung an.

- [ ] **Step 3: Neue Dossiers per Inhaltsprüfung verifizieren**

Prüfe, ob `Brasselmark` und `Kornwacht` sauber auf `Velis`, `Haus Vaelren` und die Spec verweisen.

### Task 2: Bestehende Weltseiten um Brasselmark ergänzen

**Files:**
- Modify: `Universe/Regionen/Velis.md`
- Modify: `Universe/Fraktionen/Haus Vaelren.md`
- Modify: `Universe/Städte und Siedlungen/00 Index.md`
- Modify: `Universe/08 Kanon-Index.md`
- Modify: `Universe/09 Universums-Glossar.md`

- [ ] **Step 1: `Velis` um Brasselmark konkretisieren**

Ergänze `Velis` um Verweise auf `Brasselmark`, `Kornwacht` und die Rolle von Hadriks Linie.

- [ ] **Step 2: `Haus Vaelren` um Brasselmark als Abgabekern ergänzen**

Beschreibe im Vaelren-Dossier die Rolle von `Brasselmark` für die Herrschaft von [[Herzog Hadrik Vaelren]].

- [ ] **Step 3: Indexe und Glossar aktualisieren**

Nimm `Brasselmark` und `Kornwacht` in Siedlungsindex, Kanon-Index und Glossar auf.

- [ ] **Step 4: Geänderte Weltseiten per Inhaltsprüfung verifizieren**

Prüfe, ob der neue Gegensatz `Aurenhal -> Brasselmark` klar lesbar wird.

### Task 3: Abschlussprüfung

**Files:**
- Test: `Universe/Regionen/`
- Test: `Universe/Städte und Siedlungen/`
- Test: `docs/superpowers/specs/2026-06-10-brasselmark-design.md`

- [ ] **Step 1: Neue Dateien auflisten**

Liste `Brasselmark` und `Kornwacht` in ihren Ordnern auf.

- [ ] **Step 2: Inhalte gegen die Spec abgleichen**

Vergleiche die neuen und geänderten Dateien stichprobenartig mit `docs/superpowers/specs/2026-06-10-brasselmark-design.md`.

- [ ] **Step 3: Arbeitsstand für Übergabe zusammenfassen**

Fasse Kanton, Zentralort und die nächsten logischen Ausbaupunkte zusammen.
