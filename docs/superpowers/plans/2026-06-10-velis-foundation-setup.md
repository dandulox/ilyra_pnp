# Velis Foundation Setup Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** `Velis` als erstes ausgearbeitetes Land mit Welt-, Kontinent-, Religions- und Herrschaftsbezügen im Universum verankern.

**Architecture:** Bestehende Kern-Dateien in `Universe/` werden um die neue Namens- und Machtstruktur ergänzt. Zusätzlich entstehen neue Dossiers für `Narethis`, `Velis`, `Haus Vaelren` und `Die Lehre vom Hohllicht`, während `Dornufer` an die neue Landstruktur angebunden wird.

**Tech Stack:** Obsidian-Markdown, YAML Frontmatter, Wikilinks, bestehende Universumsstruktur

---

### Task 1: Kern-Dateien des Universums auf Ilyra, Narethis und Velis ausrichten

**Files:**
- Modify: `Universe/00 Weltüberblick.md`
- Modify: `Universe/02 Geschichte und Epochen.md`
- Modify: `Universe/03 Mächte und Konfliktachsen.md`
- Modify: `Universe/04 Religionen und Kulte.md`
- Modify: `Universe/06 Völker, Kulturen und Gesellschaft.md`
- Modify: `Universe/08 Kanon-Index.md`
- Modify: `Universe/09 Universums-Glossar.md`

- [ ] **Step 1: Weltüberblick um Welt, Kontinent und Land ergänzen**

Trage `Ilyra`, `Narethis` und `Velis` als erste klare Hierarchie in `Universe/00 Weltüberblick.md` ein und verlinke auf die neuen Dossiers.

- [ ] **Step 2: Geschichts- und Machtdateien um Velis-Kontext ergänzen**

Füge in `Universe/02 Geschichte und Epochen.md` und `Universe/03 Mächte und Konfliktachsen.md` die politische Neutralität, wirtschaftliche Auszehrung und die Rolle von `Haus Vaelren` ein.

- [ ] **Step 3: Religions- und Gesellschaftsdateien um Hohllicht und Kantonlogik ergänzen**

Beschreibe in `Universe/04 Religionen und Kulte.md` die öffentliche Anerkennung und okkulte Tiefe der `Lehre vom Hohllicht` und ergänze in `Universe/06 Völker, Kulturen und Gesellschaft.md` die familiär verflochtene Kantonverwaltung von `Velis`.

- [ ] **Step 4: Index und Glossar aktualisieren**

Nimm die neuen Kernbegriffe und Dossiers in `Universe/08 Kanon-Index.md` und `Universe/09 Universums-Glossar.md` auf.

- [ ] **Step 5: Kern-Dateien per Inhaltsprüfung verifizieren**

Öffne die geänderten Dateien und prüfe, ob alle neuen Begriffe verlinkt und der rote Faden `Ilyra -> Narethis -> Velis -> Dornufer` sichtbar ist.

### Task 2: Neue Dossiers für Kontinent, Land, Religion und Herrschaft anlegen

**Files:**
- Create: `Universe/Regionen/Narethis.md`
- Create: `Universe/Regionen/Velis.md`
- Create: `Universe/Religionen/Die Lehre vom Hohllicht.md`
- Create: `Universe/Fraktionen/Haus Vaelren.md`

- [ ] **Step 1: Kontinentdossier `Narethis` erstellen**

Schreibe ein knappes Dossier, das `Narethis` als ersten benannten Kontinent von `Ilyra` beschreibt und `Velis` dort verortet.

- [ ] **Step 2: Landesdossier `Velis` erstellen**

Lege `Velis` als ausgezehrtes, neutral auftretendes Königreich mit sechs Kantonen, wirtschaftlicher Schwäche und religiös verbrämter Ausbeutung an.

- [ ] **Step 3: Religionsdossier `Die Lehre vom Hohllicht` erstellen**

Dokumentiere öffentliche Lehre, verborgenen Kern und politische Funktion der Religion.

- [ ] **Step 4: Fraktionsdossier `Haus Vaelren` erstellen**

Beschreibe das Königshaus als herrschenden Adelstamm mit Seitenlinien in fünf Kantonen und nenne die spätere Familienausarbeitung als nächsten Ausbaupfad.

- [ ] **Step 5: Neue Dossiers per Inhaltsprüfung verifizieren**

Öffne die neuen Dossiers und prüfe, ob sie konsistent aufeinander verweisen.

### Task 3: Dornufer an Velis anbinden

**Files:**
- Modify: `Universe/Regionen/Das Grenzland von Dornufer.md`
- Modify: `Universe/10 Übernahmeplan aus Kampagnen.md`

- [ ] **Step 1: Dornufer als Teil von Velis klar markieren**

Ergänze im Regionsdossier, dass `Dornufer` innerhalb von `Velis` liegt und als vernachlässigter Kantonsteil gilt.

- [ ] **Step 2: Übernahmeplan an die neue Landstruktur anpassen**

Notiere im Übernahmeplan, dass `Dornufer` nun in die Ebenen `Ilyra`, `Narethis` und `Velis` eingebettet ist.

- [ ] **Step 3: Dornufer-Änderungen per Inhaltsprüfung verifizieren**

Öffne beide Dateien und prüfe, ob `Dornufer` nicht mehr isoliert, sondern als Teil der neuen Struktur lesbar ist.

### Task 4: Abschlussprüfung

**Files:**
- Test: `Universe/`
- Test: `docs/superpowers/specs/2026-06-10-velis-foundation-design.md`

- [ ] **Step 1: Verzeichnisstruktur auf neue Dateien prüfen**

Liste `Universe/Regionen`, `Universe/Religionen` und `Universe/Fraktionen` auf und prüfe, ob die neuen Dossiers vorhanden sind.

- [ ] **Step 2: Inhalt gegen die Spec abgleichen**

Vergleiche stichprobenartig die neuen und geänderten Dateien mit `docs/superpowers/specs/2026-06-10-velis-foundation-design.md`.

- [ ] **Step 3: Arbeitsstand für Übergabe zusammenfassen**

Fasse die angelegten Inhalte, die neuen roten Fäden und den nächsten sinnvollen Ausbau von `Haus Vaelren` zusammen.
