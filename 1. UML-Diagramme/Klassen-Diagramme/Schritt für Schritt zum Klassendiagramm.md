```
Das System soll die Verwaltung von Büchern in einer Bibliothek ermöglichen. Jedes Buch hat einen Titel, einen Autor, eine ISBN-Nummer und einen Verlag. Bücher können von Mitgliedern der Bibliothek ausgeliehen werden. Jedes Mitglied hat einen Namen, eine Mitgliedsnummer und eine Kontaktinformation. Die Bibliothek möchte auch die Anzahl der verfügbaren Exemplare jedes Buches verfolgen
```




### Schritt 1: Identifizierung der Hauptobjekte

Zunächst müssen wir die Hauptobjekte oder Konzepte identifizieren, die in der Anforderung Beschrieben sind. In unserem Beispiel haben wir folgende Hauptobjekte

- Buch 
- Mitglied
- Bibliothek

Diese Hauptobjekte werden zu Klassen in unserem Klassendiagramm

### Schritt 2: Bestimmung der Attribute

Als nächstes müssen wir die Attribute jeder Klasse bestimmten. Attribute sind die Eigenschaften oder Daten, die jede Klasse beschreiben. Wir suchen nach Begriffen wie "hat", "besitzt", "enthält" oder spezifische Eigenschaften in der Anforderung

Für die Klasse "Buch" haben wir folgende Attribute

- Titel
- Autor
- ISBN-Nummer
- Verlag

Für die Klasse "Mitglied" haben wir Folgende Attribute

- Name 
- Mitgliedsnummer
- Kontaktinformation

Die Klasse "Bibliothek" hat ein Attribut

- Anzahl der verfügbaren Exemplare (pro buch)

![[AttributeKlassenDiagramm.png]]

### Schritt 3: Identifizierung der Beziehungen

Jetzt müssen die Beziehungen zwischen den Klassen identifiziert werden. Wir suchen nach Begriffen wie "hat", "gehört zu", "besteht aus" oder Aktionen, die eine Interaktion zwischen den Klassen beschreiben.

In unserem Beispiel haben wir folgende Beziehungen.

- Ein **Buch** kann von einem Mitglied ausgeliehen werden.
- Die **Bibliothek** verfolgt die Anzahl der verfügbaren Exemplare jedes Buches.

Die Beziehung zwischen **"Buch"** und **"Mitglied"** ist eine Assoziation, da ein Mitglied ein Boch ausleihen kann. Die Beziehung zwischen **"Bibliothek"** und **"Buch"** ist eine **Aggregation**, da die Bibliothek Bücher enthält und die Anzahl der verfügbaren Exemplare verfolgt.

![[Identifizierung der Beziehungen.png]]
### Schritt 4: Verfeinerung und Überprüfung

Nachdem wir die Klassen, Attribute und Beziehungen identifiziert haben, müssen wir das Klassendiagramm verfeinern und überprüfen. Wir sollten sicherstellen, dass das Diagramm die fachliche Anforderung vollständig abdeckt und keine Informationen vergessen werden.

In diesem Beispiel könnten wir noch weitere Methoden oder Operationen hinzufügen, wie zum Beispiel:

- In der Klasse **"Buch"**: eine Methode zum Ausleigen eines Buches
- In der Klasse **"Bibliothek"**: Methoden zum Hinzufügen und Entfernen von Büchern
- In der Klasse **"Mitglied"** eine Methode zum Zurückgeben eines Buches

![[verfeinern und Prüfen.png]]
