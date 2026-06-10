# Glimmernarben-Vergiftung Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Die optionale Nebenquest zur Glimmernarben-Vergiftung, die Suche nach [[Dr. Mc Mallow]] und die notwendigen Hinweise in den frühen Sessions von [[Neufurt]] in die Vault einpflegen.

**Architecture:** Die Resonanzkrankheit wird als entdeckbarer Seitenpfad innerhalb von [[Mission 01 - Stimmen an der Glimmernarbe]] ergänzt. Sessions `02` bis `05` erhalten gestufte Hinweise und Folgen; neue Quest- und NPC-Dateien tragen den Suchbogen nach [[Dr. Mc Mallow]], während Rohstoff-, Orts- und Kanondateien die neue Wahrheitsschicht sichtbar pflegen.

**Tech Stack:** Obsidian Markdown, YAML Frontmatter, Wikilinks

---

### Task 1: Nebenquest und Forscherdatei anlegen

**Files:**
- Create: `Campaigns/Neufurt/Quests/Auf der Suche nach dem Doc.md`
- Create: `Campaigns/Neufurt/NPCs/Dr. Mc Mallow.md`

- [ ] **Step 1: Nebenquest als Folgepfad schreiben**

Content requirements:
- `Auf der Suche nach dem Doc.md` beschreibt Anlass, Fundlogik, Suchpfad und die Gefahr durch verfallene Betroffene.
- Die Quest startet erst nach entdecktem Diagnose-Hinweis und bleibt als Anschlussbogen getrennt von `Wem die Stimmen folgen`.

- [ ] **Step 2: Dr. Mc Mallow als riskanten Experten schreiben**

Content requirements:
- Die NPC-Datei beschreibt ihn als unterschätzten Wahrheitsbringer mit echtem Wissen und gefährlichen Methoden.
- Sie enthält Kurzprofil, aktueller Stand, bekannter Stand für Spieler, DM-Geheimnisse, Entwicklung, Beziehungen und offene Fragen.

- [ ] **Step 3: Neue Dateien verifizieren**

Run: `Get-Content '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Quests\Auf der Suche nach dem Doc.md'`
Expected: Die Quest nennt [[Dr. Mc Mallow]], die [[Die Glimmernarbe]] und verfallene Betroffene als Such- und Konfliktachse.

### Task 2: Frühere Sessions mit Diagnose-Hinweisen erweitern

**Files:**
- Modify: `Campaigns/Neufurt/Sessions/Session 02 - Der Blanksteinpfad.md`
- Modify: `Campaigns/Neufurt/Sessions/Session 03 - Unter der stillen Ader.md`

- [ ] **Step 1: Session 02 mit frühen Warnzeichen ergänzen**

Content requirements:
- Die Session bekommt subtile Hinweise auf Schlafverlust, Ordnungszwang, Entrückung oder Reizbarkeit.
- Der Hint bleibt optional und löst noch keine offizielle Quest aus.

- [ ] **Step 2: Session 03 mit Diagnose-Durchbruch ergänzen**

Content requirements:
- Es wird ein Protokoll, Befund oder dokumentierter Symptomverlauf gefunden.
- Der Fund macht die Resonanzkrankheit plausibel und bereitet die Suche nach Mc Mallow vor.

- [ ] **Step 3: Session-Hinweise verifizieren**

Run: `Get-Content '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Sessions\Session 03 - Unter der stillen Ader.md'`
Expected: Die Session enthält klar einen Diagnose-Hinweis und einen Übergang zur Doc-Suche.

### Task 3: Folge-Sessions und Missionen mit Konsequenzen verschalten

**Files:**
- Modify: `Campaigns/Neufurt/Sessions/Session 04 - Heimkehr mit fremdem Licht.md`
- Modify: `Campaigns/Neufurt/Sessions/Session 05 - Lichter unter Schwarzweiden.md`
- Modify: `Campaigns/Neufurt/Missionen/Mission 02 - Das Schweigen im Schwarzweidenbruch.md`
- Modify: `Campaigns/Neufurt/Quests/Wem die Stimmen folgen.md`

- [ ] **Step 1: Session 04 mit erkanntem oder verpasstem Hint verzweigen**

Content requirements:
- Die Rückkehr nach `Neufurt` berücksichtigt beide Zustände: entdeckte Krankheit oder übersehene Warnung.
- Politische Debatte und erste Folgeschäden werden greifbar.

- [ ] **Step 2: Session 05 mit verfallenen Betroffenen und Mc-Mallow-Spur ergänzen**

Content requirements:
- Der Schwarzweidenbruch-Bogen enthält Begegnungen mit im Wahn verfallenen Menschen.
- Ein Hinweis auf Mc Mallows Aufenthaltsort oder letzte Spur wird spielbar.

- [ ] **Step 3: Mission 02 und Folgequesten synchronisieren**

Content requirements:
- `Mission 02` nennt die Resonanzkrankheit und den Doc-Suchpfad als parallelen Druck.
- `Wem die Stimmen folgen` verweist auf die Krankheit als sozialen Verstärker, ohne die Quest zu ersetzen.

### Task 4: Rohstoff-, Orts- und Kanondateien fortschreiben

**Files:**
- Modify: `Campaigns/Neufurt/Items/Schimmerglas.md`
- Modify: `Campaigns/Neufurt/Orte/Die Glimmernarbe.md`
- Modify: `Campaigns/Neufurt/02 Kanon-Index.md`
- Modify: `Campaigns/Neufurt/03 Offene Fragen.md`
- Modify: `Campaigns/Neufurt/07 Progression Log.md`

- [ ] **Step 1: Schimmerglas und Glimmernarbe um Krankheitsdimension ergänzen**

Content requirements:
- Beide Dateien erhalten progressive Hinweise auf geistige Zersetzung bei längerem Kontakt.
- Die Ergänzung bleibt als `DM-Geheimnis` oder entdeckter Folgestand sauber markiert.

- [ ] **Step 2: Kanondateien aktualisieren**

Content requirements:
- Der Kanon-Index nimmt die neue Quest auf.
- `03 Offene Fragen.md` und `07 Progression Log.md` spiegeln Vergiftung, Doc-Suche und Folgerisiken wider.

- [ ] **Step 3: Abschlussprüfung**

Run: `Get-ChildItem '\\NAS-HOME\Brain\Obsidian\DND\Campaigns\Neufurt\Quests' -Filter *.md | Select-Object -ExpandProperty Name`
Expected: Die Questdateien enthalten `Auf der Suche nach dem Doc.md`, `Was von der Glimmernarbe ruft.md` und `Wem die Stimmen folgen.md`.
