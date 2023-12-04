---
title: "226305 Forschungsbericht Stuttgart 21"
author: "Louis Göllner, David Vogt, Paul Antwerpes, Sinan Korkmaz, Mia Müller"
date: "`r Sys.Date()`"
output:
  html_document:
    df_print: paged
    toc: yes
    toc_depth: 5
    number_sections: yes
  word_document:
    toc: yes
    toc_depth: '5'
  pdf_document:
    toc: yes
    toc_depth: '5'
subtitle: Analyse des Beziehungsnetzwerks von Politik, Wirtschaft und Bahn-Unternehmen beim Bauprojekt Stuttgart 21
editor_options: 
  markdown: 
    wrap: 72
---

**Abstract und Keywords**

Wir analysieren die Verbindungen zwischen Politik, Wirtschaft und dem
DB-Projekt Stuttgart 21. In einem ausgegliederten Exkurs wird ein kurzer
Blick auf die aktivistische Landschaft rund um S21 geworfen. Beide
Netzwerke sind ungerichtete, two-mode-Netzwerke. Es wurde untersucht,
welche Parteien häufig vorkommen, welche Akteur\*innen bei S21 den
größten Einfluss hatten und, welche Rolle Frauen im Netzwerk s21
spielen. Dabei zeigte sich, dass die Politik in Baden-Württemberg sehr
dichte Verbindungen zur Wirtschaft pflegt und, dass diese Verbindungen
auch bei Bauprojekten wie S21 viel genutzt werden. Zudem wurde im
aktivistischen Netzwerk untersucht, welche Gruppierungen oder
Einzelpersonen hier am zentralsten positioniert sind und, wie diese
untereinander verbunden sind.

Keywords: Netzwerkanalyse, Stuttgart 21, Deutsche Bahn, S21, Bauprojekt,
Politik, Wirtschaft, Verflechtungen

# Einleitung

Die Schnittstellen zwischen Politik und Wirtschaft sind wichtiger
Bestandteil in heutigen Gesellschaften. Dabei verschwimmen die Grenzen
zwischen den beiden Bereichen immer mehr: Nicht selten wechseln
Politiker\*innen in die Wirtschaft, und auch Personen aus der Wirtschaft
nehmen tagtäglich Einfluss auf die nationale und internationale Politik.

Dieser Forschungsbericht widmet sich der Analyse der Verflechtungen
zwischen Politik, Wirtschaft und den beteiligten Bahn-Unternehmen am
konkreten Beispiel des Bauprojekts "Stuttgart 21". Das
Infrastrukturprojekt gilt auch als Symbol für die enge Verbindung
zwischen politischen Entscheidungsträger\*innen und wirtschaftlichen
Interessen. Die hier vorliegende Netzwerkanalyse zielt darauf ab, die
Dichte der Verflechtungen zu verstehen und visuell darzulegen.

Aus diesem Ziel ergibt sich die folgende Forschungsfrage: "Wie vernetzt
sind Politik und Wirtschaft in Baden-Württemberg am Beispiel von
Stuttgart 21?"

Des Weiteren wird sich in einem kurzen Exkurs damit beschäftigt,
inwieweit beteiligte Aktivist\*innen für und gegen Stuttgart 21
miteinander vernetzt sind und welche Parallelen, sowie Unterschiede es
zum Gesamtnetzwerk gibt.

# Vorarbeiten und vergleichbare Studien

## Forschungsstand

Das Thema „Stuttgart 21" wurde bereits in mehreren wissenschaftlichen
Arbeiten aufgearbeitet.

Melanie Nagel beschäftigt sich in ihrem Buch „Polarisierung im
politischen Diskurs" mit dem politischen Diskurs durch Wissens- und
Diskursnetzwerke am Beispiel von „Stuttgart 21". In ihrer
Netzwerkanalyse zeigt sie bereits die hohe Komplexität des Projekts
alleine auf der politischen Ebene auf. Des weiteren erwähnt Nagel, dass
die zeitliche Komponente auch den Datenzugang erschwert. Die Anfänge des
Großbauprojekt liegen mehr als ein Jahrzehnt zurück und somit sind
Zeitungsartikel und andere Quellen schwer rückzuverfolgen. Diese
Schwierigkeit kam auch im Verlauf der hier vorliegenden Netzwerkanalyse
der Akteur\*innen von Stuttgart21 auf.

## Arbeitshypothesen

Schon vor der Recherche wurde sich im gemeinsamen Austausch über die
Arbeitshypothesen Gedanken gemacht.

H1: Es wurde vor allem vermutet, dass Politiker\*innen und Wirtschaft
gerade im Land Baden-Württemberg sehr eng miteinander verflochten sind
und, das politische Entscheidungen damit auch die Struktur innerhalb des
Bauprojekts Stuttgart 21 beeinflussen.

H2: Es wird zudem angenommen, dass es einzelne Akteur\*innen gibt, die
eine zentralere Position im Netzwerk inne haben, damit also über mehr
Möglichkeiten zur Machtausübung verfügen.

H3: Frauen sind im Netzwerk s21 wohl in der klaren Unterzahl, dies
machen sie unter Anderem mit dichten Verbindung untereinander wett.

H4: CDU-Politiker\*innen sind in der klaren Überzahl im Gesamtnetzwerk.

H5 (Exkurs): Es wird angenommen, dass Aktivist\*innen untereinander noch
dichter vernetzt sind, als Akteur\*innen im Gesamtnetzwerk.

H6 (Exkurs): Aktivist\*innen sind nicht nur in ihrer eigenen
Meinungsblase gut vernetzt, sondern auch über die Grenzen hinweg mit
gegensätzlichen Meinungsträgern verbunden.

## Ablauf

### Pretest

Um herauszufinden, wie der Datenzugang ist, wurden bereits für den
Pretest erste Recherchen aufgewandt. Dabei wurde schnell klar, dass die
zuerst angedachte zeitliche Achse nicht umsetzbar ist, da es den Rahmen
des Arbeitsaufwands klar überschreiten würde. Darüber hinaus konnte im
Pretest festgestellt werden, dass eine Richtung der Beziehungen nicht zu
erheben ist. Die Quellenlage ist hierfür nicht annähernd ausreichend und
es liegt in der Natur von nicht-öffentlich zugänglichen Beziehungen,
dass diese nicht auffindbar sind, weil man diese nicht finden soll.

### Datenzugang

Der Datenzugang bei der Recherche fokussierte sich vor allem auf
Lobbypedia, Northdata und Lobbycontrol. Aber auch durch viele
Zeitungsartikel aus beispielsweise dem Spiegel, der Stuttgarter Zeitung
oder dem Handelsblatt wurden wichtige Daten erschlossen. Die Webseite
des Bahnprojekt Stuttgart-Ulm wurde ebenfalls herangezogen. Zudem wurden
Lebensläufe über Linked In als Datenzugang zur Verifikation genutzt.

### Vorgang im Team und Datenerhebung

Bereits im Sommersemester wurde intensiv an einem Zeitplan und
Forschungskonzept auf Notion gearbeitet. Notion half vor allem dabei,
die Arbeit und Terminplanung über die Semesterferien zu erleichtern.
Durch verschiedene Bereiche wurden die Aufgabensektoren
Politiker\*innen, Unternehmen und Aktivismus verteilt, sowie ein Bereich
für Quellen errichtet, um dadurch später direkt auf die Quellenverweise
zugreifen zu können.

Über den frühen Sommer hinweg wurde sich durch regelmäßige Calls über
den neusten Stand informiert und die Recherche und Datenauswertung
schritt voran. Vor allem das Zusammensuchen von jeglichen
Zeitungsartikeln und Lebensläufen von Politiker\*innen war hier
substantieller Bestandteil, bei der Recherche musste jede Beziehung und
Information dem Zwei-Quellen-Prinzip unterzogen werden.

Relativ früh fiel die Entscheidung in der Gruppe, das Netzwerk der
Aktivist\*innen in einen eigenen Datensatz auszugliedern - Das Netzwerk
wäre sonst zu groß gewesen.

Bei regelmäßigen Treffen, die über Zoom stattfanden, konnten Fehler und
Unstimmigkeiten früh erkannt und behoben werden.

### Datenbereinigung

Die Datenbereinigung erfolgte größtenteils über den aktiven Austausch
untereinander. Durch die zu Beginn verteilten Aufgaben und das früh
einheitlich festgelegte Codebuch wurden Mengen an Doppelungen während
der Datenerhebung im Vorhinein bereits verhindert. Durch den gemeinsamen
Vergleich von Excel Tabellen wurden zum Schluss der Recherche einzelne
Doppelungen bereinigt. Durch den Vergleich von verschiedenen Berichten
wurden zudem unsichere Daten überprüft und gesichert. Es wurden nur
solche Daten im Datensatz s21 und activists schlußendlich erhoben,
welche unter Anwendung des Zwei-Quellen-Prinzips einwandfrei verifiziert
werden konnten.

## Codebuch Gesamtnetzwerk und Aktivist\*innen

