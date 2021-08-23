# Usecase datencrawling
  
## Kurzbeschreibung
Es werden Daten von verschiedenen Quellen bezogen und ins System gespielt. Dazu läuft ein oder mehrere Services rekurrent um die Daten immer auf dem aktuellen Stand zu halten.
  
## Akteure
  | Typ | Beschreibung|
  |-----|-------------|
  |     |             | 
  |-----|-------------|
  
## Vorbedingungen
- System ist gestartet 
- **[importapi](./importapi.md)** ist erreichbar
  
## Fachlicher Auslöser
Damit die Applikation verwendet werden kann, benötigt diese Stammdaten auf denen die verschiedenen Usecases arbeiten. 

  
## Ergebnis
Das Ergebnis des Daten crawlings sind Produktmetainformationen, die in die Datenhaltung der Applikationen gespielt worden sind. 
  
## Hauptszenario
Ein Service ruft sämtliche Artikel und Produkte von einer oder mehreren Webseiten ab, parsed deren Metainformationen und speichert diese in einer bestimmten Objektstuktur. 
Diese Information wird zur Anwendung gesendet, die diese persistiert und für den Anwender aufbereitet.
