# UP Light

Denne mappe indeholder dokumentation i form af billeder og tekst, samt et mock-up af backend koden til UP Light.

## Extreme Delivery

### UseCase
System: Leverings service 
Primære aktør: Bruger , Admin 

En person opretter sig som bruger og tilføjer sin aktuelle lokation eller sin privatadresse. Herefter kan brugeren se alle stop på 'Extream Delivery's rute og vælge hvilket der er tættest på deres valgte lokation. Undervejs i processen kan brugeren følge med i varevognens kørsel, så de kan estimere den optimale ankomst. Ved ankomst på stoppestedet på det forudbestemte tidspunkt/dato kan brugeren herefter købe sin ønskede vare fra varevognen. 

forudbestemt tispunkt og dato er fastsat af firma og er altid det samme. 


##Som ___ skal man kunne….; 

*Bruger
- Oprette bruger ( adgangskode og password)
- Login som bruger (tjek DB) 
- Købe vare (sker i person når du står ved bilen ergo ikke primære fokus da vare skal kunne skiftes ud uden at forstyrre systemet) 
- Tilføje privatadresse (vis med ikon)  

*Begge
- Se inventar og priser 
- Se inventar og priser ( navn, pris, beskrivelse, type) 
- Se bilens lokation (vis med ikon) 
- Se alle stop (vis med ikon) 
- Se brugers privatadresse (vis med ikon) 
- Se afstand mellem stop og privatadresse (vis ikon og længde på afstand til analyse senere) 

*Admin 
- Login som Admin (tjek DB) 
- Se alle, tilføje, slette og rediger vare 
- Se alle, tilføje, slette og rediger ruter
- Se alle biler 
- Se alle chauføre 
- Tilføj route til bil 
- Tilføj chauffør til bil![image](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/7140c4a5-6436-4f6e-baad-89c0d1853b1b)


### User Stories 
- Som bruger skal man kunne oprette bruger med adgangskode og brugernavn.
- Som bruger skal man kunne se bilens inventar og tilbud. 
- Som bruger skal man kunne opgradere sin medlems status  til presmium og modtag særtilbud. 
- Som bruger skal man kunne købe slik fra bilen når den stopper på bilens-stoppestedet. 
- Som bruger skal man kunne tilføje sin private adresse og se afstanden til bilens-stoppested. 
(data skal bruge til yderligere optimering af routeplanlægning, A-star) 
- Som bruger skal jeg kunne følge med i slikbilens lokation på kort.
- Som Admin skal man kunne redigere, tilføje og  slette vare.
- Som Admin skal man kunne redigere, tilføje og  slette stop.
- Som Admin skal man kunne se lokation.
- Som Admin skal man kunne se op tildele router til biler 
- Som Admin skal man kunne se og tildele chauffør til biler.  

*1 iteration KlasseDiagram 
![image](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/3baac35a-9043-492a-8b23-a2c56efd678d)

*1 iteration DomæneModel 
![image](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/c2ecad28-bb55-4fd8-bf6a-d512cb04d2cf)


*1 iteration UseCaseModel 
![image](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/0ae8d3f8-fc97-4a73-ad38-b31051ca9984)

### Arkitektur 

![stack ](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113090989/7249d888-4df6-497c-941f-c10ed733e68e)
