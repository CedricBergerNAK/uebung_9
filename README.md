# Kapitel 9 Übung ("Blackjack Erweiterungen")

> Die Übungsaufgaben aus diesem Kapitel erfordern eine vorherige Umsetzung der Teile 1-4 der Blackjack-Übung aus [Übungsblock 5 bis 8](https://github.com/nordakademie-einfuehrung-java/uebungsblock_5_bis_8). Bitte setzen Sie die folgenden Teile als Ergänzung Ihrer bisherigen Blackjack-Lösung um.

Erweitern Sie das "Black Jack"-Programm wie folgt:

## Teil 5

* Erweitern Sie die Klasse ```Kartenhand``` um eine Methode ```istSiebenerDrilling```, welche ```true``` zurückliefert, wenn die Kartenhand aus nur 3 Karten besteht und alle Karten Siebenen sind.
* Prüfen Sie in der Klasse ```Start``` an geeigneter Stelle ab, ob der Spieler einen Siebener-Drilling hat und beenden Sie das Spiel gegebenfalls mit einer Gewonnen-Nachricht. Erweitern Sie dafür auch die Klasse ```Benutzerinterface``` um eine entsprechende Methode.
* Kommentieren Sie die neuen Methoden und generieren Sie ein Jar.

## Teil 6

* Erweitern Sie die Klasse ```Kartenhand``` um eine Methode ```istBlackJack```, welche ```true``` zurückliefert, wenn die Kartenhand aus nur 2 Karten besteht und 21 Punkte ergibt.
* Ergänzen Sie die Methode ```getTextdarstellung``` der Kartenhand insoweit, dass bei einem Black Jack am Ende nicht die Punkte angezeigt werden, sondern der Text "Black Jack".
* Berücksichtigen Sie zum Ende eines Spieles, dass ein Black Jack gegenüber einem Nicht-Black-Jack gewinnt. Verwenden Sie die unveränderten Methoden ```verlorenGeberHatMehr``` und ```gewonnenGeberHatWeniger``` der Klasse ```Benutzerinterface```.
 
## Teil 7

* Vor dem Spiel am Black-Jack-Tisch soll ein Geldeinsatz getätigt werden können. Gültige Einsätze sind 10, 20, 50, 100, 250, 500 und 1000 Euro.
* Das Spiel soll am Ende ausgeben, wieviel der Spieler erhält:
  * Verliert er, erhält er nichts.
  * Bei Unentschieden erhält er den Einsatz zurück.
  * Gewinnt der Spieler, erhält er seinen Einsatz zurück plus einen Gewinn in Höhe:
    * des Einsatzes bei einem "normalen" Sieg
    * des 1,5-fachen Einsatzes bei einem Siebener-Drilling sowie
    * des 1,5-fachen Einsatzes bei einem Black Jack.

* Der Einsatz soll bei jedem Spielschritt ausgegeben werden. 
