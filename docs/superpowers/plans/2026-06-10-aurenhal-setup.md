# Aurenhal Setup Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** `Aurenhal` als ersten ausgearbeiteten Kanton von `Velis` mit Hauptstadt, Machtprofil und Einbindung in den Universumskanon anlegen.

**Architecture:** Ein neues Regionsdossier für `Aurenhal` und ein neues Siedlungsdossier für `Lysanor` bilden den Kern. Bestehende Dateien wie `Velis`, `Haus Vaelren`, der Siedlungsindex, der Kanon-Index und das Glossar werden ergänzt, damit der Kanton in der Weltlogik sofort auffindbar ist.

**Tech Stack:** Obsidian-Markdown, YAML Frontmatter, Wikilinks, bestehende Universumsstruktur

---

### Task 1: Aurenhal und Lysanor als Dossiers anlegen

**Files:**
- Create: `Universe/Regionen/Aurenhal.md`
- Create: `Universe/Städte und Siedlungen/Lysanor.md`

- [ ] **Step 1: Kantondossier `Aurenhal` schreiben**

Lege `Aurenhal` als Hof- und Verwaltungskanton mit repräsentativer Fassade, Pflichtort-Logik und Intrigenkern an.

- [ ] **Step 2: Stadtdossier `Lysanor` schreiben**

Lege `Lysanor` als Hauptstadt von `Aurenhal` mit Hof-, Verwaltungs- und Symbolfunktion an.

- [ ] **Step 3: Neue Dossiers per Inhaltsprüfung verifizieren**

Prüfe, ob `Aurenhal` und `Lysanor` sauber auf `Velis`, `Haus Vaelren` und die Spec verweisen.

### Task 2: Bestehende Weltseiten um Aurenhal ergänzen

**Files:**
- Modify: `Universe/Regionen/Velis.md`
- Modify: `Universe/Fraktionen/Haus Vaelren.md`
- Modify: `Universe/Städte und Siedlungen/00 Index.md`
- Modify: `Universe/08 Kanon-Index.md`
- Modify: `Universe/09 Universums-Glossar.md`

- [ ] **Step 1: Velis um den Kanton Aurenhal konkretisieren**

Ergänze `Velis` um Verweise auf `Aurenhal` und `Lysanor`.

- [ ] **Step 2: Haus Vaelren um Aurenhal als Machtzentrum konkretisieren**

Beschreibe im Vaelren-Dossier die Rolle von `Aurenhal` und `Lysanor` für die Hauptlinie.

- [ ] **Step 3: Indexe und Glossar aktualisieren**

Nimm `Aurenhal` und `Lysanor` in Siedlungsindex, Kanon-Index und Glossar auf.

- [ ] **Step 4: Geänderte Weltseiten per Inhaltsprüfung verifizieren**

Prüfe, ob die neuen Begriffe konsistent verlinkt sind und der rote Faden von `Velis` in `Aurenhal` klar lesbar wird.

### Task 3: Abschlussprüfung

**Files:**
- Test: `Universe/Regionen/`
- Test: `Universe/Städte und Siedlungen/`
- Test: `docs/superpowers/specs/2026-06-10-aurenhal-design.md`

- [ ] **Step 1: Neue Dateien auflisten**

Liste `Aurenhal` und `Lysanor` in ihren Ordnern auf.

- [ ] **Step 2: Inhalte gegen die Spec abgleichen**

Vergleiche die neuen und geänderten Dateien stichprobenartig mit `docs/superpowers/specs/2026-06-10-aurenhal-design.md`.

- [ ] **Step 3: Arbeitsstand für Übergabe zusammenfassen**

Fasse Kanton, Hauptstadt und die nächsten logischen Ausbaupunkte zusammen.
