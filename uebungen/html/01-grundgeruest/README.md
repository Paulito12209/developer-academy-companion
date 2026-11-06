# 01 · Grundgerüst

**Ziel:** Du schreibst ein gültiges HTML-Dokument aus dem Kopf, ohne Emmet (`!` + Tab ist verboten).

## Aufgabe

Die `index.html` ist leer. Schreib von Hand:

- [ ] Doctype ganz oben
- [ ] `html`-Element mit Sprache Deutsch
- [ ] `head` mit Zeichensatz UTF-8, Viewport für Handys und dem Titel `Meine erste Seite`
- [ ] `body` mit einer Hauptüberschrift `Hallo Welt` und einem Absatz über dich (1 Satz)
- [ ] Der Browser-Tab zeigt den Titel, Umlaute (ä, ö, ü) werden korrekt angezeigt
- [ ] W3C Validator: 0 Fehler

**Bonus:** Schreib das Gerüst danach ein zweites Mal in eine neue Datei, Zeit stoppen. Unter 60 Sekunden?

<details><summary>Hinweis 1</summary>

Ein HTML-Dokument hat genau zwei Kinder unter `<html>`. Eines ist für den Browser (unsichtbar), eines für den Menschen (sichtbar).
</details>

<details><summary>Hinweis 2</summary>

Die Sprache ist ein Attribut am `html`-Tag. Zeichensatz und Viewport sind beide `<meta>`-Tags, die kein schließendes Tag brauchen.
</details>

<details><summary>Hinweis 3</summary>

Viewport: `name="viewport"` und `content="width=device-width, initial-scale=1.0"`. Zeichensatz: Attribut `charset`.
</details>
