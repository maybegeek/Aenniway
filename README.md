# Aenniway
Aenniway, liebevoll fontifizierte Handschrift!

[Dokumentation und Spielwiese](https://maybegeek.github.io/Aenniway) mit Live-Ansicht der Schrift und Möglichkeit eigener Eingabe von Text zur Ansicht in den Schriftschnitten und bei Möglichkeit die OpenType-Funktionen zu variieren.

* fontifizierte Handschrift
* in vier Schriftschnitten (regular, bold, bold-italic, italic)
* `OTF`, `TTF`, Webfont (`*.eot`, `*.woff2`, `*.woff`, `*.ttf`, `*.svg`) + `CSS`
* ordentlicher Glyphenvorrat (151)
* mit Kontextalternativen
* mit Ligaturen
* mit Fraktalen
* mit angepasstem Kerning
* mit Einhorn!

## OTF & TTF

Alle Dateien können entweder über `git` (`git clone ...`), als gesammeltes Paket vermittels des Download-Buttons (Clone or download) oder bei [Release](https://github.com/maybegeek/Aenniway/releases) heruntergeladen werden.

Für die Einbindung auf dem eigenen Rechner sind dann die beinhalteten Ordner `OTF` oder `TTF` interessant. Die darin enthaltenen Schriftschnittdateien nach Art des jeweiligen Betriebssystems installieren (oftmals reicht der Doppelklick, um Hinweise zur Installation zu erhalten).

## `HTML` und `CSS`

Version 1.7.1:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/maybegeek/Aenniway/3aedf6bb/css/aenniway.css">
```

Version 1.5.01:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/maybegeek/Aenniway/c6c242f1/css/aenniway.css">
```

oder direkt auf den aktuellen Stand verlinkend:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/maybegeek/Aenniway/master/css/aenniway.css">
```
in der `CSS`-Datei bezogen auf einen Selektor (hier `<html>` verwendend)

```css
html {
  font-family: "Aenniway-Web", cursive;
}
```

## Akzidenz

* Ansicht der Glyphen, Informationen usw.: [https://maybegeek.github.io/Aenniway](https://maybegeek.github.io/Aenniway)
* [Anmutungsähnlichkeit und Besonderheiten bei Handschriften-S](https://maybegeek.github.io/Aenniway/akzidenz/s-anmutung.htm)
* [Liste der s, S, ẞ und ß bei handwriting fonts](https://maybegeek.github.io/Aenniway/akzidenz/s-galerie.htm)
* [S-Animation bei Aenniway](https://maybegeek.github.io/Aenniway/akzidenz/s-shape.htm)

## Autoren

Anna-Lisa Wehmann & Christoph Pfeiffer

## License

SIL Open Font License, Version 1.1
