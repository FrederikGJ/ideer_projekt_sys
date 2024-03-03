# Interview
Vi har foretaget et interview i virksomheden Dansk Brand- og Sikringsteknisk Institut (i daglig tale kaldet DBI). DBI er en ingeniørvirksomhed og privat forskningsinstitution, der arbejder med brand- og sikringsteknik i bygninger.

Vi har interviewet en medarbejder, der arbejder med at udvikle software og data science applikationer til virksomheden.

Interviewet er foretaget semistruktureret  hvor vi har stillet en række spørgsmål, som underviserne har udleveret på forhånd. Det semistrukturerede interview er valgt, da det giver mulighed for at stille uddybende spørgsmål undervejs, og dermed få en dybere forståelse for de emner, vi har spurgt ind til. Tonen igennem interviewet var uformelt og spørgsmålene blev ikke givet til respondenten på forhånd. Emnet var afsløret, så respondenten havde en idé om, hvad interviewet ville handle om.  


## Tech stack - listen er baseret på interviewet med DBI.

![Python](https://img.shields.io/badge/Python-%233776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%235F8FFF?style=flat-square&logo=streamlit&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres-336791?style=flat-square&logo=postgresql&logoColor=white)
![Microsoft SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)


## Tech stack og begrundelser for valg af disse  

Da DBI er ikke en it-virksomhed, er det primært ingeniører der arbejder der og ikke udviklere. Det minimale antal af it-faglige har påvirket fokuset på forbedring og udskiftning af deres tech stack. 

I deres nuværende tech stack bruges Python og Streamlit  til udvikling af data science apps, samt apps der kræver omfattende matematiske biblioteker. 
PostgreSQL eller Microsoft SQL bruges til relationel database.  
Til for eksempel  brandsikrings-applikationerne bruges C# .NET til backend og Blazor (C#) til frontend.
Der laves også simuleringer af brande, hvor Unity bliver brugt og store embedded programmer bliver skrevet i C. Til den overordnede versionsstyring bruges Microsoft og Azure bruges som cloud. 
Virksomheden har også nogle legacy webapplikationer. Her bruges JavaScript og HTML, og nogle af dem også .NET C# og angular til frontend. 

Den eneste betalte API der anvendes hos virksomehden er OpenAIs API, som bruges både til embedding af data samt træning af forretningsspecifik LLM.

Grunden til at de kører med den valgte tech stack er primært, at udgifterne  til udskiftning er for dyre. Den er i sin tid blevet valgt af elite udviklere og mange af programmerne er stadigvæk i brug.  Nye programmer fortsætter ofte i gamle programmer ved at lave refaktorering, da omkostninger for ændringer er for høje og programmerne er stadigvæk i brug. Det kan dog betale sig at holde disse programmer vedligeholdt og dette gøres nemmere ved at bruge det samme sprog.   

Ændringer i stacken sker sjældent. Det er ca. en gang hvert 5 år at det kommer til overvejelse, men uden sikkerhed at noget bliver ændret.  Hvis ændringer sker, er der ingen formel procedure for det, det vedtages ofte ved uformelle møder mellem udviklere og ledelsen. 
Hvis det bliver, er det oftest pga sikkerhed, kunstig intelligens og andre store teknologiske udviklinger.

## App arkitektur illustreret visuelt 
![c_sharp_stack](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113090989/8cc2c7c0-1bb0-4da8-83bd-2e318380cb48)
![py_stack](https://github.com/FrederikGJ/ideer_projekt_sys/assets/113090989/d262411d-fe8e-41fc-8fef-96aa17efb7e7)

## Udviklingsmetode 

Før et udviklingsprojekt sættes i gang laves der oftest en afdækning af domænet med object-oriented analysis (Larman, 2004, s. 7). Eksempler på objekter kan være de elementer der indgår i en bærende konstruktion. 

Som udviklingsmetode kører de LEAN startup, hvor de vigtigste komponenter er BML som er en forkortelse for build measure learn (Ries, 2011, kap 4), som indebærer hurtigt levering med mange iterationer, så de starter med et MVP (minimum viable product)  (Ries, 2011, kap 4). Det gør at udviklingsprocessen er effektiv og hurtig. Nogle enkelte studenterprojekter kører med SCRUM i stedet for. De har lagt ud med en “ren” metode og derefter tilpasset lidt på LEAN startupmetoden. De har f.eks. ansat en antropolog, som udvider processen med interviews, og UX delen udvider også processen. De ændrer ikke på deres udviklingsmetode, men tilpasser den i stedet, så den passer bedre. Hvis der nu skal skiftes ud i metoden alligevel eller der skal diskuteres nogle ændringer, så bliver det gjort via fælles møder i udviklingsteamet. Det bliver ikke dokumenteret, da udviklingsteamet er så småt og det er ikke det der er virksomhedens fokus. 

## Refleksioner 

Efter besøget er det blevet  tydeligt at det er de færreste virksomheder (der ikke primært er it-virksomheder) som har formelle procedure for ændringer eller tilføjelser til deres tech stack. Hvis vi skulle komme med reelle forbedringer, ville det være at indføre skrevne regler og retningslinjer for ændringer i tech stacken. Dette vil sikre fælles forståelse og håndtering af  både ny og gammel kode. 

Overordnet virker det dog til at DBI har godt overblik over deres programmer og de teknologier der bruges. De få udviklere DBI har arbejder  tæt sammen og vægter kommunikation højt, dog kan den altid forbedres.  I interviewet var der flere hentydninger til den mangel på struktur. Dog grundet størrelsen på teamet og antallet af udviklere, ville mere struktur muligvis kun sænke processen med udvikling af nye apps. 

### Referencer

Larman, C. (2004). Applying UML and Patterns: An Introduction to Object-Oriented Analysis and Design and Iterative Development. 3rd ed. Pearson.

Ries, E. (2011) The Lean Startup: How Today's Entrepreneurs Use Continuous Innovation to Create Radically Successful Businesses. Crown Business, New York.
