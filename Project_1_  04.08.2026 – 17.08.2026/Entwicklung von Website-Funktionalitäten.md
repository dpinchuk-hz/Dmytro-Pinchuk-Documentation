project_1

1. Übersicht

Hier wird beschrieben, auf welcher Seite ich welche Funktionen verwendet und wie ich sie umgesetzt habe. Es wird gezeigt, wie diese Codeabschnitte aussehen.

2. Navigationsmenü

Der Aufbau geht in drei nahezu identische Ebenen über. Zudem gibt es einen Mechanismus zur Garnzuführung in den Fertigungsbereich; eine Anzeige signalisiert die aktuelle Seite des Nutzers mittels CSS-Klassen. Die Navigation wurde mithilfe einer ungeordneten Liste (`<ul>` und `<li>`) umgesetzt.

<img width="1005" height="574" alt="codeimage-snippet_11 (7)" src="https://github.com/user-attachments/assets/16537733-8e46-4519-97c5-1f096a08553e" />

3. Home-Seite

	1. Banner mit einer Schaltfläche, die zum Menü weiterleitet

Für die Startseite wurde ein schlichtes Banner erstellt: Es enthält die Design-Schriftart „BBH_Barte“ (eingebunden via CSS), ein zum Thema der Website passendes Foto sowie einen Button, der den Nutzer zur Menüseite (`food.html`) führt. Dank dieses Banners können Besucher das Thema der Website sofort erfassen. Darunter befinden sich zwei Fotos, die Informationen über das Unternehmen vermitteln sollen.

<img width="1341" height="507" alt="codeimage-snippet_12 (1)" src="https://github.com/user-attachments/assets/e33039b8-314e-4bb8-ab49-47c04d41894e" />


4. Menu-Seite

	1. Liste der Teiche

Das Menü ist ein zentrales Element der Website; es muss den Nutzern die verfügbaren Gerichte sowie deren Optik, Preise und Beschreibungen präsentieren. Für das Menü habe ich die Klasse „container“ verwendet, um die Gerichte in Viererreihen anzuordnen. Zur Darstellung der einzelnen Gerichte kam die Klasse „card“ zum Einsatz; innerhalb dieser Klasse habe ich alle Details zum Gericht sowie einen Button integriert, der künftig die Automatisierung des Bestellvorgangs ermöglichen soll. Um visuell zu signalisieren, dass weitere Gerichte verfügbar sind, habe ich am Ende ein Ladesymbol hinzugefügt.
4. 
	 2. Warenkorb

Der Warenkorb ist ein Bereich, der noch überarbeitet werden muss; die visuelle Gestaltung ist bereits fertig. Ich habe oben rechts eine Schaltfläche erstellt, deren Funktion darin besteht, das Seitenmenü aufzurufen. Für diese Schaltfläche habe ich keinen gewöhnlichen Text verwendet, sondern ein SVG-Symbol. Solche kleinen Details erleichtern dem Nutzer die Nutzung des Dienstes und sorgen für eine positive Benutzererfahrung.

Das Seitenpanel lässt sich auf der linken Seite ausklappen, ist über eine ID mit der Schaltfläche verknüpft, und die Ausklappfunktion selbst wurde mithilfe eines Bootstrap-JavaScript-Skripts erstellt.

<img width="2050" height="1686" alt="codeimage-snippet_11 (1)" src="https://github.com/user-attachments/assets/15510645-9598-43ca-b0b4-f1b0287b6928" />


SVG (Scalable Vector Graphics) ermöglicht es, ein Symbol direkt auf der Website zu erstellen, dessen Qualität sich um ein Vielfaches verbessert, unabhängig davon, wie stark das Bild vergrössert oder verkleinert wird.

<img width="1120" height="395" alt="codeimage-snippet_12" src="https://github.com/user-attachments/assets/ab96bf25-de03-4f3a-810a-7c50c57ff5f8" />


5. Feedback-Seite

	1. Bewertungsformular

Das Feedback wurde mithilfe mehrerer Label- und Input-Elemente verfasst; das System überprüft sofort selbst, ob die E-Mail-Adresse korrekt eingegeben wurde. Der vom Benutzer eingegebene Text verfügt über eine eigene ID und ist damit bereit, an JavaScript übergeben zu werden, um in der Datenbank gespeichert zu werden. Mithilfe von Klassen habe ich das Feedback-Fenster so gestaltet, dass es zentriert ist und einen eigenen „Rahmen“ sowie ansprechende Abstände zwischen den Code-Elementen aufweist.

<img width="1073" height="529" alt="codeimage-snippet_12 (2)" src="https://github.com/user-attachments/assets/5ff34846-7a8d-431a-9725-129f3c463d69" />
