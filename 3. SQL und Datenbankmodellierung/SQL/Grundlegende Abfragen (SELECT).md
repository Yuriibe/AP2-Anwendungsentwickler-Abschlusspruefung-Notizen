### Generelle Erklärung

Der Select-Befehl wird benutzt, um Daten aus einer oder mehreren Tabellen in einer Datenbank abzurufen. Du kannst auswählen, welche Spalten du anzeigen möchtest und wie die Daten gefiltert, gruppiert und sortiert werden.

**1. Auswahl von Spalten:**
- `SELECT Spaltenname1, Spaltenname2 FROM Tabellenname`
- Beispiel: `SELECT Name, Gehalt FROM Mitarbeiter;`
**2. Filtern von Daten mit WHERE:**
- `SELECT * FROM Tabellenname WHERE Bedingung`
- Beispiel: `SELECT * FROM Mitarbeiter WHERE Gehalt > 3000;`
**3. Sortieren von Ergebnissen mit ORDER BY:**
- `SELECT * FROM Tabellenname ORDER BY Spaltenname ASC|DESC`
- Beispiel: `SELECT * FROM Mitarbeiter ORDER BY Einstellungsdatum DESC;`
**4. Gruppiere von Daten mit GROUP BY:**
- `SELECT Spaltenname, COUNT(*) FROM Tabellenname GROUP BY Spaltenname`
- Beispiel: `SELECT Abteilung, COUNT(*) FROM Mitarbeiter GROUP BY Abteilung;`
- Nach der Ausführung des Befehls erhalten wir eine neue Tabelle, die so aussieht

| Abteilung | COUNT(*) |
| --------- | -------- |
| Vertrieb  | 2        |
| IT        | 3        |
| Marketing | 1        |
**5. *Verwenden von Aggregatfunktionen**
- COUNT, SUM, AVG, MAX, MIN
- Beispiel: `SELECT COUNT(*) FROM Mitarbeiter`