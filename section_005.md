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
Een release van een standaard is een nieuwe uitgave van de architectuur. De wijzigingen binnen een release wordt gedocumenteerd en vastgelegd in Bijlage A van het informatiemodel. De gebruiker kan zo nagaan op welke plaatsen de betreffen de architectuur gewijzigd is. De nieuwe release kenmerkt zich ten opzichte van de oude versie door een hoger versienummer. Bij de release is ieder product van de architectuur voorzien van een nieuw versienummer conform Semantic Versioning (SemVer). Binnen SemVer heeft elk product zijn eigen versienummer conform de X.Y.Z schrijfwijze, bijvoorbeeld versie 2.1.0 (=X.Y.Z):
<ul><li><b>X-wijziging.</b> Indien de NLDT Referentie Architectuur een majeure update krijgt met relatief veel nieuwe en ingrijpende wijzigingen dan wordt de architectuur als geheel aangeduid met een X wijziging. Frequentie: op voorstel van Geonovum en in overleg met het Regie-overleg geo-standaarden.</li>
</ul>
<ul><li><b>Y-wijziging.</b> Indien de NLDT Referentie Architectuur een beperkte update krijgt met een relatief klien aantal en minder ingrijpende wijzigingen dan wordt de architectuur als geheel aangeduid met een Y wijziging.  
Frequentie: op voorstel van Geonovum en in overleg met het Regie-overleg geo-standaarden.</li>
</ul>
<ul><li><b>Z-wijziging. </b>Dit zijn bugs/fouten of aanvullingen in een toelichting, die geen impact hebben op de geo-standaarden en hun versie aanduiding. 
Frequentie: zo spoedig mogelijk na constatering door Geonovum.</li>
</ul>
<br>
Na het uitbrengen van een nieuwe versie van een standaard is deze nieuwe versie beschikbaar en vindbaar via de Geonovum website, onderdeel samenhang geo-standaarden op de pagina <a href='https://www.geonovum.nl/themas/standaardisatie' target='_blank'>standaardisatie</a>.

### Oudere versie van de architectuur {#1E4463A2}
De SemVer-methodiek schrijft backwards compatibility voor op het Y-niveau. Een nieuwe versie dwingt daarmee geen directe overstap af bij de gebruikers, tenzij anders (bijvoorbeeld wettelijk) bepaald. Na het uitbrengen van de nieuwe versie van de architectuur wordt de ontwikkeling van de oude versie stop gezet.
Voor het onderhoud en de ondersteuning van een oude versie van een standaard gelden de volgende uitgangspunten:
<ul><li>Aan een oude versie worden geen nieuwe features toegevoegd, geen aanpassingen gedaan na het uitbrengen van een nieuwe versie. Verzoeken om aanpassing en wijziging voor nieuwe functionaliteit worden niet meer voor het oude Raamwerk in behandeling genomen. Correcties (Z-wijzigingen) worden wel uitgevoerd op de vorige versies zolang deze nog ondersteund worden.</li>
<li>Bij oplevering van een nieuwe versie wordt de voorgaande versie nog een van te voren vastgestelde periode ondersteund. De duur van de overgangsperiode wordt mede bepaald door de omvang van de wijzigingen (X, Y en Z wijzigingen op de vorige versies), de staat van ontwikkeling van de architectuur, en of de architectuur in voorlopig dan wel permanent beheer is.</li>
</ul>
Na het uitbrengen van een nieuwe versie van een standaard blijven oudere versies beschikbaar en zijn vindbaar via het <a href='https://docs.geostandaarden.nl/nldt/nldt-ra/' target='_blank'>NLDT Architectuur</a> op de <a href='https://www.geonovum.nl/themas/standaardisatie' target='_blank'>Geonovum website</a>.

## Proces varianten {#317FB4EA}
In paragraaf releasebeleid zijn de X, Y en Z wijzigingen uitgelegd. Wijzigingen kennen drie procesvarianten: eén voor X wijzigingen, één voor Y wijzigingen en één voor Z wijzigingen.
De start van het proces is voor alle varianten hetzelfde. Op de website wordt een wijzigingsverzoek ingediend bij de <a href='https://www.geonovum.nl/over-geonovum/contact' target='_blank'><b>Helpdesk</b><b> geo-standaarden</b></a>. De impact van deze wijziging wordt door de  <b>Werkgroep NLDT Architectuur </b>beoordeeld. Deze eerste impactanalyse beoordeelt tot welke SemVer categorie de wijziging hoort en wat de effecten van de wijziging zijn. Naast de impactanalyse wordt het wijzigingsverzoek .
<b>Proces voor X en Y wijzigingen</b>
X en Y wijzigingen vergen volledige afstemming en het doorlopen van alle in paragraaf 5.1 beschreven fasen: Inhoud, Toetsing, Besluitvorming en Implementatie. Voor de inhoudelijke fase wordt een werkgroep gestart met daarin deskundigen (experts). Het resultaat van de werkgroep is een wijzigingsvoorstel dat in het standaardenoverleg van Geonovum en in het overleg van de <b>Regiegroep geo-standaarden</b> met externe stakeholders wordt besproken. Y en X wijzigingen worden altijd voorgelegd aan de <b>Programmaraad Geonovum</b>, die stelt een nieuwe versie van de NLDT Architectuur vast.
<b>Proces voor Z wijzigingen</b>
In overleg met de Werkgroep NLDT Architectuur worden Z wijzigingen in de volgende release opgenomen. De inhoudelijke fase wordt door het beheer van de architectuur uitgevoerd. Besluitvorming vindt plaats in afstemming met de Werkgroep. Implementatie vindt plaats door het publiceren van de wijziging op de <a href='https://www.geonovum.nl/geo-standaarden/raamwerk-geo-standaarden' target='_blank'>Geonovum website</a>.

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
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='7CDDA5B2'>Programmaraad van Geonovum bestaande uit vertegenwoordigers van Kadaster, Ministerie van EZK en Ministerie van LNV, Provincie Gelderland namens de provincies en het Interprovinciaal Overleg (IPO), Ministerie van Defensie - Dienst der Hydrografie, Rijkswaterstaat, Ministerie van BZK, Geologische Dienst Nederland TNO, Vereniging van Nederlandse Gemeenten.</td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='20E94293'>Regie-overleg geo-standaarden</span></td>
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='2FABC3CA'>Het Regie-overleg heeft een diverse samenstelling van beheerders, gebruikersvertegenwoordigers en liaison met relevante standaarden organisaties. Het adviseert de Programmaraad, werkt in werkgroepen, agendeert binnen domeinstandaarden en informeert het programma Zicht op Nederland Datafundament.</span></td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='19CAFEC7'>Werkgroep NLDT Architectuur</span></td>
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='1B9CE459'>Adviseurs en experts geo-standaarden Geonovum</span></td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='7193A7AF'>Helpdesk geo-standaarden</span></td>

<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '><p id='4894E108'>Adviseurs en experts geo-standaarden Geonovum</span></td>
</tr>
<tr><td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '></td>
<td style='border-top: 0.75pt solid #DDDDDD; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; '></td>
</tr>
</tbody>
</table>

