# Usecase Vergleichsliste
  
## Kurzbeschreibung
Dem Käufer soll es möglich sein seine durch die Produktsuche gefundenen Produkte einer "Vergleichsliste" hinzuzufügen. Entgegen bekannten Warenkörben werden hier allerdings keine konkreten Produkte eines bestimmten Anbieters gespeichert, sondern lediglich Produktbezeichnungen als Grundlage eines angestrebten Produktvergleiches über mehrere Anbieter hinweg. 

Die Vergleichsliste ist also die Grundlage des kombinierten Produktvergleiches über mehrere Anbieter und Lieferoptionen hinweg.

In der Vergleichsliste werden die aus der Produktsuche hinzugefügten Elemente angezeigt. Pro Produkt soll es möglich sein die Anzahl zu verändern und Elemente zu löschen.

Schlussendlich soll aus der Vergleichsliste heraus der Produktvergleich angestoßen werden und dort angebotene Kaufoptionen gewählt werden können.  

Wünschenswert wäre es, wenn der Zustand der Vergleichsliste je Käufer persistiert ist bzw. mehrere Vergleichslisten für sich wiederholende Vergleiche angelegt werden.
  
## Akteure
  | Typ | Beschreibung|
  |-----|-------------|
  | Käufer | Privater Nutzer der Applikation, der nach Artikeln suchen möchte um diese in einen Preisvergleich zu bringen.| 
  
## Vorbedingungen
-  Damit Produkte in der Vergleichsliste dargestellt werden können, müssen diese über dir Produktsuche hinzugefügt werden.

## Fachlicher Auslöser
- Elemente werden der Vergleichsliste über die Produktsuche hinzugefügt.
- Der Vergleichsliste ist die Grundlage des Produktvergleiches. 

## Ergebnis
- Belibige Anzahl von Vergleichslisten mit bekannten Produkten und Anzahl.

## Hauptszenario
Als Käufer möchte ich einen Einkauf so günstig wie möglich kaufen. Hierfür nutze ich pro Produkt die Produktsuche und füge aus dieser heraus Produkte einer neuen Vergleichsliste hinzu. Habe ich meine Suche abgeschlossen starte ich aus der Vergleichsliste heraus einen Produktvergleich, der mit mögliche Kaufioptionen anbietet.