# Schiffe-Versenken

In dem Schiffe versenken was ich programmiert habe spielt man auf einen 10x10 Spielfeld mit 4 Schiffen. 
Es gibt das Kampfschiff welches 5 Positionen lang ist, den Kreuzer welches 4 Positionen lang ist, 
den Minensucher welches 3 lang ist und das Wissenschaftsschiff welches 2 lang ist.

Diese Schiffe können senkrecht oder waagrecht auf dem Feld platziert werden.
Zuerst wird der Spieler aufgefordert seine Schiffe zu platzieren. 
Der Spieler kann seine Koordinate angeben so wie im echten Schiffe versenken, also z.B. A5 oder B7.
Die Schiffe werden stück für stück auf einzelne Koordinaten zu platziert. 
Das Programm überprüft dann von selbst, ob die Schiffe richtig platziert wurden, also ob es im 
Spielfeld liegt und auch ob alle Jeweiligen Schiffsteile richtig miteinander verbunden sind. Falls 
nicht, wird der Spieler wieder aufgefordert sein Schiff neu zu platzieren.

Wenn alle Schiffe platziertsind, tut die KI ihre Schiffe zufällig auf dem Spielfeld platzieren.
Dann kann das Spiel schon anfangen. 
Es wird ein leeres Spielfeld angezeigt und der Spieler wird aufgefordert ein Spielfeld zu 
spezifizieren welches er attackieren will. Die Eingabe erfolgt in wieder in Koordinaten. Es wird
dann gesagt, ob es ein Treffer war oder nicht. 
Treffer werden als Rote Kreuze markiert und Keine Treffer als Blaue Kreuze.
Danach tut die KI ihren Zug spielen. Es wird nun auf das Spielfeld gewechselt wo man die 
Schiffe sehen kann vom Spieler. Anfangs ratet die KI zufällig wo attackiert werden soll.
(Falls die KI im letzten Zug was getroffen hat, dann attackiert diese umliegende Felder, bis ein 
Schiff versenkt wird. Manchmal mussjedoch die KI von neu Zufällig attackieren, wenn diese 
„Feststeckt“ bzw. keine anderen Möglichkeiten sieht.)

Es wird nun nach jedem Zug abgewechselt, bis einer alle Schiffe versenkt hat.
