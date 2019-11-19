# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   46/60 Punkten
#### Punktabzüge für:
- [x] (8) Elemente passen sich nicht an Fensterbreite an
```diff
- Scrollleiste am unteren Fensterrand
- Das Formular verschwindet bei viel zu breitem Fenster schon nach unten. Stattdessen sollte sich die Breite des Kastens an die Fensterbreite anpassen
- Die Breite des Textbereichs passt sich auch nicht an und er wird deshalb bei mobile abgeschnitten
```
- [_] (10) Tags nicht geschlossen oder falsch verschachtelt
- [_] (5) Block-Tag in Inline-Tag
- [_] (5) Kinder-Tags im Code nicht eingerückt
- [_] (10) Zweckfremde Tags verwendet
- [_] (10) Fehlende essetielle Tags (z.B. Meta-Tags)
- [_] (5) Falsche Datei-Pfade
- [x] (6) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
```diff
- die Selektoren `img` und `span` sind diesem Fall zu weitreichend, weil sie diese Styles allen Bildern und spans geben würden, die auf im Dokument in Zukunft hinzugefügt werden.
```
- [_] (5) Fehlende essentielle Tag-Attribute
