---
templateKey: blog-post
title: "Test Automation Web "
date: 2022-03-29T07:48:03.491Z
description: Week 7
featuredpost: true
featuredimage: /img/dsdqdq.jpg
tags:
  - week7
  - testautomation
  - webcases
---
Op **maandag** 21 maart was onze zevende week stage van start gegaan. We zijn de werkweek begonnen met een onderlinge sprintplanning aangezien David er niet bij kon zijn. We gingen proberen die week alle testcases van web af te werken. Zo ben ik begonnen aan de testcase van de homepage en de navigation layout. De bedoeling was om in onze testen na te gaan of alle nodige elementen in de menu aanwezig zijn per ingelogde user. Bijvoorbeeld de admin heeft in de navigatie een extra item "settings" om naar de admin panel te gaan. De bedoeling was om deze items hun aanwezigheid en functionaliteit te asserten. Daarnaast zijn alle items in de footer geassert op hun aawezigheid en de juiste hyperlink in de tag. 

**Dinsdag** heb ik me bezig gehouden met de testcase van de Registratiepagina. Hierop hebben we testen uitgevoerd om op verschillende manieren users te registreren. Eerst in de happy flow, dan bijvoorbeeld met enkel uppercase en lowercase. Vervolgens hebben we express verkeerde email inputs ingegeven om te testen of de webapplicatie de juiste errors en warnings teruggeeft. 

**Woensdag** was het tijd om de testcases van de Rent Movie Button uit te voeren. Zo werd er getest om een user weldegelijk films kan huren met voldoende credits. Ook werd er getest of men de verhuur geweigerd wordt bij onvoldoende credits en de juiste warning wordt weergegeven. Daarnaast werden testen uitgevoerd voor het verhuren van films die al bij de orders staan en wat er gebeurt wanneer een user zonder in te loggen wil huren. In de namiddag hadden we een meeting met Frederique die ons heeft verder geholpen met enkele methodes, waarbij we tot conclusie gekomen zijn dat er in sommige instanties voor B-Tube specifiek methodes geschreven moeten worden los van ons framework, om bepaalde testen nuttig te laten verlopen. Dit heeft te maken met het code van de applicatie zelf en niet ons framework.   \
\
**Donderdag** was weggelegd voor de testcase van de searchbar. Hierin werd nagaan of de searchbar aanwezig en actief is voor alle type users. Ernaast werd er nagegaan of men de juiste films gefilftered krijgt wanneer men de titel exact invoert, met undercase en uppercase alleen en met onnodige accenten. Deze slaagden allemaal. Ook werd er nagegaan of onbestaande films werkelijk niet gefiltered werd. 

**Vrijdag** werd de testcase van de van de admin panel deels uitgewerkt, waarbij de aanwezigheid van alle items visueel werd nagegaan. Erna hebben we enkele unit testen op onze framework uitgevoerd op vraag van David. Deze worden continu bijgevuld, terwijl onze framework wordt uitgebreid. 

![Testcases web](/img/testcases.jpg "testcases web")

(testcases van Web)

![]()