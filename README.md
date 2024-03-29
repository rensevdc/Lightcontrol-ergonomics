# Lightcontrol Ergonomie
*Functies in de wagen bedienen aan de hand van een swipe-paneel en kleurengebruik.* 

*Projectteam: Jarre Buyck; Rense Vandecasteele*

Datum: 24/01/2024

## Anthopometrie

**Doelstellingen**

De doelstelling van de Anthropometrie analyse is om het ergonomisch aspect ven het concept beter uit te werken en te optimaliseren. Uit deze analyse worden er opnieuw design requirements opgesteld en nieuwe iteraties gemaakt. 

**Materiaal & methoden**

Om deze analyse goed uit te voeren zijn er bepaalde materialen en methodes nodig. Er zullen nieuwe prototypes gemaakt worden die de ergonomie van de bediening beter zal kunnen bekijken. Waar in de vorige testen vooral de sensory en cognitive ergonomics bekeken werden zal er nu dieper ingegaan worden op de physical ergonomics. 

Belangrijke aspecten waar op gefocussed zal moeten worden zijn:
- Op welke plaats de bediencilinder zal moeten komen.
- Hoe de bediencilinder het beste bediendt wordt (grootte, beweging hand/vingers).
- Waar het swipepaneel zich moet bevinden.
- Hoe ver het swipepaneel zich moet bevinden.

De designmethode die zal worden gebuikt is: Design for adjustable (aangezien de zeten van de wagen per persoon kan ingesteld worden). De ergonomie zal in twee delen opgespitst worden. Eenerzijds zal de bediencilinder bekeken worden en anderzijds zal het swipepaneel bekeken worden. 

**Swipepaneel**

**Ergonomische aspecten**

