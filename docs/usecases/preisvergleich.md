# Usecase Preisevergleich

## Kurzbeschreibung

Als Endanwender sollen mir Produkte (1-n) aus meinem Warenkorb preislich verglichen und aufgelistet werden. Die Produkte sollen nach verschiedenen Kriterien gelistet und sortiert werden können.
Sortier und Filterung erfolgt nach folgenden Kriterien:

- lokalität der Shops/Produkte
- Eco friendly delivery
- Shop Bewertung
- Bester Preis / Gesamtpreis

## Akteure

| Typ    | Beschreibung                             |
| ------ | ---------------------------------------- |
|        |                                          |
| Käufer | Der Endanweder der den Vergleich auslößt |

## Vorbedingungen

Use Case **Produktsuche** muss ausgeführt worden sein und mindestens 1 Artikel in den Warenkorb gelegt worden sein.

## Fachlicher Auslöser

Der Endanwender des Systems möchte einen Vergleich seiner Artikel im Warenkorb durchführen, um den Warenkorb anhand seiner preferierten Kriterien zu filtern und in dem dafür passenden shop/shops zu bestellen.

## Ergebnis

Eine Auflistung von Bestellmöglichkeiten, bestehend aus einer Kombination aus Produkten und Shops.

## Hauptszenario

Nachdem der Benutzer nach Use Case **Produktsuche** Artikel in den Metakorb gelegt hat, ruft er über die Funktion Preisvergleich den Service auf der ihn auf die Ergebnisseite leitet. Dort wird dem Nutzer verschiedene Filter Möglichkeiten geboten, um die Bestellmöglichkeiten nach unterschiedlichen Algorithmen zu sortieren.
