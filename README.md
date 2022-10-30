# lobbytracker_v1_1

Ziel des Projektes ist es, die Daten des Lobbyregisters beim Deutschen Bundestag mit Daten aus anderen Datenquellen zusammenzuführen und auf diese Weise Abfragen über mehrere Datenquellen zu ermöglichen. 

## Vorgehen: 
Vorbereitend werden die Datenstrukturen angeglichen und Schreibweisen normalisiert. 
Aus diesen Daten wird unter Einsatz von Python und NetworkX ein Graph erstellt (Google-Colab-File; Skript AK_Entwurf_Lobbytracker.ipynb); in einem zweiten Skript können die Daten abgefragt und das Ergebnis der Abfrage in ein csv-File gespeichert werden (AK_Entwurf_Lobbytracker_Abfrage.ipynb).

## Derzeitiger Arbeitsstand: 
Die Skripte sind funktionsfähig; die Daten aus dem Lobbyregister beim Deutschen Bundestag (Stand: 20.09.2022) sind für diesen ersten Entwurf grob aufbereitet.

Im Bereich "data" sind die für diesen Entwurf aufbereiteten Daten aus dem Lobbyregister hinterlegt; mit diesen csv-Dateien kann das erste Skript "AK_Entwurf_Lobbytracker.ipynb" zum Aufbau des Graphen getestet werden. Danach ist eine weitere Aufarbeitung der erzeugten Daten erforderlich, die später noch dokumentiert wird. 

Im Bereich "data/graph" sind die aufbereiteten Daten für die Abfrage hinterlegt, die für das Ausführen des zweiten Skriptes "AK_Entwurf_Lobbytracker_Abfrage.ipynb" benötigt werden. Im Skript ist das Google-Colab-File verlinkt; die Daten werden beim Ausführen des Skriptes in den Zwischenspeicher bei Google Colab gespeichert, die erzeugten csv-Dateien können von dort heruntergeladen werden. 

## Nächste Schritte:
- Hinzufügen der Daten der Parteispenden-Datenbank von Lobbycontrol https://lobbypedia.de/wiki/Parteispenden-Datenbank und der Daten zu den Nebentätigkeiten der Mitglieder des Deutschen Bundestages von https://abgeordnetenwatch.de
- Dokumentation
