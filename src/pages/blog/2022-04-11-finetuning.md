---
templateKey: blog-post
title: Finetuning
date: 2022-04-11T06:22:23.877Z
description: Week 8
featuredpost: true
featuredimage: /img/index.jpg
tags:
  - week8
  - finetuning
---
Op **maandag** 28 maart was onze achtste week stage van start gegaan. Na de sprintplanning zijn we begonnen aan het afwerken van de Web Testcases. We hebben naar oplossingen gezocht om de enkele testen zodanig te automatiseren, zodat testen zoals Registration en RentMovieButton continu geloopt kunnen worden zonder manuele tussenkomst. De eerste manier is op zelfinvullende parameters te voorzien of om bij het begin van de testen een user aan te maken en tegen het einde van de test via de Admin Panel deze user te verwijderen. We hebben voor de laatste optie gekozen.

**Dinsdag** was het nodig om de Admin Panel Page en Testen uit te werken, zodat de test resets effectief in gang gezet kunnen worden. Deze dag heb ik me dan vooral met de Admin Panel Page bezig gehouden. Er moest een manier gevonden worden om uit een tabel van de users, een gebruiker op basis van email te filteren en in die kolom de 'remove'-button te drukken. De dag werd daaraan besteed. 

**Woensdag** heb ik in de voormiddag nog gewerkt aan de Admin Panel. In de namiddag hadden we een meeting met Frederique, waarbij enkele zaken waar we nog mee kampten werden aangehaald. Hij heeft ons enkele tips gegeven en aangeraden om naar Lambda-functies en Generic-functies te kijken. Dit hebben we als team gedaan en hebben een methode kunnen schrijven die alle users ophaalt en returned als een object.    \
\
**Donderdag** hebben we besloten om eens te kijken naar de Unit Testen op onze framework op vraag van David en de school. Zo zijn we begonnen om onze mappen te testen via Unit Testing, ik heb me vooral met de Unit Testen op onze Helpers klasse bezig gehouden. 

**Vrijdag** was het vooral refactoren van onze code en waar nodig enkele commentaar in de code schrijven, alsook enkele methodes hernoemen zodat het voor de eindgebruiker uiteindelijk veel duidelijker is wat er juist gebeurt. Zoals Availability() naar AvailabilityOfARentedMovie(). Toen ben ik begonnen aan de test resets ven enkele webcases. De komende week (eerste week van de Paasvakantie) hebben we verlof genomen. 

![]()



![]()