# Usecase Produktstatistik
  
## Kurzbeschreibung
Als Anwender (Käufer, Verkäufer) möchte ich erweiterte Informationen über Produkte in Form von Statistiken abrufen können.

Interessante Informationen:
- min, avg, max Preis
- historische Entwicklung min, avg, max Preis
- durchschnittliche Lieferzeit
- durchschnittliche Bewertung
- historische Anzahl Käufe

## Akteure
  | Typ | Beschreibung|
  |-----|-------------|
   | Käufer | Privater Nutzer der Applikation, der nach Artikeln suchen möchte um diese in einen Preisvergleich zu bringen.| 
  |Verkäufer|Verkäufer, dessen Produkte auf unserer Plattform gelistet sind und entsprechend angeboten werden.| 
  
## Vorbedingungen
- Produktdaten wurden durch den "Crawl" Prozess zusammengesucht und zentral zur Auswertung gespeichert.

## Fachlicher Auslöser
Informationsbedürfnis

## Ergebnis
- Anzeige einer Statistikview die Auswertung nach unterschiedlichen Parametern ermöglicht und die Ergebnisse entsprechend anzeigt. 

## Hauptszenario
Als Käufer möchte ich die Preisentwicklung eines Produktes untersuchen um meine Kaufentscheidung zu beeinflussen. Befindet sich der Preis aktuell auf einem hoch warte ich ggf. nochmals bis der Preis sinkt. Zur Benachrichtigung soll ein Informationsmechanismus geschaffen werden (s. usecase Alerting) 
