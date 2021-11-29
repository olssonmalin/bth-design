---
Title: Colors
Template: index
Description: En rapport om färger på webbplatser
---

Färg i en grå stad - en inblick i Berlins kulturs färgscheman
=======================

Inom ramen för kursen "Teknisk webbdesign och användbarhet" på Blekinge Tekniska Högskola under höstterminen 2021 har denna rapport sammanställts för att undersöka val av färg och typsnitt på tre olika webbplatser.

Urval
-----------------------

Båda rapportförfattarna är bosatta i Berlin. Staden har ett rikt kulturliv med många museum, klubbar, biografer, konsertlokaler und so weiter. De tre webbplatserna som undersöks i denna rapport har som gemensam faktor att de tillhör Berlins kulturliv. De representerar dock olika delar av kulturen. Detta är de tre webbplatser som valts ut:
- [Berghain](https://www.berghain.berlin/en/), en klubb som öppnade 2004[^1]
- [Columbia Theater](https://columbia-theater.de/), en konsertlokal som öppnades av amerikanska styrkor 1951[^2]
- [Berlin Wall Memorial](https://www.berliner-mauer-gedenkstaette.de/en/), en minnesplats och museum om Berlinmuren[^3]

<br>
Metod
-----------------------

För att genomföra studien har webbplatserna först letats upp för vardera företag med hjälp av Google. Webbplatserna har undersökts för att se om det finns några färg-relaterade effekter vid exempelvis hovring av ett element. Därefter har färgerna med hjälp av ett tillägg (ColorZilla) identifierats och noterats. Färgerna har sedan förts in i Adobe Color Picker (custom-läge) för att kunna se vart färgerna är utplacerade på färghjulet. Webbläsarens DevTools har använts för att se vilka fonts som webbsidan använder. 

De verktyg som använts är:
- **[Webbläsaren Mozilla Firefox med DevTools](https://www.mozilla.org/en-US/firefox/new/)**
  - Firefox har använts för att besöka webbplatserna. Det inbyggda inspektionsverktyget har använts för att kolla igenom webbsidornas struktur samt inspektera vilka värden vissa CSS-properties haft, till exempel _font-family_.
- **[Firefox-tillägget Colorzilla](https://www.colorzilla.com/)**
  - Colorzilla är ett tillägg som tillåter användaren att använda en virtuell "pipett" för att få fram vilken färg ett särskilt element på en webbsida har. Det har använts för att anteckna vilka färger som används på de olika webbplatserna.
- **[Webbläsaren Oryoki](http://oryoki.io/)**
  - Oryoki är en experimentell webbläsare med ett minimalistiskt interface. Den har använts för att ta skärmdumpar på webbplatserna, eftersom webbläsaren i sig inte har några element som "stör" bilden.
- **[Adobe Color Picker](https://color.adobe.com/create/color-wheel)**
  - Ett verktyg som bl.a. visualiserar färger i förhållande till varandra i ett color wheel. Har använts för att identifiera olika färgers relationer till varandra för att i sin tur kunna avgöra vilket typ av färgschema som använts.
- **[archive.org](https://archive.org/)**
  - Sparar snapshots av webbplatser. Har använts för att få tillgång till en tidigare version av en av webbplatserna. 

<br>
Resultat
-----------------------

###Berghain:
Bild på hemsidan:

![Berghains hemsida](%assets_url%/img/color/berghain.png) {.website-img}

Färgschema:

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<!-- HTML backround: -->
<td style="height: 50px; width: 50px; background-color: #141414">
<!-- Body backround: -->
<td style="height: 50px; width: 50px; background-color: #262525">
<!-- Hover/containers i body: -->
<td style="height: 50px; width: 50px; background-color: #333131">
<!-- Olika containers i body: -->
<td style="height: 50px; width: 50px; background-color: #3f3d3d">
<!-- Text/logo:  -->
<td style="height: 50px; width: 50px; background-color: #A7A7A7">
<!-- Accent: -->
<td style="height: 50px; width: 50px; background-color: #DCA883">
</tr>
</table>

Färgernas position på färghjul:

![Berghains färger i färhjul](%assets_url%/img/color/cw-berghain.png) {.colorwheel-img}


Typ av färgschema:
Akromatisk med accent-färg alt. helt monokromatiskt.

Bild på hemsidan i Oktober[^4]:

![Berghains hemsida okt 2021](%assets_url%/img/color/berghain-oct.png) {.website-img}

Färgschema i Oktober:

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<!-- HTML backround: -->
<td style="height: 50px; width: 50px; background-color: #141414">
<!-- Body backround: -->
<td style="height: 50px; width: 50px; background-color: #262525">
<!-- Hover/containers i body: -->
<td style="height: 50px; width: 50px; background-color: #333131">
<!-- Olika containers i body: -->
<td style="height: 50px; width: 50px; background-color: #3f3d3d">
<!-- Text/logo:  -->
<td style="height: 50px; width: 50px; background-color: #A7A7A7">
<!-- Accent: -->
<td style="height: 50px; width: 50px; background-color: #D1477F">
</tr>
</table>

**Typ av färgschema:**
Akromatisk med accent-färg alt. helt monokromatiskt.

**Typsnitt:**
Graphic på hela webbplatsen. Sans-serif.

**Kommentar:**
Färgschemat och typsnittet ligger väl i linje med Berghains rykte som techno-instutition.

###Columbia Theater:
Bild på hemsidan:

![Columbia Theaters hemsida](%assets_url%/img/color/columbia.png) {.website-img}

Färgschema:

<table style="border-spacing: 4px; border-collapse: separate">
<!-- text: -->
<td style="height: 50px; width: 50px; background-color: #53595D">
<!-- text: -->
<td style="height: 50px; width: 50px; background-color: #8E8E8E">
<!-- 
navigeringsbar top (månader):
bakgrund: -->
<td style="height: 50px; width: 50px; background-color: #EDEEF1">
<!-- text: -->
<td style="height: 50px; width: 50px; background-color: #fff">
<!-- navigering: -->
<!-- bakgrund: -->
<td style="height: 50px; width: 50px; background-color: #57BAAC">

<!-- navigering adress: -->
<td style="height: 50px; width: 50px; background-color: #9BE2D8">
<!-- main:
accenter (datum, info): -->
<!-- on hover navigering: -->
<td style="height: 50px; width: 50px; background-color: #F46D69">
</table>

Färgernas position på färghjul:

![Columbias färger i färhjul](%assets_url%/img/color/cw-columbia.png) {.colorwheel-img}


**Typ av färgschema:**
Monokromatiskt med en accentfärg (#F46D69).

**Typsnitt:**
Blandning av rubikregular och rubikmedium, sans-serif.

**Kommentar:**
Starka färger som passar webbplatsens syfte.

###Gedänkstätte Berliner Mauer
Bild på hemsidan:

![Gedänkstätte Berliner Mauer's hemsida](%assets_url%/img/color/berlinermauer.png) {.website-img}

Färgschema:

<table style="border-spacing: 4px; border-collapse: separate">
<!-- bakgrund navigering: -->
<td style="height: 50px; width: 50px; background-color: #2E2E2E">
<!-- generell textfärg: -->
<td style="height: 50px; width: 50px; background-color: #333333">
<!-- hover navigering: ^bakgrund och hover byter plats vid hover > bakgrund blir textfärg och textfärg blir bakgrundsfärg
-->
<td style="height: 50px; width: 50px; background-color: #A1A1A1">
<!-- bakgrund main: -->
<td style="height: 50px; width: 50px; background-color: #FFFFFF">
<!-- body bakgrund: -->
<!-- länkar/accent-text: -->
<td style="height: 50px; width: 50px; background-color: #780000">
<!-- header bakgrund: -->
<td style="height: 50px; width: 50px; background-color: #660000">
<!-- accenter sökfält: -->
<td style="height: 50px; width: 50px; background-color: #A74F4F">

</table>

Färgernas position på färghjul:

![Gedänkstätte Berliner Mauer's färger i färhjul](%assets_url%/img/color/cw-berlinermauer.png) {.colorwheel-img}


**Typ av färgschema:**
Helt och hållet monokromatiskt.

**Typsnitt:**
Verdana helt och hållet, sans-serif.

**Kommentar:**
Typsnitt är passande för museum. Färgschemat något skevt.

Analys
-----------------------
###Berghain

####Färgschema

Berghain's webbplats har ett monokromatiskt färgschema i gråskala. Med tanke på hur dominant nyanser av grått är på webbplatsen skulle man kunna säga att den gränsar till att vara akromatisk, dvs. utan färg. Berghain använder en ny accent-färg varje månad beroende på vilken konstnär de har i headern längst upp. Det går att argumentera för att accentfärgerna i sig skulle vara del av ett monokromatiskt färgschema, eftersom det går att komma från accentfärgerna till en av de gråa färgerna om man ändrar färgmättnad. 

Berghain's webbplats har ett färgschema i gråskala. Det är svårt att avgöra exakt vilket typ av färgschema webbplatsen använder, men det kanske bäst beskrivande ordet vore <i>akromatiskt</i>. Färgschemat på webbplatsen följer nämligen inte någon traditionell färgteori utan består av några gråa färger som funkar väl ihop. Detta kompletteras sedan av en accentfärg som ändras månatligen. I November var färgen en beige naturlig färg som för tankarna till hud. I Oktober var det en mörkrosa färg. 

####Färgval

Huvuddelen av webbplatsen är i olika nyanser av grått, främst åt det mörkare hållet, nästan gränsande på svart. Det mörka färgschemat kan påminna om natten vilket är passande för en nattklubb. Accentfärgen ändras beroende på månad; under November var det en naturlig beige färg som drar tankarna mot hud. I Oktober var det en mörkrosa färg. Accentfärgerna verkar justeras mer utifrån vilket konstverk som visas längst upp på sidan snarare än att förmedla en särskild känsla. De drar fokus mot de viktigaste delarna av webbplatsen, exempelvis nästkommande evenemang.

####Typsnitt

Webbplatsen använder bara ett typsnitt, vilket är ett sans-serif-typsnitt som heter Graphik. Eftersom det inte är särskilt mycket text (största delen av texten är rubriker av olika slag) funkar ett typsnittet väl. Det ger ett enkelt intryck och är lätt att läsa.


###Columbia Theater

####Färgschema

De färger som används på Columbia Teaters webbplats är främst nyanser av grön-blått, en nyans av rött tillsammans med vit bakgrund och mörkgrå text. De gråa nyanserna tillsammans med de grön-blåa bildar ett monokromatisk färgschema då dessa färger ligger i en rak linje i samma del av färghjulet. Nyansen av röd ligger utanför denna del av färghjulet. Om den hade legat mer i den oranga delen av färghjulet hade den kunnat ingå i ett komplement färgschema. Eftersom den röda färgen inte passar in i det övriga färgschemat och den används för att förstärka detaljer på webbplatsen är det en accentfärg.

####Färgval

Den dominerande färgen (förutom vitt) på Columbia Teaters webbplats är grön-blå. Den märks först på deras hemsida som bakgrundsfärg för navigeringen. Den används också som bakgrundsfärg för deras galleri av bilder. Grön anses ge ett intryck av natur för besökare men kan också signalera rikedom, stabilitet och utbildning. [^5]
Columbia Teater har ett blandat utbud av konserter och evenemang, där olika evenemang drar olika målgrupper. Den gröna färgen kan därför möjligtvis inge en känsla av trygghet i ett annars spretigt utbud. Webbplatsens primära mål måste antas vara att ge besökare information om de olika föreställningarna och underlätta bokning av biljetter till dessa. Detta kan vara en anledning till valet av en röd, aktiv färg som bakgrund till element som visar viktig information, så som datum för föreställningar eller knappen för att köpa biljetter. Röd färg anses stimulera adrenalin och blodtryck [^6] - man blir "hypad" - därför kan denna användning av färgen vara effektiv för webbplatsens syfte. Till exempel syns knappen för att boka biljetter väl i sidorna där man kan läsa om specifika föreställningar, vilket drar ögonen till sig och möjligtvis ökar chansen att en besökare trycker på knappen.

####Typsnitt

Webbplatsen använder enbart ett typsnitt med två olika font weights. De två typsnitten är rubik regular och rubik medium. Rubik regular har en font-weight på 400 och används mest på sidan för brödtext medans rubik medium med font-weight på 500 främst används för knappar och rubriker. Webbplatsen ger ett enhetligt och balanserat intryck när det kommer till text.

###Gedänkstätte Berliner Mauer

####Färgschema

Gedänkstätte Berliner Mauer's webbplats består av ett tydligt monokromatiskt färgschema i röda nyanser. Tillsammans med de röda nyanserna används också mörkgrått och vitt för text och bakgrund. Det används ingen accentfärg som fallar utanför färgschemat. 

####Färgval

Grunden till färgvalet för webbplatsen kan vara att den byggnad som museet ligger i är röd och även det tilhörande minnesmärke. Däremot brukar dessa mörkaröda färger förknippas med romantik och passion men också lyx. I och med att webbplatsen hör till ett minnesmuseum om Berlinmuren kanske dessa anknytningar inte ger det intryck som webbplatsen eftersträvar. Däremot har rött också en förmåga att stimulera adrenalin som kan ligga till grund till färgvalet, att det röda representerar blod och allvar som ger besökaren en alarmistisk känsla.

####Typsnitt
Webbplatsen använder enbart ett typsnitt med lite olika font-weights och storlek. Typsnittet är Verdana, vilket är ett generiskt typsnitt de flesta datorer har tillgängligt. På grund av mängden text på hemsidan kombinerat med den lilla storleken är det svårt att veta exakt vart man ska kolla. Typografin på webbplatsen känns helt enkelt inte särskilt modern.


Övrigt
-----------------------

Skrivet av mig (Malin Olsson) och Filip Lindberg.

Referenser
-----------------------
[^1]: https://www.berghain.berlin/en/
[^2]: https://columbia-theater.de/ueber-uns/
[^3]: https://www.berliner-mauer-gedenkstaette.de/en/
[^4]: archive.org - Sparad version av berghain.berlin från 20/10/2021 - hämtad 26/11/2021: <br>https://web.archive.org/web/20211020135212/www.berghain.berlin/en/
[^5]: The Principles of Beautiful Web Design s.70
[^6]: The Principles of Beautiful Web Design s.68