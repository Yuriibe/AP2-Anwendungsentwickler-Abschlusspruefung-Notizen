### Controller

Der **Controller** ist die Vermittler-Komponente, die den Fluss der Anwendung steuert. Er verbindet das Model mit der View, indem er Benutzeranfragen entgegennimmt, die entsprechende Geschäftslogik im Model aufruft und die passende View zurückgibt. Der Controller interpretiert Benutzeraktionen (z.B. Button-Klicks oder Formulareinreichungen) und aktualisiert das Model und/oder die View basierend auf diesen Aktionen.

Der Controller ist somit dafür verantwortlich, die Eingaben des Benutzers zu verarbeiten, das Model bei Bedarf zu ändern und sicherzustellen, dass die richtige View angezeigt wird.

Beispiele:

- In einer ToDo-Listen-Anwendung verarbeitet der Controller die Aktion "Aufgabe hinzufügen", ruft die entsprechende Methode im Model auf, um die Aufgabe zu speichern, und aktualisiert anschließend die View, um die aktualisierte Liste der Aufgaben anzuzeigen.
- Bei einer Suchfunktion könnte der Controller die Suchanfrage des Benutzers annehmen, die Datenbank über das Model abfragen und eine View rendern, die die Suchergebnisse anzeigt.