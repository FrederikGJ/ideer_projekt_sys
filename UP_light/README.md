# UP Light

Denne mappe indeholder dokumentation i form af billeder og tekst, samt et mock-up af backend koden til UP Light.

## Extreme Delivery

### UseCase
- System: Leverings service 
- Primære aktør: Bruger og Admin 

- En person opretter sig som bruger og tilføjer sin aktuelle lokation eller sin privatadresse. Herefter kan brugeren se alle stop på 'Extream Delivery's rute og vælge hvilket der er tættest på deres valgte lokation. Undervejs i processen kan brugeren følge med i varevognens kørsel, så de kan estimere den optimale ankomst. Ved ankomst på stoppestedet på det forudbestemte tidspunkt/dato* kan brugeren herefter købe sin ønskede vare fra varevognen. 

*forudbestemt tispunkt og dato er fastsat af firma og er altid det samme.

## Som ___ skal man kunne….; 

**Bruger**
- Oprette bruger ( adgangskode og password)
- Login som bruger (tjek DB) 
- _Købe vare (sker i person når du står ved bilen ergo ikke primære fokus da vare skal kunne skiftes ud uden at forstyrre systemet)_ 
- Tilføje privatadresse (vis med ikon)  

**Begge**
- Se inventar og priser 
- Se inventar og priser ( navn, pris, beskrivelse, type) 
- Se bilens lokation (vis med ikon) 
- Se alle stop (vis med ikon) 
- Se brugers privatadresse (vis med ikon) 
- Se afstand mellem stop og privatadresse (vis ikon og længde på afstand til analyse senere) 

**Admin** 
- Login som Admin (tjek DB) 
- Se alle, tilføje, slette og rediger vare 
- Se alle, tilføje, slette og rediger ruter
- Se alle biler 
- Se alle chauføre 
- Tilføj route til bil 
- Tilføj chauffør til bil!
  
**1 iteration KlasseDiagram**
![klassediagram1](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/e4bbdc9f-dfc9-4e88-819b-201464047878)
**1 iteration DomæneModel** 
![domainmodel1](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/f33b0766-4290-4a0e-a333-3c3b0e8b5e72)
**1 iteration UseCaseModel** 
![image](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/0ae8d3f8-fc97-4a73-ad38-b31051ca9984)

**2 iteration UseCaseModel**
![usecase2](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113087480/377037b0-a63a-4cf2-ad60-cb01771e1b96)

### Arkitektur 

![stack ](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113090989/7249d888-4df6-497c-941f-c10ed733e68e)
