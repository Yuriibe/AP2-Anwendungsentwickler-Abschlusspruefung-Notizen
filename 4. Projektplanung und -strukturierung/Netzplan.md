Ein Netzplan, auch bekannt als Projektstrukturplan, ist ein grafisches Hilfsmittel, das in der Projektplanung und -steuerung verwendet wird. Er dient dazu, die Abfolge von Aufgaben oder Aktivitäten in einem Projekt darzustellen, deren zeitlichen Ablauf zu planen und die Abhängigkeiten zwischen diesen Aufgaben zu visualisieren. Netzpläne helfen Projektmanagern, den Fortschritt zu überwachen, Engpässe zu identifizieren und sicherzustellen, dass das Projekt innerhalb des geplanten Zeitrahmens abgeschlossen wird.

Es gibt zwei Haupttypen von Netzplänen:

- **PERT-Diagramm (Program Evaluation and Review Technique)**: Ein PERT-Diagramm wird verwendet, um die verschiedenen Aufgaben und deren Abhängigkeiten zu identifizieren. Es ist besonders nützlich für die Analyse der Zeit, die für die Fertigstellung jedes Projektschritts benötigt wird.
- **CPM-Diagramm (Critical Path Method)**: Ein CPM-Diagramm hilft, den längsten Pfad von Aufgaben zu identifizieren, die für die Fertigstellung des Projekts notwendig sind. Es zeigt auch, welche Aufgaben parallel durchgeführt werden können.

### 2. Wichtige Konzepte und Begriffe, die ich für die IHK Abschlussprüfung als Fachinformatiker für Anwendungsentwicklung zu Netzplänen wissen muss

- **Knoten und Kanten**: Knoten repräsentieren Aktivitäten oder Ereignisse, während Kanten die Abhängigkeiten zwischen diesen Aktivitäten darstellen.
- **Kritischer Pfad**: Der längste Pfad durch den Netzplan, der die kürzeste Zeit für die Fertigstellung des Projekts bestimmt. Verzögerungen auf dem kritischen Pfad führen zu Verzögerungen im gesamten Projekt.
- **Vorwärts- und Rückwärtsrechnung**: Methoden zur Bestimmung der frühestmöglichen und spätestmöglichen Start- und Endzeitpunkte der Aktivitäten.
- **Pufferzeiten**: Zeitreserven, die innerhalb eines Netzplans eingeplant werden, um potenzielle Verzögerungen abzufedern, ohne den Gesamtzeitplan zu beeinträchtigen.
- **Meilensteine**: Wichtige Ereignisse oder Eckpunkte innerhalb eines Projekts, die den Fortschritt markieren.

### Formeln

FAZ = Frühster Anfanszeitpunkt
FEZ = Frühster Endzeitpunkt
SAZ = Spätester Anfangszeitpunkt
SEZ = Spätester Endzeitpunkt
D = Dauer
GP = Gesamt Puffer (maximale Verschiebung des Vorgangs ohne Projektende zu verschieben)
FP = Freier Puffer (Verschiebung ohne Einfluss auf benachbarte Vorgänge)

**FEZ** = FAZ + D

Bei normalfolge:
**FAZ** = größte FEZ (Nachfolger)

**SAZ** = SEZ - D

Bei normalfolge:
**SEZ** = kleinster SAZ (Nachfolger)

**GP** = SEZ - FEZ = SAZ - FAZ
Bei normalfolge:
**FP** = niedr. FAZ (Nachfolger) - FEZ

### 3. Praktische Beispiele oder Szenarien, die Netzpläne veranschaulichen

- **Softwareentwicklungsprojekt**: Ein Netzplan könnte die verschiedenen Phasen eines Softwareentwicklungsprojekts darstellen, einschließlich Anforderungsanalyse, Design, Implementierung, Testen und Bereitstellung. Jede Phase könnte weiter in spezifische Aufgaben unterteilt werden, z.B. "Erstellung des Datenbankmodells", "Implementierung der Benutzeroberfläche", "Integrationstest".
- **Bauprojekt**: Ein Netzplan könnte die Aktivitäten eines Bauprojekts zeigen, wie z.B. "Grundstückskauf", "Baugenehmigung einholen", "Fundament legen", "Wände errichten", "Dach decken". Abhängigkeiten zwischen den Aktivitäten würden verdeutlichen, dass das Dach erst gedeckt werden kann, wenn die Wände errichtet sind.
- **Eventplanung**: Bei der Planung einer Konferenz könnte ein Netzplan die Aufgaben "Auswahl des Veranstaltungsorts", "Einladung der Sprecher", "Marketing", "Ticketverkauf", "Logistik" und "Durchführung der Veranstaltung" umfassen. Der Netzplan hilft sicherzustellen, dass jede Aufgabe rechtzeitig und in der richtigen Reihenfolge durchgeführt wird.

### 4. Empfohlene Ressourcen wie Videos, Artikel oder Übungen, um mein Wissen zu Netzplänen zu vertiefen

- **Videos**:
    - [Project Management - Network Diagram (YouTube)](https://www.youtube.com/watch?v=I9jd0jgVvg0)
    - [Critical Path Method (CPM) - Project Management (YouTube)](https://www.youtube.com/watch?v=tJ2k1ZCINxI)
    - [Netzplan einfach erklärt](https://www.youtube.com/watch?v=MnE1kLW3rvs)
    - [Kritischer Pfad, Gesamtpuffer und freier Puffer](https://www.youtube.com/watch?v=kjjN7MDwgf0)