Das
[Codebuch](https://github.com/gllnxr/Stuttgart21/blob/main/CodebuchS21.md)
für das Gesamtnetzwerk ist auf GitHub verfügbar und beschreibt die
Variablen, Relationen und Gewichte des Gesamtnetzwerks. Der [Datensatz
s21](https://github.com/gllnxr/Stuttgart21) des Gesamtnetzwerks ist
ebenso auf GitHub hinterlegt.

Das [Codebuch für das
Aktivist\*innen-Netzwerk](https://github.com/gllnxr/Stuttgart21/blob/main/Codebuch%20Aktivist*innen.md),
sowie der Datensatz activists ist ebenfalls auf GitHub hinterlegt.

# Analyse und Interpretation

# Das Gesamtnetzwerk

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE)
library(igraph)
```

```{r Gesamtnetzwerk erstellen, include=FALSE}
edges <- read.csv("https://raw.githubusercontent.com/gllnxr/Stuttgart21/main/edges.csv", header=T, as.is=T, sep = ",")
nodes <- read.csv("https://raw.githubusercontent.com/gllnxr/Stuttgart21/main/nodes.csv", header=T, as.is=T, sep = ",")

edges$analysis_weight_strong <- edges$weight == 2

edges$analysis_relationship_strong <- edges$relationship == 2

  # edgematrix erstellen
edgematrix <- as.matrix(edges)

  # Teil des WorkArounds: Hinzufügen eines neuen Merkmals

nodes$analysis_test <- nodes$type == 1

  # igraph-Objekt erstellen
s21 <- graph_from_data_frame(d=edgematrix, vertices=nodes, directed = F)

s21

  # Benötigt man für die Degreeberechnungen: Neues Netzwerk ohne den Projekt-GmbHs
without_project_gmbh1 <- delete_vertices(s21, V(s21)[name_short == "Projekt GmbH S21"])
without_project_gmbh2 <- delete_vertices(without_project_gmbh1, V(without_project_gmbh1)[name_short == "ProjektBau GmbH"])
without_project_gmbh3 <- delete_vertices(without_project_gmbh2, V(without_project_gmbh2)[name_short == "Projekt Stuttgart-Ulm GmbH"])
```

Das Gesamtnetzwerk s21 umfasst 106 Knoten und 176 Beziehungen (siehe
iGraph-Objekt s21). Es ist ungerichtet und gewichtet.

```{r Komponenten und Simplifizierung, echo=TRUE}

s21

# Parameter zur Beschreibung des Gesamtnetzwerks

## Ist das Netzwerk bereits vereinfacht?
is.simple(s21)

## Hängt das Netzwerk zusammen?
is.connected(s21)

## Aus wievielen Komponenten besteht das Netzwerk?
count_components(s21)

## Dichte des Netzwerks
edge_density(s21, loops = F)

## Umfang des Netzwerks
diameter(s21)

## Pfaddistanzen
farthest_vertices(s21)
```

Das Gesamtnetzwerk liegt bereits vereinfacht vor und besteht aus genau
einer Hauptkomponente. Erhoben wurden sowohl natürliche Personen als
auch Organisationen. Es handelt sich bei dem Netzwerk s21 daher um ein
Two-Mode-Netzwerk. Im Netzwerk wurden 34 Organisationen, sowie 72
natürliche Personen erhoben. Das Gesamtnetzwerk weist eine Kantendichte
von `r edge_density(s21)*100` Prozent auf und hat einen Umfang von
`r diameter(s21)`. Die maximale Pfaddistanz im Gesamtnetzwerk besteht
zwischen den Knoten 26 (David McAllister) und 43 (Deutscher Sparkassen-
& Giroverband) mit einer Pfaddistanz von 15 Schritten.

```{r two-mode anzahl men, include=FALSE}
## Two-Mode: Anzahl an Männern, Frauen, Organisationen
# Frauen
subset_nodes_females_s21 <- V(s21)[sex == 2 & analysis_test]
females_s21 <- induced_subgraph(s21, subset_nodes_females_s21)

females_s21

# Männer
subset_nodes_males_s21 <- V(s21)[sex == 1 & analysis_test]
males_s21 <- induced_subgraph(s21, subset_nodes_males_s21)

males_s21

# Organisationen
subset_nodes_type_2_s21 <- V(s21)[type == 2]
type_2_s21 <- induced.subgraph(s21, subset_nodes_type_2_s21)

type_2_s21

```

Als grundlegendes Attribut in der Node-List wurde bei allen natürlichen
Personen das der Öffentlichkeit bekannte Geschlecht zugeschrieben. Dabei
stellte sich heraus, dass im Datensatz s21 genau neun weibliche
Akteurinnen und 63 männliche Akteure erhoben wurden. Der Vollständigkeit
halber wurde auch die Zuordnung "divers" im Codebuch aufgenommen, jedoch
ist keine\*r der erhobenen natürlichen Personen der Recherche nach hier
einzuordnen. So bleiben 34 erhobene Organisationen, im Netzwerk s21 mit
"type == 2" kodiert.

Das Gesamtnetzwerk liegt bereits vereinfacht vor und besteht aus genau
einer Hauptkomponente. Erhoben wurden sowohl natürliche Personen als
auch Organisationen. Es handelt sich bei dem Netzwerk s21 daher um ein
Two-Mode-Netzwerk. Im Netzwerk wurden 34 Organisationen, sowie 72
natürliche Personen erhoben.

Im Folgenden soll das Gesamtnetzwerk visualisiert werden. In der
Visualisierung werden einzelne Knoten des Gesamtnetzwerks umgeformt:
Natürliche Personen erhalten einen runden Node, Organisationen erhalten
ein quadratisches Node. Die Größe der Nodes varriiert abhängig von ihrem
jeweiligen Degree-Wert.

```{r Visualisierung Gesamtnetzwerk s21, echo=FALSE, fig.height=20, fig.width=35}
# Visualisierungsparameter
V(s21)[V(s21)$type == 1]$shape <- "circle"
V(s21)[V(s21)$type == 2]$shape <- "square"

  # nachfolgender Befehl errechnet den degreewert aller nodes in einen neuen datensatz "degree_option", dadurch kann man im plot Befehl dann die Größe der Nodes abhängig von ihrem degreewert machen!
degree_option <- degree(s21, mode="all")

plot(s21,
     asp=0,
     layout=layout_with_kk,
     edge.arrow.size=.3,
     vertex.size = degree_option*0.25,
     vertex.label.cex=1,
     main = "Netzwerk der beteiligten Personen und Organisationen und deren Beziehungen zum Bauprojekt Stuttgart 21",
     sub = "n=106; Die Größe der Knoten ist abhängig von ihren jeweiligen Degreewerten; Datenerhebung erfolgte durch Louis G, Sinan K, Mia M, David V")
```

[Fig. 1: Visualisierung des Gesamtnetzwerks]{.smallcaps} *s21*

## Analyse der Teilnetzwerke

Im nachfolgenden Abschnitt wird sich den einzelnen Teilnetzwerken des
Gesamtnetzwerks zugewandt. Beginnend mit den Teilnetzwerken der
Geschlechter wird sich nachfolgend mit den unterschiedlichen Branchen
der Organisationen beschäftigt, darüber hinaus wird die Rolle von
Politiker\*innen genauer betrachtet.

### Nach Node-Attributen

Beginnend mit den Node-Attributen Geschlecht (sex), Branche (branche),
Partei (party), Politiker\*in (politician) und Typ (type) werden
Teilnetzwerke nach Node-Attributen gebildet. Die Attribute Geschlecht,
Partei, Politiker\*in wurden nur für natürliche Personen erhoben, das
Attribut Branche nur bei Organisationen, da der Wechsel zwischen den
verschiedenen Branchen bei natürlichen Personen schwer zu greifen ist:
Die Branchenzugehörigkeit vieler erhobenen natürlichen Personen hat sich
während der Laufzeit von Stuttgart 21 mehrmals geändert.

#### Geschlecht

Wie bereits festgestellt besteht das Netzwerk des Datensatzes s21
überwiegend aus Männern. Im Folgenden soll ein Vergleich zwischen dem
Teilnetzwerk der Männer im Datensatz s21 und dem der Frauen vollzogen
werden. Dafür unterteilen wir den Datensatz zunächst in natürliche
Personen und Organisationen, betrachten hier lediglich Erstere und
nutzen Filterbefehle (wie "induced_subgraph"), die alle Frauen und alle
Männer ihren eigenen neuen Datensätze zuweisen.

```{r Teilnetzwerk Geschlechter, include=FALSE}

# Männer
isolated_males_s21 <- which(degree(males_s21)==0)
connected_males_s21 <- delete_vertices(males_s21, isolated_males_s21)

# Frauen

subset_nodes_females_s21 <- V(s21)[sex == 2 & analysis_test]
females_s21 <- induced_subgraph(s21, subset_nodes_females_s21)

isolated_females_s21 <- which(degree(females_s21)==0)
connected_females_s21 <- delete_vertices(females_s21, isolated_females_s21)
```

##### Männer im Gesamtnetzwerk s21

```{r Analyse Teilnetzwerk connected_males_s21, include=FALSE}

components(connected_males_s21)

components(connected_males_s21)$no

connected_males_comp <- decompose.graph(connected_males_s21)

connected_males_comp1 <- connected_males_comp[[1]]
connected_males_comp2 <- connected_males_comp[[2]]
connected_males_comp3 <- connected_males_comp[[3]]

# Dichte Komponente 1
density_connected_males_s21_comp1 <- edge_density(connected_males_comp1, loops = FALSE)
density_connected_males_s21_comp1

# Dichte Komponente 2
density_connected_males_s21_comp2 <- edge_density(connected_males_comp2, loops = FALSE)
density_connected_males_s21_comp2

# Dichte Komponente 3
density_connected_males_s21_comp3 <- edge_density(connected_males_comp3, loops = FALSE)
density_connected_males_s21_comp3
```

Da sich in males_s21, dem Teilnetzwerk aller erhobenen Männer in s21
noch viele Knoten ohne jeglicher Verbindungen zu anderen Männern finden
lassen, wird in einem Unterschritt jeder Knoten im Männer-Teilnetzwerk
mit einem Degree-Wert von 0 gelöscht und es wird ein neues Teilnetzwerk
connected_males_s21 gebildet. Isolates, also nicht verbundene Männer
sind nun nicht mehr im Teilnetzwerk connected_males_s21 vorzufinden. So
fällt die Anzahl der Knoten im Teilnetzwerk der Männer von 63 auf 37.

Das Teilnetzwerk aller untereinander verbundenen Männer in s21 verfügt
über `r components(connected_males_s21)$no` Komponenten, welche die
folgende Anzahl an zugehörigen Knoten haben:
`r components(connected_males_s21)$csize`. Der größten Komponente [1]
gehören also 32 Knoten an. Diese beinhaltet unter anderem die Knoten 54
(Wolfgang Schuster) und 58 (Heinrich Geißler), welche zu späterem
Zeitpunkt in diesem Forschungsbericht noch einmal genauer betrachtet
werden sollen. Die beiden anderen Komponenten verfügen nur über zwei,
beziehungsweise drei Knoten.

Die erste Komponente weist eine Kantendichte von
`r density_connected_males_s21_comp1*100` Prozent auf. Die zweite
Komponente besteht aus zwei Knoten die eine Verbindung zueinander haben,
daher liegt hier die Kantendichte selbstverständlich bei
`r density_connected_males_s21_comp2*100` Prozent. Die dritte und
letztgenannte Komponente verfügt über drei Knoten, bei denen eine
Verbindung lediglich über Knoten 106 (Fritz Kuhn) möglich ist. Daher
liegt die Kantendichte der dritten Komponente bei zwei Dritteln, also
`r density_connected_males_s21_comp3*100` Prozent.

##### Frauen im Gesamtnetzwerk s21

Bei der Analyse des Teilnetzwerks der Frauen females_s21 zeigte sich,
dass hier ein Löschen der Isolates keinen Sinn ergab: Löschte man alle
Isolates in females_s21 blieben keinerlei Knoten zurück. Es gibt also
keinerlei direkte Verbindungen zwischen den erhobenen Frauen im
Datensatz s21. Dies ist im Vergleich zu den erhobenen Männern eine erste
Auffälligkeit, die hier klar genannt werden kann. Daher wird in der
nachfolgenden Visualisierung der neue Datensatz der females_s21 genutzt.
Der Datensatz females_s21 beinhaltet alle neun weiblichen und
natürlichen Personen, die im Datensatz s21 erhoben wurden. Die Knoten
Teilnetzwerk females_s21 sind über keinerlei direkte Beziehungen
verbunden. Eine Kantendichte von
`r edge_density(females_s21, loops=FALSE)*100` Prozent ist hier die
logische Folge.

##### Visualisierung der Teilnetzwerke Männer und Frauen

Die neuen Teilnetzwerke connected_males_s21 und females_s21 werden nun
nebeneinander visualisiert, um kurz auf die Unterschiede der
Vernetzungen zwischen Männern und Frauen im Gesamtnetzwerk s21 eingehen
zu können.

```{r Visualisierung Teilnetzwerk Geschlecht, echo=FALSE, fig.height=6, fig.width=9}

# Visualisierung

par(mfrow=c(1,2), mar=c(1,2,2,2))

plot(connected_males_s21, 
     layout=layout_with_kk,
     edge.arrow.size=.5,
     edge.color="black",
     vertex.color="lightblue",
     vertex.frame.color=NA,
     vertex.label.cex=.8,
     vertex.size=10,
     main="Verbundene Männer",
     sub="n=37")

plot(females_s21, 
     layout=layout_with_kk,
     edge.arrow.size=.5,
     edge.color="black",
     vertex.color="magenta",
     vertex.frame.color=NA,
     vertex.label.cex=.8,
     vertex.size=10,
     main="Frauen",
     sub="n=9")
```

[Fig. 2: Visualisierung]{.smallcaps} *connected_males_s21*
[und]{.smallcaps} *females_s21*

Auffällig ist hier die Menge an realisierten Verbindungen der Männer im
Vergleich zu den realisierten Verbindungen der Frauen untereinander:
Während die Männer drei Komponenten bilden und in ihrer größten
Komponente immerhin eine Kantendichte von
`r density_connected_males_s21_comp1*100` Prozent aufweisen können,
bestehen bei den erhobenen Frauen im Gesamtnetzwerk s21 keinerlei
direkte Verbindungen. Dies ist auch in der Visualisierung in Fig. 2 gut
zu beobachten. Aus dieser Beobachtung lässt sich schlussfolgern, dass in
dem Gesamtnetzwerk s21 Entscheidungen immer auch über Männer laufen
mussten, Frauen konnten untereinander keine Absprachen treffen,
Entscheidungen trafen also mindestens Frauen und Männer gemeinsam. Die
Anzahl an beteiligten Männern lässt jedoch vermuten, dass Absprachen und
Entscheidungen wohl oft auch ohne Frauen getroffen wurden.

#### Branchen

Folgend soll sich den Organisationen im Gesamtnetzwerk s21 angenommen
werden. Dafür unterteilen wir den Datensatz s21 mit Hilfe des
Filter-Befehls delete_vertices auf Grundlage der festgehaltenen
Ausprägungen beim Attribut type. Für die Organisationen nutzen wir
lediglich alle Knoten mit der Ausprägung 2 beim Node-Attribut type. Das
neue Teilnetzwerk aller an S21 beteiligten Organisationen wird somit als
"type2_s21" benannt. Damit aber lediglich die direkt untereinander
verbundenen Organisationen analysiert werden

```{r Teilnetzwerk Branche, include=FALSE}
# Erstellen des Teilnetzwerks type2_s21
type2_s21 <- delete_vertices(s21, V(s21)[type != 2])
type2_s21

# Isolates löschen
connected_type2_s21 <- delete_vertices(type2_s21, V(type2_s21)[degree(type2_s21)==0])

# Komponenten
components(connected_type2_s21)
```

```{r Visualisierung Organisationen mit Isolates, echo=FALSE, fig.height=14, fig.width=25}
# Visualisierungsparameter für type2_s21

V(type2_s21)[V(type2_s21)$branche == 0]$color <- "white"
V(type2_s21)[V(type2_s21)$branche == 1]$color <- "#EC0016"
V(type2_s21)[V(type2_s21)$branche == 2]$color <- "#FF8800"
V(type2_s21)[V(type2_s21)$branche == 3]$color <- "grey90"
V(type2_s21)[V(type2_s21)$branche == 4]$color <- "lightgreen"
V(type2_s21)[V(type2_s21)$branche == 5]$color <- "grey70"
V(type2_s21)[V(type2_s21)$branche == 6]$color <- "#E11584"
V(type2_s21)[V(type2_s21)$branche == 7]$color <- "#964B00"
V(type2_s21)[V(type2_s21)$branche == 8]$color <- "lightblue"
V(type2_s21)[V(type2_s21)$branche == 9]$color <- "yellow"
V(type2_s21)[V(type2_s21)$type == 1]$shape <- "circle"
V(type2_s21)[V(type2_s21)$type == 2]$shape <- "square"

# Visualisierung
plot(type2_s21,
     layout = layout_with_kk,
     main = "Alle an Stuttgart 21 beteiligte Organisationen",
     sub = "n=34, Eingefärbt nach Branchenzugehörigkeit: rot = DB-Assoziiert, orange = Unternehmen der Infrastruktur, hellgrau = Gewerkschaften und Verbände, hellgrün = Parteien, Ministerien und Kommissionen, dunkelgrau = Wissenschaftliche Institute, pink = Veranstalter, braun = Finanzwesen, hellblau = Immobilien, gelb = Städte")
```

[Fig. 3: Visualisierung]{.smallcaps} *type2_s21*

In Figur 3 kann klar erkannt werden, dass beim Projekt Stuttgart 21
nicht nur Organisationen der Infrastruktur (orange eingefärbt), sondern
auch viele weitere Branchen beteiligt waren. So werden mehrere
Ministerien und Kommissionen abgebildet, die die Beteiligung der Politik
an dem Großprojekt darlegen. Ähnlich können auch die gelben Knoten der
Stadt Ulm und der Stadt Stuttgart verstanden werden. Als klassisches
Bahnprojekt ist natürlich auch die Deutsche Bahn AG (rot) mit ihren
verschiedenen Projektbau-GmbHs beteiligt. Das Geld für solch ein großes
Projekt muss natürlich auch von irgendwoher kommen, kein Wunder ist es
also, dass auch vier Organisationen der Finanzbranche (braun) ihren Weg
in das Teilnetzwerk gefunden haben, auch wenn diese nur als Isolates
abgebildet sind.

```{r Visualisierung Organisationen ohne Isolates, echo=FALSE, fig.height=14, fig.width=25}
# Visualisierungsparameter für connected_type2_s21

V(connected_type2_s21)[V(connected_type2_s21)$branche == 0]$color <- "white"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 1]$color <- "#EC0016"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 2]$color <- "#FF8800"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 3]$color <- "grey90"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 4]$color <- "lightgreen"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 5]$color <- "grey70"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 6]$color <- "#E11584"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 7]$color <- "#964B00"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 8]$color <- "lightblue"
V(connected_type2_s21)[V(connected_type2_s21)$branche == 9]$color <- "yellow"
V(connected_type2_s21)[V(connected_type2_s21)$type == 1]$shape <- "circle"
V(connected_type2_s21)[V(connected_type2_s21)$type == 2]$shape <- "square"

