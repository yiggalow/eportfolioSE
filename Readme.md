# SystemnaheProgrammierung
# Anti-Intruder-1000

## Präsentation

[Hier](https://unk3wn.github.io/SystemnaheProgrammierung/) findest du die Präsentation.

## Bildliche Darstellung

![Boss](https://github.com/Unk3wn/SystemnaheProgrammierung/blob/master/docs/ressources/images/boss.png)
![Raum](https://github.com/Unk3wn/SystemnaheProgrammierung/blob/master/docs/ressources/images/1_COM.png)

## Szenario

### Räume
* Innenraum -> Firmenräume
* Mitte -> "Luftschleuse"
* Außen -> "Böse Außenwelt"

### Personen
* Person - Sicherheit I 
  * Startet in der Mitte
  * als *S1* bezeichnet
* Person - Sicherheit II
  * Startet in der Mitte
  * als *S2* bezeichnet
* Person - Geldtransporter
  * Außenbereich
  * als *G* bezeichnet

### Ablauf
1. S1 & S2 drücken beide Knöpfe im mittleren Raum

2. Terminal wird aktiviert <br>
  2.1 60 Sekunden Timer wird gestartet <br>
  2.2 Code wird von G am Außenterminal eingegeben <br>
   Code richtig <br>
   Weiter zu 3. <br>
   Code falsch <br>
   Beenden des Eintrittvorgangs
   
3. Innentür schließt und Außentür öffnet
  3.1 Alle Knöpfe im mittleren Teil müssen gedrückt sein & der Code von S1 muss stimmen <br>
    3.1.1 S1 gibt Code am Mittelterminal ein <br>
    3.1.2 S2 drückt Knopf <br>
    3.1.3 G drückt Knopf <br>
     Code richtig <br>
     Weiter zu 4. <br>
     Code falsch <br>
     Beenden des Eintrittvorgangs G muss austreten
     
4. Außentür schließt sich und Innentür öffnet sich

5. Herzlich Willkommen bei Geldsack Inc.
