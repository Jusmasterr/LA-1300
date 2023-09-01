# LA-1300 Projekt-Dokumentation

Meister


# Aufgabenstellung / Ziele

In diesem Projekt programmiere ich ein Spiel, bei dem der Nutzer eine Zahl erraten muss. Das Programm sagt nach jedem Versuch ob die geratene Zahl grösser oder kleiner ist als die gesuchte Zahl.

## Anforderungen
1.	Der Computer speichert eine Zufallszahl zwischen und mit 1 bis 100 als Geheimzahl.
2.	Der Benutzer kann Zahlen raten.
3.	Für jede der geratenen Zahlen gibt der Computer einen Hinweis aus:
a.	Die geratene Zahl ist niedriger als die Geheimzahl.
b.	Die geratene Zahl ist grösser als die Geheimzahl.
c.	Die Geheimzahl wurde erraten.
4.	Wenn die Geheimzahl erraten wurde, soll die Anzahl der Rateversuche ausgegeben werden.
5.	Das Programm soll mit Fehleingaben umgehen oder sie vermeiden können.
6.	Wenn die Geheimzahl erraten wurde, soll der User entscheiden können ob er nochmal spielen möchte.
7.	Der Highscore soll ausgegeben werden, wenn die Geheimzahl erraten wurde.

## Ziele
- Ich wende Objektorientiertes Programmieren an
- Die Ausgabe des Programms in der Konsole schön und übersichtlich gestalten

# Produkt

## Planen

| Datum | Arbeitspacket | Zuständig                                             |
| ----- | ------- | ------------------------------------------------------------ |
|   18.08.2023    | Planen  | Justus |
|  25.08.2023     | Realisieren |   Justus              |
|  25.08.2023     | Testfallspezifikation |   Justus                      |
|  1.08.2023     | Testen |   Justus                      |
|  1.08.2023     | Reflexion / Auswertung |   Justus                      |





## Testfallspezifikation

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |   Programm gestartet           |    -     |         -         |
| 2.1 |  Programm gestartet            |    5     |    -           |
| 3.1 |    Zufallszahl ist 10          |    5     |    "The number is bigger"              |
|3.2 |      Zufallszahl ist 10        |    15     |    "The number is smaller"               |
|3.3   |    Zufallszahl ist 10      |  10    |     "You guessed the number"            |
| 4.1  |    Nummer nach 1 Versuch erraten      |  -    |  "You guessed the number after 1 attempt!"                |
| 4.2  |   Nummer nach 10 Versuchen erraten       |   -   | "You guessed the number after 10 attempts!"                 |
| 5.1  |    Programm gestartet      |   "Hello World"   | "Invalid Input, try again"                 |
| 5.2  |    Abfrage für erneutes Spielen      |   13   |  "Invalid Input, try again"            |
| 6.1  |  Zufallszahl erraten "Do you want to play again? (y/n)"        |   y   |     *erneutes Spiel"             |
| 6.2  |  Zufallszahl erraten "Do you want to play again? (y/n)"        |   n   |     *Programm beendet"             |
| 7.1  |  noch kein Highscore, 5 Versuche beim Raten, Geheimzahl erraten |  -  |     "Highscore: 5"          |
| 7.2  |  vorheriger Highscore = 5, Versuche beim Raten 4, Geheimzahl erraten |  -  |     "Highscore: 4"          |


## Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |  01.09.2023     |   Ok       |  Justus      |
| 2.1  |  01.09.2023     |   Ok       |   Justus     |
| 3.1  |  01.09.2023     |   Ok       |   Justus     |
| 3.2  |  01.09.2023     |   Ok       |   Justus     |
| 3.3  |  01.09.2023     |   Ok       |   Justus     |
| 4.1  |  01.09.2023     |   Ok       |   Justus     |
| 4.2  |  01.09.2023     |   Ok       |   Justus     |
| 5.1  |  01.09.2023     |   Ok       |   Justus     |
| 5.2  |  01.09.2023     |   Ok       |   Justus     |
| 6.1  |  01.09.2023     |   Ok       |   Justus     |
| 6.2  |  01.09.2023     |   Ok       |   Justus     |
| 7.1  |  01.09.2023     |   Ok       |   Justus     |
| 7.2  |  01.09.2023     |   Ok       |   Justus     |