# Visualisierung
plot(connected_type2_s21,
     layout = layout_with_kk,
     main = "An Stuttgart 21 beteiligte Organisationen (ohne Isolates)",
     sub = "n=23, Eingefärbt nach Branchenzugehörigkeit: rot = DB-Assoziiert, orange = Unternehmen der Infrastruktur, hellgrau = Gewerkschaften und Verbände, hellgrün = Parteien, Ministerien und Kommissionen, dunkelgrau = Wissenschaftliche Institute, pink = Veranstalter, braun = Finanzwesen, hellblau = Immobilien, gelb = Städte")
```

[Fig. 4: Visualisierung]{.smallcaps} *connected_type2_s21*

Zwecks einer besseren Darstellung werden in Figur 4 nunmehr solche an
Stuttgart 21 beteiligten Organisationen dargestellt, die direkt
miteinander verbunden sind. Auffällig an der Visualisierung sind dabei
folgende Punkte: Natürlich treffen am Knoten 1 (DB Projekt Stuttgart Ulm
GmbH) sehr viele Unternehmen der Infrastruktur (hier orange eingefärbt)
zusammen, es handelt sich eben um ein Bauprojekt, an dem viele
Organisationen der Infrastrukturbranche beteiligt sind und waren. Die
Stadt Stuttgart war am Projekt natürlich ebenso beteiligt, wie auch die
Stadt Ulm (beide gelb): Sie beide verbindet die neue Schnellstrecke
Stuttgart-Wendlingen-Ulm, die ein essenzieller Bestandteil von S21 ist.

Darüber hinaus ist der Knoten des Instituts für Verkehrswissenschaften
Stuttgart auffällig: Er ist sowohl mit dem Knoten der Projekt-GmbH als
auch mit dem der Deutschen Bahn AG verbunden. Das Institut der
Universität Stuttgart hatte in der Bau- und Planungszeit von S21 im
Auftrag der DBAG und der Projekt-GmbH mehrere Berichte zur Machbarkeit
und verschiedenen Kennzahlen zum neuen Bahnhof (wie Züge pro Gleis)
angefertigt.

Darüber hinaus weist das Teilnetzwerk connected_type2_s21 auch
`r components(connected_type2_s21)$no` verschiedene Komponenten auf: die
erste Komponente [1] umfasst 21 Knoten, also alle, bis auf zwei. Diese
beiden anderen Knoten kommen in der zweiten Komponente [2] unter. Sie
verbindet eine ganz eigene Geschichte, die jedoch zum Narrativ der
nicht-endenden Verbindungen bei Stuttgart 21 passen: Der
Baden-Württembergische Sparkassenverband war lange Zeit Gesellschafter
der Oettinger Gruppe GmbH, einer Unternehmens-Beratungsesellschaft aus
Ditzingen. Der Präsident des Verbands Peter Schneider war zudem
Vorsitzender des Beirats der Oettinger Gruppe. Und auch der ehemalige
Ministerpräsident Baden-Württembergs Günther Oettinger war zeitweise
Halter von 25% der Aktien der Oettinger Gruppe GmbH. Günther Oettinger
hatte zu seiner Zeit Ministerpräsident von Baden-Württemberg (2005 bis
2010) das Bahnprojekt S21 tatkräftig unterstützt. Er war nach seiner
Zeit als Ministerpräsident darüber hinaus im Aufsichtsrat bei der
Baufirma Herrenknecht (in Figur 4 in orange abgebildet). Ihm widmet sich
ein eigener Abschnitt dieses Forschungsberichts.

### Kombination von Node-Attributen

#### Politiker\*innen und ihre Parteizugehörigkeit

```{r Teilnetzwerk Politiker*innen, include=FALSE}
politicians_s21 <- delete_vertices(s21, V(s21)[politician == FALSE])

# Teilnetzwerk verbundener Politiker:innen erstellen

isolated_politicians_s21 <- which(degree(politicians_s21)==0)
connected_politicians_s21 <- delete_vertices(politicians_s21, isolated_politicians_s21)
```

Mit insgesamt 47 Knoten im Netzwerk des Datensatzes s21 sind
Politiker\*innen als maßgebliche Akteure präsent und stellen einen
beachtlichen Anteil im Gesamtnetzwerk dar. Im weiteren Verlauf soll
daher ein Teilnetzwerk aller Politiker\*innen erstellt und analysiert
werden. Auch hier unterteilen wir den Datensatz zunächst in natürliche
Personen und Organisationen, wobei ausschließlich Erstere betrachtet
werden. Filterbefehle wie "delete_vertices" weisen alle Politiker\*innen
ihrem eigenen Datensatz zu.

Da im Teilnetzwerk der Politiker\*innen, auch bekannt als
politicians_s21, viele Knoten ohne Verbindungen zu anderen
Politiker\*innen aufgeführt sind, werden in einem Zwischenschritt alle
Knoten mit einem Degree-Wert von 0 gelöscht. Daraus entsteht ein neues
Teilnetzwerk connected_politicians_s21 gebildet, in dem keine Isolates
mehr zu finden sind. So fällt die Anzahl der Knoten im Teilnetzwerk der
Politiker\*innen von 47 auf 36.

Vergleicht man die Edge Density des Gesamtnetzwerks s21
(`r edge_density(s21)*100` Prozent) mit der des Teilnetzwerks
connected_politicians_s21
(`r edge_density(connected_politicians_s21)*100` Prozent), fällt auf,
dass die Kantendichte des Teilnetzwerks deutlich höher ist. Das könnte
darauf hindeuten, dass die im Teilnetzwerk connected_politicians_s21
betrachteten Politiker\*innen engere Verbindungen aufgrund gemeinsamer
Interessen und eines ähnlichen Fokus auf Themen rund um das Projekt
Stuttgart 21 haben.

Mithilfe der Funktionen "degree()" und "which.max()" konnten wir im
Teilnetzwerk connected_politicians_s21 den Politiker identifizieren, der
die meisten Verbindungen zu anderen Politiker\*innen aufweist: Es ist
Heinrich Geißler. Das Mitglied der CDU hat durch eine Kantendichte von
13 die höchste Anzahl an Verbindungen in diesem Teilnetzwerk. Dies ist
auf seine Rolle als "Mittler" in den Schlichtungsgesprächen von
Stuttgart 21 zurückzuführen, bei denen, neben ihm, noch viele weitere
Politiker\*innen beteiligt waren.

Im nächsten Schritt wurden die Knoten der Politiker\*innen in der Farbe
ihrer Partei eingefärbt. Dementsprechend werden CDU-Politiker\*innen in
hellblau, FDP-Politiker\*innen in gelb, Politiker\*innen der Grünen in
hellgrün, SPD-Politiker\*innen in rot und SÖS-Politiker\*innen in grau
visualisiert.

Das neue Teilnetzwerk connected_politicians_s21 wird nun visualisiert,
um eventuelle Auffälligkeiten in der Vernetzung darzustellen.

```{r Analysen Teilnetzwerk Politiker*innen, include=FALSE}
# Edge Density berechnen
edge_density(s21)
edge_density(connected_politicians_s21)

# Knoten mit dem höchsten Degree-Wert berechnen

connected_politicians_s21_deg <- degree(connected_politicians_s21, mode = "total")
which.max(connected_politicians_s21_deg)

# Komponentenanalyse
components(politicians_s21)
components(connected_politicians_s21)
```

```{r Visualisierung Teilnetzwerk verbundener Politiker*innen, echo=FALSE, fig.height=10, fig.width=30}

# Visualisierungsparameter connected_politicians_s21 / Einfärben nach Parteizugehörigkeit
V(connected_politicians_s21)[V(connected_politicians_s21)$party == "CDU"]$color <- "lightblue"
V(connected_politicians_s21)[V(connected_politicians_s21)$party == "FDP"]$color <- "yellow"
V(connected_politicians_s21)[V(connected_politicians_s21)$party == "GRUENE"]$color <- "lightgreen"
V(connected_politicians_s21)[V(connected_politicians_s21)$party == "SÖS"]$color <- "grey80"
V(connected_politicians_s21)[V(connected_politicians_s21)$party == "SPD"]$color <- "red"
V(connected_politicians_s21)[V(connected_politicians_s21)$type == 1]$shape <- "circle"
V(connected_politicians_s21)[V(connected_politicians_s21)$type == 2]$shape <- "square"

# Visualisierung
plot(connected_politicians_s21,
     layout = layout_with_kk,
     vertex.size = 5,
     main = "Politiker*innen im Datensatz s21 (ohne Isolates)",
     sub = "n=36, Eingefärbt nach Parteizugehörigkeit: Rot = SPD, Grün = Bündnis 90/ Die Grünen, Hellblau = CDU, Gelb = FDP, Grau = SÖS")
```

[Fig. 5: Visualisierung]{.smallcaps} *connected_politicians_s21*

Auffällig ist hier die Menge an realisierten Verbindungen der
Politiker:innen untereinander sowie die verschiedenen Komponenten: Das
Teilnetzwerk besteht aus insgesamt 36 Knoten, wobei 27 davon der größten
"Komponente 1" angehören. Die drei anderen Komponenten sind deutlich
kleiner und umfassen lediglich zwei bis vier Knoten. Das Teilnetzwerk
der Politiker:innen besteht aus 18 CDU-Politiker:innen, 7
SPD-Politiker:innen, 6 Politiker:innen der Grünen, 3 FDP-Politiker:innen
und 2 SÖS-Politiker:innen.

#### CDU-Politiker\*innen

Da die CDU-Politiker:innen fast 50% aller Politiker\*innen im
Gesamtnetzwerk des Datensatzes s21 ausmachen, soll im nächsten Schritt
ein Teilnetzwerk ausschließlich für CDU-Politiker\*innen erstellt und
analysiert werden. Hier unterteilen wir wieder den Datensatz zunächst in
natürliche Personen und Organisationen, wobei ausschließlich Erstere
betrachtet werden. Mithilfe von Filterbefehlen wie "induced_subgraph"
werden alle CDU-Politiker\*innen ihrem eigenen Datensatz zugeordnet.
Auch im Teilnetzwerk der CDU-Politiker\*innen, cdu_politicians_s21,
finden sich ein paar Knoten ohne Verbindungen zu anderen
CDU-Politiker\*innen. Diese Isolates werden bewusst nicht entfernt, um
präzisere Rückschlüsse aus der Struktur der CDU-Politiker\*innen zu
ziehen. Damit enthält dieses Teilnetzwerk 23 CDU-Politiker\*innen von
insgesamt 47 Politiker\*innen im Gesamtnetzwerk. Auch in diesem
Teilnetzwerk wurden die Knoten hellblau eingefärbt, um ihre
Zugehörigkeit zur CDU zu verdeutlichen. Als Mitglied der CDU konnte auch
in diesem Netzwerk Heinrich Geißler als Knoten mit den meisten
Verbindungen identifiziert werden. Ihm wird eine sogenannte
"Broker"-Funktion zuteil, weil er eine Schlüsselrolle bei der
Vermittlung von Verbindungen zu anderen Knoten trägt.

Das neue Teilnetzwerk cdu_politicians_s21 wird nun visualisiert, um
eventuelle Auffälligkeiten in der Vernetzung darzustellen.

```{r CDU-Politiker*innen, include=FALSE}

# Teilnetzwerk CDU-Politiker:innen erstellen
# Das Node-Attribut analysis_test wurde zu Beginn im ersten Chunk erstellt, um einen Fehler in der Verwendung von delete.vertices zu Umgehen. Eine Anleitung, wie dieser Workaround konzipiert wurde, findet sich auch im GitHub-Verzeichnis vom User gllnxr (siehe Seite 1).

subset_nodes_cdu_politicians_s21 <- V(s21)[politician == TRUE & party == "CDU" & analysis_test]

cdu_politicians_s21 <- induced_subgraph(s21, subset_nodes_cdu_politicians_s21) 

components(cdu_politicians_s21)
```

```{r Politiker*innen aufgeteilt nach Parteizugehörigkeit, include=FALSE}
# SPD
subset_nodes_spd_politicians_s21 <- V(s21)[politician == TRUE & party == "SPD" & analysis_test]

spd_politicians_s21 <- induced_subgraph(s21, subset_nodes_spd_politicians_s21)

# Grüne
subset_nodes_green_politicians_s21 <- V(s21)[politician == TRUE & party == "GRUENE" & analysis_test]

green_politicians_s21 <- induced_subgraph(s21, subset_nodes_green_politicians_s21)

# FDP
subset_nodes_fdp_politicians_s21 <- V(s21)[politician == TRUE & party == "FDP" & analysis_test]

fdp_politicians_s21 <- induced_subgraph(s21, subset_nodes_fdp_politicians_s21)

# SÖS
subset_nodes_soes_politicians_s21 <- V(s21)[politician == TRUE & party == "SÖS" & analysis_test]

soes_politicians_s21 <- induced_subgraph(s21, subset_nodes_soes_politicians_s21)
```

```{r CDU-Politiker*innen Visualisierung, echo=FALSE, fig.width=25}
# Visualisierung Teilnetzwerk CDU-Politiker:innen

plot(cdu_politicians_s21, layout=layout_with_kk,
     edge.arrow.size=.5,
     vertex.frame.color=NA,
     vertex.label.cex=.5,
     vertex.size=14,
     vertex.color = "lightblue",
     main="CDU-Politiker*innen beteiligt an S21")
