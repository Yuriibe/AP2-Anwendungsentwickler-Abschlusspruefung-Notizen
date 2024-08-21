Pseudocode ist eine einfache Beschreibung eines Algorithmus oder Programms, die unabhängig von einer spezifischen Programmiersprache ist. Es verwendet eine Mischung aus Natürlicher Sprache und Programmiersprachen-Syntax. Pseudocode hilft dabei, den Entwurfsprozess von Programmen zu planen.
Pseudocode hat keinen vorgeschriebenen, standardisierten Syntax.

**1. Grundlegende Strukturen:**
- **Sequenzen:** Eine Abfolge von Anweisungen, die nacheinander ausgeführt werden.
- **Selektion:** Eintscheidungstrukturen wie `if`,  `else if` und `else`
- **Iteration:** Schleifenstrukturen wie `while`, `for` und `repeat until`, führen Anweisungen wiederholt aus, bis eine Bedingung erfüllt ist
### Video und Aufgaben zur Vertiefung

**Video:**
- [Pseudocode for Beginners](https://www.youtube.com/watch?v=qfckDdsEIq8)
- [5 Minutes to Code: Programming Basics "Pseudocode"](https://www.youtube.com/watch?v=HhBrkpTqzqg)

### Wissenswertes für die Abschlussprüfung

Für die IHK-Abschlussprüfung solltest du die folgenden Punkte über Pseudocode beachten:

1. **Verständlichkeit:** Der Pseudocode sollte so geschrieben sein, dass er von jemandem, der die grundlegenden Konzepte der Programmierung versteht, leicht gelesen und nachvollzogen werden kann.
2. **Struktur:** Der Pseudocode sollte die logischen Strukturen des Algorithmus klar darstellen, einschließlich Sequenzen, Selektionen und Iterationen.
3. **Einheitlichkeit:** Halte dich an eine konsistente Art der Darstellung, um Verwirrung zu vermeiden.
4. **Kommentierung:** Verwende Kommentare, um komplexe oder wichtige Teile des Algorithmus zu erklären.

**Aufgaben:**

1. **Grundlegende Sequenz:**
    
    - Schreibe Pseudocode, um zwei Zahlen einzugeben und ihre Summe zu berechnen und auszugeben.
    
	```Plaintext
	START
	DECLARE Integer num1, num2, sum
	PRINT "Enter the first number:"
	INPUT num1
	PRINT "Enter the second number:"
	INPUT num2
	sum = num1 + num2
	PRINT "The sum is:", sum
	END
	```
    
2. **Selektion:**
    - Schreibe Pseudocode, um zu überprüfen, ob eine eingegebene Zahl gerade oder ungerade ist.
    
	```Plaintext
	START
	DECLARE Integer number
	PRINT "Enter a number:"
	INPUT number
	IF (number MOD 2 == 0) THEN
	    PRINT "The number is even."
	ELSE
	    PRINT "The number is odd."
	END IF
	END
	
	```   
	    
3. **Iteration:**
    
    - Schreibe Pseudocode, um die Summe der ersten `n` natürlichen Zahlen zu berechnen.

	```Plaintext
	START
	DECLARE Integer n, sum, i
	sum = 0
	PRINT "Enter the value of n:"
	INPUT n
	FOR i = 1 TO n DO
	    sum = sum + i
	END FOR
	PRINT "The sum of the first", n, "natural numbers is:", sum
	END

	```
    
4. **Kombination:**
    
    - Schreibe Pseudocode für einen Algorithmus, der die maximale Zahl in einer Liste von Zahlen findet.

	```Plaintext
	START
	DECLARE List numbers
	DECLARE Integer max, i, n, currentNumber
	PRINT "Enter the number of elements:"
	INPUT n
	PRINT "Enter the numbers:"
	FOR i = 1 TO n DO
	    INPUT currentNumber
	    APPEND currentNumber TO numbers
	END FOR
	max = numbers[1]
	FOR i = 2 TO n DO
	    IF (numbers[i] > max) THEN
	        max = numbers[i]
	    END IF
	END FOR
	PRINT "The maximum number is:", max
	END
	```