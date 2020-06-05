# shinyClusteringMICR

## Allgemeines
Das Package ist als Bundle in Form eines komprimierten Archivs (.tar.gz) verfügbar.
Alle Daten, Abhängigkeiten und Dokumentation sind im Package enthalten.

## Installationsanweisungen
### Vorraussetzungen
- R: Version 3.4.4 oder höher.
- Webbrowser (getestet mit Firefox 76.0.1 oder höher).
- OS: Getestet mit Ubuntu 18.04.4
- *(Optional) R Studio 1.3.959 oder höher*
- Beste Darstellung der App bei einer Bildschirmauflösung von 2560 x 1440 px.
### Installation
Für die Installation wird das CRAN package [devtools](https://cran.r-project.org/web/packages/devtools/index.html) benötigt.
Installation über die R Console: `utils::install.packages("devtools")`

Anschließend lässt sich das Package in Bundleform mit dem Befehl\
`devtools::install_local("PATH/TO/shinyClusteringMICR_0.1.0.tar.gz", upgrade = FALSE)` installieren.\
Der Pfad im ersten Argument muss entsprechend angepasst werden.

Manche Abhängigkeiten benötigen zum Compilen bestimmte betriebssystemabhängige **libs**. Sind diese nicht vorhanden (oder nicht auffindbar), bricht der Prozess mit Fehlern (und Hinweisen zu den fehlenden **libs**) ab. Nachdem alle **libs** mit einem entsprechenden package-manager installiert wurden, den o.g. Befehl erneut ausführen.

Nach erfolgreicher Installation prüfen, ob das Package geladen werden kann: `library(shinyClusteringMICR)`

## Verwendung
Die App kann über die R Console mit der Funktion\
`shinyClusteringMICR::runShinyClusteringMICR()` im Standardbrowser gestartet werden.

Für eine Übersicht der vorhandenen Funktionen und detaillierte Dokumentation des Packages\
`?shinyClusteringMICR`\
-ODER-\
den Index der Dokumentation mit `help(package = "shinyClusteringMICR")` aufrufen.
