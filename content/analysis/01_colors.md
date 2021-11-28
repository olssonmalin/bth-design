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

Typ av färgschema:
Akromatisk med accent-färg alt. helt monokromatiskt.

Typsnitt:
Graphic **KOLLA UPP** på hela webbplatsen. Sans-serif.

Kommentar:
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


Typ av färgschema:
Monokromatiskt med en accentfärg (#F46D69).

Typsnitt:
Blandning av rubikregular och rubikmedium, sans-serif.

Kommentar:
Starka färger, nu äre fest!

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


Typ av färgschema:
Helt och hållet monokromatiskt.

Typsnitt:
Verdana all the way, sans-serif.

Kommentar:
Typsnitt är passande för museum. Färgschemat något skevt.

Analys
-----------------------
###Berghain:

- monikromatisk / akromatiskt + accentfärg?
- designen ändras beroende på bild i header
- DCA883 antingen accent eller del a monoschema
- klubb, label och agency (ostgut), konsertlokal (Kantine) mm. 
- DCA883 - mänsklig/hud/få röra sig bland människor igen

###Columbia Theater:


###Gedänkstätte Berliner Mauer:


Övrigt
-----------------------

Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten.

Referenser
-----------------------

[^1]: archive.org - Sparad version av berghain.berlin från 20/10/2021 - hämtad 26/11/2021: <br>https://web.archive.org/web/20211020135212/www.berghain.berlin/en/
[^2]: https://columbia-theater.de/ueber-uns/
[^3]: https://www.berliner-mauer-gedenkstaette.de/en/
[^4]: https://www.newyorker.com/magazine/2014/03/24/berlin-nights
