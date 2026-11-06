# 05 · Listen

**Ziel:** Du wählst für jede Aufzählung den richtigen Listentyp und kannst Listen verschachteln.

## Aufgabe

Baue in der `index.html` ein Rezept für Pancakes:

- [ ] **Zutaten** als Liste, bei der die Reihenfolge egal ist
- [ ] **Zubereitung** als Liste, bei der die Reihenfolge zählt (5 Schritte)
- [ ] Schritt 2 hat eine **verschachtelte** Unterliste (z. B. "trockene Zutaten mischen" mit 3 Unterpunkten)
- [ ] Ein **Glossar** am Ende mit 3 Begriffen und Erklärungen (z. B. "Unterheben", "Prise", "Teig ruhen lassen") mit der Liste für Begriff-Beschreibung-Paare
- [ ] Die Zubereitung beginnt bei Schritt **0** statt 1, ohne dass du Zahlen von Hand schreibst (ja, das ist komisch, aber du lernst ein Attribut)
- [ ] Kein `<br>` und kein "-" oder "1." von Hand im Text

**Merke für später:** Fast jede Navigation im echten Leben ist eine `ul` mit Links drin. Warum, siehst du in CSS.

<details><summary>Hinweis 1</summary>

**u**nordered vs. **o**rdered. Für das Glossar gibt es eine dritte Listenart, die mit **d** anfängt.
</details>

<details><summary>Hinweis 2</summary>

Eine verschachtelte Liste steht **innerhalb** eines `li`, nicht zwischen zwei `li`s. Das `ol`-Element hat ein Attribut für die Startzahl.
</details>

<details><summary>Hinweis 3</summary>

`<li>Schritt <ul><li>...</li></ul></li>`. `<ol start="0">`. Glossar: `<dl>`, darin abwechselnd `<dt>` (Begriff) und `<dd>` (Beschreibung).
</details>
