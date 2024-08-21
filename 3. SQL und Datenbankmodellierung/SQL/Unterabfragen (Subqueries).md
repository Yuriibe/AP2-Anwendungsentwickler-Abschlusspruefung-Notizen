### Generelle Erklärung
Unterabfragen sind Abfragen die innerhalb einer anderen SQL-Abfrage verschachtelt sind.

**1. Unterabfragen in SELECT:**
- Beispiel: `SELECT Name from Mitarbeiter WHERE Gehalt > (SElECT AVG(Gehalt) FROM Mitarbeiter);`
**2. Unterabfragen in INSERT:**
- Beispiel: `INSERT INTO MITARBIETER (NAME, GEHALT) SELECT Name, Gehalt FROM ExMitarbeter WHERE Gehalt > 3000;`
**3. Unterabfrage in UPDATE:**
- Beispiel: `UPDATE Mitarbeiter SET Gehalt = Gehalt * 1.1 WHERE AbteilungsID IN (SELECT AbteilungsID FROM Abteilung WHERE Standort = 'Berlin';`
**4. Unterabfrage in DELETE:**
- Beispiel: `DELETE FROM MITARBEITER WHERE ABTEILUNGSID = (SELECT AbteilungsID FROM Abteilungen WHERE Abteilungsname = 'HR'`