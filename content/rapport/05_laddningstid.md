Utvärdering av webbplatsers laddningstid
=======================

Syftet med den här rapporten är att analysera tre olika webbplatser som tillhör samma kategori och dokumentera hur 
deras laddnigstider är samt om det finns något som kan förbättras.

Urval
-----------------------

Jag har valt att undersöka hemsidorna för märkena som är del av, "The holy trinity of watches", Audemars Piguet, Patek Philippe och Vacheron Constantin. För att jag analyserade de sidorna i min förra analys så ville jag använda samma hemsidor i denna för att 
se om de presterar lika bra inom detta området.

Metod
-----------------------

Undersökningen utförs genom att jag kollar webbplatsernas laddningstid med google pagspeed.Sedan kontrollerade jag även laddningstiden samt hur många resurser som laddas in med hjälp av devtools nätverksflik. All data läggs in i ett [google kalkylark](https://docs.google.com/spreadsheets/d/1cgLGZ_f_pwYyPAsUFBXfvo_vizUlLbt8YswF5yJ5_iM/edit?usp=sharing).

Resultat
-----------------------

[Audemars Piguet](https://www.audemarspiguet.com)
[FIGURE class="report-img" src=img/rapport-color/ap-home.png caption="Audemars Piguet Homepage"]

Audemars Piguet presterade bäst av alla tre webbplatserna i google pagespeed. Både för desktop med 93.6 som genomsnittligt värde
och för mobile med 64.3. Webbplatsen presterade även bäst i mätningarna med developer tools, den hade överlägset snabbast laddningstid 
på 1.74 sekunder, ca hälften av de andra två sidorna. Men detta beror nog på att den endast har 22 resurser som laddas in vilket också gör 
att det är den minsta sidan när det kommer till den totala storleken på 2.23 MB. Webbplatsen är redan snabb och har inte så många onödiga resurser, så det enda som skulle kunna förbättra den är nog att skala ner på antalet bilder, för det finns det ganska många av.

<hr>

[Patek Philippe](https://www.patek.com)
[FIGURE class="report-img" src=img/rapport-color/pp-home.png caption="Patek Philippe Homepage"]

Patek Philippe presterade också bra på google pagespeed, för desktop-testet så fick den 90, snäppet sämre än Audemars Piguet. När det kommer till mobile så fick den 64.3, dvs en delad förstaplats med Audemars Piguet. När det kommer till developer tools-mätningarna så visas en annan historia. Den genomsnittliga laddningstiden var 3.43 sekunder, långsamast av alla sidorna. Men den totala storleken var ändå inte så stor som man skulle kunna tro om man kollar på laddningstiden. Bara aningen större än Audemars Piguets, med 2.8 MB. Laddningtiden beror snarare på det stora antalet resurser som laddas in, 70 stycken närmare bestämt, ca tre gånger mer än Audemars Piguet. För att förbättra laddningstiden gäller det nog att dra ner på antalet resurser som laddas in.

<hr>

[Vacheron Constantin](https://www.vacheron-constantin.com)
[FIGURE class="report-img" src=img/rapport-color/vc-home.png caption="Vacheron Constantin Homepage"]

Vacheron Constantins resultat i google pagespeed var överlägset sämst. 60.3 i desktop och 21.3 i mobile-testet. Mätningarna med 
developer tools visade att sidan är störst av alla tre, 4.20 MB. Laddningstiden på 3.35 sekunder var aningen bättre än Patek Philippes 
men bara med ca 0.08 sekunder. Antalet resurser ligger i mitten av de tre sidorna med 38. De dåliga resultaten på google pagespeed beror troligast på alla bilder plus den stora mängden javascript som verkar finnas på webbplatsen.

Analys
-----------------------
Alla tre webbplatserna har mycket bilder och en hel del javascript. Det är de främsta orsakerna till att resultaten inte är världsbra.
Att dra ner på antalet bilder eller optimera dem genom att tex inte använda onödigt stora bilder, skulle kunna förbättra resultaten ganska mycket. 

Vinnare
-----------------------
<b>1. Audemars Piguet</b>

Audemars Piguet är en ganska så överlägsen vinnare. Nästan hälften så kort laddningstid som de andra, minst antal onödiga resurser 
och den minsta totala storleken.

<b>2. Patek Philippe</b>

Patek Philippe presterade bra i google pagespeeds mätningar. Även om webbplatsen har väldigt många resurser och har långsammast laddningstid jämnfört med de andra. Så är den ändå bättre optimerad än Vacheron Constantins sida, bara snäppet långsammare fast mycket mindre i storleken.

<b>3. Vacheron Constantin </b>

Vacheron Constantin har en väldigt stor webbplats jämnfört med de andra två, den klarar sig dock precis från att inte ha den långsammaste laddningstiden. Men det väldigt dåliga resultatet i google pagespeed visar att webbplatsen har stora optimeringsproblem.

Generellt
-----------------------
Även om dessa webbplatser är ganska långsamma att ladda in så känns det ändå ganska normalt, det är tack vare det stora antalet webbplatser idag som är dåligt optimerade och använder sig av alldeles för mycket javascript. Jag skulle sätta en gräns vid 3 sekunder. En webbplats som tar längre tid än det känns väldigt långsam. Av dessa tre webbplatser är det bara Audemars Piguet som klarar sig under den gränsen medans de andra två är en bit över, det gör att de två känns ganska sega när man besöker dem.

Max Gotenstam.