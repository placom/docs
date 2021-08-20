# Usecase Anwender authentifizieren/authorisieren
  
## Kurzbeschreibung
Als Produktverantwortliche ist eine Authentifizierung aller Nutzer (Käufer, Verkäufer, Admin) unbedingt anzustreben. Darüber hinaus müssen bestimmte Nutzergruppen für nicht öffentlich zugängliche Bereiche authorisiert werden. 

Eine Authentifizierung über vielgenutzte Identity Provider ist zu überprüfen.

### Käufer
Durch authentifizierung der Nutzer soll eine Nutzung historischer Daten ermöglicht werden. Weiterhin kann der Warenkorb persistiert werden und somit ein durchgängiges Nutzererlebnis geschaffen werden.

### Verkäufer
Damit Verkäufer "Verkäuferfunktionen" (Über Verlgeichspreise informieren, Listing, Altering, Statistiken) nutzen können, müssen dieser sich als Verkäufer authentifizieren und eine entsprechende Authorisierung vorweisen.
Ggf. ist für eine Klassifizierung als Verkäufer ein weiterer Registrierungsmechanismus notwendig (Authorisierung).

### Admin
Produktverantwortliche müssen authentifiziert sein und authorisiert werden um einen Zugriff auf administrative Funktionen (User Management, Dashboarding, Monitoring, Crawler, etc.) zu erhalten

## Akteure
  | Typ | Beschreibung|
  |-----|-------------|
  | Käufer | Privater Nutzer der Applikation, der nach Artikeln suchen möchte um diese in einen Preisvergleich zu bringen.| 
  |  Verkäufer|Verkäufer, dessen Produkte auf unserer Plattform gelistet sind und entsprechend angeboten werden.|  
  | Admin | Produktverantwortliche, die administrative Aufgaben in der Applikation übernehmen  (User Management, Dashboarding, Monitoring, Crawler, etc.)|

  
## Vorbedingungen
--

## Fachlicher Auslöser
- Nutzung von Applikationsfunktionen die nicht dem öffentlichen Zugang unterliegen (Verkauf, Administration)  

## Ergebnis
- Applikationsnutzer ist authentifiziert
- Applikationsnutzer ist wenn zutreffend für Nutzung beschränkter Bereiche authorisiert. 

## Hauptszenario
Als Anwender authentifiziere ich mich normalerweise beim Anmelden am System, spätestens aber wenn ich eine "beschränkte" Funktionalität nutzen möchte, welche eine zug. authorisierung benötigt. Nach erfolgreicher Authentifizierung stehen mir alle Funktionen zur Verfügung die der zug. Authorisierung entsprechen.

D.h.
- Als Käufer stehen mir die öffentlich zugänglichen Funktionen zur Verfügung
- Als Verkäufer stehen mir Verkaufoptionen (Listing, Alerting, Statistiken) zur Verfügung
- Als Administrator stehen mir Funktionen zur administrativen Steuerung der Applikation zu Verfügung.
