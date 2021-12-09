---
Title: Load
Description: Load
Template: analys
---

Webbplatsers laddningstid
=======================

Uppgiften handlar om att analysera laddningstiden på olika webbplatser. Jag har valt tre spelföretag.
Analysen genomförs med Google Pagespeed.

Urval
-----------------------

I denna analys har jag valt tre spelföretag att analysera. Dessa spelföretag är Riot games, Hypixel studio och CD Project Red. Dessa var samma tre webbplatser som jag analyserade i min "Färger på hemsidor" analys. Om du vill veta lite mer om spelföretagen så beskrev jag dem lite i den analysen. Anledningen till att jag valde att analysera samma webbplatser igen är så att man kan få en överblick över dessa tre sidor. Man kanske kan dra sina egna slutsatser efter att ha läst mina analyser och jämföra t.ex. vad företagen fokuserar mest på. Kanske de lägger mycket mer fokus på färger och bilder för att skapa en känsla på webbplatsen istället för att allt ska ladda in snabbt.

Metod
-----------------------

Jag använder mig av Google Pagespeed och network-fliken i devtools för att analysera laddningshastigheter. Rådatan sparas ned i ett excelark och resultat tas upp i denna rapport. Datan som noteras i Google Pagespeed är Speed Index och Overall Performance för Mobile och Desktop. I devtools under network-fliken så noteras laddningstid, antal requests och hur mycket mb som överfördes.

Resultat
-----------------------

<iframe style="width: 1000px; height: 350px;" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTyrQI1wV_fmVv6QHmWxBwTY3mar6WRUWpH-WlcqbfYzOBVat9JCphpPEu56JTbnr-VLkTVf-V8-943/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

### Riot games

<a href="https://www.riotgames.com/en" target="_blank"><img src="../assets/img/riot_games.jpg" alt="riot games" style="width: 1000px; height: 500px;"></img></a>

Riot games webbplats verkar vara snabb och responsiv på desktop men när det kommer till mobil så har den väldigt låg overall performance och ganska hög speed index.
Förbättringsåtergärder för denna webbplats är att skicka bilder i modernare bildformat, använda bilder i rätt storlek och att ta bort resurser som blockerar renderingen.


### CD Project Red

<a href="https://en.cdprojektred.com/" target="_blank"><img src="../assets/img/cd_project_red.jpg" alt="cd project red" style="width: 1000px; height: 500px;"></img></a>

CD Project Red har liknande resultat som riot games med en bra overall performance och speed index på desktop men inte på mobilen. Däremot så har CD Project Red bättre overall performance än riot games på mobilen.
Förbättringsåtergäder för denna webbplats är att skicka bilder i modernare bildformat, koda bilder effektivt och reducera JavaScript som inte används.


### Hypixel studios

<a href="https://hypixelstudios.com/" target="_blank"><img src="../assets/img/hypixel_studios.jpg" alt="hypixel_studios" style="width: 1000px; height: 500px;"></img></a>

Hypixel studios resultat står ut ifrån de andra. Webbplatsen har en väldigt bra speed index och overall performance på desktop. Hypixel studios lyckas också få hyfsade resultat på mobilen.
Förbättringsåtergärder för denna webbplats är att skicka bilder i modernare bildformat och i rätt storlek samt att reducera JavaScript som inte används. Det mest förvånande här är att på mobilen är den uppskattade tidsbesparingen för att skicka bilder i modernare bildformat ca 10 sekunder.

Analys
-----------------------

Generellt sett så verkar det som alla dessa webbplatser har en mycket snabbare webbplats på desktop jämfört med på mobilen. Detta beror säkert på att de flesta som besöker deras hemsida kommer att vara personer som är intresserade av deras spel som spelas på datorn. Därför lägger de mer fokus på att hemsidan fungerar bra på desktop i första hand.

De vanligaste förbättringsåtergärderna verkar vara att skicka bilder i modernare bildformat, använda bilder i rätt storlek och att reducera JavaScript som inte används.

Om man ska rangordna dessa webbplatser så tar Hypixel Studios en stark första plats då den laddar mycket snabbare än de andra och även lyckas bättre med mobilens laddningstid. Riot games och CD Project Red ligger väldigt lika i princip alla aspekter. Dock så har CD Project Red bättre overall performance på mobilen så därför sätter jag CD Project Red på andra plats och Riot games på tredje plats.

Om jag ska sätta en gräns för absolut laddningstid så skulle det nog vara 4-5 sekunder för att webbplatsen ska uppfattas som snabb. Webbplatserna klarar alltså min gräns och jag anser generellt att dessa webbplatser är snabba. Jag märker i princip ingen skillnad mellan webbplatserna när jag laddar dem på datorn. Även på mobilen så känns det snabbt och jag tycker inte resultaten reflekterar min känsla och uppfattning av hur snabba sidorna är speciellt inte resultaten för mobilen.
Detta beror nog på att den man ser på förstasidan laddar in snabbt men andra saker som man inte ser direkt laddas in saktare/senare.

Det generella man kan säga för dess webbplatser är att det som tar mest på laddningstiden är bilder. Detta är förståligt eftersom att dessa sidor är spelföretag och de vill såklart visa mycket bilder på sina spel och tjänster.



Referenser
-----------------------

Google Pagespeed

Övrigt
-----------------------

Jag arbetade ensam på denna rapport.