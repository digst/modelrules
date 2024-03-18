# Kapitel 1: Introduktion

## Formål
Det overordnede formål med begrebs- og datamodellering er at skabe et fælles sprog med klarhed og konsensus om betydningen af begreber og de betegnelser, vi bruger om de enkelte begreber, og opnå sammenhæng mellem hvordan begreber anvendes af forretningen og til at beskrive data. Ved at data er velbeskrevne og i overensstemmelse med forretningen dannes grundlag for effektiv udvikling af it-systemer, der understøtter forretningen. Datamodeller dokumenterer desuden den information, der håndteres i forretningen.

Vi har nok alle oplevet situationer, hvor der er opstået forvirring, fordi vi har brugt en betegnelse, der var ukendt for andre, eller endnu værre har brugt en betegnelse, som modtagerne forstod på en anden måde, end vi mente. Det kan blive værre endnu, når man krydser mellem forskellige faglige domæner eller forskellige organisationer. Men selv inden for ét fagdomæne og inden for én organisation kan sprogbrug være forskelligt.

Når man modellerer begreber og data inden for et fagdomæne, kastes der lys over uenigheder, og man skaber grundlaget for en fælles forståelse. Man tilvejebringer et faglig velfunderet begrebsapparat, der er sammenhængende med den faglige praksis på området. Forretningen kan tage et større ejerskab over begreber og dermed over forståelsen af data, så fx it-udviklingen bliver mere forretningsdrevet. En god velbeskrevet datamodel, der er i overensstemmelse med forretningens behov og begrebsanvendelse, er et væsentligt skridt i forhold til at skabe it-understøttelse, der smidigt understøtter forretningsgange og er nemt at anvende.

Samtidig dokumenteres vigtig og måske tavs viden, så den er egnet til deling og videre anvendelse. Det er viden, der kan anvendes i forbindelse med udarbejdelse af lovgivning, regler, strategier mm, og dermed bidrage til at disse bliver fagligt funderede og digitaliseringsklare. Det øgede fokus på databeskyttelse (GDPR) taler også for klarhed over begreber og data.

Entydige begreber og datamodellering kan anvendes til udarbejdelse af krav til it-understøttelse, der reducerer risikoen for bekostelige misforståelser og fejl i løbet af udviklingsprocessen. Ved projekter af tværgående karakter er det særligt vigtigt at indtænke begrebsafklaring for at sikre, at der er enighed mellem de forskellige projektdeltagere ift. hvad projektet indeholder og hvordan leverancerne skal udarbejdes. Det er også et vigtigt element i forhold til at sikre interoperabilitet på tværs af systemer og sektorer.

Modellering er et solidt grundlag for klar kommunikation med borgere, erhvervsdrivende, leverandører, sagsbehandlere og andre, der er involverede i sager med berøring til domænet. Arbejdet med afklaring af robuste, meningsfyldte begreber er en god forberedelse til udvikling og implementering af de brugerrettede dele af et it-system. En fælles forståelse af data hos alle, der føder data ind i systemet og alle, der anvender data, er et vigtigt skridt i forhold til sikring af datakvalitet. Den fælles forståelse af data illustreres af Figur 1, hvor de to personer tænker på et køretøj og er enige om, at det er en personbil.

![Fælles forståelse for et begreb](Illustrations/kap1-samme-begreb-samme-forståelse.svg)

_Figur 1.1: Samme begreb - samme forståelse_

## Hvorfor anvende de fællesoffentlige regler for begrebs- og datamodellering?
Modelreglerne er en metoderamme, der udstikker fælles retningslinjer for udformning, deling og genbrug af begrebs- og datamodeller i fællesoffentligt regi og bidrager til bedre data, bedre forståelse af data, og øget deling og genbrug af data.

Reglerne er en samling af anerkendte og internationalt forankrede metoder til god begrebs- og datamodellering som understøtter:

* God modellering med forankring i forretningen
* Sammenhæng mellem lovgivning og it-system
* Fælles sprog, kompetenceudvikling og værktøjer på tværs af den offentlige sektor
* Forberedelse til nye, endnu ukendte anvendelser af data
  
Den allervigtigste grund til at anvende en fælles metoderamme er, at man dermed kan sikre interoperabilitet/sammenhæng på tværs af myndigheder og fagdomæner både på forretningsmæssigt plan og mellem forskellige it-systemer. 

Det er afgørende for udviklingen af den digitalt sammenhængende og effektive offentlige sektor, at data kan genbruges, og at digitale processer bygger på sammenhængende begreber og data. Udviklingen understøttes af det fællesoffentlige arkitekturarbejde, og initiativerne under Udvalg for arkitektur og standarder. Der er behov for interoperabilitet på flere niveauer: Juridisk, organisatorisk, semantisk og teknisk. Som Figur 2 viser, adresserer De fællesoffentlige modelregler semantisk interoperabilitet, og koblingerne mellem det semantiske niveau og henholdsvis det juridiske og tekniske niveau og sikrer sammenhæng fra forretning til udvikling.

 ![Sammenhæng](Illustrations/kap1-sammenhæng.svg)
 
_Figur 1.2: Sammenhæng_

Ensartethed, og dermed fælles forståelse, i beskrivelse af begreber og data er en forudsætning for at genbruge både modellering og faktiske data fra eksterne kilder.

Genbrug er med til at minimere det samlede ressource- og tidsforbrug på udvikling og vedligeholdelse af it-løsninger ved at undgå dobbeltarbejde. Desuden sikres høj kvalitet ved genbrug af modelelementer, der er defineret af domæneeksperter.

## Organisatoriske anbefalinger for modellering
For at opnå god begrebs- og datamodellering er det nødvendigt at forankre ansvar, opgaver, kompetencer og ressourcer i organisationen.

Hvis man som organisation ønsker at arbejde med begreber og datamodeller på en ensartet og struktureret måde, anbefales følgende tiltag som en del af den Fællesoffentlige digitale arkitektur (FDA):

1. Betragt begrebs- og datamodeller som forretningskritiske aktiver
2. Placér organisatorisk ansvar for begreber og datamodeller
3. Fastlæg processer, metoder og værktøjer til begrebs- og datamodellering
4. Sikr tilstrækkelige kompetencer og ressourcer til modellering
5. Vedligehold et overblik over organisationens begreber og datamodeller
   
