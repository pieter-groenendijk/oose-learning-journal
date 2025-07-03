## Test Driven Development
_Leerervaring_  
_Blok: 1: Week: 4_  

### Bewustzijn
#### Onderwerp 
In lesweek 4 werd het onderwerp: _"test driven development"_ aan ons voorgelegd. Dit is dan ook het onderwerp waarop 
dit bericht zich op richt.

_Unit tests_ worden niet alleen in _test driven development_ gebruikt. Natuurlijk hebben ze wel een zeer belangrijke rol.
_Test driven development_ legt een grote focus op _units tests_, dat is het verschil.

_TTD_ is een techniek die (naar mijn mening) bestaat uit de volgende primaire punten, namelijk:
1. **Tests worden eerst geschreven, daarna de logica:** Er wordt eerst gefocust op _wat_ de consequenties van een (nog niet) geschreven
stuk code zal zijn. _TDD_ is een vorm van _test-first development_.
2. **Code logica wordt geïmplementeerd in hoeverre de tests dan toestaan:** Er wordt alleen code geschreven om de 
al geschreven tests (zie vorige punt) te laten slagen.

Het schrijven van software met _TDD_ volgt de _Red-Green-Refactor Loop_. Deze cyclus bestaat uit de volgende toestanden:
1. **Red:** Een geschreven test _faalt_. De developer zal de code aanpassen totdat deze slaagt zonder dat andere tests beginnen te falen. 
Dan gaat men door naar de volgende toestand.
2. **Green:** Alle test werken; de code doet het. Hoogstwaarschijnlijk ziet de code er niet _clean_ uit. Voor die reden 
gaat men naar de volgende toestand.
3. **Refactor:** De geschreven code wordt gerefactored tot een _clean_ geheel. Hier worden nog steeds tests uitgevoerd 
om een _regression_ tegen te gaan. 


#### Proces
De gegeven lessen zorgde voor de grote lijn in het verhaal. Een aanknooppunt om vervolgens het onderwerp verder te 
onderzoeken. 

Het chaotische beeld vergaart uit de eerste les zorgde ervoor dat ik achteraf zelf aan de gang ging. Ik kwam hierbij
een boek tegen op onderwijsonline: _"A Friendly Introduction to Software Testing"_. Specifiek het hoofdstuk genaamd 
_"Test Driven Development"_. Dit hoofdstuk heb ik vervolgens in detail gelezen.

#### Nut
_TDD_ is een effectieve manier om kwaliteit binnen code waar te borgen. Tests zorgen ervoor dat de _requirements_ zowat rechtstreeks
in de code verwerkt zijn. Dit zorgt naar mijn mening voor twee voordelen:
- Het is herleidbaar wat de rol van de functie is. Als _clean_ code en de documentatie faalt, kunnen de tests nog inzicht bieden in
de rol van de code. Zo zou iemand dus bijv. achter een randvoorwaarde van de functie kunnen herleiden.
- De tests zorgen ervoor dat code niet gemakkelijk functionaliteit kan verliezen. Indien men per ongeluk gewenste functionaliteit
verwijdert uit de code zal er een _regression_ plaatsvinden. De developer heeft inzicht wanneer dit gebeurt en kan hier naar handelen.


### Evaluatie
#### Onderwerp
Ik begrijp goed hoe _TDD_, en de concepten daarbinnen, theoretisch in elkaar steken. Het is verstandig
om het nu proberen toe te passen; het praktische.

_Basic_ _unit tests_ kan ik wel implementeren. _Mocks_ en _stubs_ heb ik nog moeite mee. 

#### Effectiviteit Proces 
De methode om te leren lijkt effectief te zijn. Geen reden om het complexer te maken.

Ik ben zeker dat ik het theoretisch goed begrijp. Ik kan gemakkelijk aan iemand anders het onderwerp uitleggen. Dit is 
voor mij bewijs dat ik de theorie begrijp. 

#### Onderbouwing Nut
Ik geloof tenminste in het nut van _TDD_ uitproberen. Dit baseer ik op het volgende:
- **Vele vacatures vereisen _TDD_**: Het is moeilijk te geloven dat zoveel bedrijven en mensen hun tijd verspillen
zonder dat ze er iets uit halen. Dit zijn nadrukkelijk niet de instapbanen.
- **Het wordt gegeven op school**: Het is moeilijk te geloven dat een grote onderwijsinstantie zoals de HAN geen 
eigen onderzoek heeft verricht naar het nut van _TDD_.
- **Verhalen van gebruikers _TDD_**: Het is moeilijk te geloven dat de verhalen zoals die van Ronald nergens op gebaseerd zijn.

Het daadwerkelijke nut van _TDD_ baseer ik liever op harde feiten en ervaring. Dat heb ik momenteel nog niet.

### Regulatie
#### Onderwerp
_Mocks_ en _stubs_ moet ik meer aandacht in steken. Het lijkt mij verstandig hier specifiek wat meer theorie over te lezen. 
Het hoofdstuk _Test Doubles_ in het eerder besproken boek lijkt hier handig. 

Verder is het van belang dat ik de stof ga toepassen. Daarom ga ik _TDD_ minimaal 2 weken toepassen bij mij huidige
project. Natuurlijk gaat _TDD_ ook al bij de OOSE-casus gebruikt worden.

#### Proces 
Het is fijn om kennis op te doen. Het is nog fijner de kennis vast te houden. Daarom is puur de theorie lezen niet genoeg. 
Ik stel voor de kern uit het hoofdstuk samen te vatten in een eigen document. Het maken van een samenvatting zorgt ervoor 
dat ik het later snel terug kan lezen indien ik iets vergeten ben. Daarnaast ben ik ook simpelweg bezig met de stof, wat
ook al zeker zal helpen.

#### Nut
Het begrijpen van _TDD_ zorgt ook voor een interesse in _Behavioral-driven development_. Sommige pluspunten van _TDD_ worden 
in _BDD_ nog groter onder de loep genomen.
