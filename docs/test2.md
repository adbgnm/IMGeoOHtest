# Wegdeel
Kleinste functioneel onafhankelijk stukje van een NEN 3610 Weg met gelijkblijvende  homogene eigenschappen en relaties en primair bedoeld voor gebruik door weg-  spoor- en vliegverkeer te land.  
## Inwinregels BGT

### Indeling



Om de wegdelen in te delen wordt een ordeningsprincipe gehanteerd. De

verzameling wegdelen wordt ingedeeld naar de functie van het wegdeel en naar het

fysieke voorkomen.



Het attribuut fysiek voorkomen geldt voor het gehele wegdeel. Een overgang van

fysiek voorkomen is dus altijd ook een grens tussen twee wegdelen. Het gaat

hierbij over het voorkomen waarmee het wegdeel overwegend is bedekt. Voor

minimale stukjes, 5m2, met andere verharding hoeft geen apart wegdeel te worden

gevormd.



### Regels voor opname



Bestrate gedeelten in voor- en achtertuinen van panden worden beschouwd als

onderdeel van het erf (onbegroeid terreindeel) en worden niet nader ingewonnen.



Brandgangen, met een openbaar karakter en waarvan de breedte \>0,90 m bedraagt,

worden opgenomen tot de bebouwingslijn van gebouwen als wegdeel type voetpad.

Brandgangen met een ontsluitingsfunctie van kennelijk openbaar terrein worden

altijd opgenomen.