```

[Fig. 6: Visualisierung]{.smallcaps} *cdu_politicians_s21*

Wie bereits im Teilnetzwerk connected_politicians_s21 zu erkennen war,
halten sich die meisten CDU-Politiker:innen (12 Knoten von 23) in der
größten "Komponente 1" auf. Außerdem machen die CDU-Politiker:innen zwei
der drei kleineren Komponenten im Teilnetzwerk connected_politicians_s21
(s. Figur 6) aus, eine aus zwei Knoten, die andere aus vier Knoten
bestehend. Neben diesen Verbindungen befinden sich insgesamt fünf
Isolates im Teilnetzwerk der CDU-Politiker:innen.

### Kombination von Edge- und Node-Attributen

#### Die Mächtigen mit einer besonderen Beziehung

Der Begriff der Macht ist zweifelsohne fest mit Politik verbunden. Ein
politisches System funktioniert schwer ohne (vom Volk ernannten)
Machthabenden. Max Weber definiert Macht dabei als "jede Chance,
innerhalb einer sozialen Beziehung den eigenen Willen auch gegen
Widerstreben durchzusetzen, gleichviel worauf diese Chance beruht"
(Nohlen & Grotz, 2015, S. 365). Mächtig sind also solche Personen, die
den eigenen Willen auch gegen Widerstreben anderer Machthabenden
durchsetzen können.

Der Begriff der Hierarchie baut auf Webers Definition der Macht auf und
"bezeichnet ein System der Über- und Unterordnung oder Rangordnung"
(Schubert & Klein, 2018). Im Datensatz s21 wurden Beziehungen zwischen
Akteur\*innen auch auf ihre Machtpositionen hin untersucht. Ihre
Position in der politischen oder wirtschaftlichen Hierarchie, und damit
verbunden ihre Entscheidungsmacht in Bezug auf das Bauprojekt Stuttgart
sind also ausschlaggebend für ihre Kodierung im Edge-Attribut 'weight'.

Im Datensatz s21 wurden Kantenstärken zwischen zwei Akteur\*innen mit
dem Edge-Attribut 'weight' festgelegt. Eine Kantenstärke kodiert als '2'
steht dabei für eine vertrautere Beziehung zwischen den Akteur\*innen --
Eine Kantenstärke von '1' demnach für eine weniger vertraute, etwa
flüchtige Beziehung zwischen zwei Akteur\*innen. Außer Acht wurde dabei
eine Richtung der Beziehung gelassen, das Netzwerk ist daher
ungerichtet.

In der Datenerhebung wurden über das Edge-Attribut hinaus die Arten der
Beziehungen erhoben. Dabei wurde zwischen solchen Beziehungen die rein
geschäftlich bestanden und solchen, die mehr als geschäftlich sind
unterschieden. Letztere Beziehungsart wurde erst dann erhoben, wenn
mindestens zwei unabhängige Quellen dies bestätigten. Das Edge-Attribut
'relationship' gibt daher in '1' geschäftliche Beziehung und '2' mehr
als geschäftliche Beziehung darüber Auskunft, welche Art von Beziehungen
zwei Akteur\*innen zueinander haben. Sollten zwei Akteur\*innen sowohl
eine geschäftliche als auch eine mehr als geschäftliche Beziehung
zueinander haben, wurde, nach eingehender Prüfung eine Ausprägung von
'2' im Edge-Attribut 'relationship' notiert. Eine Beziehung, welche den
Quellen zufolge mehr als geschäftlich ist, beschreibt hier etwa eine
Freundschaft, tiefergehende geschäftliche Beziehungen etwa im gleichen
Unternehmen, oder jede andere Beziehung, die über die geschäftlichen
Grenzen hinaus geht.

Im weiteren Verlauf soll daher ein Teilnetzwerk aller Akteur\*innen
erstellt und analysiert werden, die eine solche Verbindung zueinander
vorzuweisen haben. Durch den Befehl "E(s21)[weight == 2 & relationship
== 2]" haben wir alle Kanten extrahiert, die diese Kriterien erfüllen.
Anschließend wurde mit subgraph.edges(s21,
subset_nodes_friendly_strong_s21) ein Teilnetzwerk "friendly_strong_s21"
erstellt, das nur diese ausgewählten Kanten enthält.

Auch in diesem Teilnetzwerk wurden die Knoten nach Partei eingefärbt, um
eventuelle Korrelationen zwischen der Parteizugehörigkeit und der Art
der Beziehung feststellen zu können.

```{r weight 2, include=FALSE}

# Teilnetzwerk weight 2 & relation 2 erstellen
subset_nodes_friendly_strong_s21 <- E(s21)[weight == 2 & relationship == 2]
friendly_strong_s21 <- subgraph.edges(s21, subset_nodes_friendly_strong_s21)

# Komponenten analysieren
components(friendly_strong_s21)
```

```{r weight 2 Visualisierung, echo=FALSE, fig.height=4, fig.width=9}
# Visualisierungsparameter friendly_strong_s21 / Einfärben nach Parteizugehörigkeit
V(friendly_strong_s21)[V(friendly_strong_s21)$party == "CDU"]$color <- "lightblue"
V(friendly_strong_s21)[V(friendly_strong_s21)$party == "FDP"]$color <- "yellow"
V(friendly_strong_s21)[V(friendly_strong_s21)$party == "GRUENE"]$color <- "lightgreen"
V(friendly_strong_s21)[V(friendly_strong_s21)$party == "SÖS"]$color <- "grey80"
V(friendly_strong_s21)[V(friendly_strong_s21)$party == "SPD"]$color <- "red"
V(friendly_strong_s21)[V(friendly_strong_s21)$type == 1]$shape <- "circle"
V(friendly_strong_s21)[V(friendly_strong_s21)$type == 2]$shape <- "square"

plot(friendly_strong_s21,
     layout=layout_with_kk,
     edge.arrow.size=.5,
     vertex.frame.color=NA,
     vertex.label.cex=.5,
     vertex.size=15,
     main="Mächtige, über eine geschäftliche Beziehung hinausgehende Verbindungen")
```

[Fig. 7: Visualisierung]{.smallcaps} *friendly_strong_s21*

Im Gesamtnetzwerk gibt es nicht viele solcher Verbindungen: Das
Teilnetzwerk besteht aus zwei Komponenten, die eine aus fünf Knoten, die
andere aus zwei Knoten bestehend. Auffällig ist hierbei die Tatsache,
dass das Teilnetzwerk mit der Ausnahme eines Akteurs nur aus männlichen
Politikern besteht: Die große Komponente enthält vier CDU-Politiker
"Martin Herrenknecht", "Wolfgang Schuster", "Günther Oettinger" und
"Lothar Späth". Eine weitere Verbindung zu "Rudolf Häussler", der im
Kommunikationsbeirat von S21 tätig war, wird durch die zwei zuletzt
genannten Politiker hergestellt. Eine weitere solche Verbindung besteht
zwischen GRÜNE-Politiker "Werner Wölfle" und SÖS-Politiker "Gangolf
Stocker".

## Analyse des Gesamtnetzwerks

### Komponenten

```{r Komponenten des Gesamtnetzwerks, include=FALSE}

components(s21)
```

Das Gesamtnetzwerk s21 besteht aus genau einer Komponente. Dies liegt an
der Art der Datenerhebung: Es wurden nur solche Knoten erhoben, denen
eine Verbindung mit anderen bestehenden Knoten im Datensatz nachgewiesen
werden konnte. Die Hauptkomponente 1 besteht daher aus genau
`r components(s21)$csize` Knoten.

### Cluster

Die nachfolgende Cluster-Walktrap-Analyse des Gesamtnetzwerks s21 zeigt
die verschiedenen Untergruppen (auch Communities genannt) der
Hauptkomponenten 1 visuell auf. Dabei berechnet der Befehl
cluster_walktrap die Wahrscheinlichkeit, dass verschiedene Knoten eng
zusammenhängen. Die Cluster-Walktrap-Methode berechnet dies aus der
Bildung von zufälligen Pfaden jedes Knotens, kürzere Wege führen so zu
einem gemeinsamen Cluster. Diese Cluster können auch überlappen.

```{r Cluster-Walktrap-Analyse, include=FALSE}

cluster_s21 <- cluster_walktrap(s21)
  # Cluster-Analyse der einzelnen Cluster des Netzwerks s21 (Cluster-Walktrap-Analyse)
modularity(cluster_s21)
membership_cluster_s21 <- membership(cluster_s21)
sort(membership_cluster_s21, decreasing = F)
communities(cluster_s21)
```

```{r Visualisierung cluster_s21, echo=FALSE, fig.height=14, fig.width=25}
# Visualisierung der Cluster-Walktrap Analyse des Netzwerks s21
plot(cluster_s21,
     s21,
     main = "Cluster-Walktrap Analyse des Netzwerks s21",
     set.seed=12,
     asp=0, 
     layout=layout_with_kk,
     edge.arrow.size=.3,
     vertex.size = 2,
     vertex.label.cex=1,
     sub = "n=106, eingefärbt nach Clustern (auch: Untergruppen/ Communities)")
```

[Fig. 8: Visualisierung der Cluster-Walktrap Analyse des
Datensatzes]{.smallcaps} *s21*

Auffällig bei der Cluster-Walktrap Analyse sind die verschiedenen
Untergruppen, die eingefärbt sind. Es kann festgehalten werden, welche
Knoten miteinander eng verbunden liegen. So ist hier namentlich das
Cluster um die Oettinger Gruppe GmbH zu nennen (in Figur 8 hellgrün,
links), derer sich schon an früherer Stelle angenommen wurde. Zudem
bildet auch das Planungsteam der ersten Stunde um Erwin Teufel, Manfred
Rommel, Hermann Schaufler, Matthias Wissmann und Heinz Dürr ein eigenes
Cluster (in Figur 8 lila, unten).

Zudem bilden die Sweco GmbH (vormals Grontmij), welche bei S21 als
Auftragnehmer beteiligt ist und die beiden CDU-Politiker\*innen David
McAllister und Nicole Razavi ein Cluster (in Figur 8 hellgrün, oben) für
sich. Nicole Razavi ist die ehemalige verkehrspolitische Sprecherin der
CDU im Landtag BW. Zudem agierte sie als Beraterin für die holländische
Grontmij GmbH und auch ihre deutsche Gesellschaft Sweco GmbH während
ihrer Zeit im Landtag. David McAllister ist der ehemalige
Ministerpräsident Niedersachsens. Er war ebenso wie seine CDU-Kollegin
Razavi als Berater für die Grontmij GmbH tätig.

Das Cluster um Hannes Rockenbauch, Gangolf Stocker und Werner Wölfle (in
Figur 8 pink, oben) sind Schnittstellen zum aktivistischen Netzwerk,
welches im nächsten Abschnitt als kleiner Exkurs behandelt werden soll.

Interessant ist auch das Cluster 4 (in Figur 8 gelb) um die Herrenknecht
AG, ihren Gründer und viele weitere zentrale Akteure an S21. Sie bilden
den "close circle" um das Projekt Stuttgart21. Hier finden sich unter
anderem die GmbH des Flughafen Stuttgarts, die Landesbank
Baden-Württemberg, die Stadt Stuttgart und Personen der ersten Stunde
(Lothar Späth, Rüdiger Grube, Wolfgang Schuster, Wolfgang Tiefensee
etc.).

## Zentralitäts-Maße

Um sich die Struktur des Gesamtnetzwerks des Datensatzes s21 genauer
betrachten zu können müssen im folgenden Abschnitt einige grundlegende
Berechnungen der Zentralitätsmaße vollzogen werden.

### Betweenness und Broker

Die Betweenness-Zentralität misst für jeden Knoten die Anzahl an
kürzesten Pfaden zwischen jedem Knoten-Paar in einem Netzwerk, die durch
den jeweiligen Knoten verlaufen. Je mehr kürzeste Pfade durch einen
Knoten führen, desto höher ist also sein Betweenness-Wert.

Im Folgenden soll eine Top10-Liste der Betweenness-Werte aller Knoten im
Datensatz s21 erstellt werden. Die Werte werden in absoluten Zahlen
ausgegeben.

```{r Netzwerkmaße betweenness, include=FALSE}
 # Betweenness-Berechnungen
sna_betw <- betweenness(s21, directed = F, normalized = T)
which.max(betweenness(s21))

