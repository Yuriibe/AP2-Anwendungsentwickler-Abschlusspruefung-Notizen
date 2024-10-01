### 1. Was ist das MVC-Pattern?

Das Model-View-Controller (MVC) ist ein Entwurfsmuster, das zur Strukturierung von Anwendungen in die drei Hauptkomponenten Model, View und Controller aufgeteilt wird. Diese Aufteilung fördert die Trennung von Logik und Darstellung und ermöglicht eine klarere Struktur und Wartbarkeit der Software.

- **Model**: Die Daten und Geschäftslogik der Anwendung. Hier werden die Daten verwaltet, gespeichert und verarbeitet.
- **View**: Die Präsentationsschicht, die für die Darstellung der Daten des Models an den Benutzer verantwortlich ist.
- **Controller**: Vermittler zwischen Model und View. Er verarbeitet die Benutzeranfragen, ändert das Model entsprechend und aktualisiert die View.

### 2. Wichtige Konzepte und Begriffe, die ich für die IHK-Abschlussprüfung als Fachinformatiker für Anwendungsentwicklung zum MVC-Pattern wissen muss

- **Trennung von Verantwortung**: MVC hilft, den Code zu strukturieren und klar zwischen Daten, Darstellung und Benutzerinteraktionen zu trennen.
- **Modularität und Wiederverwendbarkeit**: Komponenten können unabhängig voneinander entwickelt und getestet werden. Das View kann leicht geändert werden, ohne die Geschäftslogik im Model zu beeinträchtigen.
- **Aktualisierung der View**: Jede Änderung im Model kann leicht in der View reflektiert werden, da die Controller die Kommunikation zwischen diesen Komponenten verwaltet.

### Praktische Beispiele oder Szenarien, die das MVC-Pattern veranschaulichen

- **Webanwendung**: In einem Webshop besteht das Model aus Klassen wie `Product`, `Cart`, und `Order`, welche die Geschäftslogik und Datenbankzugriffe verwalten. Die Views sind die HTML-Seiten, die Produkte anzeigen, und die Controller koordinieren Aktionen wie das Hinzufügen eines Produkts zum Warenkorb.
- **Blog-System**: Ein Model `Post` speichert alle Beiträge und Kommentare. Die View zeigt die Artikel in HTML, und der Controller ermöglicht das Erstellen, Bearbeiten und Löschen von Beiträgen.
- **ToDo-Listen-Anwendung**: Das Model enthält die Logik zum Speichern von Aufgaben (z.B. in einer Datenbank), die View zeigt die Aufgaben in einer Liste, und der Controller verarbeitet Benutzeraktionen wie das Hinzufügen oder Abhaken von Aufgaben.

### 4. Empfohlene Ressourcen wie Videos, Artikel oder Übungen, um das Wissen zum MVC-Pattern zu vertiefen

- **Videos**:
    - [MVC Pattern Explained (YouTube)](https://www.youtube.com/watch?v=DUg2SWWK18I)