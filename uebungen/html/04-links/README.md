# 04 · Links

**Ziel:** Du kennst alle Link-Arten, die du im Alltag brauchst.

## Aufgabe

Die `index.html` hat drei Abschnitte und daneben die Datei `impressum.html`. Baue:

- [ ] Eine Navigation oben, die per Klick zu den drei Abschnitten **auf derselben Seite** springt
- [ ] Einen "Nach oben"-Link am Ende jedes Abschnitts
- [ ] Einen **relativen** Link zur `impressum.html` und von dort einen zurück zur `index.html`
- [ ] Einen **absoluten** Link zu MDN (`https://developer.mozilla.org`), der in einem neuen Tab öffnet, und zwar sicher
- [ ] Einen Link, der das E-Mail-Programm öffnet
- [ ] Einen Link, der auf dem Handy eine Telefonnummer wählt
- [ ] Jeder Linktext sagt, wohin er führt (kein "hier klicken")

**Bonus:** Lege einen Ordner `seiten/` an, verschiebe `impressum.html` hinein und repariere beide Links. Was muss sich am Pfad ändern?

<details><summary>Hinweis 1</summary>

Sprungziele brauchen eine eindeutige Kennung am Ziel-Element. Der Link zeigt mit einem bestimmten Zeichen davor darauf.
</details>

<details><summary>Hinweis 2</summary>

Neuer Tab: ein Attribut mit `target`. "Sicher" heißt: ein zweites Attribut, das verhindert, dass die neue Seite auf deine zugreift. E-Mail und Telefon funktionieren über ein Präfix im `href`.
</details>

<details><summary>Hinweis 3</summary>

`id="projekte"` + `href="#projekte"`. `target="_blank" rel="noopener noreferrer"`. `href="mailto:..."` und `href="tel:+49..."`. Aus einem Unterordner zurück: `../`.
</details>