Du kan downloade en [folder med yderligere information](https://arkitektur.digst.dk/sites/default/fileuploads/folder_god-begrebs-og-datamodellering-i-det-offentlige.docx) om disse fem anbefalinger.


# Kapitel 2: Modeltyper og proces

## Hvad er en model?
En model er en repræsentation af virkeligheden, der er egnet til at formidle viden om aspekter af virkeligheden til et bestemt formål. En model er typisk opbygget af elementer, der hver især repræsenterer ‘noget’ i virkeligheden. Modellen beskriver de egenskaber ved elementerne, der er relevante i forhold til modellens formål samt hvordan de relaterer sig til hinanden. Formelt defineres en model i kontekst af modelreglerne som et _“objekt der repræsenterer en entitet ved at besidde en ægte delmængde af dens egenskaber”_.

Der kan være forskellige tilgange til modelleringsarbejdet alt efter om det indgår i arbejdet med lovgivning, afklaring af behov og ønsker eller begrebs- og datamodellering til kørende it-systemer. Modellerne har forskelligt indhold i forhold til den sammenhæng, de indgår i.

De forskellige modeller påvirkes både af arbejdet med andre modeltyper, samt af arbejdet med fx processer, use cases og aktivitetsbeskrivelse, og der kan desuden komme tilbageløb fra videre arbejde med fx kravspecifikation og behovsopgørelse. 

Dette kapitel fortæller om de forskellige modeltyper og den overordnede proces for modeludarbejdelse. Læs mere om hvordan man i praksis udarbejder modellerne i Kapitel 5: Udarbejdelse af modeller.

## Modeltyper  
Sprogbrugen om modeltyper og deres anvendelse er forskelligartet og flertydig. I det følgende opridses den forståelse og navngivning, som tilstræbes i denne vejledning. Herefter fortæller vi lidt om arbejdet med de forskellige modeltyper.

**Terminologiske begrebsmodeller** beskriver begreber og deres indbyrdes relationer. En terminologisk begrebsmodel kan udformes som en begrebsliste eller et begrebsdiagram - eller begge dele. Terminologiske begrebsmodeller kaldes i daglig tale ofte blot begrebsmodeller. Der findes også andre modeltyper der kan blive kaldt begrebsmodeller, og ‘terminologisk begrebsmodel’ er det derfor en mere præcis term. ‘Begrebsmodel’ kan dog betragtes som en accepteret alternativ term, og den bruges i vid udstrækning i dette dokument, altid for at referere til terminologiske begrebsmodeller.

* **Begrebslister** er repræsentationer af begrebsmodeller udtrykt på listeform. 
Repræsenteres begrebsmodellen som en begrebsliste, udtrykkes den i tabelformat eller efter ISO 10241 Termposter i standarder.

![Eksempel på begrebsliste i tabelformat](Illustrations/kap2-eksempel-på-begrebsliste-i-tabelformat.svg)

_Figur 1.3: Eksempel på begrebsliste i tabelformat_

* **Begrebsdiagrammer** er repræsentationer af begrebsmodeller udtrykt visuelt som diagram. 
Der er forskellige måder at udarbejde begrebsdiagrammer. Det er ikke et krav at der udarbejdes et diagram som del af modellen. Dog betyder den systematiske og strukturerede tilgang til arbejdet med begrebsdiagrammer, at inkonsistens, eventuelle uenigheder og manglende begreber i dækning af et emneområde lettere afsløres. I denne vejledning gennemgås én metode, nemlig anvendelse af klasse- og objektdiagrammer lavet i UML (Unified Modelling Language), hvor kasser og pile fortæller om begrebernes indbyrdes sammenhæng. Diagrammer udarbejdet efter denne metode kan gøres til genstand for review i FDA-regi.

![Eksempel på begrebsdiagram](Illustrations/kap2-eksempel-på-begrebsliste-diagram.svg)

_Figur 1.4: Eksempel på begrebsdiagram_

**Informationsmodeller** er modeller som beskriver forretningsviden og som supplerer begreber med forretningsregler. De dokumenterer den information, der håndteres i forretningen, og beskriver den tilstrækkeligt til, at den kan anvendes i nye sammenhænge. Der er taget stilling til om et givent begreb skal repræsenteres som klasse, attribut eller andet, og der er angivet multipliciteter. Dermed ligner diagrammer i informationsmodeller mere datamodeldiagrammer end begrebsdiagrammer, men det semantiske indhold i en informationsmodel er begreber, og derfor kan der også udtrækkes en begrebsliste..

![Eksempel på informationsmodel](Illustrations/kap2-eksempel-på-informationsmodel.svg)

_Figur 1.5: Eksempel på informationsmodel_

**Logiske datamodeller** beskriver dataelementers logiske sammenhænge. De logiske datamodeller udarbejdes som grundlag for dataudveksling eller lagring af data, fx i en teknologisk understøttelse af den løsning de modellerer, dog således at det er de logiske sammenhænge i data og ikke den fysiske struktur der modelleres. Logiske datamodeller kan være fuldstændigt uafhængige af implementeringsmetode, men kan også indeholde konstruktioner der vender sig mod et overordnet realiseringsparadigme, fx relationelle databaser, xml eller graf. Den samme logiske model kan beskrive flere forskellige fysiske implementering med variationer i den fysiske model.

![Eksempel på logisk datamodel](Illustrations/kap2-eksempel-på-logisk-datamodel.svg)

_Figur 1.6: Eksempel på logisk datamodel_

Diagrammer der udarbejdes i forbindelse med informationsmodeller kommer som det ses til at ligne diagrammer udarbejdet i forbindelse med logiske datamodeller, da begge består af klasser, attributter og, hvor relevant, enumerationer. Der er dog et par forskelle idet en logisk datamodel angiver datatyper og navngiver associationsender fremfor associationer. Den største forskel ligger dog i hvad der modelleres. 
Informationsmodeller modellerer virkeligheden som den ser ud fra et specifikt forretningsperspektiv, og derfor er instanser af en klasse i en informationsmodel stadig fænomener i ‘den virkelige verden’ jfr. den blå bil til venstre i Figur 7. Logiske datamodeller modellerer derimod data, (som er en repræsentation af virkeligheden, men ikke selve virkeligheden), og instanser af en klasse i en logisk datamodel er derfor datainstanser jfr. tabellen til højre i Figur 7.

![Virkelighed vs. data om virkeligheden](Illustrations/kap2-cirkelighed-vs-data-om-virkeligheden.svg)

_Figur 1.7: Virkeligheden vs. data om virkeligheden_

### Arbejdet med terminologiske begrebsmodeller
En terminologisk begrebsmodel kan repræsenteres på listeform eller som et diagram, hvor begrebernes indbyrdes relationer også tydeliggøres.

Begrebsmodellering er en proces, hvor domænekyndige bliver enige om betydningen af begreber og beskriver det i en definition. Når begrebsarbejdet dokumenteres i en model opnås genbrugelighed, fordi det er tydeligt, hvad der menes med de forskellige begreber. Begrebsmodeller udviklet efter den samme metode kan sammenlignes, udbygges og sættes sammen efter behov.

Arbejdet med begrebsmodeller bør inddrage af centrale fagpersoner for det emne/domæne der modelleres, grundig research og gennemgang af kildemateriale, hvorved relevante begreber i det pågældende emneområde identificeres. Eksisterer der allerede en begrebsmodel for emnet, tages der udgangspunkt i denne, idet de samme begreber ikke skal beskrives igen. Der kan også tages afsæt i eksisterende datamodeller eller kørende digitale løsninger, hvor relevante begreber identificeres, beskrives og modelleres.

I det omfang det er muligt, bør begrebernes relation til gældende lovgrundlag, relevante standarder eller øvrige rammer undersøges. Det er vigtigt, at organisationen prioriterer at domæneeksperter med viden om forretningens lovgivning og formål deltager i begrebsafklaringen, da det netop er af hensyn til forretningen, at modellen og begreberne skal dokumenteres og forankres.

#### Anvendelse af begrebsmodeller
Formålet med begrebsmodellering er som skrevet i indledningen at skabe afklaring og enighed om betydningen af begreber, brugen af termer og begrebernes indbyrdes relationer, og den vigtige viden som domænekyndige bidrager med i processen dokumenteres og fastholdes på en ensartet måde. Det kan være relevant at udarbejde begrebsmodeller i mange forskellige sammenhænge, fx til at:

* skabe fælles sprogbrug i forretningen, så misforståelser undgås
* skabe grundlag for effektiv kommunikation mellem forretning og it ifm. it-udvikling
* skabe grundlag for effektiv kommunikation med brugere  
* bidrage til god datakvalitet via faglig klarhed i it-systemer
* understøtte sporbarhed fra data til de forretningsmæssige begreber
* bidrage til digitaliseringsklar lovgivning 
* understøtte nytænkning af fagområder
* bidrage til introduktion til fagområder ifm. oplæring af nye medarbejdere
   
Kort sagt er begrebsmodeller et middel til at dokumentere viden, skabe interoperabilitet og undgå misforståelser og fejl ved at skabe fælles forståelse. It-løsninger udarbejdet på baggrund af robust begrebsmodellering har et stærkt fundament for fagligt korrekte og relevante data uden gentagelser og støj.

#### Begrebsmodellens indhold og afgrænsning 
Det er vigtigt at undersøge det umiddelbare formål og den direkte anvendelse af begrebsarbejdet, da dette har stor indflydelse på omfanget af begrebsmodellen. Ved en anvendelsesorienteret model, fx til forberedelse af et specifikt it-system eller udvikling af en indberetningsformular, vil det være forretningsbehovene i forbindelse med anvendelsen, der dikterer modellens omfang og indhold. Men også ved emneorienteret modellering er det vigtigt at holde sig formålet for øje. Og hvor et formål som ‘at dokumentere vores faglige viden’ er yderst prisværdigt, så er det også en stor mundfuld, og det kan anbefales at starte med at prioritere et mere specifikt formål, fx ‘at dokumentere de begreber hvor vi har unik viden’, ‘at understøtte dette specifikke samarbejde med ekstern part’ eller ‘at hjælpe de projektledere, jurister mm., vi samarbejder med, til at forstå os’.

En model, der indeholder netop ét emneområdes begreber, er kendetegnet ved at være en samling af begreber, som naturligt hører sammen. Det vil sige, at der er høj begrebsmæssig samhørighed inden for modellen. Emneafgrænsning kan være svært og der er ingen endegyldige svar på hvordan det gøres. En af de komplicerende faktorer er, at afgørelsen af om noget er et eller flere emneområder, kan afhænge af detaljeringsniveauet. 

Man kan fx forestille sig en begrebsmodel på overordnet niveau om emnet transportmidler, hvor begreber der er relevante for transportmidler generelt, fx ‘fører’, ‘passager’, ‘ejer’, ‘førertilladelse’, ‘registrering’, og nogle typer, fx ‘bil’ og nogle af dets centrale undertyper såsom ‘personbil’, ‘lastbil’ og ‘varevogn’ er begreber. Man kan også forestille sig en begrebsmodel over emnet bil, hvor de forskellige undertyper udfoldes og man modellerer begreber, der er relateret til ‘bil’, såsom ‘kørekort’, ‘fremstillingsår, ‘mærke’, ‘model’, ‘parkeringsplads’, ‘nummerplade’, ‘benzin’, ‘syn’ med flere. Eller man kan lave begrebsmodeller der beskriver processen for syn, udstedelse af nummerplader, styringsmekanismers funktion etc., som alle kan være helt rimelige bud på emner afhængigt af modellens formål. 

Det er også vigtigt at pointere at man ikke er forpligtet til at modellere alt, der potentielt kan falde inden for det emneområde man modellerer. Man kan fx sagtens modellere emnet bil fra et lovgivningsperspektiv og kun medtage undertyper og bestanddele i det omfang, det er relevant for (et bestemt stykke) lovgivning. Eller man kan modellere bestanddele uden at gå i detaljer om, hvilke bestanddele en kobling, en gearkasse eller en lygte indeholder. Modellens navn og beskrivelse bør reflektere det perspektiv eller den afgrænsning, man modellerer ud fra.

Det er altså i høj grad pragmatiske vurderinger i forhold til formålet med modelleringsarbejdet der afgør hvad afgrænsningen skal være. Begrebsmodellen vil senere kunne udvides eller relateres med emnemæssigt nærliggende modeller når nye behov opstår, og et væsentligt formål med de fælles modelleringsregler er netop at smidiggøre processen med at udvide/tilføje og skabe relationer.

Som sagt er der ingen faste regler for emneafgrænsning, men et par tommelfingerregler kan dog nævnes:
* Hvis dine begreber fordeler sig i to grupper med mange relationer inden for hver gruppe og ganske få mellem grupperne burde det muligvis være to modeller 

* Hvis din model har mange elementer fra andre emneorienterede modeller sammen med en mængde du selv definerer, er det muligt du er i gang med at lave en blanding af en anvendelsesmodel og en emneorienteret model (se også afsnit om [modelomfang](husk link)).

Hvis der foretages begrebsarbejde med henblik på videre datamodellering, kan det være fordelagtigt at fokusere på de helt centrale begreber samt evt. særlige grupper af begreber hvor der savnes præcision og afklaring i forvaltningen og kommunikationen. Derudover kan det være en god idé, såfremt der er mulighed for det, at lade begrebsarbejdet og datamodelleringsarbejdet forløbe i sideløbende processer, så det er muligt for begrebsmodellører og datamodellører at sparre og tilrette modellerne undervejs.

For at afdække hvilke begreber det er relevant at medtage i begrebsmodellen og hvilke betegnelser der tidligere er blevet brugt for dem, kan man fx konsultere tidligere udarbejdede rapporter, vejledninger - både til fagfolk og borgere, blanketter samt skærmbilleder, dokumentation og dataudtræk fra tidligere systemer. 

#### Proces for begrebsmodellering
Et forløb for begrebsmodellering kunne se således ud:

![Proces for begrebsmodellering](Illustrations/proces-for-begrebsmodellering.svg)

Figur 1.8: Proces for begrebsmodellering

<ol>
<li> Etablering af arbejdsgruppe </li>
  <ol>
  <li> Arbejdsgruppen bør bestå af både modelleringskyndige og domæneeksperter, der er fagkyndige inden for emneområdet </li>

  <li> Identifikation af relevant forum for forretningsgodkendelse af begrebsmodellen </li>
  </ol>
<li> Valg af en eller flere af følgende arbejdsmetoder: (SDFE 2001): </li>
  <ol>
  <li> afholdelse af workshops, hvor deltagere med relevant viden sættes sammen for at udarbejde modellen i en iterativ proces </li>
  <li> interviews med nøglepersoner, hvor der via en struktureret spørgeramme hentes viden om de faglige aspekter, som interviewpersonen har speciel viden om, og som efterfølgende indarbejdes i modellen </li>
  <li> modelleringskyndige modellerer begreberne ved hjælp af den erfaring og viden der er indsamlet fra domæneeksperterne. </li>
  <li> analyse af kildemateriale hvor relevant fagligt materiale indsamles og analyseres, for at udlede viden, der skal indarbejdes i begrebsmodellen. Denne metode er som regel et nødvendigt supplement til de øvrige metoder </li>
    </ol>
<li> Strukturering af viden </li>
  <ol>
  <li> Udvælgelse og prioritering af relevante termer </li>
  <li> Udarbejdelse af forslag til definitioner, hvis muligt med afsæt i autoritative kilder som lovgivning og standarder (se afsnit om begrebslister og evt. begrebsdiagrammer) </li>
  <li> Angivelse af kommentarer, eksempler mv. </li>
  <li> Etablering af sammenhæng til og mulig genbrug af andre relevante modeller </li>
    </ol>
<li> Review og behandling af reviewkommentarer, jf. Kapitel 5: Review, godkendelse og udstilling </li>
<li> Forretningsgodkendelse, jf. Kapitel 5: Review, godkendelse og udstilling </li>
</ol>

Begrebsdiagrammet kan gøre det nemmere at udarbejde hensigtsmæssige definitioner, idet en god definition bygger på en analyse af det pågældende begrebs placering og relation til andre begreber i begrebsdiagrammet. Erfaring har også vist at der bruges færre ressourcer, hvis man i fællesskab på en workshop drøfter nøglebegreber og tegner de helt overordnede begrebsdiagrammer for emneområdet inden definitionsarbejdet sættes i gang. Derfor kan det være en god ide at udarbejde uformelle diagrammer som en del af Fase 3, selv om man ikke planlægger at publicere formelle diagrammer. Ved modellering af begreber, der repræsenterer fysiske objekter, kan det alternativt eller i tillæg være nyttigt at anvende tegninger af det, man modellerer.

### Informationsmodeller
Informationsmodeller udarbejdes med henblik på analyse og forretningsafklaring. De kan danne det forretningsmæssige grundlag for videre logisk datamodellering. Informationsmodeller er uafhængige af et fremtidigt valg af teknologisk understøttelse af den løsning, de modellerer. Herunder afspejler de heller ikke et specifikt paradigme for implementering, såsom relationel database, noSQL eller triple store. 

I en informationsmodel sættes begreber ind i en afgrænset kontekst og beriges med forretningslogik. I modsætning til begreber kan forretningslogik ændre sig over tid, omend den typisk er stabil over lange perioder. Fx kunne en dansk statsborger indtil 2015 kun have ét statsborgerskab, hvilket kan udtrykkes med multipliciteten 1..1. Nu kan man have to, altså have multipliciteten 1..2. I en anden forretningskontekst kan man have brug for også at repræsentere statsløse i modellen, og derfor angive multipliciteten 0..2. I alle tilfælde er begrebet statsborgerskab det samme, det er blot blevet beriget med informationer om hvordan det anvendes i en forretningsmæssig kontekst.

Ligeledes tager man i forbindelse med udarbejdelsen af en informationsmodel stilling til hvilken informationsstruktur begrebet repræsenteres af i den givne kontekst. Hvis man udarbejder en informationsmodel for at holde styr på organisationens køretøjer (placering, eftersyn, fejlmeldinger m.m.) vil man lade begrebet ‘bil’ repræsentere af en klasse, hvorimod ‘bil’ i en informationsmodel for rejseafregning måske ville være repræsenteret af en værdi i en enumeration. Begrebet ‘bil’ er det samme i begge tilfælde.

Informationsmodeller kan understøtte it-projekters behovsafklaring i forretningsanalysen, fordi modelleringen giver forståelse for og ejerskab til den forretning, der arbejdes med. Desuden er det vigtigt, at de samme metoder anvendes på tværs af forskellige projekter, så det gør det muligt at skabe sammenhæng mellem de forretningsområder, projekterne dækker. 

Et enkelt projekt kan have brug for flere sammenhængende modeller, der komplementerer hinanden, fx for at dokumentere de informationer, man anvender i sine processer, beslutninger, use cases eller services. I forbindelse med udbud kan denne øvelse bruges til at lette arbejdet med at kvalitetssikre kravspecifikationer. Ved at anvende informationsmodeller i kravspecifikationer samt modellere sammenhængen imellem disse, bliver inkonsistens, uklarheder og mangler synliggjort.

#### Proces for informationsmodellering
Informationsmodeller udarbejdes som UML-klassediagrammer.

Ofte vil en informationsmodel blive udarbejdet på baggrund af en begrebsmodel. I så fald består det primære modelleringsarbejde i at tage stilling til hvilken struktur de forskellige begreber skal repræsenteres med, samt at tilføje multipliciteter. Dette arbejde udføres primært af informationsmodellører, men det bør kvalitetssikres af forretningskyndige indenfor modellens emneområde.

Dernæst identificeres tidligere udarbejdede informationsmodeller (nogle gange kaldet byggeblokke), der indeholder relevante begreber, som kan indlånes, og dermed skabe sammenhæng til andre modeller.

Det er også tænkeligt at man identificerer enkelte nye begreber der er relevante for modellen. Hvis samme personkreds som udarbejder informationsmodellen har ansvar for begrebsmodellen kan man evt. tilføje sådanne begreber her. Ellers kan nye begreber defineres i en ny informationsmodel. I begge tilfælde bør forretningskyndige inddrages i termvalg og udarbejdelse af definition.

I tilfælde hvor der ikke er en begrebsmodel som udgangspunkt, må man starte med det begrebsafklarende og -definerende arbejde som beskrevet i kapitel 3. 

### Logiske datamodeller
Hvor begrebs- og informationsmodeller beskriver virkeligeheden, beskriver datamodeller data om virkeligheden. Logiske datamodeller er datamodeller som beskriver datas logiske sammenhænge uafhængigt af hvilken specifik fysisk struktur og teknisk implementering der anvendes til opbevaring af data. Formålet med logiske datamodeller er at give en forståelse af data, der er gyldig for alle de fysiske formater, data måtte findes i.

En god logisk datamodel kræver forståelse af den forretning og de processer, hvor data skabes og/eller anvendes. Det er derfor vigtigt, at domæneeksperter med indgående viden om forretningen deltager i modelleringsarbejdet, ligesom der bør deltage data- eller informationsarkitekter med viden om logisk datamodellering.

#### Anvendelse af logisk datamodellering:

Logiske datamodeller er velegnede til kommunikation om data, fx mellem en datadistributør og en potentiel anvender. Den logiske datamodel dokumenterer hvilke data distributøren har og hvad de betyder, men dokumenterer ikke hvordan data fysisk opbevares eller leveres, og dataleverancer kan således ske på flere måder og evt. tilpasses anvenders behov, efter at den logiske datamodel har givet anvenderen mulighed for at vurdere hvilke data der er relevante.

Logiske datamodeller danner desuden det semantiske grundlag for fysiske modeller, fx implementering i databaser eller til udvekslingsformater og bidrager dermed til at forretningens forståelse af data og de bagvedliggende begreber afspejles i de data der i praksis gemmes og udveksles.

#### Proces for logisk datamodellering
Hvis der eksisterer en veldokumenteret begrebsmodel, er det oplagt, at den logiske datamodel tager udgangspunkt i den. Hvis ikke kan det give mening at udarbejde en begrebsmodel sideløbende med udarbejdelsen af den logiske model, da det tunge arbejde med vidensindsamling, begrebsafklaring, udarbejdelse af definitioner mv. alligevel skal udføres. Processen for datamodellering varierer alt efter om der er en begrebsmodel, eller om man starter uden forudgående begrebsmodellering. Nedenfor beskrives først processen, hvor der er en begrebsmodel og derefter processen uden.

#### Processen med udgangspunkt i begrebsmodellering
Hvis der er blevet udarbejdet en eller flere begrebs- eller informationsmodeller der helt eller delvist dækker det samme emne, skal den logiske datamodel baseres på disse modeller og sammenhængen skal dokumenteres. Begrebsmodellering, informationsmodellering og logisk datamodellering er tæt forbundet, og der vil typisk være behov for at justere de forskellige modeller undervejs i modelleringsforløbet.

Når der er udarbejdet en begrebsmodel bliver arbejdet med den logiske modellering væsentligt nemmere, idet der allerede er foretaget indsamling af viden og forståelsesmæssig afklaring, samt udarbejdet definitioner og andre metadata som elementerne i den logiske datamodel kan arve. Der skal tages stilling til hvilke begreber der er relevante i den specifikke kontekst den logiske datamodel skal beskrive, og hvilken rolle det enkelte begreb har i den logiske datamodel - om det repræsenteres vha. en klasse, et attribut eller noget tredje - og hvilke associationer mv. der udtrykker datas logiske struktur. 

Afhængigt af detaljeringsniveau og scope af den eksisterende begrebsmodellering kan det desuden være nødvendigt at modellere elementer, ikke mindst attributter og associationsender, der ikke er baseret på et begreb fra en begrebsmodel. I så fald må man som del af den logiske modellering udarbejde definitioner og angive termer og anden metadata. 

Det er vigtigt, at der i denne proces inddrages både forretningsviden og datamodelleringskompentencer, så det sikres at de logiske strukturer er forankret i forretningsviden og at de samtidig er et fornuftigt udgangspunkt for den faktiske implementering.

Der skal etableres sammenhæng mellem den logiske datamodel og den begrebsmodel eller informationsmodel den er baseret på. Det gør man ved at angive hvilket begreb modelelementerne er afledt af. Dette gøres ved at angive begrebets HTTP-URI i tagget ‘wasDerivedFrom’. Desuden skal namespace for begrebsmodellen fremgå i den logiske datamodels metadata - ligeledes i tagget ‘wasDerivedFrom’. Se mere i [Kapitel 6; Dokumentation af modellen](husk link).

§14 - <span style="color:#AB2A0C;">Etablér sammenhæng mellem begrebsmodeller og logiske modeller</span>

##### Processen uden forudgående begrebsmodellering
Ligesom ved begrebsmodellering skal der foretages afklaring af de anvendte begreber og de termer der bruges til at beskrive dem, og der skal udarbejdes definitioner og angives metadata for hvert modelelement. Man kommer derved til at foretage en implicit modellering af begreber, når man udarbejder en logisk datamodel. Information om hvordan man udarbejder gode definitioner og angiver metadata findes i [Kapitel 3: Termer og definitioner](husk link) og [Kapitel 5: Udarbejdelse af modeller](Husk link). I dette kapitel gennemgås kun det, der gælder særligt for logisk datamodellering.

##### Organisering af arbejdet
Arbejdet med at identificere, indsamle og strukturere den viden, der skal indarbejdes i den logiske model, kan foregå på flere måder. Forskellige medarbejdere involveres med hver deres rolle i projektet. Hvilke roller de kommer til at spille i projektet, afhænger blandt andet af, hvilke forudsætninger de kommer ind i projektet med. 
Her følger en kort beskrivelse af de trin, modelløren typisk gennemgår:

![Proces for logisk datamodellering](Illustrations/kap2-proces-for-logisk-datamodellering.svg)

_Fig 1.9: Proces for logisk datamodellering_

<ol>
<li> Klasser tilføjes </li>
<ol>  
<li> Eksisterende klasser genbruges </li>
<li> Nye klasser defineres efter behov </li>
  </ol>
<li> Egenskaber tilføjes </li>
  <ol>
<li> Objektegenskaber tilføjes som associationsender </li>
<li> Datatypeegenskaber tilføjes som attributter </li>
  </ol>
<li> Klassifikationer tilføjes som </li>
  <ol>
<li> Klassifikationsklasser med klassifikationselementer som objekter el. </li>
<li> Klassifikationsklasser med henvisning til eksternt definerede klassifikationer el. </li>
<li> Enumerationer med klassifikationselementer som værdier </li>
    </ol>
<li> Dokumentation </li>
  <ol>
<li> Modellen dokumenteres med forretningsmetadata </li>
<li> Hvert element i modellen dokumenteres med metadata </li>
  </ol>
<li> Review og godkendelse, jf. Kapitel 5: Review, godkendelse og udstilling </li>
</ol>

Modelelementer kan sagtens være relevante for modellen og den senere anvendelse uden at de af den grund hører opgave- eller forretningsmæssigt hjemme i den pågældende organisations emne- eller forretningsområde. Disse modelelementer kan importeres i modellen da de kan være relevante i modellen, fordi de kan være direkte relateret til forretningens egne modelelementer.

### Klassifikationsmodeller
Klassifikationsmodeller kategoriserer og ordner entiteter i emneklasser. Dette kan både bruges til at modellere større hierarkier af entiteter eller til kontrollerede udfaldsrum. Kontrollerede (eller lukkede) udfaldsrum er når man har et sæt af faste værdier som en egenskab kan have, fx sagstyper, fortrolighedsgrad eller ugedage. I det sidste tilfælde vil 'mandag', 'tirsdag', 'onsdag' etc. være entiteter tilhørende emneklassen 'ugedag'.

Klassifikationsmodeller er begrebsmodeller, men kan anvendes i sammenhæng med både begrebs-, informations- og logiske datamodeller. Klassifikationer skal dog laves i separate modeller for at fremme genbrug og dermed fælles forståelse.

## Hvilke modeltyper skal jeg udarbejde?
Det er op til projektet og den modelansvarlige organisation at afklare og afgøre hvilke modeltyper, der er behov for til specifikke formål og målgrupper.

Det er dog et krav, at der etableres sammenhæng mellem modellerne, såfremt der oprettes forskellige modeltyper for det samme emne. 

Læs mere om hvordan man dokumenterer denne sammenhæng i regel 14.

Det giver i de fleste tilfælde mening at starte med at lave en begrebsmodel, da afklaring og definition af de relevante begreber er nødvendig for semantisk velfunderede modeller og derfor en del af basis for alle modeltyperne. Begrebsmodeller er også den type model, det i de fleste tilfælde er lettest for forretningen at forholde sig til, og derfor er de særligt velegnede til at sikre at modelleringen bliver forankret i forretningen.  

Informationsmodeller og logiske datamodeller skal i henhold til modelreglerne baseres på velafklarede begreber. Man kan undlade at lave en eksplicit begrebsmodel, men selve den begrebsafklaring der ligger i at lave definitioner og blive enige om termer kan man ikke springe over. Ligeledes kan man undlade at lave informationsmodel, men den forretningsafklaring der ligger i en informationsmodel, får man brug for når man skal lave en logisk datamodel.

![Illustration af hvad der skal afklares for at lave de forskellige modeltyper](Illustrations/kap2-Illustration-afklares-forskellige-modeltyper.svg)

_Figur 1.10: Illustration af hvad der skal afklares for at lave de forskellige modeltyper_

Skal der ikke udarbejdes et konkret it-system, udvekslingsformat eller lignende, men fastlægges et fælles sprogbrug om et emne, vil det ofte være tilstrækkeligt at udarbejde en begrebsmodel. Dette gælder for eksempel referencearkitekturer, vejledningsmateriale og kommunikative indsatser, samt i situationer hvor det primære formål med modelleringen er at kunne tale om et emne uden at misforstå hinanden.

Informationsmodeller og logiske datamodeller, der er udarbejdet på basis af afklarede begrebsmodeller, bliver dermed også semantisk forankrede i forretningen. Det er ikke et krav, eller nødvendigvis hensigtsmæssigt, at begrebsmodelleringen er fuldt afsluttet inden arbejdet med de andre modeltyper påbegyndes. Det videre arbejde kan sagtens afdække spørgsmål og scenarier, der påvirker begrebsafklaringen og dermed føre til ændringer i begrebsmodellen.

Informationsmodeller tilføjer yderligere forretningsmæssig information om struktur og afhængigheder, ofte kaldet forretningsregler. Informationsmodeller er fx en god måde at formidle de forretningsregler, der gælder for data, når eksterne skal udarbejde en datamodel, og der er derfor også gode bilag til kravspecifikationer.

Logiske datamodeller bør udarbejdes i projekter der beskæftiger sig med udveksling af data mellem forskellige systemer, og kan være nyttige i andre projekter der beskæftiger sig med data, herunder systemudvikling og dataanalyse. 

## Modelomfang (kernemodeller vs. anvendelsesmodeller)
Modelreglerne er baseret på en række principper om gode modeller og på en modelleringsmetode, som fremmer genbrugelighed og sammenhængende begreber og data. En del af metoden går ud på at skelne mellem modeller, der beskriver et bestemt emneområde (benævnt **kernemodeller**), og modeller, der beskriver en bestemt anvendelseskontekst (benævnt **anvendelsesmodeller**). Dette gælder for alle modeltyper. Nedenfor beskrives de to typer modeller mere indgående.

På denne måde vil selvstændige emneområder blive beskrevet selvstændigt, og de kan godkendes af et forum, der er relevant for emneområdet. Til en bestemt anvendelse kan elementer fra forskellige emneområder så sammensættes i en model der netop understøtter det konkrete formål. Det kan fx være i forbindelse med en implementering af et specifikt it-system, database, udvekslingsformat eller lignende.

Denne vigtige skelnen mellem kernemodeller og anvendelsesmodeller gør det muligt at genbruge fremmede modeller i egen modellering, og den støtter dialogen om, hvordan modelleringen bedst koordineres, og hvordan ejerskabet og ansvaret for modellen placeres.

§06 - <span style="color:#AB2A0C;"> Angiv meningsfyldte navne og beskrivelser for modeller </span>

### Kernemodeller
En kernemodel er en genbrugelig model over et afgrænset emneområde, som ikke definerer modelelementer, der er defineret i andre emneorienterede modeller. 

Modellen har typisk et centralt forretningsobjekt i fokus. En model, der netop indeholder ét emneområdes begreber, er kendetegnet ved at være en samling af begreber, der hører naturligt sammen gennem høj samhørighed i modellen. Modellerne bliver mere generelt anvendelige ved at afgrænse kernemodellerne til (mindre) emneområder uden at knytte dem til specifikke anvendelser. Kernemodellerne kan ses som byggeblokke, der gør det muligt at genbruge de modelelementer, der allerede er defineret og beskrevet inden for et relevant emne. Da kernemodeller ikke overlapper, men relaterer sig til hinanden, vil de med tiden danne et komplet modelnetværk, som beskriver hele den offentlige forretning.

![Eksempel på kernemodeller, der danner modelnetværk](Illustrations/kap2-Eksempel-på-kernemodeller-der-danner-modelnetværk.svg)

_Figur 1.11: Eksempel på kernemodeller, der danner modelnetværk_

En kernemodel kan indeholde modelelementer der ikke tilhører emneområdet, men som er nødvendige for at give kontekst til eller definere relationer fra/til de modelelementer der tilhører emneområdet. Disse modelelementer skal ideelt set være defineret i andre kernemodeller af personer, der er eksperter inden for det pågældende emneområde. Som udgangspunkt vil man kun importere elementer fra andre modeller  hvortil der oprettes en direkte relation til et af forretningens egne modelelementer. Det vil i praksis sige at man i diagrammet kun medtager ’nærmeste’ element fra den anden model - nedenfor markeret med blå.

![Genbrug af klasse](Illustrations/kap2-Genbrug-af-klasse.svg)

_Figur 1.12: Genbrug af klasse fra et andet emneområde i egen model_

I realiteten er det ikke altid muligt at finde alle de elementer man har brug for, og man kan derfor være nødt til selv, forhåbentligt midlertidigt, at definere disse modelelementer. I begge tilfælde angives det, at modelelementet ikke tilhører emneområdet. Implikationen af denne angivelse er også, at man ikke tager samme grad af ansvar for modelelementets faglige indhold, og at man planlægger at følge opdateringer af den model, der har defineret elementet, eller at erstatte sit midlertidige modelelement når en passende erstatning modelleres.

### Anvendelsesmodeller

En anvendelsesmodel er en model, som er rettet mod en specifik anvendelse i en afgrænset kontekst. 

Dette kunne være et system, et register eller lignende, der skal understøtte et forretningsområde. Anvendelsesmodeller afspejler og afgrænses af behovet for information i en bestemt anvendelsessituation og sammensættes af elementer fra en eller flere kernemodeller. Anvendelsesmodeller kan forstås som sammensætningen af forskellige byggeblokke til en bestemt anvendelse.

Modelelementer der indgår i en anvendelsesmodel skal således være defineret i kernemodeller. Der kan dog være projekter, hvor man ikke har tid/ressourcer til eksplicit at udarbejde kernemodellerne, hvorfor modelreglerne åbner mulighed for, at en eller flere kernemodeller kan modelleres som en del af en anvendelsesmodel ved anvendelse af forskellige namespaces i modelelementerens HTTP-URIer. Se mere [Kapitel 4: Anvendelse og udformning af HTTP-URIer](husk link).

![Et antal kernemodeller](Illustrations/kap2-Et-antal-kernemodeller.svg)

![Anvendelsesmodel sammensat af kernemodelelementer](Illustrations/kap2-Anvendelsesmodel-sammensat-af-kernemodelelementerk.svg)

_Figur 1.13: Et antal kernemodeller: en kernemodel kan forstås som en byggeblok for et bestemt emne- eller forretningsområde_
_Figur 1.14: Anvendelsesmodel sammensat af kernemodelelementer: en anvendelsesmodel kan forstås som sammensætningen af elementer fra byggeblokke til en bestemt anvendelsessituation_
                
§25 - <span style="color:#AB2A0C;">Sammensæt anvendelsesmodeller af elementer fra kernemodeller</span>

## Genbrug af eksisterende modellering
Genbrug af eksisterende modellering fremmer sammenhængende begreber og data, fordi genbrug af modeller og modelelementer automatisk skaber interoperabilitet mellem modeller.

Kernemodeller bør ikke overlappe andre kernemodeller, og der bør kun findes én modellering af et givet emneområde og dets modelelementer. Hvis man har behov for at anvende eksterne modelelementer til at beskrive ‘sin egen’ model, kan man repræsentere dem som indlånte i modellen. En model kan fremme genbrug ved at være grundlæggende beskrevet, udstillet via internettet og orienteret mod fællesoffentlig interoperabilitet. Det er derfor helt centralt, at sammenhængen med andre modeller og modelelementer er dokumenteret. Det vil sige, at man i henhold til modelreglerne er forpligtet til at undersøge, om de relevante begreber og modelelementer allerede er beskrevet på en fyldestgørende måde. 

Det skal være nemt at _finde_ eksisterende modeller, og derfor er der blevet oprettet et [fællesoffentligt katalog over begrebs- og datamodeller](https://data.gov.dk/catalogue/models/), også kaldet Modelkataloget. Modelkataloget indeholder en oversigt over begrebs- og datamodeller, der er udarbejdet i offentligt regi, og som er registreret med henblik på videndeling og genbrug. Nye fællesoffentlige modeller optages løbende, og der kan også optages modeller under udarbejdelse således, at andre kan se, at der er noget under udarbejdelse, og der kan etableres kommunikation om fælles modelleringsbehov. Derudover indeholder dette katalog også oplysninger om en række anerkendte internationale modeller, som kan have en bred anvendelse i dansk administrativ og fællesoffentlig kontekst.

§24 - <span style="color:#AB2A0C;">Definér kun nye modelelementer når det er nødvendigt</span>

### Undgå silomodellering
Der er i det offentlige en lang tradition for at arbejde i projekter, som har et iboende “snævert syn” på den problemstilling, som projektet arbejder med, og det kan derfor være svært at undgå silomodellering. Det er oftest meget lettere kun at tænke på projektets egne behov og ikke blive forstyrret med noget andre har beskrevet i forvejen. Hvad nu hvis det, de andre har beskrevet, ikke lige præcis er det, vi mener? Så hellere definere det selv. Det kender de fleste sikkert.

Et andet problem er, at det kan være svært for det enkelte projekt at retfærdiggøre investeringen i gode, brede og genanvendelige modeller, da det ofte vil være nogle andre end projektet selv, der får gavn af den store modelleringsindsats. Ydermere kommer gevinsten ikke lige med det samme, men måske først på længere sigt.

Der kan ikke være tvivl om, at alle vil have stor gavn og spare mange ressourcer på lang sigt, hvis vi har veldokumenterede kernemodeller på de forskellige domæner, som pr. automatik danner grundlag for anvendelse i mange forskellige projekter. Tænk bare hvor meget projekter på f.eks. skoleområdet kan spare, hvis alle begreber, termer, klassifikationer osv. ligger færdige i aftalte modeller med den rigtige governance. De forskellige leverandører på området skal ikke til at opfinde egne begreber, klassifikationer osv. men blot tage det, vi allerede har på hylden. Det vil også gøre det meget nemmere at sammenligne den ene skole med den anden eller udarbejde god ledelsesinformation, når “tingene” er sammenlignelige og tager samme udgangspunkt.

Målet er, skridt for skridt, at få etableret et sammenhængende netværk af gode kernemodeller med indbygget governance, som vi alle kan stole på og derfor også anvende som grundlag for fremtidige projekter og udvekslingsstrukturer på tværs af fagområder.

![Undgå silomodellering](Illustrations/kap2-Undgå-silomodellering.svg)

_Figur 1.14: Illustration af overgangen fra silomodellering til et sammenhængende netværk af kernemodeller_


# Kapitel 7: Det visuelle udtryk
Af hensyn til brugbarheden bør man gøre modellerne så læsevenlige som kompleksiteten i modellen tillader det, og helt overordnet anbefales det at det visuelle udtryk i UML-modellerne ensrettes så meget som muligt. 

Det visuelle udtryk af modellen understøtter kommunikation mellem forskellige interessenter såsom arkitekter, udviklere og forretningseksperter, samt på tværs af organisationer med forskellig dokumentationspraksis. Det visuelle udtryk kan dermed betragtes som UMLs største fordel, og denne udnyttes bedst, hvis diagrammerne er nemme at afkode og behagelige at kigge på. Derfor giver det mening at følge fælles principper for udarbejdelsen af diagrammer, for at opnå et genkendeligt visuelt udtryk. Dette gælder uanset om der er tale om begrebsdiagrammer, diagrammer for informationsmodeller eller logiske datamodeller.

De generelle anbefalinger nedenfor betyder ikke at selve indholdet af UML-modellen bliver bedre, men at det bliver nemmere at kommunikere modellen til interessenter. 

## Anbefalinger til grafisk opsætning og præsentation

### Undgå krydsende streger hvor det er muligt
Gør dit UML-diagram lettere at læse og forstå ved at undgå at stregerne krydser hinanden. Ligeledes bør streger ikke krydse klasser, enumerationer eller strukturerede datatyper.

Hvis dit UML-diagram er så omfattende at det kan være svært at undgå dette, så kan dette være et tegn på, at modellen med fordel kan opdeles i deldiagrammer.

### Foretræk vinkelrette knæk fremfor skrå streger
Det kan give et mere ordnet og roligt udtryk hvis modellens streger ikke tegnes skråt fra element til element, men at de derimod knækkes vinkelret.

### Ensret klassernes størrelser og justeringer
Ensret UML-klassernes størrelser og justeringer i det omfang det er muligt.
I begrebsdiagrammer: lav de klasser der repræsenterer begreberne lige høje og hvor muligt lige brede
I informationsmodeller og logiske datamodeller: lad gerne klasser være lige brede, eller brug evt. 2 faste bredder.

Man kan evt. vælge at lade diagrammets mest centrale klasse/begreb være større end resten, dels for at give en visuel indikation af at det er centralt, dels for at give bedre plads til mange associationer. At lade et mindre centralt element være større vil derimod virke forvirrende.
Det giver et mere roligt udtryk hvis klassernes kanter, hvor muligt er justeret, så kanterne flugter med hinanden.

### Sørg for at al tekst er læsbar
Navne på associationer og associationsender skal være fri af andre elementer så hele navnet er synligt og altså ikke ligge oven på hinanden.

Tag også hensyn til at indholdet af klasser (klassenavn, attributter og datatyper) bedst kan læses hvis der er plads mellem tekst og kanten af klassen. Dette kan gøre det nødvendigt at bryde ovenstående princip om ensretning af klassernes størrelse.

Desuden kan det være en god ide at øge tekststørrelsen eller gøre skrift fed for at øge læsbarheden. 

### Brug anbefalede farver
Farver skal anvendes til at fremhæve information, der allerede er tilstede i modellen. Når der anvendes farver bør man bruge dem, der anbefales i modelreglerne og dem der typisk anvendes til specifikke modelelementtyper. 

Modelreglerne fastlægger for eksempel at genbrugte/indlånte elementer fremhæves i kernemodeller med en visuel markering. Her anbefales farven blå. Informationen om at et givet modelelement er genbrugt og defineret i en anden model vil allerede være til stede i form af elementets URI og evt. kvalificerede elementnavne, men fremhæves yderligere med den visuelle markering. 

Grunddatamodellering har en praksis vedr. enumerationer og datatyper som også anbefales anvendt bredt, selvom farveanbefalingerne her ikke indgår i Modelreglerne.

Der anbefales følgende farver til modelelementer:

* Sandfarve/beige til egendefinerede klasser
* Blå til genbrugt/fremmede/indlånte klasser/begreber fra andre kernemodeller
* Grøn til klassifikationer i form af enumerationer og klassifikationsklasser
* Gul til strukturerede datatyper
* Lysegrå til objekter

De valgte farver skal egne sig til både skærm og print, og tekst placeret på disse farver skal være let læselig.

Til orientering anvendes der i grunddatamodellering disse specifikke farver:

* Klasser: Sandfarvet (RGB: 254,250,247, HEX: #FEFAF7)
  
  ![Sandfarve](Illustrations/kap7-1a-sand.svg)
  
* Indlånte klasser: Blå (RGB: 135,205,235, HEX: #87CDEB)

  ![Blå](Illustrations/kap7-1b-blå.svg)
  
* Strukturerede datatyper: Gul (RGB: 251,249,198, HEX: #FBF9C6)

  ![Gul](Illustrations/kap7-1c-gul.svg)

* Enumerationer: Grøn (RGB: 232,253,227, HEX: #E8FDE3)

  ![Grøn](Illustrations/kap7-1d-grøn.svg)

Man kan eventuelt anvende yderligere visuelle markeringer, der fremhæver aspekter af modelleringen. I så fald bør disse markeringer:
* udelukkende fremhæve - ikke tilføje - information
* supplere - ikke erstatte - de fælles anbefalede farver
* anvendes konsistent
* forklares på diagrammet

### Placer overordnede klasser over deres specialiseringer
Lad så vidt muligt generaliseringspilene pege opad. 
Når man anvender en hierarkisk relation som en specialisering, så er det lettere at afkode modellen hvis overordnede klasser også er placeret over underordnede klasser. Er dette ikke muligt, fx i forbindelse med flere omfattende generaliseringssæt, er det næstbedste at placere specialiseringerne til højre for den overordnede klasse, således at den overordnede klasse kommer først i læseretning.

### Anvend generaliseringssæt
Generaliseringssæt (hvor flere generaliseringspile samles i en spids) kan bruges til at vise at specialiserede klasser/begreber er specialiserede efter samme inddelingskriterie, fx formål eller funktion. Dette giver diagrammer mere information samtidigt med at det bliver mere roligt at se på. Læs mere om [generaliseringssæt i afsnittet om UML-modellering](#uml-modellering).

![Generaliseringssæt](Illustrations/kap7-2-generaliseringssæt.svg)

Figur 7.1: Eksempel på anvendelse af generaliseringssæt i begrebsdiagram

### Angiv retning på begrebsrelationer
UML-associationer kan angives med eller uden navigabilitet, der vises som en pil i enden af associationer. Dette omtales ofte mindre præcist som retning. Navigabilitet er ikke det samme som, men ofte sammenfaldende med læseretning. 

I begrebs- og informationsmodeller giver det ikke meget mening at tale om navigabilitet, og associationer bruges specifikt til at udtrykke relationer mellem begreber. Derfor kan pilene benyttes til at angive relationens retning. Man kan også anvende læseretningspile i forbindelse med associationsnavnet. For mange, især dem uden stor erfaring med UML, er det dog lettere at læse modeller med retning på relationerne. Desuden er det i nogle værktøjer svært at styre retningen på læseretningspile præcist.

### Brug associationer til klasser og attributter til datatyper
I UML er både attributter og associationsender egenskaber og kan teknisk have både datatyper og klasser som udfaldsrum. Det giver dog mere ensartede og letlæselige modeller hvis objektegenskaber modelleres som _associationsender_ og datatypeegenskaber som _attributter_.

![Egenskaber](Illustrations/kap7-3-egenskaber.svg)

Figur 7.2 : ??

Objektegenskaber har klasser som udfaldsrum, og datatypeegenskaber har datatyper som udfaldsrum. Her kan der være tale om primitive datatyper, strukturerede datatyper eller enumerationer. For strukturerede datatyper og enumerationer hjælper det læseren, hvis der oprettes en dependency mellem atrributtet og datatypen.

Nedenfor ses objektegenskaben ‘påLager’ med klassen ‘Cykel’ som udfaldsrum modelleret som associationsende. Datatypeegenskaberne ‘navn’, ‘cvrNr’, ‘stelnummer’ og størrelse’ er modelleret som attributter. Heraf har ‘stelnummer’ en struktureret datatype som udfaldsrum og sammenhængen mellem elementerne er illustreret med en dependency.

![Eksempel på egenskaber](Illustrations/kap7-4-egenskaber-eksempel.svg)

Figur 7.3: objektegenskaber som associationsender og datatypeegenskaber som attributter. 

## Eksempel på UML-diagram 

![Diagrameksempel](Illustrations/kap7-5-diagrameksempel.svg)

Figur 7.4: UML-diagram hvor anbefalinger følges

## Anbefalinger til organisering og kommunikation
### Skab overblik med opdeling og overordnede diagrammer 
I forbindelse med formidling af en større model anbefales det at lave en slags oversigts- eller indflyvningsdiagram, der indeholder de mest centrale elementer (uden eventuelle attributter) og relationer, og som kan fungere som en introduktion til modellen. 

Det kan også være hensigtsmæssigt at dele en stor model op i flere deldiagrammer. Generelt bør et diagram kunne være på en A4-side (gerne med landskabsorientering) eller en Powerpoint-slide, samtidigt med at det har en størrelse hvor al tekst er nemt læsbart. 

Der findes diagrammer hvor elementerne naturligt falder ind i forskellige grupperinger. Det kan være indflyvningsdiagrammer hvor et par elementer repræsenterer et emne der udfoldes i et andet diagram eller anvendelsesmodeller der sammensætter elementer fra forskellige kernemodeller. Her kan det være en god idé at visualisere grupperingerne ved at indramme elementer der hører sammen, gerne med navngivelse af rammen.

I fortællingen om hvilke kernemodeller der indgår i en en given anvendelsesmodel kan det være en idé at udarbejde et pakkediagram som viser hvilke kernemodeller en anvendelsesprofil sammensætter og/eller indramme elementer fra samme kernemodel med pakken på diagrammet. 

### Organiser diagrammet ift. rækkefølge hvor relevant 
I nogle situationer er der en indbygget logisk rækkefølge eller kronologi mellem elementerne.. Fx kommer en ansøgning om en ydelse før bevillingen af ydelsen, som igen kommer før udbetalingen af ydelsen. I disse tilfælde kan det lette læsningen af diagrammet, hvis rækkefølgen følger almindelig læseretning, således at det der kommer først står længst til venstre og det der kommer sidst står længst til højre. Organiseringen i rækkefølge har dog ingen reel betydning – det er udelukkende en læsehjælp. Ønsker man at modellere et flow eller lignende anvendes en anden modeltype, fx et procesdiagram.

### Lav også alternative visuelle diagrammer til kommunikationsformål
Det kan være relevant at formidle det centrale indhold af en begrebs- eller datamodel visuelt med andre grafiske metoder til specifikke kommunikationsformål.  

Det er typisk uformelle modeller med kasser, figurer og streger eller illustrationer med ikoner eller andre grafiske illustrationer, der repræsenterer modellens elementer og relationer. Se eksempelvis denne [illustration fra grunddataprogrammet](https://datafordeler.dk/vejledning/grunddata/datamodel/) som viser grunddata på et overordnet niveau.

En anden måde at lave diagrammer til kommunikation er at lave simplificerede views af UML-modellen. Sådanne diagrammer kan være velegnede i forbindelse med forretningsgodkendelse af modellen. Det kan fx være nyttigt at lave diagramvisninger, der ikke viser stereotyper, datatyper, prefixes eller aliaser på et andet sprog, selvom dette er en del af den bagvedliggende model.

## Yderligere best practices i international modellering
### Angivelse af kravniveau med supplerende stereotyper 
Hvis man i en UML-model ønsker at tydeliggøre de forskellige krav til anvendelse af de forskellige elementer i modellen, bør man anvende supplerende stereotyper til dette. Eksempelvis kan stereotyperne 5<<mandatory>>, <<recommended>>, og <<optional>> anvendes til at angive om udfyldelse af et givet felt er obligatorisk, anbefalet eller valgfrit. 

Disse stereotyper anvendes også typisk i anvendelsesprofilerne der udgives af Europa-Kommissionen. Se fx [UML-diagrammet til DCAT-AP 2.0.1](https://joinup.ec.europa.eu/sites/default/files/distribution/access_url/2020-06/8d26212c-3ed4-4c9d-b5a5-0b5934daae34/DCAT_AP_2.0.1.png). I [INSPIRE](https://inspire-regadmin.jrc.ec.europa.eu/dataspecification/themes/br/Chapter5.pdf) data specifikationerne anvendes også stereotypen <<voidable>> til at angive at der ikke eksisterer eller kan afledes en tilsvarende værdi i kildedatasættet. 

![Kravsniveau med stereotyper](Illustrations/kap7-6-kravniveau-med-stereotyper.svg)

Figur 7.5: Udsnit fra UML-diagram til DCAT-AP 2.0.1

### Angiv gerne namespaces og præfikser i logiske datamodeller
Ved at anvende en forkortelse for namespacet på den model hvor modelelementer er defineret som præfiks for UML-elementnavne, er det til enhver tid tydeligt hvor et givent element kommer fra. Se fx  [W3Cs UML-visualisering af DCAT](https://www.w3.org/TR/vocab-dcat-2/). Det er især relevant i anvendelsesmodeller som sammensættes af modelelementer fra forskellige kernemodeller. I kernemodeller kan man eksempelvis også vælge alene at forsyne de indlånte elementer med prefixes, så defaultlæsningen bliver at de øvrige klasser er modellens egne. 

![Præfixer](Illustrations/kap7-7-præfixer.svg)

Figur 7.6: ??

For at gøre det let at se hvilke modeller der er genbrugt i given model, bør man også indsætte en tekstboks med anvendte prefixes og namespaces i modellen, fx

![Tekstboks](Illustrations/kap7-8-tekstboks.svg)

Figur 7.7: Tekstboks med anvendte prefixes


# Kapitel 8: Governance

Modelreglerne er en del af det fællesoffentlige arkitektursamarbejde og falder styringsmæssigt under Udvalg for Arkitektur og Standarder (UAS). De skal anvendes af initiativerne i de fællesoffentlige digitaliseringsstrategier til at beskrive og modellere begreber og data. Modelreglerne kan anvendes, og anbefales anvendt, i den offentlige sektor i øvrigt.

For at sikre kvalitet og sammenhæng i modelleringsarbejdet skal modeller, der bliver udarbejdet i regi af de fællesoffentlige digitaliseringsstrategier forretningsgodkendes, gennemgå modelteknisk review og udstilles.

## Forretningsgodkendelse
Forretningsgodkendelse er en erklæring af at modellen er fagligt retvisende og accepteret som gældende for det pågældende emneområde. Den skal derfor foretages af et beslutningsdygtigt forum med relevant fagligt indsigt. Dette kan fx være det forum (styregruppe, programledelse mm), der tog beslutningen om at starte det projekt modelleringen er en del af. Det kan også være et fagligt forum, som fx grunddataprogrammets arkitekturforum. Det er op til projektet at vælge det mest relevante forum.

Når en eller flere modeller forelægges til forretningsgodkendelse, bør det godkendende forum gøres opmærksom på, at de ved godkendelsen tager ansvar for gyldigheden (på godkendelsestidspunktet) af **det semantiske indhold** af de begreber eller modelelementer, der er defineret som en del af modellen (tilhører dens emneområde). Derimod tager de ikke noget ansvar for begreber/modelelementer fra andre emneområder, der er medtaget i modellen for at give kontekst og sammenhæng. For at sikre validiteten af godkendelsen bør forummets medlemmer modtage modelmaterialet i tilstrækkelig tid til at kunne diskutere dette med andre medlemmer af deres organisation.

Forummet skal godkende det semantiske indhold af modellen. Dette kræver at modellens semantiske indhold findes i en repræsentation som er målrettet dette forum så det er det semantiske og ikke det modelleringstekniske indhold som forummet tager stilling til. Det vil typisk være en begrebsliste eller et udtræk af en UML-model, der viser betegnelser, definitioner og anden metadata, der behandles og godkendes. Dette kan, hvor det skønnes hensigtsmæssigt, ledsages af UML-diagrammerne, evt. i en forsimplet form, hvor ikke alle informationer vises.

Mange projekter vælger at foretage forretningsgodkendelse efter det modeltekniske review. I de tilfælde medsendes information om det planlagte godkendelsesflow til reviewet.

<code style="color : rgb(171,42,12)"> [§11 - Modellen skal forretningsgodkendes](https://arkitektur.digst.dk/metoder/begrebs-og-datametoder/regler-begrebs-og-datamodellering/de-faellesoffentlige-regler-begrebs#r11) </code>


## Modelteknisk review
For at understøtte anvendelsen af de fællesoffentlige modelregler, og at fælles begrebs- og datamodeller genbruges og tænkes ind i udviklingen af it-løsninger, udføres modelreviews for initiativer i fællesoffentlige digitaliseringsstrategier med væsentligt indhold af datamodellering og datadeling. Projekter der som led i det fællesoffentlige samarbejde gennemgår et arkitekturreview vil blive tjekket for, om de har (eller bør have) en eller flere modeller, der bør gennemgå et modelreview. For modeller der ikke er udarbejdet i regi af en fællesoffentlig digitaliseringsstrategi, kan review aftales med modelsekretariatet, afhængigt af dets ressourcer. Det kan især give mening for tværgående projekter, der skal understøtte datadeling mellem flere offentlige parter. 

Reviewet foretages af modelsekretariatet, hvor modelreglerne også er blevet udarbejdet. Modelsekretariatet består primært af dataarkitekter, med kompetencer inden for både begrebs- og datamodellering. Desuden deltager skiftende review-boards, typisk bestående af to personer per review. Medlemmerne i review-boardet repræsenterer de fællesoffentlige parter. Når det er muligt inkluderes personer i review-boardet med en faglig indsigt i modellens emne, fx repræsentanter for anvendere af de modellerede data, eller personer der arbejder i et relateret domæne. Dette kan dog ikke garanteres.

Modelreviewet vurderer, i hvilket omfang de fællesoffentlige modelregler anvendes og hvilke handlinger, der skal til for at løfte projektets begrebs- og datamodeller yderligere. I forbindelse med reviewet udarbejdes en rapport med anbefalinger til projektet samt en gennemgang af modellen i forhold til de enkelte regler. Der er normalt et særligt fokus på definitionerne, som ikke blot tjekkes for, om de overholder den anbefalede struktur, men også vurderes i forhold til klarhed og informationsindhold. Desuden vil der være et særligt fokus på, om modellen genbruger eksisterende modellering, hvor det er relevant. 

Selvom der ofte er deltagere i et review-board med tilstrækkelig faglig indsigt til at komme med fagligt orienterede kommentarer, er det vigtigt at huske, at der ikke er tale om en fagligt review, men et modelteknisk review. Det vil sige at reviewet kan være med til at sikre at modellen er entydig, forståelig og sammenhængsskabende, men ikke kan erstatte validering i et fagligt forum. Hvorimod det faglige forum ofte ikke kan sikre den modelleringstekniske kvalitet. 

Reviewrapporten kan udover anbefalinger til det aktuelle projekt indeholde ‘anbefalinger til det fremtidige arbejde’ og ‘tværgående anbefalinger’. Anbefalinger til det fremtidige arbejde vedrører modellens område, der vurderes til at være uden for scope af det aktuelle projekt Der er ikke nogen forventning om at de implementeres i projektet, men projektet er selvfølgelig velkommen til at lade sig inspirere. Tværgående anbefalinger bruges, hvis der i forbindelse med reviewet er identificeret problemstillinger eller behov, der bør løses på et fællesoffentligt niveau frem for i det enkelte projekt. Det kan fx være manglende fælles modeller på specifikke områder. Her er der altså heller ingen forventning om, at det aktuelle projekt løfter implementeringen af anbefalingerne.

Projektet afgør derefter i hvilket omfang det vil følge anbefalingerne i reviewrapporten. 

For projekter i regi af en fællesoffentlig digitaliseringsstrategi skal der afleveres en handlingsplan der forklarer, hvad man vil gøre for at efterleve de anbefalinger der er givet til det aktuelle projekt, eller hvorfor man ikke agter at følge dem. Projektet kan også komme med kommentarer til eventuelle anbefalinger til det fremtidige arbejde og tværgående anbefalinger. Reviewrapport og handlingsplan forelægges derefter Udvalg for Arkitektur og Standarder (UAS) til godkendelse, og vurdering af om modellen skal optages som del af FDA. 

### Proces for review
Review aftales via modelsekretariatet ved at skrive til arkitektur@digst.dk. Hvis et projekt ønsker, at et review bliver udført på et bestemt tidspunkt, fx af hensyn til den overordnede projektplan, er det en god ide at aftale tid til reviewet i god tid, så modelsekretariatet kan afsætte den fornødne tid i kalenderen og har mulighed for at besætte reviewboardet. Det også en god ide at afsætte tid i projektplanen til at behandle de anbefalinger reviewrapporten kommer med. 
Et review tager normalt to uger. Hvis det ikke kan lade sig gøre at foretage reviewet i løbet af to uger, aftales en længere periode, når det aftales, hvornår reviewet skal foregå. I den forbindelse kan modelsekretariatet bede om et udkast til modellen eller andet materiale, der kan hjælpe med at vurdere reviewopgavens omfang. 

For at afklare spørgsmål i forhold til modelreglerne, reviewet, genbrug af modellering eller andet projektet måtte ønske sparring om, er det muligt at aftale et møde med modelsekretariatet i løbet af modelleringsprocessen inden reviewet.

#### Selve reviewindleveringen
For at få det maksimale udbytte af modelreviewet, skal modellerne have det korrekte format samt opfylde de anbefalede dokumentationskrav som beskrevet i modelreglerne. 

Udover modelreglernes krav til selve modellen, anbefales det at den samlede materialepakke, der indsendes til et modelreview, omfatter følgende:

* **Afleveringsdokumentation**: dokument der giver en overordnet introduktion til modellen, herunder formålet med udarbejdelsen, samt en beskrivelse af de elementer, der indgår i afleveringen. Evt. suppleret af ændringsbeskrivelse ift. tidligere version af modellen. I dette dokument kan man beskrive valg man har taget i forbindelse med modelleringen, fx hvorfor man har valgt at genbruge fra nogle modeller frem for andre, eller opmærksomhedspunkter man ved ville kunne undre en reviewer. Er der dele af modellen der endnu ikke er færdig, eller steder hvor man bevidst har valgt ikke at overholde modelreglerne bør dette også beskrives. Når forretningsgodkendelse og/eller udstilling af modellen først foretages efter modelreviewet skal planerne for forretningsgodkendelse/udstilling beskrives for at de relevante regler kan anses som overholdt.


* **Modelfil**: fil der indeholder modellen i et standardiseret filformat (xmi/rdf). Evt. suppleret af fx. modelleringsprojektfil indeholdende modellen.


* **Modelrapport**: dokument der redegør for modellens og modelelementernes metadata.


* **Modeldiagramfil**: billedfil med det eller de visuelle diagram(mer).

## Udstilling
Ved at udstille sine modeller skaber man mulighed for genbrug og videndeling. Andre offentlige myndigheder, leverandøren m.fl. får bedre mulighed for at forstå ens forretning. Dette er selvfølgelig især vigtigt når andre skal lave modeller, hvor de har brug for at anvende elementer fra ens model, fx fordi de skal levere eller aftage data. Også mens modellen er under udvikling kan den give værdi at udstille modellen, så andre kan få et indblik i hvad der er på vej og viden om hvem de kan henvende sig til, hvis de har en modelleringsopgave, der relaterer sig til den model der er under udvikling. Derfor opfordrer modelsekretariatet til at udstille modeller under udvikling - selvfølgelig med klar indikation af at de er under udvikling og derfor ustabile. Vælger man at vente med at udstille sin model til den er helt færdig, kan man sende informationer om den planlagte udstilling ved review- altså hvor og hvornår modellen vil blive udstillet - for at reglen om at modellen skal udstilles kan betragtes som opfyldt.

Man udstiller sin model på sin organisations egen hjemmeside eller server. Man vælger selv placeringen, dog bør man sikre sig, at den valgte http-adresse er så stabil som muligt. Skulle man alligevel få behov for at ændre den, vil det være god stil i en periode at henvise fra den gamle adresse til den nye.

For at andre kan få det maksimale udbytte af modellen, skal det være muligt at læse den, at skabe sig et overblik over dens indhold, og at indlæse modellen i modelleringsværktøjer m.m. Derfor skal modellen, når den er færdig, udstilles i (mindst) to formater. Dels et menneskevendt format der kan læses i en almindelig browser, dvs. en repræsentation af modellen i listeform eller som grafisk illustration. Dels et maskinlæsbart format, nemlig XMI, som er et format, der er udviklet til at udveksle modeller mellem forskellige systemer. Derudover kan man også publicere modellen i andre formater, hvis man har mulighed for det - jo flere jo bedre. Hvis man har udviklet sin model i RDF, kan modelsekretariatet, efter aftale, bistå med konvertering til XMI.

<code style="color : rgb(171,42,12)"> [§04 - Udstil modellen online](https://arkitektur.digst.dk/metoder/begrebs-og-datametoder/regler-begrebs-og-datamodellering/de-faellesoffentlige-regler-begrebs#r04) </code>

<code style="color : rgb(171,42,12)"> [§05 - Gør modellen tilgængelig i maskinlæsbart format](https://arkitektur.digst.dk/metoder/begrebs-og-datametoder/regler-begrebs-og-datamodellering/de-faellesoffentlige-regler-begrebs#r05) </code>  

## Modelkataloget
[Det fællesoffentlige katalog over begrebs- og datamodeller (modelkataloget)](https://data.gov.dk/catalogue/models/) er en oversigt over begrebs- og datamodeller der er udarbejdet eller relevante i offentlig regi og som er registreret med henblik på videndeling og genbrug. Kataloget indeholder metadata om og links til udstilling af de registrerede modeller, men ikke modellerne selv.

I forhold til registrering af modeller, er tilgangen indtil videre at sikre bredest mulig videndeling. Modellerne registreres med henblik på inspiration og potentielt genbrug, og derfor kan alle udstillede modeller optages i kataloget. Dermed kan både modeller under udvikling og modeller, der ikke overholder modelreglerne optages. Der er heller ingen krav til hvilket format modellerne skal have, blot at de skal være offentligt tilgængelige. Bemærk at registrering i Modelkataloget dermed ikke er ensbetydende med, at modellen får status som anbefalet og optaget i FDA.

I praksis får man modeller optaget ved at henvende sig til modelsekretariatet (arkitektur@digst.dk) med et link til udstillingen af modellen og oplysninger om et kontaktpunkt (mailadresse, gerne en funktionspostkasse), hvor man kan henvende sig hvis man har spørgsmål til modellen samt angivelse af vilkårene for genanvendelse af modellen ved angivelse af en specifik licens. Modelsekretariatet anbefaler [Creative Commons — CC0 1.0 Universal (CC0)](https://creativecommons.org/publicdomain/zero/1.0/), som er en åben licens, der tillader enhver form for brug og dermed er velegnet til at understøtte genbrug af modeller. Man kan dog også vælge en anden licens, og hvis man har brug for hjælp til at vælge, kan man fx benytte [Creative Commons licensvælger](https://www.google.com/url?q=https://creativecommons.org/choose/&sa=D&source=docs&ust=1709039583509040&usg=AOvVaw2QJ9pp3yDtcB0uTv_y_Y9K) eller [Joinup Licensing Assistant (EU)](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses). Derudover bruges modelmetadata (som beskrevet i Kapitel 6: Dokumentation af modellen) INDSÆT ANCHORLINK til at beskrive modeller i kataloget. Hvis de ikke allerede er udfyldt i modellen, må de meget gerne medsendes i det omfang det er muligt; især er det vigtigt at kende modelstatus.
