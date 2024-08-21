### Generelle Erklärung
Mit Datenmanipulationsbefehlen kannst du Daten in einer Datenbank einfügen, Aktualisieren und Löschen

**Einfügen von Daten (INSERT INTO):**
- `INSERT INTO Tabellenname (Spalte1, Spalte2) VALUES (Wert1,Wert2)`
- Beispiel: `INSERT INTO Mitarbeiter (Name,Gehalt) VALUES ('Max Musterman', 3500);`
**Aktualisieren von Daten (UPDATE):**
- `UDATE Tabellenname SET Spalte1 = Wert1 WHERE Bedingung`
- Beispiel: `UPDATE Mitarbeiter SET Gehalt = 4000 WHERE ID = 5;`
**Löschen von Daten (DELETE):**
- `DELETE FROM Tabellenname WHERE Bedingung`
- Beispiel: `DELETE FROM Mitarbeiter WHERE Einstellungsdatum < '2000-01-01';`
