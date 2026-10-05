# Morphological Box

**A free, simple tool for the morphological box (Zwicky box) – right in your browser.**
No installation, no account, no data upload.

👉 **Open the tool: https://Master-D1990.github.io/morphological-box/**

[English](#english) · [Deutsch](#deutsch)

![Screenshot](docs/screenshot-en.png)

---

## English

### What is a morphological box?

A morphological box is a method for finding solutions to a technical problem in a systematic way:

1. Break the problem into **sub-functions** (e.g. *store energy*, *generate motion*, *control*).
2. For each sub-function, collect several possible **solutions** (e.g. battery, power supply, supercapacitor).
3. Combine one solution per sub-function into a **solution variant**. This gives you many possible overall concepts at a glance.

Many people do this in Excel, but sketches, ratings and comparisons quickly get messy there. This tool is made for exactly that.

### What can the tool do?

- **Grid of sub-functions and solutions:** add, rename and rearrange them by drag & drop.
- **Images and sketches:** drag a picture onto a box, or select a box and paste with `Ctrl+V` (e.g. a screenshot or a photo of a hand sketch). Images are scaled down automatically.
- **Traffic-light rating with reasons:** rate every solution green / yellow / red, with a written reason, for as many criteria as you like (e.g. feasibility, cost, weight).
- **Solution variants as coloured lines:** pick one solution per row, and the variant is drawn as a see-through coloured line across the box. Several variants can be compared side by side.
- **Variant overview:** a table below the box compares all variants, with scores per criterion, notes and sketches of each overall concept.
- **Print / PDF**, **dark mode**, **English and Swiss German**.

### How to use it

1. **Open the tool** using the link above. It runs in any modern browser (Chrome, Firefox, Edge, Safari).
2. The first time you open it, you see an **example**. Have a look around, then click **New** to start your own box.
3. **Click a box** to edit its title, description, image and rating in the sidebar on the right.
4. **Create a variant** with **+ Variant**, then click one solution per row. Click **Done** when you are finished.
5. **Save** your work as a file with **Save**. You can open it again later with **Open…**, or send it to someone else.

The sidebar on the right also contains a short **How to use** section with all keyboard shortcuts.

### Where is my data stored?

**Only on your own computer.** The tool does not upload anything to a server.

- While you work, your current state is cached automatically in your browser.
- That browser cache is **not a backup**. It is lost if you clear your browser data or switch to another browser or computer. Click **Save** regularly. This creates a `.kasten.json` file that contains everything, including all images.

### Working together

Save the file to a shared folder (e.g. OneDrive, Google Drive, Dropbox, Syncthing). Others open it with **Open…**, make their changes and save again.

Only one person should edit the file at a time. Otherwise the last person to save overwrites the others' changes.

### Use it offline

You can also download [`index.html`](index.html) and double-click it. The tool then works completely without internet.

### Questions, bugs, ideas

Please open an [issue](https://github.com/Master-D1990/morphological-box/issues).

---

## Deutsch

### Was ist ein morphologischer Kasten?

Der morphologische Kasten ist eine Methode, um für ein technisches Problem systematisch Lösungen zu finden:

1. Das Problem wird in **Teilfunktionen** zerlegt (z. B. *Energie speichern*, *Bewegung erzeugen*, *Steuern*).
2. Für jede Teilfunktion werden mehrere mögliche **Lösungen** gesammelt (z. B. Akku, Netzteil, Superkondensator).
3. Pro Teilfunktion wird eine Lösung gewählt und zu einer **Lösungsvariante** kombiniert. So entstehen auf einen Blick viele mögliche Gesamtkonzepte.

Viele machen das in Excel, aber mit Skizzen, Bewertungen und Vergleichen wird es dort schnell unübersichtlich. Genau dafür ist dieses Tool gedacht.

### Was kann das Tool?

- **Raster aus Teilfunktionen und Lösungen:** hinzufügen, umbenennen und per Drag & Drop umsortieren.
- **Bilder und Skizzen:** Bild auf ein Feld ziehen oder ein Feld anklicken und mit `Strg+V` einfügen (z. B. einen Screenshot oder ein Handyfoto einer Handskizze). Bilder werden automatisch verkleinert.
- **Ampelbewertung mit Begründung:** jede Lösung grün / gelb / rot bewerten, mit schriftlicher Begründung, für beliebig viele Kriterien (z. B. Machbarkeit, Kosten, Gewicht).
- **Lösungsvarianten als farbige Linien:** pro Zeile eine Lösung anklicken, und die Variante wird als durchsichtige farbige Linie über den Kasten gezeichnet. Mehrere Varianten lassen sich direkt vergleichen.
- **Variantenübersicht:** Eine Tabelle unter dem Kasten vergleicht alle Varianten, mit Bewertung pro Kriterium, Notizen und Skizzen des jeweiligen Gesamtkonzepts.
- **Drucken / PDF**, **Darkmode**, **Deutsch (Schweiz) und Englisch**.

### So geht's

1. **Tool öffnen** über den Link oben. Es läuft in jedem aktuellen Browser (Chrome, Firefox, Edge, Safari).
2. Beim ersten Öffnen siehst du ein **Beispiel**. Schau dich um und klicke dann auf **Neu**, um deinen eigenen Kasten anzulegen.
3. **Ein Feld anklicken**, um Titel, Beschreibung, Bild und Bewertung in der Seitenleiste rechts zu bearbeiten.
4. **Variante anlegen** mit **+ Variante**, dann pro Zeile eine Lösung anklicken. Mit **Fertig** abschliessen.
5. Mit **Speichern** sicherst du deine Arbeit als Datei. Später öffnest du sie wieder mit **Öffnen…** oder schickst sie jemandem.

In der Seitenleiste rechts steht unter **Bedienung** eine Kurzanleitung mit allen Tastenkürzeln.

### Wo werden meine Daten gespeichert?

**Nur auf deinem eigenen Computer.** Das Tool lädt nichts auf einen Server.

- Während du arbeitest, wird der aktuelle Stand automatisch im Browser zwischengespeichert.
- Dieser Zwischenspeicher ist **keine Sicherung**. Er geht verloren, wenn du die Browserdaten löschst oder den Browser oder Computer wechselst. Klicke deshalb regelmässig auf **Speichern**. So entsteht eine `.kasten.json`-Datei, die alles enthält, auch alle Bilder.

### Gemeinsam arbeiten

Speichere die Datei in einem geteilten Ordner (z. B. OneDrive, Google Drive, Dropbox, Syncthing). Andere öffnen sie mit **Öffnen…**, machen ihre Änderungen und speichern wieder.

Es sollte immer nur eine Person gleichzeitig daran arbeiten. Sonst überschreibt, wer zuletzt speichert, die Änderungen der anderen.

### Offline nutzen

Du kannst [`index.html`](index.html) auch herunterladen und per Doppelklick öffnen. Dann funktioniert das Tool komplett ohne Internet.

### Fragen, Fehler, Ideen

Bitte ein [Issue](https://github.com/Master-D1990/morphological-box/issues) eröffnen.

---

## License

[MIT](LICENSE): free to use, change and share, also commercially.
