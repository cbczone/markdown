# markdown

HEADER:

Mit # vor der zeile erschaffen wir eine überschrift, die anzahl der # bestimmt, wie groß diese überschrift sein wird, den umso mehr # wir in den anfang der zeile schreiben, umso kleiner wird der text. (1-6)

# 1. Titel

## 2. Titel

### 3. Titel

#### 4. Titel

##### 5. Titel

###### 6. Titel


EMPHASIS:

Wir können texte in Markdown nicht farblich stylen, was wir aber können ist anzugeben ob wir den text fett, kursiv, oder unterstrichen haben wollen.

__fett__ - 2 unterstriche vorne und hinten, machen den text FETT

alternativ:

**fett** - 2 sternchen vorne und hinten, machen den text FETT.

_kursiv_ - 1 unterstrich vorne und hinten, machen den text KURSIV

alternativ:

*kursiv* - 1 sternchen vorne und hinten, machen den text KURSIV

wir können auch beides mixen, indem wir jeweils die verschiedenen angegebenen alternativen gemeinsam nutzen

**FETT und _KURSIV_**

_KURSIV und **FETT**_

PARAGRAPH:

Eine zeile text:

Wenn wir ohne eine leerze zeile zwischen den texten schreiben, wird alles, was wir schreiben in einer zeile angezeigt. Leerzeichen werden automatisch zwischen den worten eingefügt.

Eine
Zeile
Text

Um mehrere paragraphen zu erstellen, müssen wir eine leerze zeile zwischen den sätzen einfügen:

Mehrere

Zeilen

Text

LISTEN:

Automatisch sortierte listen, erschaffen wir, indem wir an den anfang der zeile eine nummer, gefolgt von einem punkt setzen.

1. Ein Eintrag
2. Ein weiterer eintrag
3. noch ein eintrag
4. noch ein weiterer eintrag

Unsortierte listen erstellen wir, indem wir einen bindestrich an den anfang der zeile setzen, nutzen wir tab, vor diesem bindestrich, definieren wir das sich der eintrag eine ebene tiefer als der vorherige eintrag befindet.

- Ein Eintrag
- Ein weiterer Eintrag
    - Ein untereintrag
    - Ein weiterer untereintag
        - Eine ebene tiefer

LINKS:

Wir haben die möglichkeit in eine markdowndatei links einzufügen, und ihnen anzeigenamen zu geben.

[Dies ist ein link zu google](https://www.google.de)

[Dies ist auch ein link zu google](https://www.google.de "Google")

BILDER:

Ein bild können wir ähnlich angeben wie einen link, wir setzen davor nur ein ausrufezeichen, gefolgt vom altrnativtitel, wenn das bild nicht angezeigt werden kann.

![Dies ist ein Testbild](testbild.png)

CODE:

Wir können code innerhalb von einem markdown dokument anzeigen, egal in welcher sprache.

Eine zeile code: `console.log("Hallo Welt!")`

Mehrere zeilen code: 

```
console.log("Hallo Welt");
alert("Hello");
```

wenn wir die programiersprache nach den backticks eingeben, können wir den code kolorieren. zb:

```js
console.log("Hallo Welt");
alert("Hello");
```

ZITATE:

Zitate, oder eingerückte textelemente, können wir mit dem pfeil nach rechts angeben:

> Ich bin ein **ZITAT**
