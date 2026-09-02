#  Integration von Bootstrap
project_1

1. Übersicht

Diese Dokumentation beschreibt das verwendete Framework sowie die eingesetzten spezifischen Komponenten und deren Integration.

2. Bootstrap                          

Dies ist ein kostenloses Frontend-Framework für die Website-Erstellung, das eine breite Palette an Stilen und JavaScript-Komponenten umfasst. Seine Vielseitigkeit und Funktionalität tragen dazu bei, die Entwicklungszeit zu verkürzen. Die Hauptgründe für den Einsatz dieses Frameworks sind die schnelle Entwicklung und die Anpassungsfähigkeit an Bildschirme jeder Grösse.

Zu den verwendeten Komponenten gehören Schaltflächen, Hilfsklassen für Abstände, Offcanvas-Elemente, Flexbox-Hilfsklassen sowie Navigationskomponenten.

3. Integration

Um Bootstrap einzubinden, habe ich den `@import`-Befehl in meiner CSS-Datei verwendet. Dies vereinfacht den Styling-Prozess erheblich: Alles befindet sich in einer einzigen Datei, und da die Bootstrap-Styles ganz oben stehen, haben meine eigenen Klassen Vorrang.

@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css");

Um die Seitenleiste des Frameworks nutzen zu können, musste ich ein Skript in die Datei `food.html` einbinden.

 <script defer src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>

Diese Dokumentation beschreibt das verwendete Framework sowie die eingesetzten spezifischen Komponenten und deren Integration.
