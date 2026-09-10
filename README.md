# Verzweigungen, Schleifen und Listen

## Aufgabe 1

Erstelle eine Liste mit Zahlen von 1 bis 10. Gib mit Hilfe einer Schleife und Verzweigung nur die geraden Zahlen aus.

Zum Überprüfen, ob eine Zahl gerade ist oder nicht, kann Modulo verwendet werden: `if zahl % 2 == 0`

---

## Aufgabe 2

Eine Liste von Schulnoten ist gegeben. Gib für jede Note eine Bewertung aus:

- 5 - 6: sehr gut
- 4 - 5: gut
- 1 - 4: ungenügend

---

## Aufgabe 3

Eine Liste mit Produktpreisen ist gegeben. Nun muss der Gesamtpreis berechnet werden und ausserdem noch die Mehrwertsteuer von 8,1 % addiert werden.

---

## Aufgabe 4

Die Temperaturen der letzten Tage wurden gemessen und in einer Liste gespeichert. Gib aus:
- An wie vielen Tagen die Temperatur gemessen wurde
- Was die Durchschnittstemperatur war
- An wie vielen Tagen es über 20°C war
- An wie vielen Tagen es unter 10°C war

---

## Aufgabe 5

Programmiere ein Zahlenratespiel. Das Spiel soll folgende Funktionalitäten haben:

- Der Computer denkt sich eine zufällige Zahl zwischen 1 und 10 aus
- Der Benutzer hat nun die Möglichkeit, die Zahl zu erraten
- Der Computer gibt danach aus, ob die Zahl "zu hoch", "zu tief" oder "richtig" war
- Das Spiel endet, wenn die korrekte Zahl gewählt wurde

Um eine zufällige Zahl zu generieren, muss random importiert werden: `import random` und dann kann so eine zufällige Zahl generiert werden: `random.randint(1, 10)`

---

## Aufgabe 6

Finde die grösste und die kleinste Zahl in einer Liste.

1. Verwende im ersten Code die Funktionen `max()` und `min()`
2. Im zweiten Code müssen die grösste und die kleinste Zahl ohne zusätzliche Funktionen gefunden werden

---

## Aufgabe 7

Erstelle eine neue Liste, die keine Duplikate enthält, und übernimm dafür alle Zahlen einmal von der gegebenen Liste.

---

## Aufgabe 8

Analysiere einen Text und gib folgende Informationen aus:
- Anzahl der Wörter
- Anzahl der Sätze (Punkte zählen)
- Längstes Wort
- Durchschnittliche Wortlänge

Mit `text.split()` können die Wörter in einem Text aufgeteilt werden.