# Usecase Checkout
  
## Kurzbeschreibung
Nachdem ich als Anwender ein oder mehrere Produkte gesucht, diese der Liste hinzugefügt und mich mittels eines Vergleichsalgorithmus' für eine Bestell-, Anbieter, -Lieferoption entschieden habe soll der Kaufprozess eingeleitet werden.

Hierfür sollen perspektivisch mehrere Optionen zur Verfügung stehen:

### Weiterleitung (Prio 1)
Unterstüzung des Kaufs durch Weiterleitung auf die Seiten der Anbieter der gewählten Kaufoption. 
Wünschenswert: Vorbefüllung des Einkaufskorbs des Käufers beim jeweiligen Anbieter um den Kaufprozess so kurz wie möglich zu gestalten.

### Dropshipping (Prio 2)
Integrierte Bestellung der ausgewählten Kaufoption direkt auf der eigenen Platform. Nachgeorderte Bestellvorgänge werden gestartet und die Produkte direkt zum Nutzer versand.
Zu beatrachten: Rücksendungen und Abwicklung muss in der Verantwortung der eigenen Plattform dunrchgeführt werden.
Vorteil: Keine Lagerhaltung!

### Eigene Produkte (Prio 3)
Als letzte Option soll die Führung eigener Produkte (begonnen mit vereinzelten vielversprechenden Verkaufsgaranten) inkl. Versand, Lagerhaltung etc. betrachtet werden.


## Akteure
  | Typ   -| Beschreibung|
  |--------|-------------|
  | Käufer | Privater Nutzer der Applikation, der nach Artikeln suchen möchte um diese in einen Preisvergleich zu bringen.| 
  |Verkäufer|Verkäufer dessen Produkte auf unserer Plattform gelistet sind und entsprechend angeboten werden.|
  
## Vorbedingungen
- Applikation gestartet
- Startseite geladen
- Käufer ist sich seines Suchziels bewusst
- Produktsuche durchgeführt
- Ein oder mehrere Produkte der Liste hinzufügen
- Preisverlgeich durchgeführt
- Für Checkoutoption entschieden.

## Fachlicher Auslöser
- Preisvergleich wurde erfolgreich durchgeführt und der Anwender möchte die gewählte Kaufoption kaufen.
  
## Ergebnis
- Kaufprozess abgeschlossen.

## Hauptszenario
Als Nutzer habe ich bereits den Preisvergleich abgeschlossen und mich auf Basis der Ergebnisse für eine Kaufoption entschieden. Durch Auswahl der Kaufoption wird diese (vorerst) durch Weiterleitung auf die entsprechenden Verkaufsseiten initiiert und begleitet, bis zu einem bestätigten Kaufabschluss.
