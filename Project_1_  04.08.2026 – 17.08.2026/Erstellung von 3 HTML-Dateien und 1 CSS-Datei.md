project_1

1. Übersicht

Dieses Dokument erklärt, was HTML und CSS sind, beschreibt die Struktur meiner Website und erläutert, wie die Seiten miteinander verknüpft sind.

2. HTML

HyperText Markup Language  -  Es ist das Fundament, auf dem jede Website aufbaut; es ist die Programmiersprache, die es dem Ersteller ermöglicht, das Grundgerüst der Website zu erschaffen – Elemente wie Schaltflächen, Text, Bilder und Navigation werden mithilfe von HTML erstellt. Typischerweise wird HTML in Kombination mit CSS für das Design der Website sowie mit JavaScript für Animationen und Funktionalitäten eingesetzt.

HTML arbeitet mit sogenannten Tags – Befehlen, die etwa so aussehen: "<…>", wobei ein spezifischer Befehl innerhalb der Klammern steht. Die Struktur der Website sieht folgendermassen aus:

![[Pasted image 20260824162850.png|143]]

![[Pasted image 20260824162935.png]]

3. CSS

Cascading Style Sheets - Dies ist eine Programmiersprache zur Gestaltung von Webseiten. Sie dient zum Schreiben von Selektoren, Eigenschaften und Direktiven, die auf HTML oder XML angewendet werden. Hier ist ein Beispiel für diese Programmiersprache.

![[Pasted image 20260824163011.png|197]]

![[Pasted image 20260824163101.png|339]]

4. Struktur

Die Struktur der Website sieht folgendermaііen aus:

- Code
	- home.html
	- food.html
	- form.html
	- web_css.css
	- photos

Ich habe drei HTML-Dateien, eine CSS-Datei und einen Ordner  "photos" mit den Bildern der Website.

Jede Seite ist mit einer CSS-Datei verknüpft, wodurch dank dieses Befehls ein einheitlicher visueller Stil gewährleistet wird:

<link rel="stylesheet" href="web_css.css">

Jede Seite ist über die Navigationsleiste verbunden, sodass diese Zeilen auf allen Seiten identisch sind.



