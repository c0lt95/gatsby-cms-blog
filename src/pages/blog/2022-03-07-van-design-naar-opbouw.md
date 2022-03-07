---
templateKey: blog-post
title: Van Design naar Opbouw
date: 2022-03-07T09:21:34.338Z
description: Week 4
featuredpost: true
featuredimage: /img/blueprint-png-1-transparent-images.png
tags:
  - week4
  - solid
  - skeletstructuur
  - framework
---
Op **maandag** 28 februari was onze vierde week stage van start gegaan. Het was tijd om onze skeletstructuur op te bouwen aan de hand van de SOLID principles en desin patterns. Het uittekenen van de UML structuur heeft hier goed voor geholpen. Ik ben van start gegaan na overleg met de team met het coderen van de BasePage en BaseTest. Erna heb ik de namiddag besteed aan het coderen van enkele Generators, namelijk ListGenerator en EnumGenerator. Dit zijn extensions voor onze framework die helpen voor het aanmaken van lijst en enums. Ze worden gebruikt voor de testcases beter te automatiseren. 

**Dinsdag** ben ik begonnen om een valuescanner methode te schrijven, die we opnemen in de Generators. De resterende dag heb ik me bezig gehouden met het schrijven van verschillende extensions voor onze framework. Om meer specifiek te zijn voor de Webdrivers. Dit zijn methoden die we gaan dienen in onze framework om testen mee te schrijven. Frederique vroeg om custom wrappers te maken en Selenium zoveel mogelijk naar het achtergrond te duwen. Ik heb de Clicker, ElementFinder en ElementTargeter extensies kunnen coderen. 

**Woensdag** heb ik het coderen van de Extensions verdergezet. Het was tijd om de custom wrapper klassen aan te maken voor FormFiller, SurftToURL en TextSelector. De twee eerste extensies werkten zonder errors, maar ik kreeg een bug bij de TextSelector, waarbij de WaitForClickable methode van de OpenQA.Selenium.Support niet herkend werd. Gelukkig heb ik het opgelost gekregen door de NuGeT package te downgraden met de compatiebele versie van de driver. \
\
**Donderdag** heb ik me bezig gehouden met het uitschrijven van de WaitExtension en Screenshot extensie. Voor de Screenshot had ik me gebaseerd op een voorbeeld op GitHub, maar deze bleek obselete te zijn. De package diende manual geïnstalleerd te worden, waarbij de effectiviteit voor onze framework in vraag gesteld. Na overleg met de team heb ik besloten om een andere manier voor de constructors van de Screenshot extensie te zoeken en ben dusdanig mijn research begonnen. \
\
**Vrijdag** heb ik besteed aan het samenvoegen van de verschillende mappen en klassen. De Helpers en Models gecodeerd door Hugues werden toegevoegd aan de andere mappen, zodat we een skeletstructuur hebben voor onze framework. We hebben geprobeerd alles volgens de principes van OOP toe te passen. Er werden nogal veel errors gegeven, die vaak lagen aan de imports van de geïnstalleerde packages. Deze hebben we kunnen wegwerken en was het tijd om een repo aan te maken op GitHuB.

![skeletstructuur framework](/img/skeletstructuur.jpg "skeletstructuur")

###### (Huidige skeletstructuur)

![]()