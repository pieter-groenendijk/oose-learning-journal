# (OOSE) Learning Journal
Een (HAN) opdracht voor het vak OOSE.

## Inleiding
### Context
Het is belangrijk om te leren van het leerproces. Om dit succesvol te doen is er intense reflectie nodig. Men zou moet 
letten op de _"wat"_, _"hoe"_ en _"waarom"_ vragen.

Om echt nut te hebben aan reflectie moet er een doel uit moeten komen. Een concreet doel waar men aan kan werken. Dat
is niet mogelijk zonder eerst bewust te zijn van zijn eigen leerproces. Reflectie levert de beste antwoorden, in de vorm
van doelen, wanneer men zichzelf kritisch de moeilijke vragen stelt. Dat is de kern van dit document.

Het is natuurlijk leuk om nieuwe technieken en methodes te leren. De lesstof van HBO-ICT zou uiteindelijk moeten dienen 
als ontwikkeling richting een carrière. Nu is het de vraag of de lesstof in werkelijk relevant is. Daar heeft een
deeltijdstudent geluk; het is al mogelijk om het (gedeeltelijk) te relatieveren tot de beroepspraktijk. 

### Opdeling
Het document is opgedeeld per bericht. Een bericht zal zowel het onderwerp als de evaluatie en regulatie bevatten.

## Inhoud

## Berichten

### Bericht 1: Use Cases
_Blok: 1; Week 2_

- **Overschrijven vanuit telefoon.**

### Bericht 2: Test Driven Development
_Blok: 1; Week: 4_  

#### Bewustzijn
##### Onderwerp
In lesweek 4 werd het onderwerp: _"test driven development"_ aan ons voorgelegd. Dit is dan ook het onderwerp waarop 
dit bericht zich op richt.

_Unit tests_ worden niet alleen in _test driven development_ gebruikt. Natuurlijk hebben ze wel een zeer belangrijke rol.
_Test driven development_ onderscheidt zich voornamelijk in de volgorde.

_TTD_ is een techniek die (naar mijn mening) bestaat uit de volgende primaire punten, namelijk:
1. **Tests worden eerst geschreven, daarna de code:** Er wordt eerst gefocust op _wat_ de consequenties van een (nog niet) geschreven
stuk code zal zijn. _TDD_ is een vorm van _test-first development_.
2. **Code logica wordt geimplementeerd in hoeverre de tests dan toestaan:** Er wordt alleen code geschreven om de 
al geschreven tests (zie vorige punt) te laten slagen.

Het schrijven van software met _TDD_ volgt de _Red-Green-Refactor Loop_. Deze cyclus bestaat uit de volgende toestanden:
1. **Red:** Een geschreven test _faalt_[^1]. De developer zal de code aanpassen totdat deze slaagt zonder dat andere tests beginnen te falen. 
Dan gaat men door naar de volgende toestand.
2. **Green:** Alle test werken; de code doet het. Hoogwaarschijnlijk ziet de code er niet _clean_ uit. Voor die reden gaat men naar de volgende
toestand.
3. **Refactor:** De geschreven code wordt gerefactored tot een _clean_ geheel. Hier worden nogsteeds tests uitgevoed om een _regression_
tegen te gaan. _First make it green, then make it green._

[^1]: De test is correct geschreven en functioneert. Met falen wordt bedoelt dat de geschreven code niet voldoet aan de 
eisen die getest worden.

##### Aanpak
De gegeven lessen zorgde voor de grote lijn in het verhaal. Een aanknoppunt om vervolgens het onderwerp verder te 
onderzoeken. 

Het chaotische beeld vergaart uit de eerste les zorgte ervoor dat ik achteraf zelf aan de gang ging. Ik begon mijn 
zoektocht binnen _onderwijsonline_. 

Hier vond ik onder de les meerdere bestanden gaande over het onderwerp. Ik scande elk om zo te kunnen vaststellen of deze
nu nuttig voor mij zouden zijn.

Het boek _"A Friendly Introduction to Software Testing"_ leek mij te kunnen helpen. Specifiek het hoofdstuk genaamd 
_"Test Driven Development"_. Dit hoofdstuk heb ik gelezen.

##### Bruikbaarheid
_TDD_ is een effectieve manier om kwaliteit binnen code waar te borgen. Tests zorgen ervoor dat de _requirements_ zowat rechtstreeks
in de code verwerkt zijn. Dit zorgt naar mijn mening voor twee postieven:
- Het is herleidbaar wat de rol van de functie is. Als _clean_ code en de documentatie faalt, kunnen de tests nog inzicht bieden in
de rol van de code.
- De tests zorgen ervoor dat code niet gemakkelijk functionaliteit kan verliezen. Indien men per ongeluk gewenste functionaliteit
verwijdert uit de code zal er een _regression_ plaatsvinden. De developer heeft inzicht wanneer dit gebeurt en kan hier naar handelen.


#### Evaluatie
##### Onderwerp

##### Aanpak

##### Bruikbaarheid


#### Regulatie

##### Onderwerp

##### Aanpak

##### Bruikbaarheid

###

## Conclusie
