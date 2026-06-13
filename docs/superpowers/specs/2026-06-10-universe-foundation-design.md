# Design Spec: Universums-Grundlage vor Kampagnen

## Ziel

Der Vault soll nicht mehr primär kampagnengetrieben wachsen, sondern zuerst ein zentrales, kampagnenstabiles Universum erhalten. Dieses Universum dient als gemeinsame Wissensbasis für spätere Kampagnen, ohne dass Kampagnen den Kernkanon dauerhaft überschreiben.

## Ausgangslage

Aktuell liegt der Schwerpunkt in `Campaigns/Neufurt/`. Dort befindet sich bereits allgemeines Weltwissen, das über die einzelne Kampagne hinaus brauchbar ist, zum Beispiel zu [[Regionen/Das Grenzland von Dornufer|Das Grenzland von Dornufer]], [[Rohstoffe und Artefakte/Schimmerglas|Schimmerglas]] und grundlegenden sozialen, wirtschaftlichen und magischen Zusammenhängen.

Diese Informationen sollen nicht verworfen werden. Allgemeingültige Inhalte werden schrittweise in einen zentralen Universumsbereich übernommen. Kampagnenspezifische Perspektiven, Geheimnisse, Missionsfolgen und Session-Konsequenzen bleiben in der jeweiligen Kampagne.

## Leitentscheidungen

- Es gibt ein zentrales gemeinsames Universum für alles.
- Kampagnen dürfen den Kern des Universums nicht dauerhaft zurückschreiben.
- Das Universum wird direkt tief ausgearbeitet, nicht nur grob skizziert.
- Die Weltbasis bleibt tonal neutral; Kampagnen können später ihren eigenen Ton setzen.
- Bestehende allgemeine Weltinformationen aus `Neufurt` werden übernommen.
- Das Universum enthält nicht nur gesicherte Wahrheiten, sondern auch Überlieferungen, Legenden und umstrittene Deutungen.
- Der Strukturansatz ist ein Hybrid aus Kern-Dateien und vertiefenden Dossiers.

## Zielstruktur

```text
Universe/
├── 00 Weltüberblick.md
├── 01 Kosmologie und Grundgesetze.md
├── 02 Geschichte und Epochen.md
├── 03 Mächte und Konfliktachsen.md
├── 04 Religionen und Kulte.md
├── 05 Magie und übernatürliche Phänomene.md
├── 06 Völker, Kulturen und Gesellschaft.md
├── 07 Wahrheiten, Legenden und Streitfragen.md
├── 08 Kanon-Index.md
├── 09 Universums-Glossar.md
├── 10 Übernahmeplan aus Kampagnen.md
├── Regionen/
├── Städte und Siedlungen/
├── Fraktionen/
├── Religionen/
├── Personen/
├── Kreaturen/
├── Rohstoffe und Artefakte/
├── Mythen und Überlieferungen/
└── Bilder/
```

## Strukturprinzip

Die Universumsstruktur besteht aus zwei Ebenen:

1. Kern-Dateien für Überblick und Orientierung
2. Dossiers für einzelne Entitäten mit höherem Detailgrad

Die Kern-Dateien beantworten die großen Fragen der Welt: Was ist diese Welt, wie funktioniert sie, welche historischen Brüche gibt es, welche Mächte prägen sie, welche Grundkonflikte laufen durch sie hindurch?

Die Dossiers sind für konkrete Einträge gedacht, die dauerhaft referenzierbar sein sollen, zum Beispiel einzelne Regionen, Siedlungen, Fraktionen, Rohstoffe oder bedeutende Personen. Die Kern-Dateien verlinken in die Dossiers, und die Dossiers verlinken zurück auf die einschlägigen Kern-Dateien.

## Abgrenzung zwischen Universum und Kampagnen

`Universe/` enthält:

- allgemeingültigen Weltkanon
- überregionale Geschichte und Epochen
- wiederkehrende Fraktionen, Mächte, Kulte und Phänomene
- Regionen, Orte, Rohstoffe und Konzepte mit Bedeutung über eine einzelne Kampagne hinaus
- markierte Legenden, Überlieferungen und Streitfragen

`Campaigns/<Name>/` enthält:

