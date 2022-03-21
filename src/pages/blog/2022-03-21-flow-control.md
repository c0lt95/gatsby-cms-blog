---
templateKey: blog-post
title: Flow control
date: 2022-03-21T05:54:32.799Z
description: Week 6
featuredpost: true
featuredimage: /img/hqdefault.jpg
tags:
  - week6
  - assertions
  - mobiledrivers
---
Op **maandag** 14 maart was onze zesde week stage van start gegaan. We zijn met z'n 3 vroeg begonnen met het voorbereiden van de demo aan David. Na de feedback zijn we start gegaan. Ik heb me vooral verdiept in het verwerken van de Assertion methode.

**Dinsdag** moesten we enkele aanpassingen doen in onze code. Sommige extension werden niet op de juiste manier opgeroepen, waardoor er nood aan refactoring was. Daarnaast ben ik van start gegaan met de implementatie van simpele assertions voor het vergelijken van individuele elementen.

**Woensdag** wou ik in de Assertion extensie enkele methodes bij doen die gebruik maakten van de Populator extension, waarbij twee gevulde lijsten met data met elkaar vergeleken kon worden. Dit leek niet zo simpel als eerder gedacht en het nog erger te maken, bleek de Wait() Function niet te werken in onze testcases. We dachten initieel dat dit aan onze framework lag.  In de namiddag hadden we een technische meeting met Frederique, waarbij onze code werd overlopen en hij gaf ons enkele mogelijke oplossingen voor de Wait() Functie probleem op te lossen. \
\
**Donderdag** heb ik me bezig gehouden met het oplossen van de Wait() Functie. Ik heb eerst geprobeerd dit met de voorstellen van Frederique te doen, zoals het downgraden van Selenium of gebruik te maken van Lambda functies, maar niet leek te helpen. Ik werd zot. Ik kende de eerste paginas van mijn Google zoekopdrachten al van buiten, alles toegepast en niets werkte. Uiteindelijk hebben we besloten de methodes op een andere website dan die van B-Tube te proberen; et voila! Het werkte op Google en Netflix! Het lag dus niet aan onze code maar de website die we ware aan het testen. 

**Vrijdag** heb ik me vooral bezig gehouden met het finetunen van de Assertion methode, vooral met het ophalen en vergelijken van lijsten met data. Het zou nog veranderd moeten worden, zodat de gegevens op basis van een geselecteerde WebElement van de website worden ingevuld en vergeleken, in plaats een lijst ineens als parameter mee te geven. 

![]()



![]()