![](https://raw.githubusercontent.com/Geonovum/IMGeo-dev/master/catalogus/bgt/8eeffe79b8eac59b938801ebe9da837b.jpg)



Voorbeeld van weg- en terreindelen



De kruinlijn moet bij het wegdeel worden opgenomen indien de helling een

verhouding heeft van verticaal:horizontaal van 1:4 of steiler en het

hoogteverschil \> 1 m bedraagt.



Eén van de zijden van het wegdeel valt altijd samen met de kruinlijn, zijnde

bovenkant talud. De coördinaten van de kruinlijn zijn identiek met die van de

objectbegrenzing ter plaatse. Het gedeelte van een object dat op het talud ligt,

is altijd een apart begrensd vlak ten opzichte van het deel van het object dat

niet op het talud ligt.



Als er meer dan een objecttype op een talud ligt, bevat alleen het hoogst

gelegen object een kruinlijngeometrie. De coördinaten van de kruinlijn zijn

identiek aan de coördinaten van de objectbegrenzing die samenvalt met de

kruinlijn.



### Aandachtspunten



Het begin van een wegdeel van een auto(snel)weg wordt aangegeven middels een

bord G01 (autosnelweg) en G03 (autoweg). Dit kan zijn ter plaatse van een

kruispunt. In de praktijk staat zo'n bord nooit precies op het kruispunt, maar

enkele meter verder, de praktische werking van het bord geldt vanaf dat

kruispunt.



Een autosnelweg kan ook beginnen zonder dat er kruispunt aanwezig is.



Het beëindigen van een wegdeel van een auto(snel)weg kan gebeuren door een bord

G2 (einde autosnelweg) of G04 (einde autoweg). Een autoweg kan ook eindigen bij

een kruispunt. Het bord G03 moet namelijk ná elk kruispunt worden herhaald.



Een autosnelweg kan ook eindigen zonder aanwezig kruispunt. Dan wordt het bord

G2 gebruikt en gaat de weg over in een regionale weg.



Bij een autoweg is er sprake van een, meestal fysieke, scheiding tussen langzaam

verkeer en snelverkeer.



Samenvattend geldt dat voor het begin en einde van een wegdeel van een

auto(snel)weg de plaats van het bord bepalend is, op basis van de betekenis in

het RVV 1990.



Molgoten langs wegdelen maken deel uit van dat wegdeel, ook als zij uit een

andere ver­harding bestaan. De buitenzijde van de molgoot vormt de begrenzing

van het wegdeel met vrijwel gelijke hoogte.



Een afsluitende band hoort bij het wegdeel, verkeerseiland of berm dat gelijk

ligt met de bovenzijde van de band.



Fietspaden vormen BGT inhoud indien aangeduid met een blauw bord met daarop een

wit rijwiel (bord G11 of G12a), of een blauw of zwart bord met daarop de tekst

“FIETSPAD” of “RIJWIELPAD” (bord G13). In IMGeo mogen stroken oranjekleurige

verharding voorzien van een wit rijwielsymbool worden opgenomen als fietspad.



Aaneengesloten parkeervakken die zijn bedoeld voor één voertuig, worden

ingewonnen als één aaneengesloten wegdeel waarbij functieWeg de waarde

‘parkeervlak’ heeft.



Uitsparingen in wegdelen, meestal van het type voetpad, voor stedelijk groen

worden niet afzonderlijk ingwonnen indien \<5 m2. Het wegdeel wordt daarbij

geacht door te lopen.



Belijning, kleur en symboliek zijn geen begrenzingen van wegdelen, zoals

rijbanen, OV-banen en parkeervakken. Een uitzondering geldt voor de

oranjekleurige fietsstroken voorzien van een wit rijwielsymbool. Deze worden

ingewonnen als fietspad.



Inritten (toegangswegen, oprijlanen) naar erven en terreinen vormen BGT inhoud

wanneer ze langer zijn dan 25 m. Kortere inritten kunnen worden opgenomen in

IMGeo.

## Inwinregels IMGeo

Ten behoeve van beheer kan een BGT wegdeel uit meerdere beheereenheden bestaan.

Men mag deze zo afbakenen als voor beheer gewenst is. Voor levering conform BGT

of IMGeo moeten voor de attributen de BGT respectievelijk IMGeo-domeinwaarden

zijn ingevuld.



In IMGeo kunnen inrichtingselementen, die op wegdelen voorkomen, worden

opgenomen met het objecttype weginrichtingselement.



-   Lijnafwatering wordt opgenomen als lijnobject. Geleideconstructie kan worden

    opgenomen als punt-, lijn- of vlakobject. Wegmarkeringen worden opgenomen

    als lijnobject als het gaat om belijning, en als puntobject als het gaat om

    symbolen op het wegdek



-   Wildrooster en rooster worden opgenomen als punt-, lijn- of vlakobject.



-   Grasklinkers die onderdeel zijn van een wegdeel kunnen worden opgenomen met

    fysiek voorkomen ‘half verhard: grasklinkers’.



-   In de BGT maken molgoten deel uit van een wegdeel. In IMGeo kunnen molgoten

    worden opgenomen als Weginrichtingselement type molgoot (lijngeometrie).



-   In de BGT maakt een afsluitende band deel uit van een wegdeel,

    verkeerseiland of berm. In IMGeo kan een band worden opgenomen als

    Weginrichtingselement type geleideconstructie.



-   In IMGeo kunnen stroken oranjekleurige verharding voorzien van een wit

    rijwielsymbool worden opgenomen als fietspad. Fietssuggestiestroken (zonder

    wit rijwielsymbool) vormen geen inhoud van IMGeo.



-   In de BGT worden aaneengesloten parkeervakken ingewonnen als één wegdeel. In

    IMGeo kunnen deze eventueel nader worden ingedeeld. Ook kan de belijning als

    weginrichtingselement worden opgenomen.



-   In de BGT worden uitsparingen in wegdelen voor stedelijk groen niet apart

    ingewonnen indien \< 5 m2. In IMGeo kunnen deze worden opgenomen als

    ‘begroeid terreindeel groenvoorziening’.



-   Wegmarkeringen zoals symbolen, belijning en kleur zijn geen BGT inhoud maar

    kunnen in IMGEO worden opgenomen als weginrichtingselement.



-   Inritten (toegangswegen, oprijlanen) naar erven en terreinen korter dan 25 m

    kunnen worden opgenomen als IMGeo inhoud.

## FunctieWeg
Specificatie van het hoofdgebruiksdoel van het wegdeel.
## FunctieWegPlus
Specificatie van het hoofdgebruiksdoel van het wegdeel, nadere classificatie.
## FysiekVoorkomenWeg
Mate waarin het wegdeel al of niet verhard is.
## FysiekVoorkomenWegPlus
Mate waarin het wegdeel al of niet verhard is, nadere classificatie.
# OndersteunendWegdeel
Een deel van de weg dat niet primair bedoeld is voor gebruik door het verkeer. 
## Inwinregels BGT

### Indeling



Dit object kent een onderverdeling in de typen verkeerseiland en berm. Berm kent

als fysiek voorkomen de verschillende verhardingssoorten en groenvoorziening.



### Regels voor opname



In de regel is dit object scherp begrensd met het aanliggende wegdeel door

bijvoorbeeld een band of de kant van de verharding. Als een berm bestaat uit een

deel verhard en een deel begroeid, ontstaan er voor de BGT twee objecten

OndersteunendWegdeel.



De niet-wegdeel begrenzing van een begroeide berm met een aanliggend begroeid

terrein zal niet altijd even duidelijk herkenbaar zijn. Als begrenzing hanteert

men dan een herkenbare overgang met een ander gewas of een ander maairegime.



Bij een naast een wegdeel liggend waterdeel geldt dat als de afstand tussen

wegdeel en kant insteek \> 30 cm bedraagt, het deel daartussen als berm wordt

opgenomen. Mogelijke waterbegrenzingen staan beschreven bij Waterdeel.



De kruinlijn moet bij het ondersteunend wegdeel worden opgenomen indien de

helling een verhouding heeft van verticaal:horizontaal van 1:4 of steiler en het

hoogteverschil \>1m bedraagt. Eén van de zijden van het ondersteunend wegdeel

valt altijd samen met de kruinlijn, zijnde bovenkant talud. De coördinaten van

de kruinlijn zijn identiek met die van de objectbegrenzing ter plaatse. Het

gedeelte van een object dat op het talud ligt is altijd een apart begrensd vlak

ten opzichte van het deel van het object dat niet op het talud ligt.



Als er meer dan een objecttype op een talud ligt, bevat alleen het hoogst

gelegen object een kruinlijngeometrie. De coördinaten van de kruinlijn zijn

identiek aan de coördinaten van de objectbegrenzing die samenvalt met de

kruinlijn.

## Inwinregels IMGeo

Grasklinkers liggen soms naast een wegdeel in de berm. Het betreffende vlak

vormt dan een afzonderlijk ondersteunend wegdeel. Wanneer een berm bestaat uit

een deel gras en een deel grasklinkers zijn dat twee verschillende objecten

-ondersteunend wegdeel- voor IMGeo/BGT; berm met als fysiek voorkomen

respectievelijk groenvoorziening gras en half verhard grasklinkers.

## FunctieOndersteunendWegdeel
Specificatie van de functie van het ondersteunend wegdeel.
## FunctieOndersteunendWegdeelPlus
Specificatie van het soort ondersteunend wegdeel, nadere classificatie.
## FysiekVoorkomenOndersteunendWegdeel
Mate waarin het ondersteunend wegdeel al of niet verhard is.
## FysiekVoorkomenOndersteunendWegdeelPlus
Mate waarin het ondersteunend wegdeel al of niet verhard is, nadere classificatie.
# Spoor
De as van het spoor  dat wil zeggen het midden van twee stalen staven op een onderling vaste afstand  waarover trein  tram  of sneltram rijdt. 
## Inwinregels BGT

### Regels voor opname



Het midden tussen de twee staven van een spoor, de as van het spoor, wordt als

lijn vastgelegd.



De as van elk afzonderlijk spoor wordt weergegeven.

## FunctieSpoor
Specificatie van het soort gebruik van het spoor.
## FunctieSpoorPlus
Specificatie van het soort gebruik van het spoor, indien dit een IMGeo uitbreiding van de populatie betreft.
# OnbegroeidTerreindeel
Kleinste functioneel onafhankelijk stukje van een terrein  dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden  zonder aaneengesloten vegetatie. 
## FysiekVoorkomenOnbegroeidTerrein
Classificatie van het soort terrein, ingedeeld naar de uiterlijke verschijningsvorm.
## FysiekVoorkomenOnbegroeidTerreinPlus
Nadere classificatie van het soort terrein, ingedeeld naar de uiterlijke verschijningsvorm.
# BegroeidTerreindeel
Kleinste functioneel onafhankelijk stukje van een terrein dat er binnen het objecttype Terrein van NEN 3610 wordt onderscheiden  met aaneengesloten vegetatie. 
## FysiekVoorkomenBegroeidTerrein
Classificatie van het vegetatiedek, ingedeeld naar soort vegetatie.
## FysiekVoorkomenBegroeidTerreinPlus
Nadere classificatie van het vegetatiedek, ingedeeld naar soort vegetatie.
# Waterdeel
Kleinste functioneel onafhankelijk stukje water met gelijkblijvende  homogene eigenschappen en relaties dat er binnen het objecttype Water van NEN 3610 wordt onderscheiden en dat permanent met water bedekt is. 
## Inwinregels BGT

De volgende paragrafen beschrijven op welke wijze land en water zijn gescheiden

in de BGT.



### Algemeen



De BGT kent vier typen waterdeel: · zee; · waterloop; · watervlakte; · greppel,

droge sloot. En twee typen ondersteunend waterdeel: · oever, slootkant; · slik.



De kruinlijngeometrie wordt bij het ondersteunend waterdeel niet opgenomen.

Impliciet is de – niet-waterbegrenzing – van een oever altijd de hoogste kant.



Voor de begrenzing van land en zee maakt de BGT onderscheid in de begrenzing

langs de Noordzee enerzijds en die langs de Waddenzee en de Zuidwestelijke delta

in Zeeland en Zuid-Holland anderzijds.



Onder waterlopen vallen rivieren, kanalen, beken, sloten en grachten.



Watervlakten zijn meren, plassen, vennen en vijvers. Ook havens vallen in de

regel hieronder.



Greppels en droge sloten hebben een functie in de waterhuishouding.



Oevers en slootkanten zijn de delen die enerzijds begrensd worden door de

waterlijn en anderzijds door een kant insteek.



Slikken zijn bij laagwater droogvallende delen. Zij komen uitsluitend voor in de

Waddenzee en in de Zuidwestelijke delta.



In het algemeen geldt dat zichtbare topografie altijd als begrenzing voorkomt,

in de beschreven situaties aangevuld met niet of niet-altijd zichtbare

topografische begrenzingen.



### Noordzee



Voor de begrenzing van terrein en water langs de Noordzee gebruikt de BGT de

UNCLOS-basislijn. Deze basislijn valt onder verantwoording van de Dienst der

Hydrografie van het ministerie van Defensie. Deze dienst voert deze taak uit op

basis van het Zeerechtverdrag van de Verenigde Naties uit 1982 "United Nations

Convention on the Law of the Sea (UNCLOS)". Dit verdrag regelt de rechten die

staten hebben op zee en de manier waarop buurstaten deze rechten begrenzen.

Centraal in dit verdrag staat de basislijn, die het verloop van de kust

definieert.



De Nederlandse basislijn is een combinatie van normale basislijnen en rechte

(‘getrokken’) basislijnen. In tegenstelling tot de normale basislijn, zijn de

rechte basislijnen onveranderlijk en bij Nederlandse wet vastgesteld. De rechte

basislijnen vormen de af­sluiting van zeegaten, en daarmee de begrenzing tussen

de territoriale zee en de binnenwateren.



Sluit de basislijn een waterdeel af zoals onder meer van de Westerschelde,

Nieuwe Waterweg en Waddenzee, dan vormt de basislijn de begrenzing van dat

waterdeel met de Noordzee.



#### Actualiteit



Een of enkele keren per jaar publiceert de Dienst der Hydrografie een nieuwe

UNCLOS-basislijn. De dienst maakt gebruikers attent op deze wijzigingen, onder

meer via de eigen website[^1] en via een mailing per e-mail.



[^1]: Zie www.hydro.nl



#### Strand



Langs de Noordzee bezit het onbegroeid terreindeel grenzend aan de basislijn het

fysiek voorkomen ‘zand’.



Aan de ‘landzijde’ wordt het strand altijd begrensd door zichtbare topografie,

zoals de overgang naar de duinen bestaande uit een hek of duinvoet. In het geval

een kunstmatige aangelegde waterkering aanwezig is, zoals bij de Hondsbossche

Zeewering, bestaat de begrenzing uit kademuur of walbescherming.



#### Waddenzee en Zuidwestelijke delta



In deze wateren is altijd een kunstmatig aangelegde waterkering aanwezig in de

vorm van een kademuur of walbescherming. Deze vormen altijd een begrenzing voor

de BGT.



Daarnaast worden in deze wateren peilingen verricht voor het Lowest Astronomical

Tide (LAT). Als de ligging daarvan beschikbaar is voor de BGT vormt het de

scheiding tussen het waterdeel en het ondersteunend waterdeel type slik.

Ontbreekt het LAT dan vormt de kunstmatige waterkering de scheiding tussen

terrein en water.



#### Rivieren



In de BGT komt bij rivieren of een begrenzing voor in de vorm van een kademuur

of walbescherming, of een oever. Van nature komt er een variabel peil voor. In

de grote, bevaarbare rivieren hanteert Rijkswaterstaat hier een peil met de naam

Overeengekomen Lage Rivierwaterstand (OLR). Als een presentatie van dit peil

beschikbaar is, vormt het voor de BGT de begrenzing van waterdeel met

ondersteunend waterdeel type oever. Bij het ontbreken van het OLR vormt het

laagste streefpeil, eveneens onder verantwoording van Rijkswaterstaat, deze

begrenzing. Is de ligging van een peil niet beschikbaar voor de BGT dan vormt de

kunstmatige waterkering de scheiding tussen terrein en water.



#### Meren



Bij meren komen kunstmatig aangelegde waterkeringen voor in de vorm van een

kademuur of walbescherming, soms is er sprake van een oever. Als een kunstmatige

waterkering aanwezig is in de vorm van een kademuur of walbescherming vormt dit

de begrenzing van terrein en water. Bij het ontbreken daarvan vormt het object

begrensd door waterlijn en de bovenzijde van een herkenbare insteek een

ondersteunend waterdeel type oever/slootkant.



In meren wordt een streefpeil beheerd door bemalen en/of spuien. Als de ligging

van een peil bekend is en de horizontale afstand tussen een herkenbare insteek

bedraagt 1m of meer dan ontstaat in de BGT een ondersteunend waterdeel van het

type oever. Waar sprake is van meerdere streefpeilen, wordt uitgegaan van het

laagste niveau of ondergrenspeil.



#### Overige waterlopen en -vlakken



Hier geldt onderstaand stroomdiagram. Als kant water de begrenzing van objecten

vormt, geldt dat dit een presentatie is van het laagst mogelijke streefpeil ter

plaatse. Als de horizontale afstand tussen waterlijn en de bovenkant van een

herkenbare insteek 1m of meer bedraagt dan ontstaat in de BGT een ondersteunend

waterdeel van het type oever/slootkant.



![](https://raw.githubusercontent.com/Geonovum/IMGeo-dev/master/catalogus/bgt/90e8671da8cb5b1bb54087d56fa4a146.jpg)



Stroomdiagram

## Inwinregels IMGeo

In IMGeo zijn waterlopen en watervlakten nader te classificeren.



In IMGeo kunnen inrichtingselementen, die op en in het water voorkomen, worden

opgenomen met het objecttype waterinrichtingselement.



-   Van remmingswerk, geleidewerk en vuilvang wordt de lijngeometrie opgenomen

    waarbij voor remmingswerk en geleidewerk geldt dat deze worden ingewonnen

    aan die zijde waar de scheepvaart langs vaart.



-   Van betonning, meerpaal en hoogtemerk wordt de puntgeometrie opgenomen.



Het objecttype functioneel gebied kent op het gebied van de waterhuishouding de

classificaties ‘kering’ als BGT inhoud, en in het optionele deel

‘waterbergingsgebied’ en ‘infrastructuur waterstaatswerken’. Zie de paragraaf

over functioneel gebied voor meer informatie. Functionele gebieden bevatten geen

plaatsbepalingspunten.

## TypeWater
Specificatie van het soort Water.
## TypeWaterPlus
Specificatie van het soort Water, nadere classificatie.
# OndersteunendWaterdeel
Object dat in het kader van de waterhuishouding periodiek gedeeltelijk of geheel met water is bedekt. 
## TypeOndersteunendWaterdeel
Specificatie van het soort Water.
# Pand
Een PAND is de kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is. 
## Inwinregels BGT

### Regels voor opname



De BGT bevat alleen die objecten die de bestaande situatie in de werkelijkheid

representeren. Uitsluitend panden die in de BAG voorkomen met de volgende status

maken met hun grondvlakgeometrie deel uit van de BGT: • ‘Bouw gestart’; • ‘Pand

in gebruik (niet ingemeten)’; • ‘Pand in gebruik’; • ‘Sloopvergunning verleend’;

• ‘Pand buiten gebruik’.



De voorwaarde is wel dat deze panden al zijn ingemeten en/of dat het gaat om

bestaande panden, waarvoor een bouwvergunning is verleend.



De grondvlakgeometrie is daar waar de ‘footprint’ van het pand de ondergrond

raakt (rh = 0).



Voor panden die in hun geheel boven water liggen, bijvoorbeeld een

brugwachtershuis dat aan een brug hangt, geldt dat dit pand in de BGT voorkomt

met een relatieve hoogte (rh) \> 0, in ieder geval ligt het hoger dan het water

waar het zich boven bevindt.



Uitstulpingen in gevels, zoals steunberen, behoren tot de pandgeometrie als de

afmetingen groter zijn dan 30x30cm. Als zij kleiner zijn, worden zij niet

opgenomen (generalisatie). Als zich op de hoeken van een gebouw uitstulpingen

bevinden \< 30 cm wordt de lijn die over de uiteinden van deze uitstulpingen

loopt, beschouwd als gevellijn voor het pand. De gevel van erkers en

schoorstenen, die meer dan 30 cm buiten de doorgaande gevellijn van de voorgevel

liggen, behoren tot de geometrie van het pand. Indien de grondvlakgeometrie van

een pand uit meerdere losse vlakken bestaat, worden deze in één multivlak

vastgelegd. Kolommen van een dak, luifel of uitbouw (overbouw) van een pand

behoren tot de grondvlakgeometrie als de kleinste afmeting (rechthoekzijde of

middellijn) op het grondvlak meer dan 30 cm bedraagt.



Aandachtspunten Voor veel panden is de grondvlakgeometrie overgenomen door de

BAG als geometrie voor de buitenomtrek van het pand omdat deze geometrieën

identiek zijn, met inachtneming van de in vorige paragraaf vermelde twee regels.

<br />
<b>Notice</b>:  Undefined index: skos:definition in <b>C:\xampp\htdocs\objectenhandboek\combine-skos.php</b> on line <b>36</b><br />
# OverigBouwwerk

## Inwinregels BGT

### Regels voor opname



De geometrie is waar het grondvlak van het overig bouwwerk de ondergrond raakt.



### Aandachtspunten



Bassins en bezinkbakken bij zuiveringsinstallaties zijn geen waterdelen, maar

worden geclassificeerd als overig bouwwerk.



Zwembaden worden als type bassin vastgelegd.



Alleen bovengrondse opslagtanks worden opgenomen.



Bij overkappingen wordt de grondvlakgeometrie van de pilaren (footprint) waarop

de overkapping rust geregistreerd wanneer de afmetingen (rechthoekzijde of

middellijn) ≥ 0,30 m bedraagt.



Het afdak van de overkapping is eventueel IMGeo inhoud.

## Inwinregels IMGeo

Bunkers, voedersilo’s en schuren zijn geen BGT inhoud, maar kunnen wel in IMGeo

als overig bouwwerk worden opgenomen.

## TypeOverigBouwwerk
Specificatie van het soort overig bouwwerk.
## TypeOverigBouwwerkPlus
Specificatie van het soort overig bouwwerk, indien dit een IMGeo uitbreiding van de populatie betreft.
# Overbruggingsdeel
Onderdeel van een beweegbare of vaste verbinding tussen twee punten  die door water  een weg of anderszins gescheiden zijn  dat essentieel is voor de constructie .  
## Inwinregels BGT

### Regels voor opname



Er is sprake van een overbrugging wanneer een van de onderdelen bestaat uit een

afzonderlijk dek dat op een bak en/of pijlers rust. Dit in tegenstelling tot een tunnel,

die uit een gesloten kokerconstructie met een in- en uitgang bestaat.



Delen van overbruggingen worden in de BGT niet verder getypeerd. Zo worden zowel

het brugdek als de pijler van een overbrugging in de BGT aangeduid als

overbruggingsdeel.



Eén van de in onderstaande tabel vermelde situaties zal voorkomen om een

overbrugging in delen te kunnen opknippen.



| Rij-ijzer of voeg | Object met hoogste hiërarchie | Uitwerking |

|-------------------|-------------------------------|------------|

| Aanwezig          | n.v.t.                        | A          |

| Niet aanwezig     | Onder overbrugging            | B          |

| Niet aanwezig     | Op overbrugging               | C          |



Een schematische visualisatie van deze situaties staat in paragraaf 2.9.2 van

het BGT IMGeo Objectenhandboek.



Indien een rij-ijzer of voeg zichtbaar is in het brugdek worden daarmee de

overbrugging en de op de overbrugging gelegen objecten afgebakend volgens

uitwerking A.



Indien er geen rij-ijzer of voeg zichtbaar is, dan is de uitwerking afhankelijk

van de hiërarchie van de objecten ter plekke van de overbrugging. Van belang is

het object met de hoogste hiërarchie op de overbrugging en het object met de

hoogste hiërarchie onder de overbrugging. Voor de hiërarchie geldt de volgorde

van het objecttype uit hoofdstuk 8 van deze gegevenscatalogus (wegen, onbegroeid

terrein, begroeid terrein etc.). Is het objecttype gelijk dan geldt de volgorde

van de attributen en domeinwaarden uit hoofdstuk 9. Als algemene regel geldt dat

een waterdeel altijd niveau nul heeft. Water heeft in deze uitwerking de hoogste

hiërarchie.



Ligt het object met de hoogste hiërarchie onder de overbrugging dan is de

uitwerking volgens B. Ligt het object met de hoogste hiërarchie op de

overbrugging dan is de uitwerking volgens C.



Voorbeelden zonder rij-ijzer of voeg in de overbrugging zijn:



-   Op de overbrugging loopt een weg (rijbaan lokale weg) met een fietspad.

    Eronder loopt een weg (rijbaan autoweg). De uitwerking is dan volgens B,

    omdat de functie van de weg onder de overbrugging eerder in de tabel met

    functies van wegen staat.



-   Op de overbrugging loopt een weg (rijbaan lokale weg, gesloten verharding)

    met een fietspad. Er onder loopt een weg (rijbaan lokale weg, open

    verharding). De uitwerking is dan volgens C, omdat de functie van de wegen

    gelijk is, maar de weg op de overbrugging staat eerder in de tabel met

    fysiek voorkomen van wegen.



### Niveau-aanduiding



Voor het toekennen van de niveau-aanduiding geldt de algemene regel dat een

waterdeel onder of op een overbrugging (aquaduct) altijd niveau 0 heeft.



Verder geldt het attribuut relatieve hoogteligging voor elk afzonderlijk

overbruggingsdeel, niet voor de gehele overbrugging.



Wegdelen krijgen dezelfde relatieve hoogte aanduiding als het overbruggingsdeel

waarop zij liggen. Hierbij geldt één uitzondering: in de hierboven onder C

beschreven situatie, heeft het op het brugdeel gelegen wegdeel niveau 0. Het

brugdeel waarop dat wegdeel ligt, heeft één niveau lager: -1.Dit is vanwege het

feit dat er geen overlappende objecten mogen voorkomen op niveau 0.



Het object dat onder deze overbrugging ligt, wordt onder meer opgeknipt door de

projectie van de bovenliggende begrenzing van het wegdeel. Dit is vanwege de

regel dat er een aaneengesloten oppervlakte op niveau 0 in de BGT moet

voorkomen.



Pijlers van een overbrugging krijgen de niveauaanduiding van het object waarop

zij staan en zullen dus een lagere waarde hebben voor dit attribuut dan het

brugdek dat op de pijlers ligt. Het wegdeel dat daarop kan voorkomen, heeft

dezelfde waarde voor de relatieve hoogteligging als het brugdek.



In het BGT Objectenhandboek zijn voornoemde uitwerkingen A, B en C schematisch

gevisualiseerd.

## Inwinregels IMGeo

In IMGeo kunnen bij het overbruggingsdeel ook kenmerken van de gehele

overbrugging worden opgenomen. Het overbruggingsdeel (CityGML

BridgeConstructionElement) zelf kan nader worden geclassificeerd als

bijvoorbeeld landhoofd of pijler, door dit in te vullen in het attribuut

typeOverbruggingsdeel.



Voor het nader classificeren van de gehele overbrugging wordt het attribuut

hoortBijTypeOverbrugging gebruikt, om aan te geven of het object een brug,

aquaduct, viaduct enz. is. Daarnaast kan het attribuut overbruggingIsBeweegbaar

worden gebruikt .

## TypeOverbrugging
Nadere classificatie van de overbrugging waar het overbruggingsdeel een onderdeel van is.
## TypeOverbruggingsdeel
Het soort onderdeel van de brugconstructie.
# Tunneldeel
Onderdeel van een kunstmatig aangelegde  kokervormige onderdoorgang dat essentieel is voor de constructie. 
## Inwinregels BGT

### Regels voor opname



Er is sprake van een tunnel wanneer deze bestaat uit een gesloten

kokerconstructie met een in- en een uitgang. Bij overbruggingsdelen zoals

bijvoorbeeld een viaduct is er altijd sprake van een afzonderlijk dek dat op een bak

en/of pijlers rust.



De buitenste begrenzing van tunneldelen ligt onder het maaiveld en is niet

zichtbaar. Opname daarvan in de BGT gebeurt aan de hand van beschikbare

informatie, zoals bouwtekeningen. Dat geldt ook voor de in het tunneldeel

gelegen wegdelen.



Interieur van tunnels, zoals (scheidings)muren, trappen, vormen geen BGT-inhoud,

omdat dit nadere invulling is van CityGML LOD1 en hoger.



### Aandachtspunten



Zichtbare muren enzovoort die de buitenste delen van een tunnel vormen worden in

de BGT als muur enzovoort geclassificeerd.



### Relatieve hoogte



De relatieve hoogte van tunneldelen bedraagt altijd \< 0. In tunneldelen ligt of

liggen altijd één of meer wegdelen. Deze wegdelen bezitten dezelfde aanduiding

voor relatieve hoogte als het tunneldeel waarin zij liggen.

## Inwinregels IMGeo

In IMGeo kunnen functionele gebieden worden opgenomen als vlakobject. De

functionele gebieden zijn inrichtend en mogen overlappen met elkaar en met

andere vlakobjecten van alle soorten. De functionele gebieden hoeven niet samen

een landsdekkend geheel zonder gaten te vormen. Ze bevatten geen

plaatsbepalingspunten.

<br />
<b>Notice</b>:  Undefined index: skos:definition in <b>C:\xampp\htdocs\objectenhandboek\combine-skos.php</b> on line <b>36</b><br />
# Kunstwerkdeel

## Inwinregels BGT

### Regels voor opname



Een kunstwerkdeel wordt opgenomen met de buitenste begrenzing die is bepaald

door karakteristieke punten.



Als de breedte van het kunstwerkdeel \<30cm is, wordt het object als lijn

vastgelegd.



### Aandachtspunten



Kunstwerkdelen worden getypeerd naar het geheel waarvan zij deel uitmaken.



De aanduiding voor het kunstwerkdeel in de BGT heeft betrekking op die delen van

het kunstwerk die nog niet als een ander object of objecttype tot de BGT- inhoud

behoren.



Het kunstwerkdeel erft het attribuut relatieve hoogteligging van het object

waarop het staat of ligt.



#### Hoogspanningsmast



Alleen masten van het type hoogspanningsmast zijn onderdeel van de BGT. De voet

van de mast wordt als multipunt of multivlak vastgelegd.



Als er geen afzonderlijke afmeting van de mastvoeten beschikbaar is, wordt elk

hoekpunt van de omtrek om de mastvoeten als multipunt van de hoogspanningsmast

geclassificeerd.



Als er afzonderlijke afmetingen van de mastvoeten bekend zijn, wordt elke

mastvoet als multivlak van de hoogspanningsmast geclassificeerd wanneer de

afmetingen van de mastvoet (rechthoekzijde of middellijn) ≥ 0,30 m bedraagt.



#### Gemaaldelen, sluisdeur, stuw



Bij een gemaal worden de eventueel aanwezige bakken waar het water door wordt

geleid als gemaaldeel opgenomen in de BGT. De eventuele overige objecten zoals

muren, kademuren, panden en overbruggingen vormen als zodanig inhoud van de BGT.

Nadere typeringen van gemaal wordt beschouwd als beheerinformatie en niet

opgenomen in de BGT.



Bij een sluis behoren alleen de sluisdeuren, in gesloten stand, tot BGT-inhoud.

De eventuele overige objecten zoals muren, kademuren, panden en overbruggingen

vormen als zodanig inhoud van de BGT. Nadere typeringen van sluis wordt

beschouwd als beheerinformatie en niet opgenomen in de BGT.



Bij een stuw behoort uitsluitend de klep of schuif waarover het water kan

stromen tot BGT-inhoud. De eventueel aanwezige bakken waar het water door wordt

geleid, worden als stuwdeel opgenomen in de BGT. Eventuele overige objecten

zoals muren, kademuren, panden en overbruggingen vormen als zodanig inhoud van

de BGT.

## Inwinregels IMGeoIMGeo voegt enkele optionele kunstwerken toe. Dit zijn allemaal vlakobjecten, met uitzondering duiker: deze heeft vlak- of lijngeometrie.

De relatieve hoogte van een duiker bedraagt altijd < 0.

Het waterdeel in de duiker wordt niet afgebeeld.

## TypeKunstwerk
Specificatie van het soort kunstwerk.
## TypeKunstwerkPlus
Specificatie van het soort kunstwerk, indien dit een IMGeo uitbreiding van de populatie betreft.
<br />
<b>Notice</b>:  Undefined index: skos:definition in <b>C:\xampp\htdocs\objectenhandboek\combine-skos.php</b> on line <b>36</b><br />
# Scheiding

## Inwinregels BGT

### Indeling



De volgende scheidingen zijn BGT-inhoud: hekken, geluidsschermen, muren,

kademuren en walbeschermingen.



### Regels voor opname



Scheidingen worden als lijnobject vastgelegd als de breedte kleiner is dan 30cm.

Bij scheidingen breder dan 30cm moet de buitenomtrek waar het object de grond

raakt worden ingewonnen en vastgelegd als vlakgeometrie.



Een scheiding wordt vastgelegd waar het object de ondergrond raakt.



In de scheidingen worden onderbrekingen van \<1m genegeerd. Doorgangen worden

gezien als integraal onderdeel van de scheiding.



Scheidingen van het type hek die een minimale lengte van 10m en een minimale

hoogte van 1m hebben, worden vastgelegd.



Scheidingen van de typen kademuur en walbescherming worden opgenomen aan de

bovenzijde aan de waterkant. Kademuren breder dan 30cm worden ingewonnen als

vlakobject; de omtrek van het object aan de bovenzijde wordt dan vastgelegd.



Scheidingen van het type muur, met een minimale lengte van 1m en met een

minimale breedte van 30cm worden opgenomen. Een muur smaller dan 30cm wordt als

lijnobject vastgelegd, een bredere muur als vlakobject. Muren met een minimale

hoogte van 50cm worden vastgelegd.



In terreinen met een fysiek voorkomen ‘erf’ worden alleen die scheidingen

opgenomen die direct aan de straatzijde zijn gelegen.



Ter ondersteuning bij het vaststellen welk objecttype het betreft, geldt

onderstaande beslisboom voor muren en wanden.



![](https://raw.githubusercontent.com/Geonovum/IMGeo-dev/master/catalogus/bgt/8579806fb776a782ef3b4609d8463e79.png)



*Beslisboom afbakening van muren, wanden en dammen.*

## Inwinregels IMGeo

IMGeo kent naast de BGT typen scheiding ook draadraster en faunaraster.

Bovendien zijn heggen/hagen in IMGeo vertegenwoordigd, zij het niet als

scheiding maar als vegetatieobject. Draadraster en faunaraster worden als

lijnobject opgenomen.



In de BGT worden scheidingen alleen vastgelegd als ze bepaalde minimum

afmetingen hebben, die per type scheiding verschillen (zie deel I). In IMGeo

kunnen scheidingen worden opgenomen die kleiner zijn dan de voor de BGT vermelde

minimum afmetingen. Ook kunnen in IMGeo scheidingen worden opgenomen die binnen

een erf en niet aan de straatzijde of openbare ruimte zijde zijn gelegen.



De populatie van Scheiding in IMGeo bestaat uit:



-   Scheidingen die niet voldoen aan de BGT minimummaat;



-   Scheidingen in terrein met fysiek voorkomen ‘erf’ die niet aan de

    straatzijde gelegen zijn.



IMGeo muren en kademuren van breder dan 30 cm worden als vlakobject vastgelegd;

smallere worden als lijnobject vastgelegd.

## TypeScheiding
Specificatie van het soort scheiding.
## TypeScheidingPlus
Specificatie van het soort scheiding, indien dit een IMGeo uitbreiding van de populatie betreft.
# GebouwInstallatie
Een component aan de buitenzijde van een gebouw  die het aanzicht van het gebouw mede bepaalt.  
## Inwinregels IMGeo

Gebouwinstallaties zijn aan het pand verbonden toegangstrappen, luifels en

bordessen.

## TypeGebouwInstallatie
Specificatie van het soort gebouwinstallatie.
## TypeGebouwInstallatiePlus
Specificatie van het soort gebouwinstallatie, indien dit een IMGeo uitbreiding van de populatie betreft.
# Inrichtingselement
Een ruimtelijk object al dan niet ter detaillering dan wel ter inrichting van de overige benoemde ruimtelijke objecten of een ander inrichtingselement. 
# Bak
Object met een permanent karakter dat dient om iets in te bergen of te verzamelen. 
## TypeBak

## TypeBakPlus
Het soort bak (IMGeo plus-populatie).
# Bord
Een paneel waarop informatie wordt afgebeeld. 
## TypeBord

## TypeBordPlus
Het soort bord (IMGeo plus-populatie).
# Installatie
Samenhangend systeem dat een bepaald doel dient. 
## TypeInstallatie

## TypeInstallatiePlus
Het soort installatie (IMGeo plus-populatie).
# Kast
Object met een permanent karakter dat dient om iets in te bergen en te beschermen. 
## TypeKast

## TypeKastPlus
Het soort kast (IMGeo plus-populatie).
# Mast
Hoge draagconstructie. 
## TypeMast

## TypeMastPlus
Het soort mast (IMGeo plus-populatie).
# Paal
Langwerpig stuk hout  ijzer  steen enz.  dat in de grond staat. 
## TypePaal

## TypePaalPlus
Het soort paal (IMGeo plus-populatie).
# Put
Gegraven of geboorde kokervormige diepte waarin zich  vloei stoffen bevinden. 
## TypePut

## TypePutPlus
Het soort put (IMGeo plus-populatie).
# Sensor
Apparaat voor de meting van een fysieke grootheid  bijv. temperatuur  licht  druk  elektriciteit .  
## TypeSensor

## TypeSensorPlus
Het soort sensor (IMGeo plus-populatie).
# Straatmeubilair
Een ruimtelijk object ter inrichting van de openbare ruimte.  
## TypeStraatmeubilair

## TypeStraatmeubilairPlus
Het soort straatmeubilair (IMGeo plus-populatie).
# Waterinrichtingselement
Een ruimtelijk object ter inrichting van het water. 
## TypeWaterinrichting

## TypeWaterinrichtingPlus
Het soort waterinrichtingselement (IMGeo plus-populatie).
# Weginrichtingselement
Een ruimtelijk object dat dient voor de inrichting van de openbare weg. 
## 
<br />
<b>Notice</b>:  Undefined index:  in <b>C:\xampp\htdocs\objectenhandboek\combine-skos.php</b> on line <b>58</b><br />

## TypeWeginrichtingPlus
Het soort weginrichtingselement (IMGeo plus-populatie).
# VegetatieObject
Solitair vegetatieobject of lijn- of vlakvormige groep gelijksoortige vegetatieobjecten met een beperkte omvang. 
## Inwinregels IMGeo

Dit zijn bomen en hagen. Bomen worden opgenomen als puntobject. Hagen worden

opgenomen als lijnobject indien ze smaller zijn dan 30 cm, anders als

vlakobject.

## TypeVegetatieObject
De specificatie van het soort vrijstaand vegetatieobject.
## TypeVegetatieObjectPlus
De specificatie van het soort vrijstaand vegetatieobject.
# OpenbareRuimteLabel
Naam en plaatsingspunten van een in de BAG geregistreerde OPENBARE RUIMTE.  
## 
<br />
<b>Notice</b>:  Undefined index:  in <b>C:\xampp\htdocs\objectenhandboek\combine-skos.php</b> on line <b>58</b><br />

## TypeOpenbareRuimte
De aard van de als zodanig benoemde OPENBARE RUIMTE.
# RegistratiefGebied
Op basis van wet- of regelgeving afgebakend gebied dat als eenheid geldt van politiek bestuurlijke verantwoordelijkheid of voor bedrijfsvoering. 
## Inwinregels IMGeo

In IMGeo kunnen verschillende soorten registratieve gebieden worden opgenomen,

allen als vlakobject.



Openbare ruimte mag als vlakobject worden opgenomen. Het is mogelijk een relatie

te leggen naar de BGT OpenbareRuimteLabel, waarin de BAG identificatie, openbare

ruimte type en openbare ruimte naam en plaatsingspunt zijn opgenomen. De

afbakening van de openbare ruimte geometrie kan geschieden op de plaatsen waar

de openbare ruimte naam wijzigt en aan de wegkanten de begrenzing van de erin

gelegen wegdelen volgen.



Buurt, wijk, stadsdeel en waterschap worden opgenomen met vlakgeometrie.



Registratieve gebieden bevatten geen plaatsbepalingspunten.

# FunctioneelGebied
Begrensd en benoemd gebied dat door een functionele eenheid beschreven wordt. 
## TypeFunctioneelGebied
Specificatie van het soort Functioneel Gebied.
## TypeFunctioneelGebiedPlus
Specificatie van het soort Functioneel Gebied, indien het een IMGeo uitbreiding van de populatie betreft.
# Plaatsbepalingspunt
Punt dat is ingemeten en vervolgens gebruikt is bij en onderdeel uitmaakt van de begrenzing van BGT objecten. 
## Inwinningsmethode
De wijze waarop het punt is ingewonnen.
<br />
<b>Warning</b>:  file_get_contents(https://definities.geostandaarden.nl/imgeo/doc/begrip/VoidReasonValue?format=json): failed to open stream: HTTP request failed! HTTP/1.1 404 Not Found
 in <b>C:\xampp\htdocs\objectenhandboek\combine-skos.php</b> on line <b>33</b><br />
# VoidReasonValue

## VoidReasonValue
reden waarom een ’void-waarde’ is ingevuld
