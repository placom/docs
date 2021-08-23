# Usecase importapi
  
## Kurzbeschreibung
Es sollen verschiedenen Quellen als Datenursprung in das System gespielt werden können damite dem Benutzer immer die besten Angebote zur Verfügung stehen. Dabei sollen automatische Systeme, als auch manuell importierte Daten beachtet werden können. 
Damit das System nicht zu peak Zeiten belastet wird, soll die Schnittstelle, möglichst zu pitzeiten die Daten updaten. 
  
## Akteure
  | Typ | Beschreibung|
  |-----|-------------|
  |     |             | 
  |-----|-------------|
  
## Vorbedingungen
- System ist gestartet 
- Datenbank erreichbar

  
## Fachlicher Auslöser
Der Endanwender des Systems möchte ich immer die aktuellsten Preise und Angebote von andern Anbietern vergleichen können. 
Der Verkäufer möchte seine Angebote selbst veröffentlichen. 
 
## Ergebnis
Eine Schnittstelle die unterschiedliche Datenformate harmonisieren und in das System einplegen kann. 
  
## Hauptszenario
- Der Verkäufer lädt eine Liste seine aktuellen Produkte und Angebote über die importapi hoch
- Der Datencrawler lädt automatisch gesammelte Daten über die importapi hoch

