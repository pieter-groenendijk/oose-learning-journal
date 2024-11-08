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
_Leerervaring_  
_Blok: 1; Week: 4_  

#### Bewustzijn
##### Inhoudelijk
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

##### Methode
De gegeven lessen zorgde voor de grote lijn in het verhaal. Een aanknoppunt om vervolgens het onderwerp verder te 
onderzoeken. 

Het chaotische beeld vergaart uit de eerste les zorgte ervoor dat ik achteraf zelf aan de gang ging. 

Hier vond ik onder de les meerdere bestanden gaande over het onderwerp. Ik scande elk om zo te kunnen vaststellen of deze
nu nuttig voor mij zouden zijn.

Ik heb verschillende documenten op _onderwijsonline_ gescant. _"A Friendly Introduction to Software Testing"_ leek momenteel
het meest nuttig. Specifiek het hoofdstuk genaamd _"Test Driven Development"_. Dit hoofdstuk ben ik vervolgens in detail gaan
lezen.

##### Nut
_TDD_ is een effectieve manier om kwaliteit binnen code waar te borgen. Tests zorgen ervoor dat de _requirements_ zowat rechtstreeks
in de code verwerkt zijn. Dit zorgt naar mijn mening voor twee postieven:
- Het is herleidbaar wat de rol van de functie is. Als _clean_ code en de documentatie faalt, kunnen de tests nog inzicht bieden in
de rol van de code.
- De tests zorgen ervoor dat code niet gemakkelijk functionaliteit kan verliezen. Indien men per ongeluk gewenste functionaliteit
verwijdert uit de code zal er een _regression_ plaatsvinden. De developer heeft inzicht wanneer dit gebeurt en kan hier naar handelen.


#### Evaluatie
##### Inhoudelijk
Ik begrijp goed hoe _TDD_, en de concepten daarbinnen, theoretisch in elkaar steken. Het is verstandig
om het nu proberen toe te passen; het praktische.

_Basic_ _unit tests_ kan ik wel implementeren. _Mocks_ en _stubs_ heb ik nog moeite mee. 

##### Methode
De methode om te leren lijkt effectief te zijn. Geen reden om het complexer te maken.

Ik ben zeker dat ik het theoretisch goed begrijp. Ik kan gemakkelijk aan iemand anders het onderwerp uitleggen. Dit is voor mij bewijs
dat ik de theorie begrijp. 

##### Nut
Ik geloof in het nut van _TDD_. Dit baseer ik op het volgende:
- **Vele vacatures vereisen _TDD_**: Het is moeilijk te geloven dat zoveel bedrijven en mensen hun tijd verspillen
zonder dat ze er iets uit halen. Dit zijn nadrukkelijk niet de instapbanen.
- **Het wordt gegeven op school**: Het is moeilijk te geloven dat een grote onderwijsinstantie zoals de HAN geen 
eigen onderzoek heeft verricht naar het nut van _TDD_.
- **Verhalen van gebruikers _TDD_**: Het is moeilijk te geloven dat de verhalen zoals die van Ronald nergens op gebaseerd zijn.

#### Regulatie
##### Inhoudelijk
_Mocks_ en _stubs_ moet ik meer aandacht in steken. Het lijkt mij verstandig hier specifiek wat meer theorie over te lezen. 
Het hoofdstuk _Test Doubles_ in het eerder besproken boek is hier handig. 

Verder is het van belang dat ik praktisch ermee omga. 

##### Methode
Het is fijn om kennis op te doen. Het is nog fijner de kennis vast te houden. Daarom is puur de theorie lezen niet genoeg. 
Ik stel voor de kern uit het hoofdstuk samen te vatten in een eigen document. Het maken van een samenvatting zorgt ervoor 
dat ik het later snel terug kan lezen indien ik iets vergeten ben.

##### Nut
Het begrijpen van _TDD_ zorgt ook voor een interesse in _Behavioral-driven development_. Pluspunten worden in _BDD_ nog
groter onder de loep genomen.


### Bericht 3: Design Patterns
_Leerervaring in relatie tot professionele ontwikkeling_  
_Blok: 1; Week: 4_   


#### Bewustzijn
##### Nut
Het begrijpen en toepassen van _design patterns_ is van hoge waarde voor mijn professionele ontwikkeling. Correcte
toepassing van deze _patterns_ zorgt ervoor dat veelvoorkomende problemen in software design effectief kunnen
worden opgelost, zonder elke keer het wiel moeten opnieuw uit te vinden.

##### Obstakels
Als zelfstandig _fullstack developer_ is mijn productiviteit van groot belang. De prijzen die ik declareer zijn 
doorgaans gebaseerd op de functionaliteit die ik lever, niet op een doorlopend uurtarief (de _waarom_ is voor nu weggelaten). 
Als ik vertraag, vertraagt de oplevering van het project en daarmee mijn betaling.  

##### Gerelateerde doelen
Vloeiend uit het benoemde obstakel komt het doel:

Ik wil een project van vergelijkbare schaal en complexiteit sneller kunnen afronden, zonder kwaliteit daarmee in te leveren. 

Dit is een doel wat waarschijnlijk nooit echt zal verdwijnen. Dit doel geldt altijd relatief tot een (vorig) moment. 

#### Evaluatie
Het leren van _design patterns_ laat mij zien dat het behalen van het genoemde doel haalbaar is. Door technieken
zoals deze te leren is het inderdaad mogelijk om de ontwikkeldsnelheid van een project significant positief te 
beinvloeden.

Hoewel het gebaseerd is op gevoel, kan ik wel met enige zekerheid zeggen dat ik beter ben geworden in het designen van 
object georienteerde applicaties. De _patterns_ hebben daarmee geholpen. Niet per se omdat ik inhoudelijk de _patterns_
nooit eerder heb gezien, maar omdat ze mij helpen de structuur van een applicatie te kunnen abstraheren, en daarmee te kunnen
verwoorden. 

#### Bron Obstakels
Dit obstakel is simpelweg oplosbaar door te gaan declaren op een vast uurtarief, niet de waarde van een functionaliteit.
Echter denk ik niet dat onverwachte kosten helpen met het behouden van een transparante relatie. 

#### Regulatie






































