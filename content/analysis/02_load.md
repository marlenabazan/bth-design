---
Title: Load
Description: Load analysis.
Template: analysis-article
---

Laddningstid
=======================

Analysera laddningstid på tre webbplatser. Jag har valt olika webbutvecklare portföljer.

Urval
-----------------------

Jag har valt tre webbutvecklare portföljer:
- https://www.jason.af/
- https://robbowen.digital/
- https://www.shanemielke.com/

Urvalet gjordes genom att googla olika portföljer och jag har valt tre med intressanta färgval.

Metod
-----------------------

Analysen görs med hjälp av PageSpeed Insights och Google Chrome devtools. För varje sida mäter jag sidans laddningstid 3 gånger och samlar in snittet av mätvärdena i en Google kalkylark.

Resultat
-----------------------
<iframe class="analysis-load" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSU7SRBH2oyCuAO9OPkSYYyVz3ZbCpdkHnW3f3ZTvltgKj1Hz14TNhhar7S11m_hX2GGZ0SetXVHR6M/pubhtml?gid=634347005&amp;single=true&amp;widget=true&amp;headers=false"></iframe>  
<br>

### https://www.jason.af/
<img class="website-screen" src="../image/jason.png" height="400" alt="jason">

Sidan fungerar snabbt och alla tester markeras med grönt. Jag ser inget som kan förbättras.
<br>

### https://robbowen.digital/
<img class="website-screen" src="../image/robbowen.png" height="400" alt="robbowen">

PageSpeed Insights säger att LCP behöver förbätttras och föreslår att det kan göras med att ta bort resurser som blockerar sidans första rendering.
<br>

### https://www.shanemielke.com/
<img class="website-screen" src="../image/shane.png" height="400" alt="shane">
Den här sidan har den längsta laddningstid jämfört med de andra. Det finns mycket rörelse och många bilder på webbsidan så sidan kan förbättra sig genom att reducera JavaScript lite och använda mindre eller lägre kvalitet bilder.
<br>


Analys
-----------------------

De vanligaste förbättringsåtgärderna verkar vara att begränsa JavaScript och använda mindre eller lägre kvalitet bilder. Sammanfattningsvis har valda webbsidor en bra prestanda, förutom Shanes sida. För mig som användare känns det att sidorna laddas snabbt och på Shanes sida efter en viss tid känns det att man väntar och väntar...

Webbsidor rangordnade enligt laddningstid:
1. https://www.jason.af/
2. https://robbowen.digital/
3. https://www.shanemielke.com/

Jasons sida klarar alla tester och fungerar snabbt och smidigt. Robbs sida fungerar också ganska snabbt men det finns något litet som kan förbättras. Shanes sida är den långsammaste av alla. Den är den största och mest "levande" men när man klickar runt på sidan så laddas den ibland i några sekunder.

Min gräns för vad som är en rimlig laddningstid ligger på ca 2 sekunder och när det närmar sig 3-4 sekunder så börjar sidan upplevas som långsam. Första två sidor klarar min gränsvärde men Shanes sida är lite för långsam. Man vill inte vänta några sekunder på att varje sida ska laddas.

Övrigt
-----------------------

Marlena Bazan, enpersonsgrupp.