top10_betw_s21 <- head(sort(sna_betw, decreasing = TRUE), 10)
```

```{r Ausgabe top10 von betweenness, echo=FALSE}
top10_betw_s21
```

Aufgrund der Art der Erhebung des Gesamtnetzwerks s21 stehen die beiden
Knoten der DB AG und der Projekt GmbH von Stuttgart 21 an der Spitze
dieser Top10-Liste: Es wurden lediglich solche Knoten erhoben, welche
eine Verbindung zum Bauprojekt S21 haben.

Betrachtet man die Top10-Liste ab dem dritten Platz so stellt man fest,
dass der ehemalige Stuttgarter OB Wolfgang Schuster mit
`r top10_betw_s21[3]` den dritthöchsten Betweenness-Wert im Netzwerk s21
besitzt. Ihm folgt Heinrich Geißler mit einem Wert von
`r top10_betw_s21[4]`. Zu ihm gesellen sich Günther Oettinger mit einem
Betweenness-Wert von `r top10_betw_s21[5]` und die CDU-Politikerin Tanja
Gönner mit einem Wert von `r top10_betw_s21[6]`. Die Oettinger Gruppe
GmbH folgt mit einem Wert von `r top10_betw_s21[7]`.

Nach den beiden DB-Knoten auf den Plätzen 1 und 2 haben also die Knoten
von Wolfgang Schuster und Heinrich Geißler den höchsten Betweenness-Wert
im Netzwerk. Ihnen soll sich im Abschnitt der Ego-Netzwerke noch einmal
genauer angenommen werden.

### Closeness

Der Closeness-Wert gibt an, wie nah ein Knoten im Netzwerk
durchschnittlich zu anderen Knoten positioniert ist. Ist der
Closeness-Wert hoch, heißt das, dass der Knoten im Durchschnitt eine
zentrale Positionierung im Netzwerk einnimmt, er hat schnellen Zugriff
auf andere Knoten im Netzwerk.

Im Folgenden soll eine Top10-Liste der Closeness-Werte aller Knoten im
Datensatz s21 erstellt werden. Die Werte werden in absoluten Zahlen
ausgegeben.

```{r Netzwerkmaße Closeness, include=FALSE}
# Closeness-Berechnung
sna_close <- closeness(s21)
which.max(closeness(s21))
top10_close_s21 <- head(sort(sna_close, decreasing = TRUE), 10)
```

```{r Ausgabe top10 von Closeness, echo=FALSE}
top10_close_s21
```

Auffällig ist hier, dass der Knoten der Deutschen Bahn AG in der
Top10-Liste der Closeness-Werte nicht seinen üblichen zweiten Platz
behält, sondern auf den siebten Platz abrutscht. Seinen Platz übernimmt
der Knoten von Stefan Garber, der ehemalige Netz-Vorstand der DB AG,
welcher mit einem Closeness-Wert von `r top10_close_s21[2]` wohl eine
zentrale Position im Netzwerk einnehmen kann. Durch seine Verbindungen
sowohl in die DB AG als auch zum Projekt und zu Günther Oettinger kann
er viele Knoten im Netzwerk schnell erreichen. Ihm folgt der Knoten von
eben diesem Günther Oettinger, welcher mit einem Closeness-Wert von
`r top10_close_s21[3]` ebenfalls eine zentrale Rolle im Netzwerk
einnimmt. Auch in dieser Top10-Liste ist die CDU-Politikerin Tanja
Gönner abgebildet. Sie steht mit einem Closeness-Wert von
`r top10_close_s21[5]` an fünfter Stelle der Liste. Oettinger, Schuster
und Gönner haben hier den gleichen Wert, haben also alle drei den
gleichen Zugriff auf andere Knoten im Netzwerk.

### Eigenvektor-Zentralität

```{r Netzwerkmaße Eigenvektor-Zentralität, include=FALSE}
s21_eigenvec <- eigen_centrality(s21)
s21_eigenvec_new <- s21_eigenvec$vector
top10_eigenvec_new_s21 <- head(sort(s21_eigenvec_new, decreasing = TRUE), 10)
```

Ein weiteres Zentralitätsmaß ist die Eigenvektor-Zentralität. Sie
beschreibt, wie stark ein Knoten mit anderen zentralen Knoten im
Netzwerk s21 verbunden ist.

Im Folgenden wird aus dem Eigenvektor-Zentralitäts-Wert eine Top10-Liste
der höchsten Werte gebildet.

```{r Ausgabe top10 des eigenvektors, echo=FALSE}
top10_eigenvec_new_s21
```

Auch hier stehen die DB AG und die Projekt-GmbH Stuttgart 21 an der
Spitze der Liste, mit einem Wert von `r top10_eigenvec_new_s21[1]`
(Projekt S21), beziehungsweise `r top10_eigenvec_new_s21[2]` (DB AG).
Die Flughafen Stuttgart GmbH ist im Netzwerk sowohl mit der DB AG als
auch mit der Projekt GmbH S21 verbunden. So erklärt sich der Wert von
`r top10_eigenvec_new_s21[3]`, der hier den dritten Platz in der Liste
bedeutet. Wolfgang Schuster ist auf dem vierten Platz mit einem Wert von
`r top10_eigenvec_new_s21[4]`, seine Rolle im Netzwerk wird im Abschnitt
der Ego-Netzwerke weiter thematisiert.

### Degree

```{r Netzwerkmaße degree, include=FALSE}
# Degree-Berechnungen aller Edges eines Nodes (?)
s21_degree <- degree(s21, mode = "total")
which.max(s21_degree)
s21_degree

  # Top 10 der Degreewerte
top10_degree_s21 <- head(sort(s21_degree, decreasing = T),10)
top10_degree_s21

# optional: nun wird der Datensatz without_dbpsu verwendet, um Degree-Werte bereinigt von dem Knoten DBPSU betrachten zu können
#s_21_without_projectgmbhs_degree <- degree(without_project_gmbh3, mode = "in")

#which.max(s_21_without_projectgmbhs_degree)

#top10_true_degree_s21 <- head(sort(s_21_without_projectgmbhs_degree, decreasing = T), 10)
#top10_true_degree_s21
```

Der Befehl degree(s21, mode="total") errechnet für jeden Knoten im
Datensatz seinen zugehörigen Degree-Wert. Der neue Value mit allen
Degree-Werten des Datensatzes s21 trägt den Namen s21_degree. Der
Degree-Wert beschreibt dabei die Anzahl an Kanten, die von einem Knoten
weg-, und zu einem Knoten hinführen. Ein hoher Degree-Wert steht daher
für eine breite Vernetzung im Netzwerk und kann solche Knoten
erkenntlich machen, welche sehr aktiv im Netzwerk sind. In Schritt 2
kann sich dann mit dem Befehl head(sort(s21_degree, decreasing = TRUE),
10) eine Top10-Liste derer Knoten angezeigt werden lassen, welche den
höchsten Degree-Wert im Netzwerk s21 haben.

```{r Ausgabe Degree-Werte Max, echo=FALSE}
top10_degree_s21
```

Nicht überraschend sind dies die Knoten der Projekt GmbH und der
Deutschen Bahn AG: Der Knoten der DB AG besitzt einen Degree-Wert von
`r top10_degree_s21[2]`, der Knoten der Projekt GmbH DBPSU sogar einen
Degree-Wert von `r top10_degree_s21[1]`. Da im Netzwerk s21 aber alle
Akteur\*innen mit Verbindungen zum Projekt Stuttgart21, somit also auch
nur solche mit Verbindungen zu der Projekt GmbH und der DB AG erhoben
wurden erklärt dies die hohen Degree-Werte der beiden hier betrachteten
Knoten.

Interessant wird es ab dem dritten Platz in der Top10-Liste der
Degree-Werte: Der ehemalige Stuttgarter Oberbürgermeister Wolfgang
Schuster belegt mit einem Degree-Wert von `r top10_degree_s21[3]` den
dritten Platz der Liste. Es folgt der Leiter der Schlichtungsgespräche
rund um Stuttgart 21, Heinrich Geißler mit einem Degree-Wert von
`r top10_degree_s21[4]`. An fünfter Stelle steht Baden-Württembergs
ehemaliger Ministerpräsident Günther Oettinger, welcher mit einem
Degree-Wert von `r top10_degree_s21[5]` ebenfalls eine beachtliche Rolle
im Netzwerk spielt. An achter Stelle steht die Herrenknecht AG. Sie hat
es als einziges Unternehmen der Infrastrutur mit einem Degree-Wert von
`r top10_degree_s21[8]` in diese Top10-Liste geschafft, da sie nicht nur
mit dem Projekt verbunden ist, sondern auch mit weiteren Akteur\*innen
im Netzwerk s21. Die Frau mit dem höchsten Degree-Wert ist die
CDU-Politikerin Tanja Gönner. In einem beinahe reinen Männernetzwerk
(vgl. Figur 1) hat sie es mit einem Degree-Wert von
`r top10_degree_s21[10]` auf den zehnten Platz der Top10-Liste
geschafft. All diesen Akteur\*innen soll sich im folgenden Abschnitt
noch einmal vertiefend gewidmet werden, ihre Netzwerke werden dabei
einzeln betrachtet, um zu verstehen, welche Knoten sich um diese
Akteur\*innen herum positionieren.

### Ego-Netzwerke

Folgend soll sich also vertiefend mit den Ego-Netzwerken einiger
zentraler Akteure im Netzwerk des Datensatzes s21 beschäftigt werden.

#### Ego-Netzwerk der Herrenknecht AG

```{r Ego-Netzwerk Herrenknecht AG, echo=FALSE, fig.align='left', fig.height=9, fig.width=14}
# Ego-Netzwerk Herrenknecht AG

Herrenknecht_AG_Ego <- make_ego_graph(s21, order = 1, nodes = V(s21)$name == "Herrenknecht AG")

Herrenknecht_AG_Ego1 <- Herrenknecht_AG_Ego[[1]]

plot(Herrenknecht_AG_Ego1,
     layout=layout_with_kk,
     main="Ego-Netzwerk Knoten 18 (Herrenknecht AG), erster Grad",
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5,
     sub = "n=7")
```

[Fig. 9: Visualisierung des Egonetzwerks vom Knoten Herrenknecht
AG]{.smallcaps}

Die Baufirma Herrenknecht AG ist der Knoten mit dem siebthöchsten
Degree-Wert im Gesamtnetzwerk s21. Er kann beinahe symbolisch für die
Verbindung zwischen Politik und Wirtschaft verstanden werden und ist
klar als ein Bindeglied zwischen dem Projekt Stuttgart 21 und
Politiker\*innen zu benennen. Im Ego-Netzwerk in Figur 9 wird
ersichtlich, dass es direkte Verbindungen zur Politiker\*innen gibt,
welche wiederum direkten Einfluss auf Entscheidungen rund um das Projekt
Stuttgart 21 haben.

Vielmehr verdeutlicht dieses erste Ego-Netzwerk, wie eng die Partei CDU
in dieses Projekt verstrickt ist. Was unter anderem auf ihre Position in
Regierungen in Baden-Württemberg, und dies wiederum auf Wahlergebnisse
zurückzuführen ist, so muss man doch auch die Bedeutung des Knoten
"Martin Herrenknecht" dem Vorstandssvorsitzenden und Gründer der
"Herrenknecht AG" betonen. Dieser war zum Zeitpunkt der Planung, sowie
der Projektvergabe Mitglied der CDU und liefert einen direkten Beweis
für die bestehende Nähe von Politik und Wirtschaft rund um das Projekt
Stuttgart 21. Zudem spendete Herrenknecht mehrere zehntausende Euro an
die Landes-CDU in Baden-Württemberg.

#### Ego-Netzwerk von Wolfgang Schuster

Auch dem ehemaligen Oberbürgermeister von Stuttgart soll ein
Ego-Netzwerk in diesem Forschungsbericht gewidmet werden. Die
Visualisierung wird zeigen, wie dicht seine Verbindungen in die
Wirtschaft waren.

```{r Ego-Netzwerk Schuster, echo=FALSE, fig.height=14, fig.width=25, fig.align='left'}
SchusterEgo <- make_ego_graph(s21, order = 1, nodes = V(s21)$name == "Wolfgang Schuster")

SchusterEgo1 <- SchusterEgo[[1]]

plot(SchusterEgo1,
     layout=layout_with_kk,
     main="Ego-Netzwerk Knoten 54, erster Grad",
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5,
     sub = "n=16")
```

[Fig. 10: Visualisierung des Egonetzwerks vom Knoten Wolfgang
Schuster]{.smallcaps}

Ebenfalls in der Top 10 der Degree-Werte des Datensatzes s21 ist der
CDU-Politiker und ehemaliger Oberbürgermeister Wolfgang Schuster. Wie
auch schon im vorherigen Ego-Netzwerk der Herrenknecht AG wird ein
Muster der Verwobenheit von Politik und Wirtschaft deutlich. Ebenso wird
ersichtlich, dass es mit dem Knoten von Günther Oettinger eine
Überschneidung in den beiden Ego-Netzwerke gibt.

Von großer Bedeutung sind aber vor allem die direkten Verbindungen zu
wichtigen Organisationen der Infrastruktur, was durch seine
Aufsichtsratposten und seine Rolle als ehemaliger OB Stuttgarts zu
begründen ist. Gleichzeitig muss betont werden, dass Wolfgang Schuster
ein Befürworter des Projekts Stuttgart 21 ist. Er hatte sich bereits in
seiner ersten Amtszeit gegen den Kontrahenten der Grünene Rezzo Schlauch
(im Netzwerk der Knoten 78) und in seiner zweiten Amtszeit gegen Boris
Palmer (im Netzwerk der Knoten 65) durchgesetzt. Er war zudem einer der
Befürworter während der Schlichtungsgespräche mit Heinrich Geißler (im
Netzwerk der Knoten 58).

Anhand dieser engen Verbindungen wird deutlich, wie wichtig die Persona
Schuster und seine Verbindungen für das Netzwerk ist und es gerade für
das Bauprojekt Stuttgart 21 war.

#### Ego-Netzwerk von Günther Oettinger

```{r Ego-Netzwerk Günther Oettinger, echo=FALSE, fig.height=9, fig.width=20, fig.align='left'}
# Ego-Netzwerk von Günther Oettinger

GOettinger <- make_ego_graph(s21, order = 2, nodes = V(s21)$name == "Günther Oettinger")

GOettinger1 <- GOettinger[[1]]

plot(GOettinger1,
     layout=layout_with_kk,
     main="Ego-Netzwerk Knoten 31, zweiten Grades",
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5,
     sub="n=31")
```

[Fig. 11: Visualisierung des Egonetzwerks zweiten Grades vom Knoten
Günther Oettinger]{.smallcaps}

Mittels des Ego-Netzwerks (zweiten Grades) von Günther Oettinger , dem
ehemaligen Ministerpräsidenten Baden-Württembergs, wird im Folgenden
versucht, die Schnittstellen und das Ausmaß der politischen und
wirtschaftlichen Verbindungen herauszuarbeiten. Da Günther Oettinger
sowohl in der Top 10 der Degree-Werte als auch eine gemeinsame
Verbindung des Ego-Netzwerks von Wolfang Schuster und dem Ego-Netzwerk
der Herrenknecht AG ist, wird das Ego-Netzwerk auf den zweiten Grad
ausgeweitet, um einen weiteren Blick auf die Position von Oettinger im
Gesamtnetzwerk zu erhalten.

In Figur 11 konnten unter anderem gemeinsame Schnittpunkte in der
Wirtschaft gezeigt werden, zudem auch Verbindungen mit Politikern. Es
lässt sich festhalten, dass Günther Oettinger in Anbetracht seiner
Position als ehemaliger Ministerpräsident einen extrem hohen Stellenwert
für das Projekt Stuttgart 21 hat. Gleichzeitig ist er, sowie zahlreiche
Überschneidungen der Knoten aus den zwei vorherigen Ego-Netzwerken (z.B.
Knoten 42 und 55) in einer sehr hohen hierarchischen Machtposition.

```{r Visualisierung Ego-Netzwerk Oettinger 1 und 2 Grades, echo=FALSE, fig.height=15, fig.width=35}
# Ego-Netzwerk von Günther Oettinger

GOettinger_first <- make_ego_graph(s21, order = 1, nodes = V(s21)$name == "Günther Oettinger")

GOettinger_first1 <- GOettinger_first[[1]]

