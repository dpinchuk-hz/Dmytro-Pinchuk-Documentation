| Datum            | 26.08.2026                   |
| ---------------- | ---------------------------- |
| Thema            | Introducing Python Lesson №3 |
|                  | Chapter 6. If and Match      |
| Verwandte Seiten | [[lesson_4    31.08.2026]]   |
## Inhalt

- Übersicht
- Gelerntes
	- Kommentare
		- Einzeilige Kommentare (`#`) 
		- Mehrzeilige Zeichenfolgen (`"""`)
	- Vergleichsoperatoren if, elif, and, else
		- If-Operator
		- Elif-Operator
		- Else-Operator
	- Walrus
- Reflexion
## Übersicht

  Wir haben uns angesehen, wie man Kommentare richtig schreibt (mit #) und wie man sie alternativ schreiben kann, was jedoch etwas mehr Ressourcen beansprucht (mit “““, z. B. : “““Kommentar“““); wie man Code von einer Zeile in die nächste fortsetzt; die Vergleichsoperatoren if, elif und else – wie sie funktionieren und wie man sie einsetzt; die Anweisungsoperatoren und wie man sie durch Vergleichsoperatoren ersetzen kann; Walrus; Match.

## Gelerntes

### Kommentare

1. Einzeilige Kommentare (`#`) 

Das ist die beste Methode, Kommentare zu schreiben, da der Code sie sofort ignoriert und dafür keine Ressourcen verbraucht. Allerdings erfordert diese Methode, dass Sie in jeder Zeile, in der ein Kommentar vorkommt, vor diesem ein `#`-Zeichen setzen.

2. Mehrzeilige Zeichenfolgen (`"""`)

Diese Methode ist praktischer, da Sie sofort eine große Textmenge über mehrere Zeilen hinweg schreiben können und lediglich die Anführungszeichen `"""` öffnen und schliessen müssen. Der Code ignoriert diesen Text jedoch nicht – er erstellt ein Objekt mit diesem Text, prüft, ob er irgendwo verwendet wird, und gibt ihn unmittelbar nach der Überprüfung aus. Daher sollte diese Methode vermieden werden, da sie etwas Ressourcen beanspruchen kann.

### Vergleichsoperatoren if, elif, and, else

Dies sind Operatoren, mit denen geprüft werden kann, ob eine Bedingung wahr ist oder nicht; ist sie nicht wahr, wird die Ausführung an den nächsten Operator weitergeleitet.

1. If-Operator

Dieser Operator muss zwingend angegeben werden, um andere Vergleichsoperatoren verwenden zu können.

  
2. Elif-Operator

Mit diesem Operator kann eine weitere Bedingung und eine Aktion hinzugefügt werden. Er kann zwar weggelassen werden, doch die Verwendung von „elif“ macht den Code einfacher und lesbarer.

Anwendungsbeispiel:

  ![[codeimage-snippet_31 (1) 1.png]]

Beispiel für eine Alternative:
![[codeimage-snippet_31.png]]
  
3. Else-Operator

Auch dies ist, wie „elif“, eine Erweiterung des „if“-Befehls. Seine Aufgabe besteht darin, eine Aktion anzugeben, falls weder „if“ noch „elif“ die Bedingung erfüllen.


### Walrus

Dies ist ein Operator, der in anderen Operatoren verwendet werden kann. Seine Funktion besteht darin, einer Variablen in einem Operator bestimmte Daten zuzuweisen.

Anwendungsbeispiel:

![[codeimage-snippet_31 (3).png]]

Beispiel für eine alternative Variante:

![[codeimage-snippet_31 (2).png]]
## Reflexion

Alles war super, ich habe mir kurz wieder ins Gedächtnis gerufen, wie man Kommentare schreibt (mit """), und herausgefunden, was „Match“ und „Walrus“ sind.