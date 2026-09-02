
| Datum            | 24.08.2026                                           |
| ---------------- | ---------------------------------------------------- |
| Thema            | Introducing Python Lesson №2                         |
|                  | Chapter 4. Strings;   Chapter 5. Bytes and Bytearray |
| Verwandte Seiten | [[lesson_3    26.08.2026]]]                          |

## Inhalt

- Übersicht
- Gelerntes
	- Die drei Arten Formatierung 
		- Old style: %
		- New style: {} and format()
		- Newest Style: f-strings
	- Teilzeichenfolge mit einem Slice
- Reflexion
## Übersicht

Wir haben das Thema „String“ in Kapitel 4 behandelt. Wir haben die Zeichenketten, grundlegende Funktionen wie print(), len(); Substrings mit einem Slice; String-Funktionen, Formatierung sowie Escape-Zeichen mit \ besprochen.

## Gelerntes
### Die Formatierung lässt sich in drei Arten unterteilen:

 1. Old style: %

Es handelt sich um ein veraltetes System, das seit den Anfängen von Python  genutzt wurde. Seine Struktur sieht wie folgt aus: format_string % data.

Hier sind die Umwandlungstypen, die verwendet werden mussten

| **Format code** | **Usage**                    |
| --------------- | ---------------------------- |
| %s              | String                       |
| %d              | Decimal integer              |
| %x              | Hex integer                  |
| %o              | Octal integer                |
| %f              | Decimal float                |
| %e              | Exponential float            |
| %g              | Decimal or exponential float |
| %%              | A literal %                  |

 2. New style: {} and format()

Dieses System wurde  in Python 2.6 eingeführt. Diese Version löste viele Probleme mit inkompatiblen Änderungen. Die Syntax lautet wie folgt: format_string.format(data).

Anwendungsbeispiel:

<img width="1108" height="432" alt="codeimage-snippet_25" src="https://github.com/user-attachments/assets/59a744ab-3975-4b07-bb63-0268c3e7889b" />


Output: 'The woodchuck is in the lake.'

 3. Newest Style: f-strings

Dies ist das neueste System, das   mit Python 3.6 eingeführt wurde.

Anwendungsbeispiel:

<img width="1108" height="386" alt="codeimage-snippet_25 (1)" src="https://github.com/user-attachments/assets/77ea9171-98e2-4458-ab51-6d622b200131" />


Output: 'The woodchuck is in the lake.'


### Teilzeichenfolge mit einem Slice

Nachdem wir die Formatierung besprochen hatten, haben wir uns mit einer weiteren wichtigen String-Funktion beschäftigt: dem Slicing

Dies ist eine Funktion, mit der du den gewünschten Teil einer Zeichenkette extrahieren kannst. Die Syntax sieht wie folgt aus:

x [ start : end : step ]

An die Stellen „start“, „end“ und „step“ werden Zahlen eingesetzt: „start“ gibt an, ab welchem Zeichen der Ausschnitt aus der Zeichenkette entnommen wird, „end“ gibt an, wo der Ausschnitt endet, und „step“ gibt an, in welchen Schritten die Zeichen entnommen werden.

Anwendungsbeispiel:

<img width="878" height="342" alt="codeimage-snippet_25 (2)" src="https://github.com/user-attachments/assets/bed6472c-15af-4fdb-9afd-fcc842e825e2" />

Output: 'ehknqt'

## Reflexion

Dank dieser Unterrichtsstunde habe ich mir ein paar Python-Grundlagen wieder ins Gedächtnis gerufen und mich mit für mich neuen, aber gleichzeitig veralteten Formatierungssystemen vertraut gemacht: Old Style: %, New Style: {} und format() sowie mit String-Funktionen, da ich dieses Thema früher beim Lernen von Python gemieden hatte. Alles ist verständlich, alles ist einfach. Nach der Lektion hatten wir die Möglichkeit, unsere neu erworbenen Fähigkeiten anhand von Übungen zu vertiefen, die Francesco im chatGPT erstellt hatte
