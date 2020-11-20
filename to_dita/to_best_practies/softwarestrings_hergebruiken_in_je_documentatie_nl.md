---
authorinformation: null
---

# Softwarestrings hergebruiken in je documentatie

## Probleem / uitdaging

Stel, je hebt een softwareprogramma en je hebt documentatie erbij, zoals bijvoorbeeld een handleiding, onlinehulp of een API-referentiegids. Je wilt dan uiteraard dat de tekst uit de gebruikersinterface, zoals bijvoorbeeld uit de menucommando’s en dialoogvensters, consistent hergebruikt wordt in je documentatie en uiteraard ook in de vertalingen ervan.

Die consistentie is er misschien wel in de eerste versie van de documentatie, maar is dat ook nog zo in latere versies? Als die tekst uit de gebruikersinterface gewoon overgetypt is in de teksten van de documentatie, is het bij elke update van de software weer zoeken naar de stukjes tekst in de documentatie die overeenkomstig aangepast moeten worden. En dan is nog eens dezelfde oefening nodig in de vertalingen.

## Oplossing

Maar het kan ook anders. Je zou ook de teksten uit je softwareprogramma, de “softwarestrings”, met een dynamische link kunnen hergebruiken in je documentatie. Dit werkt als volgt:

![](../../.gitbook/assets/software_strings_process.svg)

1. Je export de teksten uit je software naar een bestand in een gestructureerd formaat, bijvoorbeeld XML, CSV of JSON. Of misschien heb je die teksten al in zo’n formaat beschikbaar?
2. We transformeren dit bestand naar een DITA-bestand, zodat de softwarestrings herbruikbare componenten \(“reusable components”\) worden.
3. De schrijvers typen de softwarestrings niet meer in de documentatie, maar slepen ze uit het bestand met herbruikbare componenten in de content. Hierdoor wordt automatisch een dynamische link gecreëerd.
4. Bij een update van de software voeren we enkel nog stappen 1 en 2 uit: de tekst uit de gebruikersinterface opnieuw exporteren en het softwarestringsbestand opnieuw transformeren. De softwarestrings in de documentatie zijn meteen up-to-date, aangezien ze met een link hergebruikt zijn.
5. En uiteraard werkt stap 4 ook voor de updates van de vertalingen: tekst uit de vertaalde gebruikersinterface opnieuw exporteren, transformeren en je bent klaar!

Handig niet?

## Meer weten?

Contacteer ons via [info@flowtime.be](mailto://info@flowtime.be)

