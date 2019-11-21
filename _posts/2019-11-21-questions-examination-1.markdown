---
title: "Examination 1"
date:   2019-11-21 07:00:00 +0200
categories: examination 1
tags: [1dv022]
excerpt_separator: <!--more-->
og_description: Frågor att besvara i examinationsuppgift 1
og_image: codes_story.jpg
og_type: article
---

[CoursePress](http://coursepress.lnu.se/kurs/klientbaserad-webbprogrammering/examination/exam-assignment-1/ "Länk till uppgiftsbeskrivning")

1. Vad tycker du om att förkompilera CSS?
    * Jämför med vanlig CSS.
    * Vilka tekniker använde du?
    * Fördelar och nackdelar?   
<!--more-->
2. Vad tycker du om *static site generators* (SSG)?
    > "Investeringstiden" i början var högre än att komma igång med utveckling av en "vanlig" statisk webbplats, men när strukturen och förhållandet mellan delarna faller på plats gillar jag enkelheten med mallar och markdown.
    * Vilken typ av projekt är de lämpliga för?
    > SSG lämpar sig för projekt där innehållet på avdelningarna uppdateras frekvent. Detta eftersom strukturen för att hantera texter på webbplatsen är relativt enkel, mha. markdown, och ingen `html` behöver ändras för att lägga till nytt material.
    > SSG behövs ingen databas sättas upp för att hantera innehållet och därmed kan det vara enklare att hosta siten och underhålla den.
    > Därmed anser jag att exempelvis Jekyll är passande när syftet med webbplatsen är att hantera texter och innehåll som uppdateras ofta, då det blir svårt att underhålla en statisk webbplats och för komplicerat med en CMS-plattform.

3. Vad är robots.txt och hur konfigurerarade du denna för din webbplats?
    > Denna textfil ger instruktioner till sökmotorerna hur webbplatsen ska indexeras och är viktig del av sökmotorsoptimeringen. Den gör det möjligt att begränsa sökmotorernas **spindlar/robotar** och därmed blockera åtkomst till delar av webbplatsens innehåll. I robots.txt defineras med andra ord **spindelns beteende**.

    > Den här webbplatsens **robots.txt** är konfigurerad så att reglerna i filen gäller alla sökrobotar och att endast `_site`, där de generarade filerna ligger, indexeras. Regler för tillgång till `css` och `js` defineras också i textfilen.

4. Vad är humans.txt och hur konfigurerarade du denna för din webbplats?
    > Textfilen innehåller infromation om personen/personerna som skapat eller är kopplade till webbplatsen på något vis. Syftet med filen är alltså att sökmotorsspindeln ska hitta relevant information kring utvecklingsteamet, personer som bidragit till utvecklingen samt information om vilka verktyg som använts för utveckling, senaste uppdaterad och språkinformation.

5. Hur implementerade du kommentarer på blogginlägg?
    > Jag implementerade kommentarsfält på blogginläggen m.h.a. **Disqus**. Genom att skapa ett användarkonto på [disqus.com](https://www.disqus.com) och följa instruktionerna för konfigurering kan man på önskade avdelningar lägga till ett kommentarsfält. 

    > Detta kommentarsfält kan nyttjas av användaren och med administratörsrättigheter finns det möjlighet att få sammanställd statistik över all aktivitet gällande kommentering på webbplatsen. 

6. Vad är *Open Graph* och hur använder du detta?
    > Open Graph är meta-taggar som definerar informationen som ska visas när webbsidan delas på exempelvis sociala medier. Med hjälp av Open Graph defineras eventuellt den bild, titel, beskrivning etc. som ska visas på tredjepartswebbplatsen. 
    > Jag har på denna webbplats användt Open Graph för att definera vilken bild, titel, beskrivning och typ som ska visas när blogginlägg, startsida och om-mig-sida delas.