# nebeneinander visualisieren
par(mfrow=c(1,2), mar=c(1,2,2,2))
plot(GOettinger_first1,
     layout=layout_with_kk,
     main="Ego-Netzwerk Knoten 31, ersten Grades",
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5,
     sub = "n=10")
plot(GOettinger1,
     layout=layout_with_kk,
     main="Ego-Netzwerk Knoten 31, zweiten Grades",
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5,
     sub = "n=31")
```

[Fig. 12: Visualisierung der Egonetzwerke ersten und zweiten Grades vom
Knoten Günther Oettinger]{.smallcaps}

In Figur 12 wurden die Ego-Netzwerke des Knoten 31 (Oettinger) des
ersten und zweiten Grades gegenüber gestellt, um einen kurzen Vergleich
zu ermöglichen. Dabei fällt insbesondere auf, dass Oettinger in seinem
Ego-Netzwerk ersten Grades bereits hochrangige Akteur\*innen des
Netzwerks aufweist, das Ego-Netzwerk zählt aber hier erst 10 Knoten. Im
Netzwerk zweiten Grades ist Oettinger jedoch schon mit 31 Knoten
verbunden. Er hat also die Möglichkeit, über nur einen Zwischenschritt
bereits über 30 Knoten im Datensatz zu erreichen. Dies macht ihn zu
einem der wichtigsten Akteure des ganzen Netzwerks s21.

#### Ego-Netzwerk Heinrich Geißler

```{r Ego Netzwerk Heinrich Geißler, echo=FALSE, fig.height=9, fig.width=16, fig.align='left'}

# Ego-Netzwerk von Heinrich Geißler

GeißlerEgo <- make_ego_graph(s21, order = 2, nodes = V(s21)$name == "Heinrich Geißler")

GeißlerEgo1 <- GeißlerEgo[[1]]

plot(GeißlerEgo1,
     layout=layout_with_kk,
     main="Ego-Netzwerk Knoten 58, zweiten Grades",
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5)
```

[Fig. 13: Visualisierung des Egonetzwerks zweiten Grades vom Knoten
Heinrich Geißler]{.smallcaps}

Als vierter Platz in der Top10-Liste der Degree-Werte von s21 steht
Heinrich Geißler ganz besonders im Fokus des Gesamtnetzwerks s21. Der
damalige Mediator führte die Schlichtungsgespräche zwischen
Gegner\*innen und Befürworter\*innen des "DBSPU21". Dies erklärt bereits
in vielerlei Hinsicht den hohen Degree-Wert.

Mit Knoten 71 (Stefan Mappus) und Knoten 54 (Wolfgang Schuster) wird
zudem das Bindeglied zu Günther Oettinger geschlossen. Dies verdeutlicht
den Einfluss der CDU im Datensatz s21. Hervorzuheben ist vor allem der
Fakt, dass Stefan Mappus (ehem. Ministerpräsident BW), Heinrich Geißler
als Mediator eingesetzt hat und damit einer Bitte der Grünen
nachgekommen ist.

In vielerlei Hinsicht lässt sich damit sagen, dass Heinrich Geißler nur
für die damalige Rolle als Mediator und Schlichter einen so hohen
Stellenwert in diesem Netzwerk einnimmt. Interessant sind gerade die
Knoten, die politische Ämter innehaben und Beziehungen und Verbindungen
in die Bereiche der Wirtschaft und der Infrastruktur haben, sowie über
eine hohe Machtposition verfügen. So die Knoten 54 (Wolfgang Schuster),
Knoten 31 (Günther Oettinger), aber auch Knoten 60 (Tanja Gönner),
welche als Befürworter des Projekts S21 und mit einer Art
"Broker"-Funktionen hin zur Wirtschaft betrachtet werden.

#### Ego-Netzwerk Tanja Gönner

```{r Ego-Netzwerk Tanja Gönner, echo=FALSE, fig.align='left', fig.height=5, fig.width=12}
# Ego-Netzwerk Tanja Gönner

TGönner <- make_ego_graph(s21, order = 1, nodes = V(s21)$name == "Tanja Gönner")

TGönner1 <- TGönner[[1]]

plot(TGönner1,
     layout=layout_with_kk,
     main="Ego-Netzwerk Knoten 60, erster Grad",
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5)
```

[Fig. 14: Visualisierung des Egonetzwerks ersten Grades vom Knoten Tanja
Gönner]{.smallcaps}

In einem Netzwerk das stark von Männern dominiert ist, war es
überraschend, mit Tanja Gönner eine Frau in der Top 10 der Degree-Werte
zu sehen. Besonders interessant ist der Vergleich auf etwaige
Unterschiede auf gemeinsame Verbindungen auf politischer und
wirtschaftlicher Ebene.

Abseits der gleichen Parteimitgliedschaft der CDU gab es nur
Überschneidungen zu dem Projekt S21 als Knoten selbst und Knoten 58
(Heiner Geißler). Der vermutlich wichtigste Knoten des Ego-Netzwerks von
Tanja Gönner ist Knoten 99 (Bundesverband der deutschen Inustrie e.V.),
in dem Tanja Gönner Mitlied des Vorstands ist und somit eine direkte
Schnittstelle der Politik der CDU zur Wirtschaft aufzeigt.

# Exkurs: Das Aktivist\*innen-Netzwerk

## Gesamtnetzwerk activists

Um sich nun dem Netzwerk der beteiligten Aktivist\*innen und
aktivistischen Organisationen an Stuttgart 21 zu widmen muss ein neues
Netzwerk activists erstellt werden. Dieses wird im Folgenden analysiert
und visualisiert.

```{r Setup Aktivist*innen, include=FALSE}

knitr::opts_chunk$set(echo = TRUE)
library(igraph)
```

```{r Netzwerk Aktivist*innen einlesen, include=FALSE}

# Setup-Chunk 
  # Daten einlesen
edges_akt <- read.csv("https://raw.githubusercontent.com/gllnxr/Stuttgart21/main/Aktivist_Edgelist.csv", header=T, as.is=T, sep = ",")
nodes_akt <- read.csv("https://raw.githubusercontent.com/gllnxr/Stuttgart21/main/Aktivist_Nodelist.csv", header=T, as.is=T, sep = ",")

  # edgematrix erstellen
edgematrix <- as.matrix(edges_akt)

  # Workaround unknownvertexselected
nodes_akt$analysis_person_akti <- nodes_akt$type == 1

  # igraph-Objekt erstellen
activists <- graph_from_data_frame(d=edgematrix, vertices=nodes_akt, directed = F)
```

```{r Ausgabe activists, echo=FALSE}
activists
```

Das Teilnetzwerk der Aktivist\*innen besteht aus 49 Knoten und 141
Kanten (siehe iGraph-Objekt activists). Es ist ebenso wie das
Hauptnetzwerk s21 ungerichtet und gewichtet.

```{r Komponenten und Dichte Aktivist*innen, include=FALSE}

ecount(activists)
#Das Netzwerk der an Stuttgart 21 beteiligten Aktivist*innen hat 141 Kanten.

vcount(activists)
#Das Netzwerk der an Stuttgart 21 beteiligten Aktivist*innen hat 49 Knoten.  

is.directed(activists)
#Das Netzwerk ist ungerichtet.

is.weighted(activists)
#Das Netzwerk ist gewichtet.

count_components(activists)
#Das Netzwerk activists hat genau eine Komponente.

edge_density(activists)
#Das Netzwerk SNA_S21 hat eine Kantendichte von etwa 11,9 %
```

Das Netzwerk besteht aus genau einer Hauptkomponente. Die Kantendichte
beträgt hier 11,9 %. Neben aktivistischen Organisationen wurden auch
dazugehörige natürliche Personen erhoben. Daher ist dieses Netzwerk
ebenso wie das der Politiker\*innen ein Two-Mode-Netzwerk. Es finden
sich 25 Organisationen sowie 24 natürliche Personen darin.

Als grundlegendes Attribut in der Node-List wurde wie im Gesamtnetzwerk
s21 bei allen natürlichen Personen das Geschlecht erhoben. Nach einer
Analyse wurde klar, dass im Aktivismusnetzwerk lediglich nur 3 weibliche
Akteurinnen, dafür aber 21 männliche Akteure erhoben wurden. Der
Vollständigkeit halber wurde auch die Zuordnung "divers" im Codebuch
aufgenommen, jedoch ist keine\*r der erhobenen natürlichen Personen der
Recherche nach hier einzuordnen. So bleiben 25 erhobene Organisationen,
im Netzwerk "activists" mit "type == 2" kodiert.

```{r Untersuchungen an activists, include=FALSE}

  # Degree-Wert
sna_deg <- degree(activists, mode = "total")
which.max(sna_deg)
  # Den höchsten Degreewert besitzt Klaus Gebhardt mit 19.

  # Betweenness-Wert
sna_betw <- betweenness(activists, directed = F, normalized = T)
which.max(betweenness(activists))
sort(sna_betw, decreasing = T)
  # Hier ist Klaus Riedel der Node mit dem höchsten Betweenness-Wert.

  # Closeness-Wert
sna_close <- closeness(activists)
which.max(closeness(activists))
sort(sna_close, decreasing = T)
  #Der Node mit dem höchsten Closeness-Wert ist Nisha Toussaint.

  # Eigenvector-Zentralitäts-Berechnung
sna_eigenvec <- eigen_centrality(activists)
sna_eigenvec_new <- sna_eigenvec$vector

sna_eigenvec$value
#Die Eigenvektor-Zentralität beträgt 0.0732
```

Das Gesamtnetzwerk hat eine Kantendichte von
`r edge_density(activists)*100` Prozent. Den höchsten Degreewert im
Netzwerk besitzt der Knoten `r which.max(sna_deg)` (Klaus Gebhardt). Der
Akteur Klaus Riedel wiederum hat in diesem Netzwerk den höchsten
Betweenness-Wert von rund 0,2497. Die Person mit dem höchsten
Closeness-Wert heißt Nisha Toussaint, sie besitzt einen Wert von 0,0077.
Die Eigenvektor-Zentralität beträgt hier 0,0732.

Im Folgenden wird das Netzwerk der Aktivist\*innen an S21 visualisiert.

```{r Visualisierung Gesamtnetzwerk, echo=FALSE, fig.height=9, fig.width=16}
# Organisationen und Personen entsprechend kenntlich machen (two-mode-network); Zusatz: nach Parteien einfärben
V(activists)[V(activists)$type == 1]$shape <- "circle"
V(activists)[V(activists)$type == 2]$shape <- "square"

  # nachfolgender Befehl errechnet den degreewert aller nodes in einen neuen datensatz "degree_option"
degree_option_acti <- degree(activists, mode="all")

plot(activists,
     set.seed=12,
     asp=0, 
     layout=layout_with_kk,
     edge.arrow.size=.3,
     vertex.size = 2,
     vertex.label.cex=0.5,
     vertex.size = degree_option_acti*0.5,
     vertex.label.cex=1,
     main = "Netzwerk der beteiligten Aktivist*innen und deren zugehörigen Gruppen",
     sub = "n=49; Quadrate = Organisationen, Kreise = natürliche Personen; Die Größe der Knoten ist abhängig von ihren jeweiligen Degreewerten — Datenerhebung erfolgte durch Louis G, Sinan K, Mia M, David V, Paul A")
```

[Fig. 15: Visualisierung des Gesamtnetzwerks]{.smallcaps} *activists*

Im nachfolgenden Abschnitt wird sich den einzelnen Teilnetzwerken des
Gesamtnetzwerks zugewandt. Beginnend mit den Teilnetzwerken der
Geschlechter wird sich nachfolgend mit dem Teilnetzwerk der erhobenen
Politiker\*innen und dem force-Teilnetzwerk beschäftigt.

## Analyse der Teilnetzwerke

### Nach Node-Attributen

#### Geschlecht

Wie bereits festgestellt besteht das Netzwerk des Datensatzes activists
überwiegend aus Männern. Nun soll es einen Vergleich zwischen dem
Teilnetzwerk der Männer im Datensatz activists und dem der Frauen geben.
Dafür unterteilen wir den Datensatz zunächst in natürliche Personen und
Organisationen, betrachten hier lediglich Erstere und nutzen
Filterbefehle (wie "induced_subgraph"), die alle Frauen und alle Männer
ihren eigenen neuen Datensätze zuweisen.

Als grundlegendes Attribut in der Node-List wurde wie im Hauptnetzwerk
s21 bei allen natürlichen Personen das Geschlecht genommen. Nach einer
Analyse wurde klar, dass im Aktivismusnetzwerk lediglich nur 3 weibliche
Akteurinnen, dafür aber 21 männliche Akteure erhoben wurden. Der
Vollständigkeit halber wurde auch die Zuordnung "divers" im Codebuch
aufgenommen, jedoch ist keine der erhobenen natürlichen Personen der
Recherche nach hier einzuordnen. So bleiben 25 erhobene Organisationen,
im Netzwerk "activists" mit "type == 2" kodiert.

##### Männer

```{r Teilnetzwerk Männer activists, fig.height=9, fig.width=16, include=FALSE}
#Teilnetzwerk Männer

list.edge.attributes(activists)
edge.attributes(activists)

subset_nodes_males_akti <- V(activists)[sex == 1 & analysis_person_akti]
males_akti <- induced_subgraph(activists, subset_nodes_males_akti)
males_akti
```

```{r Analyse Männer Teilnetzwerk activists, include=FALSE}
vcount(males_akti)
#Das Teilnetzwerk der männlichen Aktivisten besteht aus 21 Knoten. 

ecount(males_akti)
#Das Teilnetzwerk der männlichen Aktivisten hat 37 Kanten.

edge_density(males_akti)
#Die Dichte im männlichen Teilnetzwerk beträgt 0.1761.

diameter(males_akti)
#Die Pfaddistanz im männlichen Teilnetzwerk beträgt 5.
```

Das Netzwerk der männlichen Aktivisten besitzt 21 Knoten. Dazu kommen
noch 37 Kanten. Die Dichte im männlichen Teilnetzwerk beträgt 0.1761.
Die Pfaddistanz in diesem Netzwerk hat einen Wert von 5.

```{r Visualisierung männer activists, echo=FALSE, fig.height=9, fig.width=16}
plot(males_akti,
  asp=0,
  layout=layout_with_kk,
  edge.arrow.size=.7,
  edge.color="black",
  vertex.size = 4,
  vertex.color = "lightblue",
  main = "Männer im activists-Netzwerk",
  sub = "n=21"
  )
