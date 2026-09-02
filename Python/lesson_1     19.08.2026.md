| Datum            | 19.08.2026                                                                     |
| ---------------- | ------------------------------------------------------------------------------ |
| Thema            | Introducing Python Lesson №1                                                   |
|                  |  Chapter 1. Introduction ; Chapter 2. Types and Variables ; Chapter 3. Numbers |
| Verwandte Seiten | [[lesson_2    24.08.2026]]                                                     |
## Inhalt

- Übersicht
- Gelerntes
	- Bit, Bytes And Multibytes
	- Python Types
- Reflexion
## Übersicht

Wir haben das Thema „Numbers, Types And Variables“ (Kapitel 1, 2, 3) behandelt. Wir haben uns mit Python vertraut gemacht und gelernt, worin sich diese Sprache von anderen unterscheidet; wir haben uns mit Datentypen befasst und erfahren, was das Besondere an Integer, Floats und Booleans ist und welche Operatoren man verwenden kann; wir haben uns mit den verschiedenen Zahlensystemen beschäftigt und gelernt, wie sie funktionieren; außerdem haben wir gelernt, wie ein Computer funktioniert und was ein Bit, ein Byte und ein Multibyte sind.

## Gelerntes

### Bit, Bytes And Multibytes

Wir haben uns die kleinste Einheit eines Computers angesehen, nämlich das Bit, das nur die Werte 0 und 1 annehmen kann. Ein Byte besteht aus 8 Bits, und aus Bytes setzt sich ein Multibyte zusammen.

Es gibt drei Zahlensysteme, die Python verarbeiten kann: das binäre, das hexadezimale und das oktale. Nachfolgend finden Sie ein Beispiel dafür.

	Binärzahl:        0b1000001  →  entspricht 5 (dezimal)
	Oktalzahl:        0o45    →  entspricht 37 (dezimal)
	Hexadezimalzahl:  0xFF    →  entspricht 255 (dezimal)

Jeder Ziffer ist ein eigenes Zeichen zugeordnet, und die Werte werden nach dem UTF-8-Standard zugewiesen. Zum Beispiel:

	chr(0b1000001)         ->        A
	chr(0o45)              ->        %
	chr(0xFF)              ->        ÿ

###  Python Types

Es gibt viele Datentypen, hier ist eine Liste:

| Name           | Type        | Examples                                                |
| -------------- | ----------- | ------------------------------------------------------- |
| Boolean        | `bool`      | `True`, `False`                                         |
| Integer        | `int`       | `47`, `25000`, `25_000`                                 |
| Floating point | `float`     | `3.14`, `2.7e5`                                         |
| Complex        | `complex`   | `3j`, `5 + 9j`                                          |
| Text string    | `str`       | `'alas'`, `"alack"`, `'''a verse attack'''`             |
| List           | `list`      | `['Winken', 'Blinken', 'Nod']`                          |
| Tuple          | `tuple`     | `(2, 4, 8)`                                             |
| Bytes          | `bytes`     | `b'ab\xff'`                                             |
| Bytearray      | `bytearray` | `bytearray(...)`                                        |
| Set            | `set`       | `set([3, 5, 7])`                                        |
| Frozen set     | `frozenset` | `frozenset(['Elsa', 'Otto'])`                           |
| Dictionary     | `dict`      | `{'game': 'bingo', 'dog': 'dingo', 'drummer': 'Ringo'}` |

Wir haben uns jedoch drei davon genauer angesehen: Booleans, Integers und Floats. Sie sind alle miteinander verbunden, da sie als Zahlen interpretiert werden können.  

- Booleans -  können nur zwei Werte annehmen: 0 oder 1, also „False“ oder „True“

- Integers – das sind reine Zahlen, positiv oder negativ. Sie können zur besseren Lesbarkeit durch Unterstriche getrennt werden (z. B. 100_000)

- Floats – das sind Zahlen mit einem Dezimalteil (z. B. 3,14)

## Reflexion

In der ersten Stunde habe ich mich mit den Besonderheiten von Python und den Zahlensystemen, insbesondere dem Hexadezimal- und dem Oktalsystem, vertraut gemacht – diese waren für mich neu. Alles andere war mir bereits bekannt; es war sozusagen eine Wiederholung bereits erlernter Kenntnisse. Insgesamt ist alles gut gelaufen
