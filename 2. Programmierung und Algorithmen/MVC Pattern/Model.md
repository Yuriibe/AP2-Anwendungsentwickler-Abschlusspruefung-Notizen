### Model

Das **Model** ist der Teil des MVC-Patterns, der die Daten und die Geschäftslogik einer Anwendung verwaltet. Es ist verantwortlich für das Speichern, Verarbeiten und Verwalten von Daten sowie für die Umsetzung aller Geschäftsregeln, die im System erforderlich sind. Das Model kommuniziert mit Datenbanken, Web-APIs oder anderen Datenquellen und stellt diese Daten strukturiert bereit. Zudem fungiert es als "Single Source of Truth" für die Anwendung.

Beispiele:

- In einer Blogging-Anwendung könnte das Model eine Klasse `Post` sein, die die Felder `title`, `content` und `date` enthält. Die Geschäftslogik könnte Methoden zur Erstellung, Bearbeitung oder Löschung von Posts beinhalten.
- Bei einem E-Commerce-System könnte das Model Klassen wie `Product`, `Cart`, oder `Order` enthalten, um Produkte zu verwalten, Warenkorb-Funktionen zu handhaben und Bestellungen zu verarbeiten.