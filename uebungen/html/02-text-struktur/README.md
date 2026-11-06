# 02 · Text-Struktur

**Ziel:** Du gibst Text eine sinnvolle Hierarchie, so wie ein Screenreader oder Google sie lesen würde.

## Aufgabe

In der `index.html` steht ein Blogartikel als ein einziger Textblock. Strukturiere ihn:

- [ ] Genau **eine** `h1` (der Artikeltitel)
- [ ] Die drei Abschnitte bekommen `h2`, der Unterpunkt "Mein Setup" eine `h3`
- [ ] Keine Überschriften-Ebene wird übersprungen (nicht von h2 auf h4)
- [ ] Jeder Gedanke ist ein eigener Absatz, kein `<br><br>` als Absatz-Ersatz
- [ ] Das Wort **wichtig** ist inhaltlich wichtig markiert, das Wort *wirklich* ist betont
- [ ] Der Code-Begriff `console.log()` ist als Code markiert
- [ ] Ein Zitat am Ende ist als Zitat markiert

**Frage zum Nachdenken (beantworte sie in deiner Abgabe):** Warum nimmt man nicht einfach `h4`, wenn man eine kleinere Schrift will?

<details><summary>Hinweis 1</summary>

Es gibt zwei Paare, die gleich aussehen, aber Unterschiedliches bedeuten: `b`/`strong` und `i`/`em`. Du willst die Bedeutung, nicht nur das Aussehen.
</details>

<details><summary>Hinweis 2</summary>

Für Code gibt es ein eigenes Inline-Element mit 4 Buchstaben. Für längere Zitate gibt es ein Block-Element, das mit `block` beginnt.
</details>

<details><summary>Hinweis 3</summary>

`<strong>`, `<em>`, `<code>`, `<blockquote>`. Größe regelt später CSS, Überschriften regeln nur die Gliederung.
</details>
