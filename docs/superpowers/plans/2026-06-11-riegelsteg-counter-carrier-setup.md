# Riegelsteg Counter Carrier Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** `Riegelsteg` um eine erste vorsichtige Gegenfigur ergänzen, die Bewegung weniger lesbar macht.

**Architecture:** Ein neues Personendossier bildet den Kern. Danach werden `Riegelsteg`, `Der Winterzoll von Riegelsteg`, `Hagbrunn` und der Personenindex knapp nachgezogen, damit die Figur als stiller Gegenpol zu den Kontrollfiguren unmittelbar lesbar ist.

**Tech Stack:** Obsidian-Markdown, YAML-Frontmatter, Wikilinks, bestehende Universumsstruktur

---

### Task 1: Gegenfigur als Fuhrmensch anlegen

**Files:**
- Create: `Universe/Personen/Wagenlenker Jerrik Voss.md`

- [ ] **Step 1: Namen und Rollenprofil festziehen**

Lege `Wagenlenker Jerrik Voss` als stillen Lenker von Mischlasten fest, der Timing, Vorwand und Unauffälligkeit besser liest als offene Konfrontation.

- [ ] **Step 2: Personendossier schreiben**

Schreibe Jerrik mit Kurzprofil, aktuellem Stand, öffentlicher Stellung, verdeckten Spannungen, Hintergrund, Beziehungen und Rolle in Brasselmark.

- [ ] **Step 3: Rollenabgrenzung prüfen**

Prüfe, ob Jerrik weder wie ein offener Rebell noch wie eine dritte Kontrollfigur wirkt.

### Task 2: Riegelsteg, Winterzoll und Hagbrunn ergänzen

**Files:**
- Modify: `Universe/Städte und Siedlungen/Riegelsteg.md`
- Modify: `Universe/Regionen/Brasselmark - Der Winterzoll von Riegelsteg.md`
- Modify: `Universe/Städte und Siedlungen/Hagbrunn.md`

- [ ] **Step 1: `Riegelsteg` um die Gegenfigur ergänzen**

Ergänze das Ortsdossier so, dass Jerrik als stille Musterlücke neben den Kontrollfiguren lesbar wird.

- [ ] **Step 2: `Der Winterzoll von Riegelsteg` um seine riskante Funktion ergänzen**

Zeige im Konfliktdossier knapp, wie Jerrik Transporte weniger eindeutig erscheinen lässt, ohne die Kontrolle offen zu brechen.

- [ ] **Step 3: `Hagbrunn` um einen vorsichtigen Verbindungsfaden ergänzen**

Zeige, dass für einzelne kleine Bewegungen nach außen Figuren wie Jerrik wichtig werden, ohne daraus bereits ein stabiles Netzwerk zu machen.

- [ ] **Step 4: Verweislogik prüfen**

Prüfe, ob alle drei Dateien sauber auf Jerrik verlinken und sein Dossier auf Ort und Konflikt zurückweist.

### Task 3: Personenindex aktualisieren und Abschlussprüfung

**Files:**
- Modify: `Universe/Personen/00 Index.md`
- Test: `docs/superpowers/specs/2026-06-11-riegelsteg-counter-carrier-design.md`

- [ ] **Step 1: Personenindex im Abschnitt `Riegelsteg` ergänzen**

Nimm `Wagenlenker Jerrik Voss` in den bestehenden Abschnitt auf.

- [ ] **Step 2: Datumsstand des Index nachziehen**

Setze `last_updated_in` und `Gültig ab` auf `2026-06-11-riegelsteg-counter-carrier`.

- [ ] **Step 3: Arbeitsstand gegen die Spec abgleichen**

Prüfe stichprobenartig, ob Jerrik als vorsichtige Gegenfigur, nicht als Held oder offener Aufständischer, lesbar ist.
