Gruppenarbeit Wahl-o-Mat USA Auswahlverfahren mit Putin-Faktor.

Allgemeine Vorgehensweise
Irgendwann in der Zukunft findet eine Wahl statt.
Schließlich wird ein Mahlowat konfiguriert.

Gelößt wurde ein Problem der echten Welt, incl. Strukturiertem Arbeiten mit folgender Vorgehensweise.

1. Lesen und verstehen des Sachverhaltes.

2. Analysieren jedes möglichen Szenarios, welches bei Wahlen stattfinden kann/könnte.

3. Quellen der Recherche: Jan Krüger Grafische Benutzeroberflächen mit Swing,
   https://de.wikipedia.org/wiki/Liste_der_Bundesstaaten_der_Vereinigten_Staaten_nach_Einwohnerzahl
   
4. Erstellen eines Ablauf u. Klassendiagramms

5. Schreiben des Codes 
     Bundeststaaten inkl. Einwohnerzahl wurde über eine csv-Datei in ein Array mit der Klasse class import csv eingebunden.
     Array wird eingelesen und - Sieger Array initialisiert. 
     Im nächsten Schritt wird die Funktion SiegerErmitteln/erfaken mit dem Ergebnis 0=Demokraten oder 1=Republikaner aufgerufen. Wenn die Mehrheit feststeht(Republikaner oder Demokraten), wird
     wieder die Funktion SiegerErmitteln aufgerufen, um zu bestimmen wieviele Staaten für 0 und wieviele für  1 gestimmt haben. 
     Gewinnen in diesem Wahlomat die Demokraten die Wahl, greift der Putineffekt (in Form einer do-whileSchleife) ins Wahlgeschehen ein.
     Das Ergebnis =(Rep.) wird anschließend ausgegeben und in Textform, in einer Datei, gespeichert.

