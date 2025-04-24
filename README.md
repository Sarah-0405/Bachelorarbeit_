# Bachelorarbeit_

Dieses Repositorium beinhaltet die Codes zum Methodik Teil der Bachelorarbeit "Charakterisierung von Cold Spots der Landoberflächentemperatur in bayerischen Städten mit Hilfe von Satellitendaten". 

Die Notebooks "Gitterzellen_auf_Stadtgebiet_zuschneiden" und "CSV-Tabellenbereinigung" bereiten die Zensusdaten auf die weiteren Analysen vor. 
Im Notebook "Cluster_Analysis_Zensus" werden die Bevölkerungsdaten räumlich analyisert und geclustert. 

Das Notebook "LST_calculations_Landsat8" beinhaltet alle Schritte zur Berechnung der mittleren und maximalen LST zu den verschiedenen Zeitpunkten. Darauf basierend werden im Notebook "Cold_Spots_Analysen" die Cold Spots definiert.

In "ERA-5-visualizations" und "CORINE" werden die LST Daten validiert, indem sie mit der 2-m-Temperatur sowie Daten zur Landbedeckung verglichen werden. 

Das Notebook "OSMnx_accessibilities" beinhaltet schließlich den Bezug der Fußwegenetz und die Berechnung zonaler Statistiken bezüglich der Erreichbarkeit von Cold Spots. 

Die in QGIS erstellten Isochrone der Erreichbarkeitszonen sind hier als Shapefiles enthalten. 

Zusätzlich beinhaltet das "Übersichtskarten_OSM"-Notebook den Vorgang zum Erstellen allgemeiner Karten zur Einordnung der Stadtgebiete, basierend auf der OpenStreetMap
