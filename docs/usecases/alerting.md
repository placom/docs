# Usecase Alerting
  
## Kurzbeschreibung
Je nach eingenommener Rolle (Käufer, Verkäufer) sollen unterschiedliche Benachrichtigungen möglich sein, die bei vorher definierten Events ausgelöst werden.

Events sollen vom Anwender spezifisch und umfangreich definiert werden können.

### Käufer
Für den Käufer sind folgende Alerts interessant:
- Produkt wieder verfügbar
- Produkt unter bestimmten Preis
- Produktzusammenstellung als ganzes wieder verfügbar
- Produktzusammenstellung unter einem bestimmten Preis
- Ausgewählte Kaufoption wieder verfügbar.
- Neuer Verkäufer führt markierten Artikel
- etc.

### Verkäufer
- Eigenes Produkt befindet sich / befindet sich nicht mehr im Marktvergleich in einem bestimmten Segment
- Konkurrenz führt markiertes Produkt /führt markiertes Produkt nicht mehr
- etc.

  
## Akteure
  | Typ | Beschreibung|
  |-----|-------------|
  | Käufer | Privater Nutzer der Applikation, der nach Artikeln suchen möchte um diese in einen Preisvergleich zu bringen.| 
  |Verkäufer|Verkäufer, dessen Produkte auf unserer Plattform gelistet sind und entsprechend angeboten werden.|  

## Vorbedingungen
- Alerting wurde vom Anwender definiert.

## Fachlicher Auslöser
- Definiertes Ereignis tritt ein

## Ergebnis
- Der Anwender wird über das Eintreten seines selbst definierten Events per E-Mail / SMS / Push-Msg o.ä. benachrichtigt.

## Hauptszenario
Als Käufer möchte ich benachrichtigt werden, wenn eine Produktzusammenstellung unter einem bestimmen Preis erhältlich ist. Hierfür suche ich diese Produkte einzeln in der Produktsuche zusammen und füge Sie meinem "Warenkorb" hinzu. Anschließend erstelle ich einen Alert für die eben definierte Produktzusammenstellung indem ich zusätzlich zu den Produkten noch einen zu unterschreitenden Preis hinzufüge. Sobald die definierte Prämisse eintritt, werde ich vom System benachrichtigt und entsprechend wieder zu einem analogen Warenkorb geleitet um meine Bestellung zum aktuellen Preis (unterhalb meiner Alert Einstellung) fortführen bzw. abschließen zu können.