```

[Fig. 16: Visualisierung des Teilnetzwerks]{.smallcaps} *males_akti*

##### Frauen

Für die geringe Anzahl an bekannten weiblichen Gesichtern der Proteste
gibt es keine genaue Erklärung, Es ist jedoch festzustellen, dass bei
den meisten aktivistischen Organisationen Männer die Führung haben,
weshalb weibliche Aktivistinnen in den Hintergrund gerückt werden
könnten. Die Zahl der tatsächlichen Aktivistinnen dürfte höher sein,
jedoch treten diese nicht in einer führenden Rolle bei den Protesten auf
und können aufgrund der hohen Fluktuation bei den Protesten nicht
verlässlich festgestellt werden.

```{r Teilnetzwerk Frauen, echo=FALSE, fig.height=9, fig.width=16}
#Teilnetzwerk Frauen

subset_nodes_females_akti <- V(activists)[sex == 2 & analysis_person_akti]
females_akti <- induced_subgraph(activists, subset_nodes_females_akti)

plot(females_akti,
  asp=0,
  layout=layout_with_kk,
  edge.arrow.size=.7,
  edge.color="black",
  vertex.color="pink",
  main = "Frauen im activists-Netzwerk",
  sub = "n=3"
  )
```

[Fig. 17: Visualisierung des Teilnetzwerks]{.smallcaps} *females_akti*

```{r Analyse Frauen activists, include=FALSE}
#Analyse Teilnetzwerk Frauen 

ecount(females_akti)
#Das Teilnetzwerk der weiblichen Aktivistinnen hat genau eine Kante.

vcount(females_akti)
#Das Teilnetzwerk der weiblichen Aktivistinnen besteht aus 3 Knoten. 

edge_density(females_akti)
#Die Dichte im weiblichen Teilnetzwerk beträgt 0,333333. 

diameter(females_akti)
#Die durchschnittliche Pfaddistanz im Netzwerk der Frauen beträgt genau 1.
```

Das Teilnetzwerk der Frauen hat zwei Komponenten, welchen 3 Knoten
angehören. Ihre Dichte beträgt 33,3 Prozent und das Teilnetzwerk verfügt
über genau eine Kante.

### Teilnetzwerk Politiker\*innen und Parteienzugehörigkeit

Im Netzwerk der Aktivist\*innen gibt es auch die ein oder andere Person
aus der Politik. Namentlich zu nennen wäre hier zum einen Gregor Gysi.
Der Linken-Politiker tritt häufiger mal bei Veranstaltungen der aktiven
Parkschützer auf. Wichtig hierbei ist seine freundschaftliche Beziehung
zu Prof. Dr. Heiner Monheim, der dort ebenfalls in Erscheinung tritt und
mit dem sich Gysi regelmäßig über die Thematik austauscht.

Auch interessant ist die Rolle von Johanna Tjarks, die Teil der
Fraktionsgemeinschaft "Die Fraktion" ist. Sie tritt ebenfalls regelmäßig
bei Veranstaltungen der Aktiven Parkschützern auf. Dabei ist sie
Fraktionssprecherin von "Die Fraktion."

Klaus Riedel, Gangolf Stocker, Peter Gürlich, Hannes Rockenbauch und
Werner Wölfle sind ebenfalls große Namen, die sich regelmäßig den
Aktivist\*Innen anschließen. Somit bestehen in dem Netzwerk auch
Verbindungen zu den Parteien SOES und Bündnis 90/die Grünen.

```{r activists Politiker*innen und Zugehörigkeit, include=FALSE}
subset_nodes_politician_akti <- V(activists)[politician == TRUE & analysis_person_akti]
politician_akti <- induced_subgraph(activists, subset_nodes_politician_akti)
politician_akti
# Teilnetzwerk Politiker untersuchen

politician_akti
list.edge.attributes(politician_akti)
edge.attributes(politician_akti)$relation
```

```{r Visualisierung Parteien, echo=FALSE, fig.height=9, fig.width=16}
#Parteien einfärben

V(politician_akti)[V(politician_akti)$party == "SPD"]$color <- "red"
V(politician_akti)[V(politician_akti)$party == "Die Linke "]$color <- "pink"
V(politician_akti)[V(politician_akti)$party == "Gruene"]$color <- "green"
V(politician_akti)[V(politician_akti)$party == "Fraktionsgemeinschaft Die Fraktion"]$color <- "beige"
V(politician_akti)[V(politician_akti)$party == "SOES"]$color <- "grey70"

plot(politician_akti, 
     main="Politiker*innen unter den S21-Aktivist*innen",
     asp=0,
     layout=layout_with_kk,
     edge.arrow.size=.7,
     edge.color="black",
     sub="n=7; eingefärbt nach Parteizugehörigkeiten: rot = SPD, pink = Linke, grün = Grüne, beige = Die Fraktion, grau = SÖS")
```

[Fig. 18: Visualisierung des Teilnetzwerks]{.smallcaps}
*politician_akti*

### Teilnetzwerk force

```{r force Teilnetzwerk, include=FALSE}
#Teilnetzwerke erstellen

force <- subgraph.edges(activists, E(activists)[weight==2])
force

count_components(force)
#Das Teilnetzwerk force besteht aus 4 Komponenten.

edge_density(force)
#Das Teilnetzwerk force hat eine Kantendichte von etwa 7,86 %

vcount(force)

#Das Teilnetzwerk Force hat 32 Knoten

ecount(force)

#Das Teilnetzwerk Force hat 39 Kanten.

edge_density(force)

#Das Teilnetzwerk Force hat eine Dichte von 0,0786. 

diameter(force)

#Die gesamte Pfaddistanz im Teilnetzwerk Force beträgt 14. 

which.max(diameter(force))

#Die längste Pfaddistanz im Netzwerk Forces beträgt 1.

is.directed(force)
is.weighted(force)
```

Das Teilnetzwerk Force hat 32 Knoten. Es umfasst auch 39 Kanten Das
Teilnetzwerk besitzt eine relativ niedrige Dichte von etwa 7, 86 %. Die
gesamte Pfaddistanz im Teilnetzwerk beträgt 14. Die längste Pfaddistanz
ist 1. Das Netzwerk ist ungerichtet und gewichtet.

```{r Visualisierung force Teilnetzwerk, echo=FALSE}
plot(force,
     main = "Teilnetzwerk force",
     set.seed=12,
     asp=0,
     layout=layout_with_kk,
     edge.arrow.size=.3,
     vertex.size = 2,
     vertex.label.cex=0.5)
```

[Fig. 19: Visualisierung des Teilnetzwerks]{.smallcaps} *force*

## Cluster-Analyse

```{r Cluster-Analyse activisits, echo=FALSE}
cl_activists <- cluster_walktrap(activists)

  # Cluster-Analyse der einzelnen Cluster des Netzwerks activists (Cluster-Walktrap-Analyse)
cl_activists <- cluster_walktrap(activists)

plot(cl_activists,
     activists,
     main = "Cluster-Walktrap Analyse des Netzwerks activists",
     set.seed=12,
     asp=0, 
     layout=layout_with_kk,
     edge.arrow.size=.3,
     vertex.size = 2,
     vertex.label.cex=0.5)
```

[Fig. 20: Visualisierung der Cluster-Walktrap Analyse des
Gesamtnetzwerks]{.smallcaps} *activists*

Die Cluster-Analyse zeigt sehr anschaulich auf, welche verschiedenen
Untergruppen im Netzwerk activists gebildet wurden. Auffällig ist hier
das Cluster um Jürgen Resch (grün in Figur 20), das Cluster um Gregor
Gysi (lila in Figur 20), und auch das Cluster um die Schutzgemeinschaft
Filder (mittig in Figur 20). Daher wird sich dem Knoten der
Schutzgemeinschaft Filder im Folgenden noch vertieft angenommen.

## Ego-Netzwerke activists

### Ego-Netzwerk der Schutzgemeinschaft Filder

Eine Organisation, die viele der Aktivist\*innen miteinander vereint,
ist die Schutzgemeinschaft Filder. Hier finden sich gleich 10
Akteur\*Innen aus dem Netzwerk wieder. Von diesen sind 2 der insgesamt 3
weiblichen Akteurinnen vertreten. Namentlich handelt es sich hierbei um
Judith Scheytt und Nisha Toussaint. Nur über die Schutzgemeinschaft
Filder lassen sich auch Verbindungen zum Deutschen Gewerkschaftsbund,
der Gewerkschaft der Polizei, dem Bündnis "Bei Abriss Aufstand" und "Für
K21" darstellen.

```{r Ego Filder, echo=FALSE, fig.height=9, fig.width=16}
Schutzgemeinschaft_Filder_Ego <- make_ego_graph(activists, order = 1, nodes = V(activists)$name == "Schutzgemeinschaft Filder")

Schutzgemeinschaft_Filder_Ego1 <- Schutzgemeinschaft_Filder_Ego[[1]]

plot(Schutzgemeinschaft_Filder_Ego1,
     main="Ego-Netzwerk Knoten 7, erster Grad",
     layout = layout_with_kk,
     edge.color="grey80",
     edge.arrow.size=.3,
     vertex.size=5,
     sub = "n=13")
```

[Fig. 21: Visualisierung des Ego-Netzwerks ersten Grades der
Schutzgemeinschaft Filder]{.smallcaps}

```{r Analyse Ego Netzwerk, include=FALSE}
#Schutzgemeinschaft Filder Analyse 

vcount(Schutzgemeinschaft_Filder_Ego1)
#Das Egonetwerk der Schutzgemeinschaft Filder besitzt insgesamt 13 Knoten. 

ecount(Schutzgemeinschaft_Filder_Ego1)
#Das Egonetzwerk der Schutzgemeinschaft Filder besitzt insgesamt 55 Kanten. 

is.directed(Schutzgemeinschaft_Filder_Ego1)
#Das Egonetzwerk der Schutzgemeinschaft Filder ist ungerichtet.

is.weighted(Schutzgemeinschaft_Filder_Ego1)
#Das Egonetzwerk der Schutzgemeischaft Filder ist gewichtet. 

edge_density(Schutzgemeinschaft_Filder_Ego1)
#Das Egonetzwerk der Schutzgemeinschaft Filder hat eine Dichte von etwa 70,51 Prozent. 