- kampagnenspezifische Ausprägungen und Perspektiven
- Session-, Missions- und Quest-Folgen
- lokale Geheimnisse und Enthüllungen
- spielerbezogene Entwicklung
- konkrete Abweichungen der Wahrnehmung auf Ortsebene

Wenn eine Kampagne auf universelle Inhalte verweist, soll das Universum die Primärquelle für den allgemeinen Sachverhalt sein. Die Kampagne beschreibt dann, wie dieser Sachverhalt lokal erlebt, missverstanden, instrumentalisiert oder entdeckt wird.

## Umgang mit Wahrheit und Unsicherheit

Das Universum enthält bewusst mehrere Wissensarten:

- `Gesicherte Wahrheit`
- `Überlieferung`
- `Legende`
- `Umstrittene Deutung`

Diese Trennung ist wichtig, damit nicht jeder spannende Mythos automatisch als faktischer Kanon gelesen wird. Der Ordner `Mythen und Überlieferungen/` sammelt besonders verdichtete Erzählungen, während `07 Wahrheiten, Legenden und Streitfragen.md` als Überblicks- und Navigationsdatei für konkurrierende Weltdeutungen dient.

## Übernahme aus Neufurt

`Campaigns/Neufurt/06 World Bible.md` dient als erste Quelle für den Aufbau des Universums. Die Übernahme erfolgt selektiv:

- Inhalte mit allgemeiner Weltbedeutung werden in `Universe/` überführt.
- Inhalte mit rein kampagnenspezifischer Funktion bleiben in `Campaigns/Neufurt/`.
- Grenzfälle werden zunächst im `10 Übernahmeplan aus Kampagnen.md` gesammelt.

Beispiele für wahrscheinliche Übernahmen:

- [[Regionen/Das Grenzland von Dornufer|Das Grenzland von Dornufer]] als Region oder Grenzraum
- [[Rohstoffe und Artefakte/Schimmerglas|Schimmerglas]] als Rohstoff oder Phänomen
- übergeordnete Aussagen zu Magie, Wirtschaft, religiöser Praxis und älteren Spuren im Land

## Daten- und Linklogik

Die bestehende Obsidian-Arbeitsweise bleibt erhalten:

- jede wichtige Entität als eigene Markdown-Datei
- YAML Frontmatter für Typ, Status und Einordnung
- konsequente Wikilinks
- sichtbare Trennung von Kanon, Gerücht und Geheimnis

Zusätzlich sollte das Universum eigene Typen oder klare Bezeichner für Welt-Dossiers nutzen, damit sie nicht mit rein kampagnenspezifischen Dateien verwechselt werden.

## Fehler- und Pflegekonzept

Das größte Risiko ist doppelte Pflege zwischen `Universe/` und `Campaigns/Neufurt/`. Um das zu vermeiden:

- allgemeine Aussagen werden möglichst nur an einer Primärstelle gepflegt
- Kampagnendateien verlinken bei allgemeinen Fakten auf Universumsdateien
- unsichere oder noch nicht sauber zuordenbare Inhalte landen vorläufig im Übernahmeplan

Ein zweites Risiko ist Tonvermischung. Deshalb bleibt das Universum absichtlich neutral formuliert. Atmosphärische Zuspitzung geschieht später in den Kampagnen.

## Erfolgskriterien

Der Umbau ist erfolgreich, wenn:

- `Universe/` als eigener, verständlicher Wissensraum existiert
- die Kern-Dateien eine lesbare Weltübersicht geben
- wichtige tiefe Themen als Dossiers auslagerbar sind
- `Neufurt` als Kampagne erhalten bleibt
- allgemeines Weltwissen aus `Neufurt` erkennbar in den Universumsbereich überführt werden kann
- Fakten, Überlieferungen und umstrittene Deutungen sichtbar voneinander getrennt sind

## Erste Umsetzungsphase

Die erste Ausbaustufe sollte noch nicht das ganze Universum fertig ausformulieren, sondern die tragende Struktur schaffen:

1. `Universe/` anlegen
2. Kern-Dateien als Grundgerüst erstellen
3. Dossier-Ordner anlegen
4. einen Übernahmeplan für `Neufurt` erstellen
5. erste offensichtliche allgemeine Inhalte aus `Neufurt` identifizieren und zuordnen

Damit entsteht erst die Architektur. Die eigentliche Weltbefüllung kann danach kontrolliert und ohne Kampagnendurcheinander weitergehen.
