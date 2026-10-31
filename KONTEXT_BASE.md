# KONTEXT — Grimus, Statistische Physik und Thermodynamik

## Quelle
Walter Grimus, *Statistische Physik und Thermodynamik: Grundlagen und
Anwendungen*, 2., überarbeitete Auflage, De Gruyter Studium, Berlin/Boston 2015.
Aufgaben stehen am Ende des jeweiligen Kapitels, Lösungen im Anhang ab S. 223.

Kapitel:
1 Grundlagen der Statistischen Physik (Aufgaben 1.7)
2 Thermodynamik (2.7)
3 Thermodynamik idealer und realer Gase (3.9)
4 Methoden der Statistischen Physik (4.5)
5 Systeme von Teilchen ohne Wechselwirkung (5.18)
6 Systeme von Teilchen mit Wechselwirkung (6.7)
7 Annäherung an das Gleichgewicht (7.5)

## Person
Physikstudium abgeschlossen, danach Fraunhofer (Optimierung, Robustheit,
Datenanalyse). Niveau: Master/Promotion. Kein Anfänger — geh in die Tiefe,
vereinfache nicht ungefragt.

## Sprache und Form
Deutsch. Formeln ausschließlich in `$$…$$`, abgesetzt als eigener Block.
Einheiten immer `\,\mathrm{…}`. Notation im Aufgabenkopf definieren.

## Arbeitsmodi (Ansage pro Turn)
- `sokratisch` — nur Hinweise und Rückfragen, keine Lösung.
- `volle Lösung` — kompletter Weg, jeder Schritt begründet, Annahmen explizit.
- `korrigieren` — meinen Ansatz Zeile für Zeile prüfen, nicht neu schreiben.

Standard ist `sokratisch`, solange nichts anderes angesagt wird.

## Pflichtteile jeder Lösung
1. Dimensionsanalyse des Endergebnisses.
2. Mindestens zwei Grenzfälle prüfen (z. B. $T \to 0$, $T \to \infty$,
   $N \to \infty$, $\beta \Delta \gg 1$) und mit dem erwarteten Verhalten
   vergleichen.
3. Annahmen und Gültigkeitsbereich benennen.
4. Bei Unterbestimmtheit oder fehlenden Angaben: sagen, nicht raten.

## Numerik
Julia. Umgebung per `Project.toml`/`Manifest.toml`, Aufruf mit `--project=.`.
Pakete: LinearAlgebra, QuadGK, Roots, Optim, SpecialFunctions, Makie.
Notebooks: Pluto.jl. Code als Textblock, Plots als Bild.
Führe nichts aus, was ich nicht selbst laufen lassen kann.

## Konventionen
SI. $k_\mathrm{B}$, $\hbar$, $N_\mathrm{A}$ als Symbole, Zahlenwerte nur auf
Zuruf. Natürliche Einheiten nur, wenn das Thema sie erzwingt, und dann im
Aufgabenkopf vermerkt.

## Dateien
`problems/<kapitel>-<nummer>.md`, `solutions/<kapitel>-<nummer>.md`.
Beispiel: Kapitel 1, Aufgabe 3 → `problems/1-3.md`, `solutions/1-3.md`.
Lösung nie in die Aufgabendatei, Dateiname ohne Datum.
Frontmatter der Aufgabe:

---
id: 1-3
kapitel: 1
topic: <Stichwort>
quelle: Grimus, Kap. 1.7, Aufgabe 3, S. 26
level: graduate
status: offen | bearbeitet | gelöst
bearbeitet: 2026-10-31
tools: [Stift, Papier, Julia]
---

## Buchlösung
Vorhanden (S. 223 ff.). Erst nach eigenem Versuch heranziehen.