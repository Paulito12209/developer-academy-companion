# 07 · Formulare

**Ziel:** Du baust ein Formular, das barrierefrei ist und ohne JavaScript schon Eingaben prüft.

## Aufgabe

Baue in der `index.html` eine Anmeldung für einen Coding-Workshop:

- [ ] Name (Pflichtfeld, mindestens 2 Zeichen)
- [ ] E-Mail (Pflichtfeld, der Browser prüft das Format)
- [ ] Alter (nur Zahlen von 16 bis 99)
- [ ] Erfahrungslevel als Auswahl, bei der man **genau eine** von drei Optionen wählt (Anfänger, Fortgeschritten, Profi); die Gruppe hat eine Überschrift
- [ ] Interessen als Auswahl, bei der man **mehrere** wählen kann (HTML, CSS, JavaScript)
- [ ] Workshop-Termin aus einem Dropdown mit 3 Daten
- [ ] Nachrichtenfeld für mehrzeiligen Text
- [ ] Checkbox "Ich akzeptiere die Datenschutzerklärung" (Pflicht)
- [ ] Ein Absende-Button
- [ ] **Jedes** Eingabefeld hat ein `label`, das mit ihm verknüpft ist. Test: Klick auf den Label-Text setzt den Cursor ins Feld bzw. hakt die Box an
- [ ] Teste: Klick auf "Absenden" mit leeren Feldern. Der Browser muss meckern

**Frage:** Warum reicht die Prüfung im Browser nicht aus, um einer Eingabe zu vertrauen?

<details><summary>Hinweis 1</summary>

Das `type`-Attribut von `input` macht viel Arbeit für dich: Es gibt Typen für E-Mail, Zahlen, Checkboxen und Radio-Buttons. Mehrzeiliger Text und Dropdowns sind eigene Elemente.
</details>

<details><summary>Hinweis 2</summary>

Label-Verknüpfung: das `for` am Label muss zur `id` am Feld passen. Radio-Buttons gehören zusammen, wenn sie denselben `name` haben. Eine Gruppe mit Überschrift: `fieldset` + `legend`.
</details>

<details><summary>Hinweis 3</summary>

Attribute: `required`, `minlength="2"`, `type="number" min="16" max="99"`, `<select><option>`, `<textarea>`, `<button type="submit">`. Jedes Feld braucht ein `name`, sonst wird es nicht mitgeschickt.
</details>
