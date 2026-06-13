# Brasselmark Transport Chokepoint Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** `Brasselmark` um einen dritten Ortsknoten und einen zweiten direkt anschließenden Konfliktbogen erweitern.

**Architecture:** Ein neuer Übergabe- und Kontrollort in `Brasselmark` bildet den räumlichen Kern. Eine neue Konfliktdatei zeigt, wie sich der Druck aus `Kornwacht` nach `Das erste Siegel von Hagbrunn` auf Wege, Wagen und Winterversorgung ausdehnt. Anschließend werden die bestehenden Kanton- und Ortsdossiers knapp nachgezogen.

**Tech Stack:** Obsidian-Markdown, YAML-Frontmatter, Wikilinks, bestehende Universumsstruktur

---

### Task 1: Neuen Brasselmark-Ort und Folgekonflikt anlegen

**Files:**
- Create: `Universe/Städte und Siedlungen/Riegelsteg.md`
- Create: `Universe/Regionen/Brasselmark/Brasselmark - Der Winterzoll von Riegelsteg.md`

- [ ] **Step 1: Ortsnamen und Konfliktnamen festziehen**

Lege `Riegelsteg` als kleinen Weg-, Brücken- und Übergabeort fest und `Der Winterzoll von Riegelsteg` als Folgekonflikt.

- [ ] **Step 2: Ortsdossier `Riegelsteg` schreiben**

Schreibe `Riegelsteg` als nüchternen Kontrollpunkt zwischen Dorfverkehr und Kornwacht-Logik mit Kurzprofil, aktuellem Stand, Funktionen, öffentlicher Lage, verdeckten Spannungen und Verweisen.

- [ ] **Step 3: Konfliktdossier `Der Winterzoll von Riegelsteg` schreiben**

Schreibe den Folgekonflikt als Ausweitung der Ordnung auf Wege, Zugtiere, Brennholz und Nebenvorräte.

- [ ] **Step 4: Neue Dateien inhaltlich gegeneinander prüfen**

Prüfe, ob `Riegelsteg` und `Der Winterzoll von Riegelsteg` denselben Ton tragen und klar an `Hagbrunn`, `Kornwacht` und `Das erste Siegel von Hagbrunn` anschließen.

### Task 2: Bestehende Brasselmark-Dateien verknüpfen

**Files:**
- Modify: `Universe/Regionen/Brasselmark.md`
- Modify: `Universe/Städte und Siedlungen/Kornwacht.md`
- Modify: `Universe/Städte und Siedlungen/Hagbrunn.md`

- [ ] **Step 1: `Brasselmark` um Riegelsteg und den Winterzoll ergänzen**

Ergänze den Kanton um den dritten Ortstyp und die neue Konfliktlinie der Wegaufsicht.

- [ ] **Step 2: `Kornwacht` um den vorgelagerten Kontrollpunkt ergänzen**

Ergänze `Kornwacht` um die Funktion von `Riegelsteg` als Vorfeld von Prüfung, Umlenkung und Druck.

- [ ] **Step 3: `Hagbrunn` um die neue Druckwelle ergänzen**

Ergänze `Hagbrunn` um die Folge, dass selbst Wege und Wintertransporte nach dem ersten Siegel unsicherer werden.

- [ ] **Step 4: Verweislogik prüfen**

Prüfe, ob alle drei Dateien sauber auf `Riegelsteg`, `Der Winterzoll von Riegelsteg` und die bestehenden Brasselmark-Konflikte verlinken.

### Task 3: Übersichten nachziehen und Abschlussprüfung

**Files:**
- Modify: `Universe/Städte und Siedlungen/00 Index.md`
- Modify: `Universe/08 Kanon-Index.md`
- Modify: `Universe/09 Universums-Glossar.md`
- Test: `docs/superpowers/specs/2026-06-11-brasselmark-transport-chokepoint-design.md`

- [ ] **Step 1: Siedlungsindex aktualisieren**

Nimm `Riegelsteg` in den Siedlungsindex auf.

- [ ] **Step 2: Kanon-Index aktualisieren**

Nimm `Riegelsteg` und `Der Winterzoll von Riegelsteg` in den Kanon-Index auf.

- [ ] **Step 3: Glossar um den Orts- oder Konfliktbegriff erweitern**

Ergänze `Riegelsteg` und bei Bedarf `Winterzoll` als klaren Weltbegriff.

- [ ] **Step 4: Arbeitsstand gegen die Spec abgleichen**

Prüfe stichprobenartig, ob Ort, Konflikt und Verknüpfungen die Leitentscheidungen aus `docs/superpowers/specs/2026-06-11-brasselmark-transport-chokepoint-design.md` erfüllen.
