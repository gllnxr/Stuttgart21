# Datensatz Stuttgart21

Codebuch Stand 2023-07, aktualisiert 2023-09 erstellt von Louis Göllner

## Inhalt

-   Edges.csv

-   Nodes.csv

-   Codebuch.md

<div>

## Ursprung und Datenerhebung

Im Datensatz SNA_S21 wurde das Netzwerk der Beziehungen aller relevanten beteiligten Akteurinnen an dem Bauprojekt Stuttgart 21 erhoben.

Das Netzwerk ist ein ungerichtetes *two-mode-network*. Also eine Erhebung von sowohl natürlichen Personen sowie Organisationen.

</div>

<div>

## EDGE-Attribute

**id** (eindeutige Codierung des Knoten)

codiert von 1 bis 106, jede ID entspricht genau einem Knoten

**from** Knoten A, welcher mit Knoten B verbunden ist

**to** Knoten B, welcher mit Knoten A verbunden ist

**weight**

Ausprägung der Beziehungsstärke; hier: Auflistung der Macht zwischen zweier Knoten

1 = wenig Entscheidungsmacht

2 = viel Entscheidungsmacht

**relationship**

Definiert die Art der Beziehung bei multiplexen Netzwerken mit verschienden Beziehungsarten

1 = Geschäftlich

2 = Freundschaftlich (nachweislich... )

</div>

<div>

## NODE-Attribute

**id** (eindeutige Codierung des Knoten)

codiert von 1 bis 106, jede ID entspricht genau einem Knoten

**name** Character; Voller Name oder offizielle Bezeichnung des Knotens

**name_short** Character; Name (Vorname und Nachname) oder Kurzbezeichnung (altern.: Abkürzung)

**type** Numerisch;

1 = natürliche Person

2 = Organisation

**sex** Numerisch; trichotome Ausprägung

1 = male

2 = female

3 = divers

**branche** Numerisch;

1 = DB-Assoziiert

2 = Unternehmen der Infrastruktur

3 = Gewerkschaften und Verbände

4 = Parteien, Ministerien und Kommissionen

5 = Wissenschaftliche Institute

6 = Veranstalter

7 = Finanzwesen

8 = Immobilien

9 = Städte

**party** Character

**politician** Character;

TRUE\
FALSE

**NA** definiert fehlende Werte

</div>
