### Generelle Erklärung
Joins werden verwendet, um Daten aus mehreren Tabellen basieren auf einander verwandten Spalten zu kombinieren

**INNER JOIN:**
- Zeigt nur die Datensätze, die in beiden Tabellen übereinstimmende Werte haben.
- Beispiel: `SELECT * FROM Mitarbeiter INNER JOIN Abteilungen ON Mitarbeiter.AbteilungsID = Abteilungen.AbteilungsID;`
**LEFT JOIN**:
- Zeigt alle Datensätze aus der linken Tabelle und die übereinstimmenden Datensätze aus der rechten Tabelle. 
- Beispiel: `SELECT * FROM Mitarbeiter LEFT JOIN Abteilungen ON Mitarbeiter.AbteilungsID = Abteilungen.AbteilungsID;`
**RIGHT JOIN:**
- Zeigt alle Datensätze aus der rechten Tabelle und die übereinstimmenden Datensätze aus der Linken Tabelle.
- Beispiel: `SELECT * FROM Mitarbeiter RIGHT JOIN Abteilungen ON Mitarbeiter.AbteilungsID = Abteilungen.AbteilungsID;` 
**FULL JOIN:**
- Zeigt alle Datensätze, wenn es eine Übereinstimmung in entweder der linken oder rechten Tabelle gibt
- Beispiel: `SELECT * FROM Mitarbeiter FULL JOIN Abteilungen ON Mitarbeiter.AbteilungsId = Abteilungen.AbteilungsID`

![[Pasted image 20240806103837.png]]

![[Pasted image 20240806103806.png]]