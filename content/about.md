---
Title: About
Description: Om mitt tillvägagångsätt.
Author: Malin Olsson
---

Tekniker använda på sidan
==========================

Jag har änvänt mig av sass på olika sätt. Jag har en del olika moduler som importeras i style.scss. Jag har använt mig av variabler i modulen för variabler för att till exempel sätta bodyns bredd på större skärmar till att vara 2/3 av hela beredden och även en default size för bilder. Dessa variabler används i style.scss. 

Jag har försökt lägga upp min kod till viss del som SMACSS. Där style.scss är min base och blir en dafault att falla tillbaka på men för att också kunna ändras genom moduler för specifica sidor som till exempel _index.scss. Skulle jag vilja att texten på sidan index ska vara en annan font-family kan jag specificera det i _index.scss och i och med att den modulen importeras efter i koden kommer texten att få än ny font-family än vad som bestäms i style.scss. 

