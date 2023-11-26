# Codebuch Stand 2023-11
Erstellt von Paul Antwerpes (pa025@hdm-stuttgart.de)

## Datenerhebung 
Das Netzwerk ist ein ungerichtetes Two-Mode-Netzwerk 
Die hier dargelegten Daten stammen aus einer Recherche zwischen Juni und Oktober 2023, unter anderem unter Berufung auf das Buch „Stuttgart 21 – eine Rekonstruktion der Proteste“ der Autorin Julia von Staden.
Umgang mit fehlenden Werten: Fehlende Werte werden nicht erfasst 

## Edge – Attribute: 
ID 
(= eindeutige Codierung eines Knotens , jede ID entspricht genau einem Knoten) 
From 
(= initiierender Knoten, Richtung irrelevant, da ungerichtet) 
To
(= erhaltender Knoten. Richtung irrelevant, da ungerichtet) 

## Node – Attribute: 
ID 
(= identisch wie in der Edgelist, zur Identifikation des Knotens) 
Name 
(= ID numerisch) 
Sex 
(= 1 – männlich, 2 – weiblich, 3 – divers) 
Type 
(= 1 – natürliche Person, 2 = Organisation Pro/Contra Stuttgart 21) 
Branche 
Aus welcher Brache kommen die Aktivist*innen? 
(= 1 - Politik, 2 - Infrastruktur) 
Politician
(= Nur angegeben, wenn in Politik tätig, True)
Party 
(= Nur angeben, wenn in irgendeiner Berbindung zu einer politischen Partei, numerisch)
