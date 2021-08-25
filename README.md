# HomeAssistant // Wake-up light alarm with sunrise effect

## Diese Automatisierung hilft unseren Kindern beim Aufstehen, indem ein farbenreicher Sonnenaufgang simuliert wird.

In einer Lovelace-Karte kann der Wecker mit einem "input_boolean" Ein-& Ausgeschaltet werden.
Mit "input_datetime" wird die Uhrzeit zum Aufstehen eingeschaltet. Damit dieser auslösen kann, muss hierfür ein template_script angelegt werden.

<img width="408" alt="Bildschirmfoto 2021-08-24 um 16 24 06" src="https://user-images.githubusercontent.com/54147030/130635912-e9fb05c6-15e8-44ef-bc1f-b543e963e6b0.png">

Es stehen weitere "input's" zur Verfügung um diese Karte auch für Wochenenden und Schlafenszeiten anzuwenden (Beisipelweise verwenden wir hier eine Automatierung, dass sich der Fernseher ausschaltet)

Die Automatisierung für das "Aufstehen" arbeitet so, dass 5 Minuten vor der Weckzeit das Licht mit einer "minimum brightness" von 1 anfängt und allmählich heller wird.
Zeitgleich bekommt man eine Pushbenachrichtung auf sein Handy, mit der man entweder bestätigen kann, dass man aufsteht, oder noch kurz liegen bleiben möchte.
Nutzt man die "Sleep-Funktion" geht nach 5 Minuten das Licht an und wird allmählig heller.

Für den Start belasse ich das bei diesem Code. Dieser ist enorm ausbaufähig! Beispielweise könnten die Eltern informiert werden, wenn der "Sleep-Modus" sich 2 mal wiederholt hat.

Danke an Sbyx für das Blueprint als Grundbaustein --> https://community.home-assistant.io/t/wake-up-light-alarm-with-sunrise-effect/255193
