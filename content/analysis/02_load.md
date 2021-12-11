---
Title: Load
Description: A paper about load in web design.
Template: index
---
Snabbmat eller långkok?
=======================
## Tre livsmedelskedjors webbplatser och deras snabbhet

Inom ramen för kursen "Teknisk webbdesign och användbarhet" på Blekinge Tekniska Högskola under höstterminen 2021 har denna rapport sammanställts för att undersöka hastigheten på tre olika webbplatser.

Urval
-----------------------
Eftersom analysen gäller snabbhet valde vi tre webbplatser som förväntas ha liknande innehåll eftersom de verkar inom samma bransch. Vidare ansåg vi att företagen vars webbplatser analyserades kan anses vara tillräckligt stora för att man ska kunna anta att de har resurser för att optimera sina webbplatser. De webbplatser som analyserats är:

- [ICA](https://www.ica.se/) [^1]
- [COOP](https://www.coop.se/) [^2]
- [Willys](https://www.willys.se/) [^3]

<br />
Metod
-----------------------
För att genomföra analyserna har tre utvalda sidor på vardera webbplats testats med hjälp av Googles verktyg [PageSpeed Insights](https://pagespeed.web.dev/)[^4]. Resultatet för “Performance” för såväl mobil som desktop har noterats i ett Numbers-ark (motsvarande Excel). Samma sidor har sedan inspekterats med hjälp av verktyget Network/Nätverk i Firefox DevTools. Sidorna har sedan laddats om utan cache varpå värdena för laddningstid (load), antal förfrågningar (requests) samt sidans totala storlek (x kB/MB transferred) har noterats i samma Numbers-ark. 

Webbplatserna har även poängsatts enligt ett enkelt poängsystem. Medelvärdet för tre olika mätvärden har jämförts mellan de tre olika webbplatserna. Mätvärdena är performance, laddtid per MB och snittladdtid. Det bästa värdet (snabbast eller liknande) får två poäng, det näst snabbaste får ett poäng och det sämsta värdet får noll poäng. Om två värden är lika får båda samma poäng.


Resultat
-----------------------
### ICA
![ICAs webbplats](%assets_url%/img/load/ica.png) {.website-img}
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSecwwkd62xE4N1luuydbHr8z05i-kcgb8P6LFGXrqtHOdgOOYeRBFtRjwZdGahLaV9ge-WrjNAp_JV/pubhtml?gid=1391571426&amp;single=true&amp;widget=false&amp;headers=false&amp;chrome=false" class="load-table"></iframe>

#### Förbättringspotential
Enligt PageSpeed Insights innehåller webbplatsens kodbas JavaScript som inte används. Om detta åtgärdades skulle hemsidan enligt PageSpeed Insights kunna laddas ~0,33 sekunder snabbare.

### COOP
![COOPs webbplats](%assets_url%/img/load/coop.png) {.website-img}
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSecwwkd62xE4N1luuydbHr8z05i-kcgb8P6LFGXrqtHOdgOOYeRBFtRjwZdGahLaV9ge-WrjNAp_JV/pubhtml?gid=767820399&amp;single=true&amp;widget=false&amp;headers=false&amp;chrome=false" class="load-table"></iframe>

#### Förbättringspotential
COOPs webbplats har också problem med oanvända skript men PageSpeed Insights indikerar också att det finns resurser som blockerar resten av webbplatsen från att ladda vilket försenar "First Paint". Enligt PageSpeed Insights hade detta kunnat spara ~0,51s laddtid.

### WILLYS
![Willys webbplats](%assets_url%/img/load/willys.png) {.website-img}
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSecwwkd62xE4N1luuydbHr8z05i-kcgb8P6LFGXrqtHOdgOOYeRBFtRjwZdGahLaV9ge-WrjNAp_JV/pubhtml?gid=1543509236&amp;single=true&amp;widget=false&amp;headers=false&amp;chrome=false" class="load-table"></iframe>

#### Förbättringspotential
Willys webbplats lider av samma problem som ICA och COOPs webbplatser gör, med oanvända skript och resurser som blockerar laddning av webbsidorna. Om dessa problem hade lösts skulle webbplatsen kunna spara ~0,53s enligt PageSpeed Insights. 

Analys
-----------------------
Samtliga tre webbplatser har dålig prestanda. Denna slutsats går att dra utifrån resultatet där alla tre webbplatser har under 49 i snitt på PageSpeed Insights nyckeltal "Performance". Enligt PageSpeed Insights webbplats är 0-49 underkänt. Deras snitt dras i samtliga fall ner markant av de mobila versionerna av webbplatserna som verkar mycket dåligt optimerade. Resultatet är någorlunda förvånande eftersom de företag som undersökts är välkända, stora och ekonomiskt starka. Man skulle kunna tänka att de skulle kunna se värdet i att lägga mer resurser på välutvecklade webbplatser år 2021. 

De vanligaste förbättringsmöjligheterna som webbplatserna hade enligt PageSpeed Insights var:
- Oanvänd JavaScript
  - Om en webbplats laddar in script som inte används tar detta upp bandbredd vilket gör att sidan laddar långsammare. Ifall sådan kod reduceras kan webbplatsens prestanda och laddtider förbättras. För att lösa detta problem behöver man hitta den oanvända koden och ta bort den. I en artikel på web.dev[^6] presenteras ett antal verktyg som kan hjälpa till med att hitta oanvänd kod.
- Resurser som blockerar rendering av webbplatsen
  - När en webbsida laddas behöver den vissa resurser (script, stylesheets, etc.) för att kunna visa en första representation av innehållet. Dessa resurser, som behövs för att rendera sidan above the fold, kallas kritiska resurser. Om något fördröjer laddningen av en eller flera av dessa resurser blockeras första visuella innehållet på webbplatsen, s.k. _first paint_. Ett exempel på något som kan orsaka detta problem är att en resurs är väldigt stor med mycket icke-kritisk kod. En åtgärd skulle enligt web.dev[^5] kunna vara att lägga kritiska delar av script och stylesheets direkt i headen.

### Rangordning av webbplatserna
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSecwwkd62xE4N1luuydbHr8z05i-kcgb8P6LFGXrqtHOdgOOYeRBFtRjwZdGahLaV9ge-WrjNAp_JV/pubhtml?gid=1845205902&amp;single=true&amp;widget=false&amp;headers=false&amp;chrome=false"></iframe>

Ovan är resultatet från det poängsystem som beskrivs under underrubriken 'Metod'. Trots de generellt dåliga resultaten lyckades vi kora en vinnare: Willys!

### Uppfattning av laddningstid
Utifrån de tester vi genomfört för rapporten upplever vi att laddtider från ~1s och uppåt känns långsamma. De enda webbsidorna som kom under denna _magiska_ gräns var samtliga av de sidor vi undersökte från Willys samt en sida från COOP.

Övrigt
-----------------------
Texten är skriven av mig (Malin Olsson) och Filip Lindberg.


Referenser
-----------------------

[^1]: https://www.ica.se/
[^2]: https://www.coop.se/
[^3]: https://www.willys.se/
[^4]: https://pagespeed.web.dev/
[^5]: https://web.dev/render-blocking-resources/?utm_source=lighthouse&utm_medium=lr
[^6]: https://web.dev/unused-javascript/?utm_source=lighthouse&utm_medium=lr