Het eerste aspect dat bekeken wordt voor het swipepaneel is hoe ver het gemonteerd moet zijn t.o.v. de bestuurder. Zoals in onderstaande figuur te zien is, zou het swipepaneel best in een cirkel met een straal tussen de 394 en 508 mm komen te staan waarbij het middelpunt de rechterscouder van de bestuurder is en het eindpunte de hand van de bestuurder. (Zhanfeng, 2018)[^1] 
Een volgend ascpect is te bepalen hoe diep het paneel moet wegzitten in het dashboard. 
![image](https://github.com/rensevdc/Lightcontrol-ergonomics/assets/155004668/6eaba38c-1336-4648-9423-11f3994a7f10)

Ook hiervoor wordt er naar onderstaande figuur verwezen. De beste hoogte om het display te bedienen is op elbooghoogte. Dit komt meestal overeen met een hoogte tussen de 150 mm onder elbooghoogte en 250 mm boven elbooghoogte. De diepte van het dashboard (x-as) wordt kleiner naarmate het display hoger of lager komt te staan. Zo is op elbooghoogte deze nog maximaal 50cm ten opzichte van de borst. Indien de hand op 250 mm boven de elbooghoogte geposistioneerd is wordt de diepte maximaal 600 mm. En ten laatste wanneer de hand zich op 150mm onder de elbooghoogte bevind is de maximale diepte 400 mm van de borst af. (Blumstengel, 2019)[^2]

![image](https://github.com/rensevdc/Lightcontrol-ergonomics/assets/155004668/98b7f8ab-325a-456e-bf75-417ddaa0cffc)

Vervolgens kunnen er designrequirements opgesteld worden. Het swipepaneel tussen een afstand van 394 en 508 mm van de schouder van de bestuurder zitten en tussen een afstand van 250 mm boven of 150 mm onder de elbooghoogte. 

**Standaardderivaties en percentielen**

Via de DINBELG worden enkele maten bekeken voor de bevolking. 

Rijkdiepte: De gemiddelde rijkdiepte is 767 mm, voor 95,5% van de bevolking is de rijkdiepte in een zittende houding tussen de 667 en 867 mm. Hieruit blijkt dat 95,5% van de bevolking zeker aan de maximale opgestelde diepte van het swipepaneel geraakt. 

Schouderbreedte: De gemiddelde schouderbreedte is 438 mm, voor 95,5% van de bevolking geldt dat in een zittende houding de schouderbreedte tussen 374 en 502 mm ligt. Het swipepaneel ligt dus best op een minimale afstand van 251 mm van het midden van het stuur (502/2 mm) en een maximale afstand van 695 mm (374/2 + 508 mm) van het midden van het stuur af. 

Ellebooghoogte: De gemiddelde ellebooghoogte is 244 mm, voor 95,5% van de bevolking in een zittende houding ligt de ellebooghouding tussen 196 en 292 mm. Het swipepaneel moet dus op een hoogte van minimaal 46 mm (196 -150 mm) en maximaal 542 mm (292 +250 mm) staan t.o.v. het zitvlak. 



**Simulatie**

Vervolgens worden deze waarden in een Siemens NX simulatie geanalyseerd. Er worden verschillende situaties bekeken, het swipepaneel wordt telkens op een andere plaats gezet, de eerste manier is op een afstand van 250 mm van het stuur en op een maximale afstand van 508mm van de schouder van de bestuurder vandaan (cirkel rond shcouder), ook wordt het op schoduerhoogte gezet (100 mm boven ellebooghoogte). Zoals te zien is op onderstaande figuur is de rechter arm hoogte buiten de comfort zone, de schouderpositie zitten juist op de rand van comfortabel, dit blijft zo voor elke verschillende positie en heeft dus niks te maken met de positie van het swipepaneel. 

![image](https://github.com/rensevdc/Lightcontrol-ergonomics/assets/155004668/4404519c-4530-4c7d-b497-929f125680d1)

De volgende positie is indien het swipepaneel swipepaneel op een afstand van 394 mm ten opzichte van de schouder geplaatst wordt. De andere waarden veranderen niet, hieruit blijkt dat de arm elevation een nog slechtere comfortabilieteit heeft dan bij de vorige opstelling. De andere waarden blijven ongeveer gelijk.

Vervolgens wordt het scherm terug op de 508 mm geplaatst t.o.v. de schouder, deze keer staat het scherm op een hoogte van 250 mm boven de elleboog. Hierbij is de arm elevation nogmaals slechter dan voordien. Indien het scherm op een hoogte van 100 mm onder de elleboog geplaatst wordt is de arm elevation beter een pak beter. Hoe lager het swipepaneel staat hoe comfortabeler deze positie aanvaard wordt. Het zal moeten blijken uit gebruikerstesten welke positie de beste is bij een beweging van het stuur naar het swipepaneel heen. 

Om een swipebeweging te maken wordt het op elke positie als een comfortabele positie gezien. 

![image](https://github.com/rensevdc/Lightcontrol-ergonomics/assets/155004668/8e0a45ee-d865-4466-b5c2-8035d5d743ae)

Voor het swipepaneel geldt dus dat dit het best tussen een afstand van 251 mm en 695 mm van het midden van het stuur zit. Het zit op een diepte tussen twee cirkels met een straal van 394 mm en 508 mm bekeken vanaf de schouder (middelpunt). Op een hoogte tussen 46 mm en 542mm ten opzichte van het zitvlak bevestigd zit. In het volgende deel zullen de gebruikerstesten beschreven worden.

**Resultaten**

**Swipepaneel** 

Het testprotocol voor deze test staat in de bijlage. 

**Conclusies & implicaties**

## Kritische reflectie

## Bronnen

Blumstengel, B.S. (2019). Lunch & Learn Series: Office Ergonomics Done Right van [URL]([https://pdfs.semanticscholar.org/1b99/b3f87a1eef62f601bcd0519c6107bc6e018c.pdf](https://freshworks.io/office-ergonomics-done-right/))

Zhanfeng, Z.Z. (2018). Improvement and Innovation of Appearance Design of
Coffee Machine van [URL](https://pdfs.semanticscholar.org/1b99/b3f87a1eef62f601bcd0519c6107bc6e018c.pdf)


[^1]: Zhanfeng, Z.Z. (2018). Improvement and Innovation of Appearance Design of
Coffee Machine van [URL](https://pdfs.semanticscholar.org/1b99/b3f87a1eef62f601bcd0519c6107bc6e018c.pdf)

[^2]: Blumstengel, B.S. (2019). Lunch & Learn Series: Office Ergonomics Done Right van [URL]([https://pdfs.semanticscholar.org/1b99/b3f87a1eef62f601bcd0519c6107bc6e018c.pdf](https://freshworks.io/office-ergonomics-done-right/))

## Bijlagen


