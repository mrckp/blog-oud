---
layout: post
title: DNS filters
excerpt_separator:  <!--more-->
tags: Privacy, DNS
---
<!--more-->
Helaas is het internet vergeven van reclame en dataverzamelaars. Soms is het nodig omdat het de enige vorm van inkomsten van een site is. Helaas leidt het vaak ook veel te veel af van de inhoud en worden er oneigenlijke gegevens verzameld. Hier valt eenvoudig wat aan te doen.
<!--more-->
Natuurlijk kun je een adblocker installeren als plugin voor je webbrowser. Ze zijn beschikbaar voor alle grote browsers op alle platformen. Al het verkeer van de webbrowser wordt gefilterd op verwijzingen naar de bekende advertentienetwerken. Ze werken prima maar bijvoorbeeld email in een mailprogramma met z'n tracking pixels en advertenties wordt niet gefilterd. Om maar niet te spreken over apparaten als smart-TV's etc.. Deze zoeken zonder aanwijsbare redenen regelmatig contact met de servers van de leverancier.

Door op een iets fundamenteler niveau dit probleem aan te pakken is er een oplossing nodig voor alles wat gebruik maakt van een internet verbinding. Door ieder verzoek van ieder apparaat achter de internet router te controleren tegen een lijst met bekende reclame (en malware!) sites is het mogelijk om verwijzingen naar deze ongewenste informatie op webpagina's maar ook onnodige verzoeken van zogenaamde smart apparaten uit het verkeer te filteren.

Bedrijven als AdGuard bieden DNS servers aan met deze filter mogelijkheid. Kijk [hier](https://adguard-dns.io/en/public-dns.html) voor een instructie om de router thuis zodanig in te stellen dat er (bijna) geen reclame doorkomt. Bijkomend voordeel is dat het laden van websites een stuk sneller gaat.

[image AdGuard-logo.png "AdGuard" left 200 200] Zo'n DNS server is een prima oplossing om zonder al te veel gedoe de meeste reclame buiten te houden. Beperking is dat jezelf geen invloed kunt uitoefenen wat er daadwerkelijk gefilterd en doorgelaten worden. Wil je dit wel dan kun je bij AdGuard een eigen DNS server in de cloud huren of je installeert zo'n filter op een kleine server thuis. Op de GitHub site [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) wordt verschillende opties voor thuis-installatie beschreven. Vervolgens kun je zelf de uitzonderingen op de standaardlijsten maken door sites op te nemen in de configuratie.

Een server met AdGuard home thuis draaien heeft nog een voordeel: er is voorzien in een basis monitoring zodat je kunt zien welke DNS verzoeken gedaan worden. Ervaring na een jaar gebruik van AdGuard Home leert dat er ongeveer 13% van de DNS verzoeken worden onderschept. Waarschijnlijk dat ook het totale internet verkeer met een dergelijk volume afneemt.

Mocht je wel een dergelijk service willen hebben maar om een of andere reden AdGuard niet zien zitten, het is immers een bedrijf op Cyprus met Russische roots, PiHole biedt een vergelijkbare aanpak.