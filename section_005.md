# Gebruik van het wijzigingsprotocol {#55CD880F}

Het wijzigingsprotocol schrijft een vast stramien voor het wijzigen van de NLDT Referentie Architectuur voor. Het protocol benoemt de fasen en de op te leveren resultaten. Belangrijk zijn de randvoorwaarden en uitgangspunten. De gebruikers, deskundigen (experts) en andere stakeholders van de NLDT Referentie Architectuur worden bij het wijzigen van de NLDT Referentie Architectuur nauw betrokken.

Het wijzigingsprotocol voor de NLDT Referentie Architectuur geeft:

- Inzicht in het behandel- en besluitproces dat ten grondslag ligt aan het versiebeheer;
- Inzicht in de wijzigingsverzoeken;
- Inzicht in een voorgestelde wijziging van de architectuur;
- Stabiliteit aan de architectuur;
- Continuïteit aan de architectuur;
- Een eenduidige aanpak.


## Releasebeleid {#3EE7FC49}

### Nieuwe versie van de architectuur {#64C6632B}
Een release is een nieuwe uitgave van de architectuur. De wijzigingen binnen een release wordt gedocumenteerd en vastgelegd in de sectie versiemanagement van de architectuur. De gebruiker kan zo nagaan op welke plaatsen de betreffen de architectuur gewijzigd is. De nieuwe release kenmerkt zich ten opzichte van de oude versie door een hoger versienummer. Bij de release is ieder product van de architectuur voorzien van een nieuw versienummer conform Semantic Versioning (SemVer). Binnen SemVer heeft elk product zijn eigen versienummer conform de X.Y.Z schrijfwijze, bijvoorbeeld versie 2.1.0 (=X.Y.Z):

<ul><li><b>X-wijziging.</b> Indien de NLDT Referentie Architectuur een majeure update krijgt met relatief veel nieuwe en ingrijpende wijzigingen dan wordt de architectuur als geheel aangeduid met een X wijziging. Frequentie: op voorstel van Geonovum en in overleg met de NLDT Stuurgroep.</li>
</ul>
<ul><li><b>Y-wijziging.</b> Indien de NLDT Referentie Architectuur een beperkte update krijgt met een relatief klien aantal en minder ingrijpende wijzigingen dan wordt de architectuur als geheel aangeduid met een Y wijziging.  
Frequentie: op voorstel van Geonovum en in overleg met de NLDT Stuurgroep.</li>
</ul>
<ul><li><b>Z-wijziging. </b>Dit zijn bugs/fouten of aanvullingen in een toelichting, die geen impact hebben op de wezenlijke architectuur. 
Frequentie: zo spoedig mogelijk na constatering door Geonovum.</li>
</ul>
<br>
Na het uitbrengen van een nieuwe versie van de architectuur is deze nieuwe versie beschikbaar en vindbaar via de Geonovum website.

### Oudere versie van de architectuur {#1E4463A2}
De SemVer-methodiek schrijft backwards compatibility voor op het Y-niveau. Een nieuwe versie dwingt daarmee geen directe overstap af bij de gebruikers, tenzij anders (bijvoorbeeld wettelijk) bepaald. Na het uitbrengen van de nieuwe versie van de architectuur wordt de ontwikkeling van de oude versie stop gezet.
Voor het onderhoud en de ondersteuning van een oude versie van een standaard gelden de volgende uitgangspunten:
<ul><li>Aan een oude versie worden geen nieuwe features toegevoegd, geen aanpassingen gedaan na het uitbrengen van een nieuwe versie. Verzoeken om aanpassing en wijziging voor nieuwe functionaliteit worden niet meer in behandeling genomen. Correcties (Z-wijzigingen) worden wel uitgevoerd op de vorige versies zolang deze nog ondersteund worden.</li>
<li>Bij oplevering van een nieuwe versie wordt de voorgaande versie nog een van te voren vastgestelde periode ondersteund. De duur van de overgangsperiode wordt mede bepaald door de omvang van de wijzigingen (X, Y en Z wijzigingen op de vorige versies), de staat van ontwikkeling van de architectuur, en of de architectuur in voorlopig dan wel permanent beheer is.</li>
</ul>
Na het uitbrengen van een nieuwe versie van de architectuur blijven oudere versies beschikbaar en zijn vindbaar via de Geonovum website.

