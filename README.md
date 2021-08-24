# HomeAssistant // W

## Diese Automatisierung hilft unseren Kindern beim Aufstehen, indem ein farbenreicher Sonnenaufgang simuliert wird.

In einer Lovelace-Karte kann der Wecker mit einem "input_boolean" Ein-& Ausgeschaltet werden.
Mit "input_date" wird die Uhrzeit zum Aufstehen eingeschaltet.

Es stehen weitere "input's" zur Verfügung um diese Karte auch für Wochenenden und Schlafenszeiten anzuwenden (Beisipelweise verwenden wir hier eine Automatierung, dass sich der Fernseher ausschaltet)

Die Automatisierung für das "Aufstehen" arbeitet so, dass 5 Minuten vor der Weckzeit das Licht mit einer "minimum brightness" von 1 anfängt und allmählich heller wird.
Zeitgleich bekommt man eine Pushbenachrichtung auf sein Handy, mit der man entweder bestätigen kann, dass man aufsteht, oder noch kurz liegen bleiben möchte.
Nutzt man die "Sleep-Funktion" geht nach 5 Minuten das Licht auf 50% Helligkeit an.

Für den Start belasse ich das bei diesem Code. Dieser ist enorm ausbaufähig! Beispielweise könnten die Eltern informiert werden, wenn der "Sleep-Modus" sich 2 mal wiederholt hat.
