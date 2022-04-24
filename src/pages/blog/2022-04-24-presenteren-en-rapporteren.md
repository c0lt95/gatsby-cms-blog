---
templateKey: blog-post
title: Presenteren en rapporteren
date: 2022-04-24T12:56:59.312Z
description: Week 11
featuredpost: true
featuredimage: /img/how-to-crash-your-own-presentation.jpg
tags:
  - week11
  - marketing
  - sequentialtesting
---
Op **maandag** 18 april is week 11 van start gegaan. Er waren nog heel wat errors in de mobile testcases, waardoor we genoodzaakt waren enkele stories mee te nemen. Dit vonden zij bij Brightest niet erg, aangezien we ook extra opdrachten de week ervoor hadden gekregen, zoals het voorbereiden van de presentatie, een nieuwe stagevoorstel uitschrijven en test runs documenteren. De resterende dag was nog besteed aan het oplossen van de problemen. 

**Dinsdag** heb ik me vooral bezig gehouden op B-Tube specifiek aanpassingen te doen voor ons framework. Herschrijven van enkele methodes, om extra parameters mee te geven en code korter te maken. Ook heb ik voor de Extensions en enkele andere Helper de summaries uitgeschreven in de code, zodat toekomstige gebruikers de gebruik ervan beter uitgelegd krijgen in hun IDE.  

**Woensdag** heb ik nog wat summaries aangevuld. We hebben dan een sequentiële test uitgewerkt, waarbij zowel Web- als MobileDriver aangeroepen wordt. Het ging als volgt: Een user registreert zich op web en logt in op Mobile. Vervolgens probeert deze user in de Mobile applicatie een film te huren zonder credits aan te kopen, wat uiteraard niet lukt en dit asserten we. Op Web gaat men inloggen als admin en de user op mobile enkele credits toekennen. Hierna zal de user op mobile terug een film huren en dit zou moeten lukken. We asserten het positief en is de test bijgevolg gelukt. Aanpassingen in de admin panel worden dus real-time doorgegeven in de databank. In de namiddag hebben we de presentatie voor de andere groep overlopen en we hadden ook een technische meeting.  \
\
**Donderdag** waren we om 9u terug op kantoor. Tot de middag hebben we onze framework gepresenteerd aan de andere groep en die van hun ook gevolgd. We merkten veel gelijkenissen, maar bijvoorbeeld lag er bij ons het focus meer op de functionele aspecten zoals duurzaamheid (obselete-proof maximaliseren) en hergebruikbaarheid. De andere groep spitste zich vooral toe op het documenteren en automatiseren van rapporteringen via Azure DevOps en het aanleg van pipelines. We hebben zeker wat kunnen leren van elkaar. Over het algemeen kregen we positieve feedback, maar uiteraard was niet alles perfect. We hebben enkele tips nog gekregen in verband van het anders schrijven van methodes en  de builders. Om 15u hadden we een meeting met de marketingteam en technische supervisors van Brightest over het uitwerken van de marketingfilm. 

**Vrijdag** hebben we gekeken naar de feedback van de dag ervoor en deze grotendeel toegepast op ons framework. Ook heb ik me bezig gehouden met een beetje documentatie. Daarnaast hebben we een korte word document opgesteld met de visie en voorlopige script van het marketingfilm dat we (hopelijk) gaan maken. We beginnen de week erop met een Masterclass Test Automation. Dit is een 2 week durende bootcamp van Brightest voor juniors die bij hun aan de slag gaan. Na deze bootcamp kunnen we meedoen met een examen voor de International Software Testing Qualifications Board. Hopelijk behalen we de Foundation ISTQB certificaat na de bootcamp. 

![pres](/img/pres.jpg "pres")

![]()