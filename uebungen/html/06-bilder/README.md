# 06 · Bilder

**Ziel:** Du bindest Bilder barrierefrei und performant ein.

## Aufgabe

Baue in der `index.html` eine kleine Galerie mit 3 Bildern. Nutze Platzhalter von `https://picsum.photos/id/<zahl>/600/400` (z. B. id 10, 20, 30) und zusätzlich das lokale Logo `../../../img/da-logo.jpeg`.

- [ ] Jedes Inhaltsbild hat einen `alt`-Text, der beschreibt, **was** man sieht (nicht "Bild von...")
- [ ] Jedes Galeriebild hat eine sichtbare Bildunterschrift, die semantisch zum Bild gehört
- [ ] Jedes Bild hat Breite und Höhe als Attribute (verhindert, dass die Seite beim Laden springt)
- [ ] Die Bilder weiter unten laden erst, wenn man hinscrollt
- [ ] Ein rein **dekoratives** Bild (z. B. ein Trenner) hat den korrekten leeren alt-Text
- [ ] Das Logo ist ein Link zur Startseite (`index.html`), und der alt-Text sagt, wohin es führt
- [ ] Teste: Ändere eine Bild-URL absichtlich falsch. Was zeigt der Browser jetzt an?

<details><summary>Hinweis 1</summary>

Für "Bild + Unterschrift als Einheit" gibt es ein Element-Paar, das mit `fig` anfängt.
</details>

<details><summary>Hinweis 2</summary>

Lazy Loading ist ein einziges Attribut am `img`. Bei dekorativen Bildern lässt man `alt` **nicht** weg, sondern...
</details>

<details><summary>Hinweis 3</summary>

`<figure><img ...><figcaption>...</figcaption></figure>`, `loading="lazy"`, `alt=""`. Bei einem Bild als Link beschreibt der alt-Text das Ziel, z. B. `alt="Zur Startseite"`.
</details>
