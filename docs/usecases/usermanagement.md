# Usecase usermanagement
  
## Kurzbeschreibung
Als Admin möchte ich die Möglichkeit besitzen, 
- User im System sehen
- Gruppen erstellen können
- Rollen erstellen können
- User zu Gruppen hinzuzufügen können
- zu sperren und updaten können.


## Akteure
  | Typ | Beschreibung|
  |-----|-------------|
  |     |             | 
  | Admins | Benutzer des System mit besonderen Rechten und Zugriffen |
  
## Vorbedingungen
- System ist gestartet
  
## Fachlicher Auslöser
- Manuelles lösen von User spezifischen Problemen die während des Betriebes aufgetreten sind.
- Hinzufügen von Gruppen/Rollen zum verwenden in anndern Teilen der Applikation
  
## Ergebnis
Dem Benutzer (Admin) liegt ein eigener Bereich oder eine eigene Applikation zum steuern der Benutzerdaten vor. 
Dieser Bereich ist durch **[authentifizieren/authorisieren](./anwender-authentifizieren-authorisieren.md)** geschützt 
und kann nicht von unauthorisierten Benutzern aufgerufen werden.
  
## Hauptszenario
Der Admin erstellt neue Gruppen und Rollen, die in der Applikation verwendet werden sollen. Dazu öffnet er die Usermanagementansicht und fügt entsprechende Rollen oder Gruppen hinzu. 
Dabei können in der Applikation verschiedene Probleme auftauchen. Beispielsweise tritt ein konkretes Problem mit Benutzerdaten auf, dass nicht vorgesehen war, wie ein Benutzer wurde nicht der erwarteten Gruppen hinzugefügt.
Der Admin öffnet den geschützen Bereich um Daten eines Benutzers zu verändern. Er sucht nach dem betroffenen User und fügt eine weitere Gruppe dem User hinzu. 

