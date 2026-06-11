# Riegelsteg Control Figures Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** `Riegelsteg` durch zwei erste Kontrollfiguren als sozialer Druckraum personifizieren.

**Architecture:** Zwei neue Personendossiers bilden die Ebenen von formaler und persönlicher Kontrolle ab. Danach werden `Riegelsteg`, `Der Winterzoll von Riegelsteg` und der Personenindex knapp nachgezogen, damit Ort, Konflikt und Figuren unmittelbar zusammen lesbar sind.

**Tech Stack:** Obsidian-Markdown, YAML-Frontmatter, Wikilinks, bestehende Universumsstruktur

---

### Task 1: Zwei Kontrollfiguren für Riegelsteg anlegen

**Files:**
- Create: `Universe/Personen/Wegaufseherin Lysa Dorn.md`
- Create: `Universe/Personen/Brückenwart Hobb Kerlen.md`

- [ ] **Step 1: Namen und Rollen festziehen**

Lege `Wegaufseherin Lysa Dorn` als kühle Instanz der Sichtung und `Brückenwart Hobb Kerlen` als ortskundiges Gedächtnis von Riegelsteg fest.

- [ ] **Step 2: Personendossier für Lysa Dorn schreiben**

Schreibe Lysa mit Kurzprofil, aktuellem Stand, öffentlicher Stellung, verdeckten Spannungen, Hintergrund, Beziehungen und Rolle in Brasselmark.

- [ ] **Step 3: Personendossier für Hobb Kerlen schreiben**

Schreibe Hobb mit Kurzprofil, aktuellem Stand, öffentlicher Stellung, verdeckten Spannungen, Hintergrund, Beziehungen und Rolle in Brasselmark.

- [ ] **Step 4: Neue Figuren gegeneinander prüfen**

Prüfe, ob Lysa für formale Ordnung und Hobb für persönliche Ortskontrolle klar unterscheidbar bleiben.

### Task 2: Riegelsteg und Winterzoll um die Figuren ergänzen

**Files:**
- Modify: `Universe/Städte und Siedlungen/Riegelsteg.md`
- Modify: `Universe/Regionen/Brasselmark - Der Winterzoll von Riegelsteg.md`

- [ ] **Step 1: `Riegelsteg` um eine Schlüsselfiguren-Sektion ergänzen**

Trage beide Figuren mit je einer prägnanten Rollenbeschreibung in das Ortsdossier ein.

- [ ] **Step 2: `Der Winterzoll von Riegelsteg` um die Rollen im Ablauf ergänzen**

Zeige im Konfliktdossier knapp, wie Lysa die formale Sichtung trägt und Hobb Abweichungen aus Ortskenntnis früh erkennt.

- [ ] **Step 3: Verweislogik prüfen**

Prüfe, ob beide Dateien sauber auf die neuen Figuren verlinken und die Figuren zurück auf Ort und Konflikt weisen.

### Task 3: Personenindex aktualisieren und Abschlussprüfung

**Files:**
- Modify: `Universe/Personen/00 Index.md`
- Test: `docs/superpowers/specs/2026-06-11-riegelsteg-control-figures-design.md`

- [ ] **Step 1: Personenindex aktualisieren**

Lege einen neuen Abschnitt `Riegelsteg` an und nimm beide Figuren dort auf.

- [ ] **Step 2: Datumsstand des Index nachziehen**

Setze `last_updated_in` und `Gültig ab` auf `2026-06-11-riegelsteg-control-figures`.

- [ ] **Step 3: Arbeitsstand gegen die Spec abgleichen**

Prüfe stichprobenartig, ob Rollenabgrenzung, Ton und betroffene Dateien die Leitentscheidungen aus `docs/superpowers/specs/2026-06-11-riegelsteg-control-figures-design.md` erfüllen.
