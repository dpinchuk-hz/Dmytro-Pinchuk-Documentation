project_1

1. Übersicht

Hier wird beschrieben, auf welcher Seite ich welche Funktionen verwendet und wie ich sie umgesetzt habe. Es wird gezeigt, wie diese Codeabschnitte aussehen.

2. Navigationsmenü

Der Aufbau geht in drei nahezu identische Ebenen über. Zudem gibt es einen Mechanismus zur Garnzuführung in den Fertigungsbereich; eine Anzeige signalisiert die aktuelle Seite des Nutzers mittels CSS-Klassen. Die Navigation wurde mithilfe einer ungeordneten Liste (`<ul>` und `<li>`) umgesetzt.

![[Pasted image 20260824163358.png]]

3. Home-Seite

	1. Banner mit einer Schaltfläche, die zum Menü weiterleitet

Für die Startseite wurde ein schlichtes Banner erstellt: Es enthält die Design-Schriftart „BBH_Barte“ (eingebunden via CSS), ein zum Thema der Website passendes Foto sowie einen Button, der den Nutzer zur Menüseite (`food.html`) führt. Dank dieses Banners können Besucher das Thema der Website sofort erfassen. Darunter befinden sich zwei Fotos, die Informationen über das Unternehmen vermitteln sollen.

![[Pasted image 20260824163608.png]]

4. Menu-Seite

	1. Liste der Teiche

Das Menü ist ein zentrales Element der Website; es muss den Nutzern die verfügbaren Gerichte sowie deren Optik, Preise und Beschreibungen präsentieren. Für das Menü habe ich die Klasse „container“ verwendet, um die Gerichte in Viererreihen anzuordnen. Zur Darstellung der einzelnen Gerichte kam die Klasse „card“ zum Einsatz; innerhalb dieser Klasse habe ich alle Details zum Gericht sowie einen Button integriert, der künftig die Automatisierung des Bestellvorgangs ermöglichen soll. Um visuell zu signalisieren, dass weitere Gerichte verfügbar sind, habe ich am Ende ein Ladesymbol hinzugefügt.
4. 
	 2. Warenkorb

Der Warenkorb ist ein Bereich, der noch überarbeitet werden muss; die visuelle Gestaltung ist bereits fertig. Ich habe oben rechts eine Schaltfläche erstellt, deren Funktion darin besteht, das Seitenmenü aufzurufen. Für diese Schaltfläche habe ich keinen gewöhnlichen Text verwendet, sondern ein SVG-Symbol. Solche kleinen Details erleichtern dem Nutzer die Nutzung des Dienstes und sorgen für eine positive Benutzererfahrung.

Das Seitenpanel lässt sich auf der linken Seite ausklappen, ist über eine ID mit der Schaltfläche verknüpft, und die Ausklappfunktion selbst wurde mithilfe eines Bootstrap-JavaScript-Skripts erstellt.

![[Pasted image 20260824163548.png]]

SVG (Scalable Vector Graphics) ermöglicht es, ein Symbol direkt auf der Website zu erstellen, dessen Qualität sich um ein Vielfaches verbessert, unabhängig davon, wie stark das Bild vergrössert oder verkleinert wird.

![[Pasted image 20260824163538.png]]

5. Feedback-Seite

	1. Bewertungsformular

Das Feedback wurde mithilfe mehrerer Label- und Input-Elemente verfasst; das System überprüft sofort selbst, ob die E-Mail-Adresse korrekt eingegeben wurde. Der vom Benutzer eingegebene Text verfügt über eine eigene ID und ist damit bereit, an JavaScript übergeben zu werden, um in der Datenbank gespeichert zu werden. Mithilfe von Klassen habe ich das Feedback-Fenster so gestaltet, dass es zentriert ist und einen eigenen „Rahmen“ sowie ansprechende Abstände zwischen den Code-Elementen aufweist.

![[Pasted image 20260824163530.png]]