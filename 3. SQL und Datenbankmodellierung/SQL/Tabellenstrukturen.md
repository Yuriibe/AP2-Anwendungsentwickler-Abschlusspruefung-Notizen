### Generelle Erklärung
Mit Befehlen zur Verwaltung von Tabellenstrukturen kannst du neue Tabellen erstellen, bestehende bearbeiten und löschen

**1. Erstellen von Tabellen (Create Table)**
- `CREATE TABLE Tabellenname (Spalte1 Datentyp, Spalte2 Datentyp)`
- Beispiel `Create TABLE Abteilung (AbteilungsID INT, Abteilungsname VARCHAR(50)`
**2. Ändern von Tabellen (ALTER TABLE)**
- Hinzufügen von Spalten: `ALTER TABLE Tabellenname ADD Spaltenname Datentyp`
- Beispiel: `ALTER TABLE Mitarbeiter ADD Geburtsdatum DATE`
**3. Löschen von Tabellen (DROP TABLE):**
- `DROP TABLE Tabellenname;`
- Beispiel: `DROP TABLE Abteilung`