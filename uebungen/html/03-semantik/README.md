# 03 · Semantik

**Ziel:** Du ersetzt "div-Suppe" durch semantische Elemente. Das ist eine der häufigsten Fragen im Junior-Interview.

## Aufgabe

Die `index.html` besteht nur aus `div`s mit Klassen. Ersetze sie:

- [ ] Kopfbereich, Navigation, Hauptinhalt, Seitenleiste und Fußbereich haben jeweils das passende semantische Element
- [ ] Die zwei Blogposts sind jeweils eigenständige Inhalte (könnte man einzeln teilen)
- [ ] Innerhalb eines Posts gibt es einen kleinen Kopfbereich mit Titel und Datum
- [ ] Das Datum ist maschinenlesbar (Tipp: es gibt ein Element dafür)
- [ ] Es gibt nur **ein** `main` auf der Seite
- [ ] Am Ende bleibt **kein einziges** `div` übrig
- [ ] Die Klassen-Namen kannst du löschen, sie werden nicht mehr gebraucht

**Frage:** Wann ist `section` richtig und wann `article`? Ein Satz reicht.

<details><summary>Hinweis 1</summary>

Lies die Klassen-Namen laut vor. Fast jeder entspricht 1:1 einem HTML5-Element.
</details>

<details><summary>Hinweis 2</summary>

`header` darf mehrmals vorkommen: einmal für die Seite, und einmal in jedem Post. `main` nur einmal.
</details>

<details><summary>Hinweis 3</summary>

Elemente: `header`, `nav`, `main`, `article`, `aside`, `footer`, `time datetime="2026-11-06"`. Test für `article`: Würde der Inhalt allein in einem RSS-Feed Sinn ergeben?
</details>
