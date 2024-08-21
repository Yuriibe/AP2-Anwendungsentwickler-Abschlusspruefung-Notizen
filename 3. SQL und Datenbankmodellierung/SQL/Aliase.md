### Generelle Erklärung
Aliase in SQL sind alternative Namen, die für die Tabellen oder Spalten verwendet werden, um Abfragen lesbarer zu machen und ihre Verständlichkeit zu verbessern. Sie sind besonders nützlich bei langen oder Komplexen Abfragen. Aliase werden durch das Schlüsselwort `AS` benutzt.

**Spalten-Alias:**
- Ein Spalten-Alias gibt einer Spalte in der SQL-Abfrage einen neuen Namen.
- `SELECT Spaltenname AS Aliasname FROM Tabellenname;`
- Beispiel: `SELECT MitarbeiterName AS Name, MitarbeiterGehalt AS Gehalt FROM Mitarbeiter;`
**Tabellen-Alias:**
- Ein Tabellen-Alias gibt einer Tabellen bei einer Abfragen einen neuen Namen. Dies ist besonders nützlich bei Joins
```SQL
SELECT t1.Spalte1, t2.Spalte2
FROM Tabelle1 As t1
JOIN Tabelle2 AS t2 ON t1.ID = t2.ID; 
```
- Beispiel:
```SQL
SELECT m.Name, a.Abteilungsname
FROM Mitarbeiter AS m
JOIN Abteilungen AS a ON m.AbteilungsID = a.AbteilungsID;
```

### Video und Aufgaben zur Vertiefung

**Video:**
- [SQL Aliases Tutorial](https://www.youtube.com/watch?v=Y9iWt1G8IaQ)