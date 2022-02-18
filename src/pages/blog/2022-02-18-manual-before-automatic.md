---
templateKey: blog-post
title: "Manual before Automatic "
date: 2022-02-18T13:54:32.628Z
description: "Week 2 "
featuredpost: true
featuredimage: /img/dzaezaeaze.png
tags:
  - week2
  - testcase
  - testscenario
  - manual
  - automation
---
Op **maandag** 14 februari was onze tweede week stage van start gegaan. David was op die dag op verlof, dus hebben we de sprintplanning onder elkaar gehouden. We hebben de voormiddag wat meer onderzoek naar Selenium en het Page Object Model gedaan. Erna zijn we begonnen aan enkele scripts uit te schrijven en enkele Unit Testen uit te voeren. 

**Dinsdag** was David terug en heeft ons erop gewezen dat we momenteel de testen manueel zouden moeten uitvoeren en documenteren. We kregen een template toegestuurd voor het uitschrijven van testcases. Hiermee zouden er 10 voor Web en 10 voor Mobile moeten uitgewerkt worden. Daar zijn we ook per direct aan begonnen. 

**Woensdag** zaten we terug op kantoor in Kontich en zijn de voormiddag begonnen met een team meeting en is de high level planning voor (bijna) alle komende weken ingevuld op vraag van David, die ons later ook kwam joinen voor de meeting met onze stagementor. Later op de dag hebben we wat verder gewerkt aan de testcases voor Web en rond 15.00 hadden we een technische meeting met Frederique, waar de mogelijkheid was om vragen te stellen. Hij heeft ons verder geholpen met de eventuele vraagstukken.\
\
**Donderdag** zijn we gestart met een meeting met David en de aanvulling van onze high level planning te bekijken. Het leek in orde te zijn en na de meeting zijn we meteen begonnen aan het verder uitwerken van onze testcases voor Web. Deze zijn voor het grootste deel uitgewerkt geweest, het was dan tijd dat we elkanders testcases manueel uitvoerden. Op deze manier zijn er enkele bugs gevonden, die vervolgens gedocumenteerd werden op een overzichtelijke manier in de Excel-bestand. \
\
**Vrijdag** kregen we feedback van David op onze uitgewerkte testcases voor Web. Het was positief en hij vond het goed dat we bugs hebben gevonden: dit betekent dat er zinvolle testen zijn uitgevoerd. Ik ben dan begonnen aan het reformatten en finaliseren van onze Testcase Web document en de testcase verloop op verschillende browsers (Chrome, Mozilla Firefox, Microsoft Edge en Safari) uit te voeren en documenteren. Aangezien onze formaat voor de testscenario's van Web in orde was, was het mogelijk om aan de testcases voor Mobile te beginnen. Hiermee zijn mijn teamgenoten ook aan slag gegaan. 

![meetin in kontich](/img/stagemeeting.png "De studenten van AP met David in Gnosia 1 ")

## Het nut van de testcases

Vooraleer we beginnen aan de test automatisatie is het nuttig om de testen **manueel** uit te voeren en deze stapsgewijs te **noteren**. Zo kan er makkelijker gekeken worden naar de **high level flow** in de automatisatie zelf: bij **welke stappen** kunnen er zaken misgaan en met **wat** heeft het te maken. Een veelvoorkomend test is op de **inputvelden**: wat als er letters ingevoerd worden wanneer er cijfers gevraagd worden, wat als men een e-mailadres in de verkeerde formaat invult, enz. Men vertrekt vanuit een **happy flow** waar alles juist verloopt en breidt men uit met de **wat-als** situaties. \
\
Op deze manier kan de developer zien waar er **generators** nodig zijn, zodat er op de wat-als situaties **maximaal** getest kan worden. Dit kan door methodes die **random waarden**, volgens een vastgestelde structuur, **genereren** in te zetten en mee te nemen in de framework. \
\
Daarnaast kunnen de testcases gebruikt worden om voor **klanten** duidelijk te maken **hoe er getest** wordt en **welke nut** de testen hebben. Zo is het makkelijk in te zien dat **kwalitatieve testen** voor **kwalitatieve applicaties** zorgen. Ook geeft het de **efficiëntie van automatisatie** van de testen aan: zonder generators zou men exponentieel meer tijd verliezen door manueel zelf de mogelijke inputwaarden uit te testen. Dit kan zeer tijd- en kostenrovend zijn. \
\
Hieronder een klein voorbeeld van een testcase dat nagaat of een gebruiker de mogelijkheid heeft om een film met een verlopen leenperiode te bekijken. *(Het is mogelijk => Bug gevonden)*

![](/img/testcase.jpg)