count_components(Schutzgemeinschaft_Filder_Ego1)
#Das Egonetzwerk der Schutzgemeinschaft Filder hat genau eine Komponente.
```

Das Ego-Netzwerk ersten Grades der Schutzgemeinschaft Filder hat genau
eine Komponente und besitzt 13 Knoten und 55 Kanten. Es ist ungerichtet
und gewichtet und hat eine Dichte von 70,51 Prozent, ist also sehr dicht
untereinander vernetzt.

# Diskussion und Fazit

Die vorliegende Netzwerkanalyse zur Frage: "Wie vernetzt sind Politik
und Wirtschaft in Baden-Württemberg am Beispiel von Stuttgart 21?" hat
sich mit den Verbindungen zwischen Politik und Wirtschaft anhand des
Bauprojekts Stuttgart 21 beschäftigt. Dabei wurden viele Erkenntnisse
bezüglich der Dichte der Netzwerke festgehalten. Darüber hinaus wurde
sich mit der Position einzelner Akteur\*innen im Gesamtnetzwerk
beschäftigt. Abschließend wurde ein kurzer Exkurs in ein weiteres
erhobenes Netzwerk vollzogen, welcher den Blick auf die aktivistischen
Akteur\*innen bei Stuttgart 21 gelegt hat.

Schlussendlich soll nun ein erneuter Blick auf die aufgestellten
Hypothesen und Annahmen geworfen werden. Diese wurden zu Beginn der
Datenerhebung aufgestellt und sollen nun anhand der Analysen und
allgemeinen Datenlage verifiziert, korrigiert oder falsifiziert werden.

[**H1:**]{.underline} **Es wird vermutet, dass Politiker\*innen und
Wirtschaft gerade im Land Baden-Württemberg sehr eng miteinander
verflochten sind und, das politische Entscheidungen damit auch die
Struktur innerhalb des Bauprojekts Stuttgart 21 beeinflussen.**

[zu H1:]{.underline} Zwar beträgt Dichte des Gesamtnetzwerks s21 nur
`r edge_density(s21)*100` Prozent, aber die verschiedenen Ego-Netzwerke
der Knoten Herrenknecht AG, Günther Oettinger, Wolfgang Schuster und
Tanja Gönner zeigten klar auf, dass in Baden-Württemberg zumindest an
einigen Stellen sehr enge Vernetzung zwischen Politik und Wirtschaft
bestehen. Dies lässt sich auch anhand der Zentralitätsmaße von s21
belegen: Gönner und Oettinger führten die Top10-Listen der Closeness-
und Degree-Werte immer mit an. Anhand der Ergebnisse dieser
Forschungsarbeit lässt sich also festhalten, dass es an vielen Stellen
im Kontext des Bauprojekts Stuttgart 21 enge Verbindungen zwischen
Politik und Wirtschaft gegeben hat.

**H2: Es wird zudem angenommen, dass es einzelne Akteur\*innen gibt, die
eine zentralere Position im Netzwerk inne haben, damit also über mehr
Möglichkeiten zur Machtausübung verfügen.**

[zu H2:]{.underline} Wie bereits in der Ausführung zu H1 erwähnt, wurde
belegt, dass es gewisse Akteur\*innen gab, die eine zentrale Position im
Netzwerk eingenommen haben: Mit Tanja Gönner, Günther Oettinger und
Wolfgang Schuster wären nur einige Namen genannt, die von großer
Bedeutung in dem Netzwerk s21 sind. Auch hier können die Ausarbeitung zu
den Zentralitätsmaßen erklärend herangezogen werden.

**H3: Frauen sind im Netzwerk s21 wohl in der klaren Unterzahl, dies
machen sie unter Anderem mit dichten Verbindung untereinander wett.**

[zu H3:]{.underline} Die Annahme, dass Frauen im Netzwerk s21 in der
klaren Unterzahl sind hat sich als korrekt erwiesen. Jedoch wurde die
Hypothese 3 falsifiziert: Im Teilnetzwerk der Frauen konnte klar
aufgezeigt werden, dass es lediglich 9 Frauen im Datensatz s21 gibt,
welche untereinander aber keinerlei Verbindungen unter den Frauen
bestanden. Es ließ sich also schlussfolgern, dass in dem Gesamtnetzwerk
s21 Entscheidungen immer auch über Männer laufen mussten. Die
Entscheidungen mussten immer auch über Männer laufen, sie wurden also
mindestens von Frauen und Männer gemeinsam getroffen. Die Anzahl an
beteiligten Männern lässt jedoch vermuten, dass Absprachen und
Entscheidungen wohl oft auch ohne Frauen getroffen wurden.

**H4: CDU-Politiker\*innen sind in der klaren Überzahl im
Gesamtnetzwerk.**

[zu H4:]{.underline} Die Hypothese, dass es im Netzwerk s21 eine klare
Überzahl derer Politiker\*innen gibt, die der CDU angehören, konnte
bestätigt werden: Der SPD gehören 10 Knoten, der FDP 4 Knoten, den
Grünen 8 Knoten und der SÖS 2 Knoten des Datensatzes s21 an. Der CDU
gehören dabei ganze 23 Knoten an. Eine Häufung, die natürlich auch auf
die Wahlergebnisse und die Summe an BW-Regierungen mit CDU-Beteiligungen
zurückzuführen ist. Nicht desto trotz sind mit Günther Oettinger und
Tanja Gönner nur zwei Knoten zu nennen, welche sehr enge Verbindung zu
Wirtschaft haben. Dies legt den Schluss nahe, dass es auch in der Natur
eines Infrastrukturprojekts, wie Stuttgart 21 liegt, dass die
wirtschaftsnahe Baden-Württembergische CDU auch deshalb so zahlreich im
Datensatz s21 vertreten ist.

**H5 (Exkurs): Es wird angenommen, dass Aktivist\*innen untereinander
noch dichter vernetzt sind, als Akteur\*innen im Gesamtnetzwerk s21.**

[zu H5:]{.underline} Vergleicht man die Dichte im Netzwerk s21
(`r edge_density(s21, loops=F)*100` Prozent) mit der des Netzwerks
activists (`r edge_density(activists, loops=F)*100` Prozent), so fällt
auf, dass das Aktivist\*innen-Netzwerk eine höhere Kantendichte besitzt.
Die Hypothese, dass Aktivist\*innen untereinander dichter verbunden
sind, als die Akteur\*innen innerhalb des Gesamtnetzwerks s21 konnte
also im Laufe der Arbeit mit den Daten ausreichend belegt werden.

**H6 (Exkurs): Aktivist\*innen sind nicht nur in ihrer eigenen
Meinungsblase gut vernetzt, sondern auch über die Grenzen hinweg mit
gegensätzlichen Meinungsträgern verbunden.**

[zu H6:]{.underline} Aktivist\*innen geben sich nicht nur mit ihrer
eigenen Bubble zufrieden, denn sie wollen keine gleichgeschaltete
Meinung. Aktivist\*innen zielen aktiv auf den Diskurs mit
gegensätzlichen Ansichten ab: Nicht umsonst gründete Christian List die
Initiative „Laufen für Stuttgart 21" als Gegeninitative zu „Laufen gegen
Stuttgart 21/Ausstieg jetzt" von Steffen Kauderer. Aktivist\*innen
zielen gerade auf die Provokation und den Austausch mit einer
gegensätzlichen Meinung ab, denn daraus ziehen sie die Kraft für ihre
Proteste. Die Bildung der Initiative "Laufen für Stuttgart 21" kann
somit als Beleg angesehen werden, warum die Hypothese 6 wahr ist.

# Limitationen

Die vorliegende Netzwerkanalyse hat dabei aber auch einige Limitationen
aufzuweisen. So musste bei der Datenerhebung, aufgrund von
eingeschränkten zeitlichen Ressourcen auf ein Aufnehmen einer Zeitachse
verzichtet werden. Das Gesamtnetzwerk s21 ist daher ein statischer Blick
auf die Verbindungen zwischen Politik, Wirtschaft und dem Bauprojekt
Stuttgart 21. Ebenfalls wurde in der Datenerhebung bereits eine grobe
Datenbereinigung durchgeführt: Es wurden nur solche Knoten und ihre
Verbindungen erhoben, die auch zu anderen, bereits bestehenden Knoten im
Datensatz s21 Verbindungen aufwiesen. Dies verzerrt den Blick, der hier
auf die Verbindungen geworfen wird zuteilen.

Zudem wurde in der Datenerhebung mit äußerster Vorsicht eine Ausprägung
("1" oder "2") im Edge-Attribut "weight" für jede Kante notiert. Dies
ist auch beim Edge-Attribut "relationship" anzumerken: Hier wurde auf
der Grundlage von öffentlich zugänglichen Quellen und des Codebuchs eine
Kodierung der Art und der Gewichtung der Verbindung notiert. Es ist
dabei jedoch nicht auszuschließen, dass die im Datensatz s21 kodierte
Verbindung von der, in Wirklichkeit existierenden Verbindung abweicht.
Es konnte sich bei der Kodierung der Daten nur auf öffentlich
zugängliche Datenquellen gestützt werden.

Es kann also nicht mit 100-prozentiger Sicherheit gesagt werden, ob die
hier erhobenen Kanten und Knoten vollständig sind. Die Datenerhebung zu
zum Datensatz s21 kann keine Anspruch darauf erheben, die tatsächlichen
Verbindungen bei Stuttgart 21 aufzeigen zu können. Jede Verbindung und
jeder erhobene Node wurde jedoch anhand des zwei-Quellen-Prinzips
geprüft und Informationen so verlässlich verifiziert.

In weiterer Forschung und in der Zukunft könnte sich auf Grundlage der
aufgezeigten Ergebnisse ein tieferer Blick auf die Rolle der CDU und die
Verbindungen zwischen dem Gesamtnetzwerk s21 und dem der Aktivist\*innen
lohnen. Es könnte auch eine Analyse der Aufträge und Spenden im Kontext
zu Stuttgart 21 vollzogen werden, denn die Auftragslage zu S21 ist in
der Öffentlichkeit oft unklar, jedoch von großer Bedeutung für die
beteiligten Unternehmen. Bei einem Projekt ohne einer zeitlichen
Begrenzung und mehr Ressourcen hätten Recherche und Datenmenge
ausgeweitet und ein noch detailreicheres Netzwerk erstellt werden
können.

# Anlage

## Literatur

Nagel, M. (2016). Polarisierung im politischen Diskurs. Springer
Fachmedien Wiesbaden. <https://doi.org/10.1007/978-3-658-11225-7>

Nohlen, D. & Grotz, F. (2015). Kleines Lexikon der Politik (6.).
C.H.BECK.

Schubert, K. & Klein, M. (2020). *Das Politiklexikon* (7. Aufl.).
Dietz. <https://www.bpb.de/kurz-knapp/lexika/politiklexikon/296375/hierarchie/>

Ein Link zur Quellensammlung der gesamten Datenerhebung ist nach APA 7
[[hier]{.underline}](https://stuttgart21-sna.notion.site/Quellensammlung-c6f75ee3cc8e47d4ae58ac1c30e93059?pvs=4)
hinterlegt.

## Codebuch und Datenmaterial

Das Codebuch für den Datensatz s21 ist auf GitHub zu finden.

Das gesamte [[Verzeichnis mit allen wichtigen
Dateien]{.underline}](https://github.com/gllnxr/Stuttgart21/) zu s21 ist
ebenfalls auf GitHub hinterlegt.

```{r Übersicht Netzwerkattribute s21}
list.vertex.attributes(s21)
list.edge.attributes(s21)
```

Das Netzwerk s21 hat dem
[[Codebuch]{.underline}](https://github.com/gllnxr/Stuttgart21/blob/main/CodebuchS21.md)
zufolge die folgenden Attribute:

*Vertex-Attribute:*

-   **id** Numerisch (eindeutige Codierung des Knoten): codiert von 1
    bis 106

-   **name** Character: Voller Name oder offizielle Bezeichnung des
    Knotens

-   **name_short** Character: Name (Vorname und Nachname) oder
    Kurzbezeichnung (altern.: Abkürzung)

-   **type** Numerisch: 1 = natürliche Person; 2 = Organisation

-   **sex** Numerisch - trichotome Ausprägung: 1 = male; 2 = female; 3 =
    divers

-   **branche** Numerisch: 0 = keine Branchen-Zugehörigkeit, da
    natürliche Person; 1 = DB-Assoziiert; 2 = Unternehmen der
    Infrastruktur; 3 = Gewerkschaften und Verbände; 4 = Parteien,
    Ministerien und Kommissionen; 5 = Wissenschaftliche Institute; 6 =
    Veranstalter; 7 = Finanzwesen; 8 = Immobilien; 9 = Städte

-   **party** Character: Parteizugehörigkeit, angegeben, wenn politician
    == TRUE

-   **politician** Character: TRUE; FALSE

    **NA** definiert fehlende Werte

*Edge-Attribute:*

-   **id** (eindeutige Codierung des Knoten): codiert von 1 bis 106

-   **from** Knoten A, welcher mit Knoten B verbunden ist

-   **to** Knoten B, welcher mit Knoten A verbunden ist

-   **weight** Ausprägung der Beziehungsstärke - hier: Auflistung der
    Macht zwischen zweier Knoten: 1 = wenig Entscheidungsmacht; 2 = viel
    Entscheidungsmacht

-   **relationship** Definiert die Art der Beziehung bei multiplexen
    Netzwerken mit verschiedenen Beziehungsarten: 1 = Geschäftlich; 2 =
    mehr als Geschäftlich (nachweislich\... )

Hinzu kommen noch die **Edge-Attribute** "**analysis_weight_strong**"
und "**analysis_relationship_strong**", welche im ersten Set-Up-Chunk
dieser Rmd-Datei erstellt werden. Sie sind beide [**Teil eines
Work-Arounds**]{.underline}, da ein Teil des iGraph-Pakets im Herbst
2023 Fehlermeldungen unbekannter Art produziert hat und sich mit dem
Code nicht mehr arbeiten ließ. Der Work-Around gibt dem Datensatz
jeweils ein neues Attribut in der Edgelist auf der Grundlage der Frage,
ob eine Ausprägung von "2" in "weight", oder "relationship" gegeben ist.
Beide neuen Edge-Attribute beantworten diese Frage mit "TRUE" oder
"FALSE". Das neue Attribut "analysis_weight_strong" gibt so an, ob eine
starke Gewichtung der Beziehung vorliegt, oder nicht. Das neue Attribut
"analysis_relationship_strong" gibt an, ob eine starke Beziehungsart
(als "2" kodiert) vorliegt, oder nicht.

Das gleiche geschieht in der Node-List: Hier wird im ersten Set-Up-Chunk
dieser Rmd-Datei das **Node-Attribut** "**analysis_test**" hinzugefügt,
welches auf der Grundlage der Frage, ob eine Ausprägung von "1" beim
Node-Attribut "type" vorliegt, oder nicht die Ausprägungen "TRUE" oder
"FALSE" verteilt.

Eine genaue [Anleitung zum
Work-Around](https://github.com/gllnxr/Stuttgart21/blob/main/Anleitung%20Work-Around%20Fehler%20SNA.pdf)
ist auf GitHub hinterlegt.

## Team, Arbeitsaufwand und Lessons Learned

### Teammitglieder

Louis Göllner, Sinan Korkmaz, Mia Müller, David Vogt, Paul Antwerpes

### Arbeitsaufwand und Rollen im Team

Louis Göllner: Projektleitung, Recherche, Auswertung und Visualisierung,
Zwischenpräsentation, Poster-Session und Coding\
Sinan Korkmaz: Recherche, Auswertung und Visualisierung, Coding\
Mia Müller: Recherche, Teil des Forschungsberichts\
David Vogt: Recherche, Auswertung und Visualisierung,
Zwischenpräsentation, Coding\
Paul Antwerpes: Recherche, Auswertung und Visualisierung

**MVP** (Most Valuable Member): Louis Göllner

### Lessons learned

Die größte Herausforderung dieses Projektes war die umfangreiche
Recherchearbeit. Diese musste auf die einzelne Gruppenmitglieder
aufgeteilt werden, um mit der Datenmenge zurecht zu kommen. Dieses
Vorgehen zog aber mit sich, das die Projektplanung um einiges
schwieriger wurde, da parallel gearbeitet wurde. Zudem war der
Datenzugang erschwert: Der Mangel an Informationen zu allen kleineren
Akteur\*innen rund um das Projekt S21 und die teils variierende
Informationslage machten die Arbeit im Sommer schwieriger. Auch die
Menge an Berichten, Pressemitteilungen und Meldungen, welche separat
überprüft werden mussten war sehr aufwendig und schluckte viel Kapazität
einzelner Gruppenmitglieder. Darüber hinaus waren einige
Gruppenmitglieder versierter im Umgang mit RStudio als andere, musste
die Arbeit am Code auch genau abgesprochen werden.

Einer der Lernfolge für uns als Team war es, den Nutzen der
Netzwerkanalyse in unserem späteren Berufsfeld anhand des Projektes zu
erkennen. In den vergangenen Monaten hat man als Gruppe sehr viel
gelernt: Die Arbeit im Team über einen längeren Zeitraum ist
anspruchsvoller, als eine Gruppenarbeit nur auf kurze Zeit. Eine gute
Projektplanung im Vorhinein hat uns vor vielen bösen Überraschungen
bewahrt und verhalf zu einem guten Überblick über To-Do's und den
Fortschritt als Team. Und es wurde bewusst, welche Dimensionen solche
Projekte einnehmen können und wie diese die Teamarbeit fordern und
nachhaltig prägen.
