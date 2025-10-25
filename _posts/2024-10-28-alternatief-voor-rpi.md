---
title: Alternatief voor Raspberry PI
layout: Post
tags: IT, RPi
---
Sinds 2012 zijn de diverse Raspberry PI's een goed platform voor kleinschalige thuisserver toepassingen. Menig website, multimedia of file server wordt gedraaid op deze compacte single board computers.[--more--]

Door onderdelenschaarste, inflatie en technische groei is de prijs in de afgelopen 12 jaar helaas fors opgelopen. Gingen de eerste versies nog voor circa 35 euro over de toonbank nu ligt de prijs al gauw op 75 tot 90 euro. Dit is dan de prijs voor de Pi zelf. Daar komen dan nog kosten voor behuizing, voeding en eventueel koelsysteem bij. Je winkelwagentje in een webshop tikt zo maar €150 aan.

Gelukkig heeft de Raspberry Pi organisatie dit zelf ook ingezien en levert inmiddels ook een serie vereenvoudigde bordjes onder de namen Zero en Pico. Deze laatsen zijn wellicht prima te gebruiken voor DIY-projecten maar zijn minder geschikt voor server toepassingen.

Een goede ontwikkeling bij het laatste Pi 5 model is de mogelijkheid om niet langer gebruik te maken van de trage en kwetsbare SD kaartjes maar over te stappen naar NVME M.2 opslag media. Helaas is hier wel een extra HAT voor nodig wat de prijs verder opdrijft en de doorvoor voor PCI 2.0 interface is beperkt tot maximaal 500 MB/s. Daarnaast blijken er soms compatibiliteitsproblemen op te treden tussen Pi 5 en de NVME M.2 opslag media.

[image hp_prodesk_400_g5.jpg "HP Prodesk 400 G5" right 200 200]Een potentieel alternatief voor een Pi 5 met toebehoren is het gebruik van een mini of small form factor (sff) PC. Als je kiest voor een tweedehands HP, Lenovo of Dell dan heb je vanaf pakweg €100 een prima basis voor een thuis server. Een beetje afhankelijk van type en bouwjaar geeft je de keuze uit een i3, i5 of i7 Intel of AMD processor, 2 SO-DIMM slots voor 32 of 64GB memory, een SATA III aansluiting, WiFi en een NVME M.2 slot op basis van PCI 3.0 of 4.0. Net als een Pi heeft een dergelijke PC een 4-tal USB 2.0/3.x aansluitingen Het stroomverbruik (idle) ligt rond de 10 watt per uur, dus dat valt ook te overzien. Deze zeer gangbare Intel/AMD platformen ondersteunen alle gangbare versies van FreeBSD of Linux.

Dit alternatief voor een RPi gaat natuurlijk alleen op als je geen gebruik hoeft te maken van de 40-polige GPIO interface!