## Proces varianten {#317FB4EA}
In paragraaf releasebeleid zijn de X, Y en Z wijzigingen uitgelegd. Wijzigingen kennen drie procesvarianten: eén voor X wijzigingen, één voor Y wijzigingen en één voor Z wijzigingen.
De start van het proces is voor alle varianten hetzelfde. Op de [github repository](https://github.com/Geonovum/NLDT-Architectuur/issues) wordt een issue ingediend. De impact van deze wijziging wordt door de <b>Werkgroep NLDT Architectuur </b>beoordeeld. Deze eerste impactanalyse beoordeelt tot welke SemVer categorie de wijziging hoort en wat de effecten van de wijziging zijn. 


<b>Proces voor X en Y wijzigingen</b>
X en Y wijzigingen vergen volledige afstemming en het doorlopen van alle in paragraaf 5.1 beschreven fasen: Inhoud, Toetsing, Besluitvorming en Implementatie. Voor de inhoudelijke fase wordt een werkgroep gestart met daarin deskundigen (experts). Het resultaat van de werkgroep is een wijzigingsvoorstel dat in de Werkgroep NLDT Architectuur en in het overleg van de <b>NLDT Stuurgroep</b> met externe stakeholders wordt besproken. Y en X wijzigingen worden altijd voorgelegd aan het <b>GI-Beraad</b>, die stelt een nieuwe versie van de NLDT Architectuur vast.
<b>Proces voor Z wijzigingen</b>
In overleg met de Werkgroep NLDT Architectuur worden Z wijzigingen in de volgende release opgenomen. De inhoudelijke fase wordt door het beheer van de architectuur uitgevoerd. Besluitvorming vindt plaats in afstemming met de Werkgroep. Implementatie vindt plaats door het publiceren van de wijziging op de Geonovum website.

## Betrokkenen {#40EBAE8E}
De volgende betrokkenen spelen een rol in het wijzigingsproces van de NLDT Referentie Architectuur:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 24.973779279804216%;'>
<col id='col2' style='width: 75.02622072019578%;'>
</colgroup>
<thead><tr><th style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000;'><p id='502496B4'><b><span style='color: #FFFFFF;'>Rol</span></b></th>
<th style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '>Stakeholder</span></b></th>
</tr>
</thead>
<tbody><tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='79779D62'>Opdrachtgever (eigenaar) van de NLDT Referentie Architectuur</span></td>
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='7CDDA5B2'>Ministerie van BZK.</td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='20E94293'>GI-Beraad</span></td>
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='2FABC3CA'>Het GI-beraad doet aanbevelingen aan de minister van Binnenlandse Zaken, overige ministers en overheidsorganen over de strategische onderwerpen op het gebied van de geo-informatie in de publieke sector in Nederland. Het GI-beraad bestaat uit vertegenwoordigers van de verschillende gebruikersgroepen uit de publieke sector, zowel van het Rijk, de provincies, gemeenten en waterschappen. Het GI-Beraad stelt een X- of Y- versie van de NLDT Architectuur vast.</span></td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='19CAFEC7'>NLDT Stuurgroep</span></td>
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='1B9CE459'>De NLDT heeft een interbestuurlijke stuurgroep die optreedt als adviesgremium. Deze geeft een advies aan het GI-Beraad over het vaststellen van de architectuur</span></td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='7193A7AF'>Werkgroep NLDT Architectuur.</span></td>

<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='4894E108'>De werkgroep bespreekt wijzigingen en adviseert het beheerteam.</span></td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '></td>
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '></td>
</tr>
</tbody>
</table>

