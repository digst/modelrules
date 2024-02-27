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
  ![svg](Illustrations/ny.svg)

Man kan eventuelt anvende yderligere visuelle markeringer, der fremhæver aspekter af modelleringen. I så fald bør disse markeringer:
* udelukkende fremhæve - ikke tilføje - information
* supplere - ikke erstatte - de fælles anbefalede farver
* anvendes konsistent
* forklares på diagrammet

### Placer overordnede klasser over deres specialiseringer
Lad så vidt muligt generaliseringspilene pege opad. 
Når man anvender en hierarkisk relation som en specialisering, så er det lettere at afkode modellen hvis overordnede klasser også er placeret over underordnede klasser. Er dette ikke muligt, fx i forbindelse med flere omfattende generaliseringssæt, er det næstbedste at placere specialiseringerne til højre for den overordnede klasse, således at den overordnede klasse kommer først i læseretning.

### Anvend generaliseringssæt
Generaliseringssæt (hvor flere generaliseringspile samles i en spids) kan bruges til at vise at specialiserede klasser/begreber er specialiserede efter samme inddelingskriterie, fx formål eller funktion. Dette giver diagrammer mere information samtidigt med at det bliver mere roligt at se på. Læs mere om generaliseringssæt i afsnittet om UML-modellering.

Figur xx: Eksempel på anvendelse af generaliseringssæt i begrebsdiagram

### Angiv retning på begrebsrelationer
UML-associationer kan angives med eller uden navigabilitet, der vises som en pil i enden af associationer. Dette omtales ofte mindre præcist som retning. Navigabilitet er ikke det samme som, men ofte sammenfaldende med læseretning. 

I begrebs- og informationsmodeller giver det ikke meget mening at tale om navigabilitet, og associationer bruges specifikt til at udtrykke relationer mellem begreber. Derfor kan pilene benyttes til at angive relationens retning. Man kan også anvende læseretningspile i forbindelse med associationsnavnet. For mange, især dem uden stor erfaring med UML, er det dog lettere at læse modeller med retning på relationerne. Desuden er det i nogle værktøjer svært at styre retningen på læseretningspile præcist.

### Brug associationer til klasser og attributter til datatyper
I UML er både attributter og associationsender egenskaber og kan teknisk have både datatyper og klasser som udfaldsrum. Det giver dog mere ensartede og letlæselige modeller hvis objektegenskaber modelleres som associationsender og datatypeegenskaber som attributter.

Objektegenskaber har klasser som udfaldsrum, og datatypeegenskaber har datatyper som udfaldsrum. Her kan der være tale om primitive datatyper, strukturerede datatyper eller enumerationer. For strukturerede datatyper og enumerationer hjælper det læseren, hvis der oprettes en dependency mellem atrributtet og datatypen.

Nedenfor ses objektegenskaben ‘påLager’ med klassen ‘Cykel’ som udfaldsrum modelleret som associationsende. Datatypeegenskaberne ‘navn’, ‘cvrNr’, ‘stelnummer’ og størrelse’ er modelleret som attributter. Heraf har ‘stelnummer’ en struktureret datatype som udfaldsrum og sammenhængen mellem elementerne er illustreret med en dependency.

Figur xx : objektegenskaber som associationsender og datatypeegenskaber som attributter. 

## Eksempel på UML-diagram 

Figur xx : UML-diagram hvor anbefalinger følges

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

Figur xx: Udsnit fra UML-diagram til DCAT-AP 2.0.1

### Angiv gerne namespaces og præfikser i logiske datamodeller
Ved at anvende en forkortelse for namespacet på den model hvor modelelementer er defineret som præfiks for UML-elementnavne, er det til enhver tid tydeligt hvor et givent element kommer fra. Se fx  [W3Cs UML-visualisering af DCAT](https://www.w3.org/TR/vocab-dcat-2/). Det er især relevant i anvendelsesmodeller som sammensættes af modelelementer fra forskellige kernemodeller. I kernemodeller kan man eksempelvis også vælge alene at forsyne de indlånte elementer med prefixes, så defaultlæsningen bliver at de øvrige klasser er modellens egne. 

Figur xx: ??
For at gøre det let at se hvilke modeller der er genbruges i given model, bør man også indsætte en tekstboks med anvendte prefixes og namespaces i modellen, fx

Figur xx: Tekstboks med anvendte prefixes


# Kapitel 8: Governance

Modelreglerne er en del af det fællesoffentlige arkitektursamarbejde og falder styringsmæssigt under Udvalg for Arkitektur og Standarder (UAS). De skal anvendes af initiativerne i de fællesoffentlige digitaliseringsstrategier til at beskrive og modellere begreber og data. Modelreglerne kan anvendes, og anbefales anvendt, i den offentlige sektor i øvrigt.

For at sikre kvalitet og sammenhæng i modelleringsarbejdet skal modeller, der bliver udarbejdet i regi af de fællesoffentlige digitaliseringsstrategier forretningsgodkendes, gennemgå modelteknisk review og udstilles.

## Forretningsgodkendelse
Forretningsgodkendelse er en erklæring af at modellen er fagligt retvisende og accepteret som gældende for det pågældende emneområde. Den skal derfor foretages af et beslutningsdygtigt forum med relevant fagligt indsigt. Dette kan fx være det forum (styregruppe, programledelse mm), der tog beslutningen om at starte det projekt modelleringen er en del af. Det kan også være et fagligt forum, som fx grunddataprogrammets arkitekturforum. Det er op til projektet at vælge det mest relevante forum.

Når en eller flere modeller forelægges til forretningsgodkendelse, bør det godkendende forum gøres opmærksom på, at de ved godkendelsen tager ansvar for gyldigheden (på godkendelsestidspunktet) af **det semantiske indhold** af de begreber eller modelelementer, der er defineret som en del af modellen (tilhører dens emneområde). Derimod tager de ikke noget ansvar for begreber/modelelementer fra andre emneområder, der er medtaget i modellen for at give kontekst og sammenhæng. For at sikre validiteten af godkendelsen bør forummets medlemmer modtage modelmaterialet i tilstrækkelig tid til at kunne diskutere dette med andre medlemmer af deres organisation.

Forummet skal godkende det semantiske indhold af modellen. Dette kræver at modellens semantiske indhold findes i en repræsentation som er målrettet dette forum så det er det semantiske og ikke det modelleringstekniske indhold som forummet tager stilling til. Det vil typisk være en begrebsliste eller et udtræk af en UML-model, der viser betegnelser, definitioner og anden metadata, der behandles og godkendes. Dette kan, hvor det skønnes hensigtsmæssigt, ledsages af UML-diagrammerne, evt. i en forsimplet form, hvor ikke alle informationer vises.

Mange projekter vælger at foretage forretningsgodkendelse efter det modeltekniske review. I de tilfælde medsendes information om det planlagte godkendelsesflow til reviewet.

[§11 - Modellen skal forretningsgodkendes](https://arkitektur.digst.dk/metoder/begrebs-og-datametoder/regler-begrebs-og-datamodellering/de-faellesoffentlige-regler-begrebs#r11)

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

[§04 - Udstil modellen online](https://arkitektur.digst.dk/metoder/begrebs-og-datametoder/regler-begrebs-og-datamodellering/de-faellesoffentlige-regler-begrebs#r04) 

[§05 - Gør modellen tilgængelig i maskinlæsbart format](https://arkitektur.digst.dk/metoder/begrebs-og-datametoder/regler-begrebs-og-datamodellering/de-faellesoffentlige-regler-begrebs#r05)   

## Modelkataloget
[Det fællesoffentlige katalog over begrebs- og datamodeller (modelkataloget)](https://data.gov.dk/catalogue/models/) er en oversigt over begrebs- og datamodeller der er udarbejdet eller relevante i offentlig regi og som er registreret med henblik på videndeling og genbrug. Kataloget indeholder metadata om og links til udstilling af de registrerede modeller, men ikke modellerne selv.

I forhold til registrering af modeller, er tilgangen indtil videre at sikre bredest mulig videndeling. Modellerne registreres med henblik på inspiration og potentielt genbrug, og derfor kan alle udstillede modeller optages i kataloget. Dermed kan både modeller under udvikling og modeller, der ikke overholder modelreglerne optages. Der er heller ingen krav til hvilket format modellerne skal have, blot at de skal være offentligt tilgængelige. Bemærk at registrering i Modelkataloget dermed ikke er ensbetydende med, at modellen får status som anbefalet og optaget i FDA.

I praksis får man modeller optaget ved at henvende sig til modelsekretariatet (arkitektur@digst.dk) med et link til udstillingen af modellen og oplysninger om et kontaktpunkt (mailadresse, gerne en funktionspostkasse), hvor man kan henvende sig hvis man har spørgsmål til modellen samt angivelse af vilkårene for genanvendelse af modellen ved angivelse af en specifik licens. Modelsekretariatet anbefaler [Creative Commons — CC0 1.0 Universal (CC0)](https://creativecommons.org/publicdomain/zero/1.0/), som er en åben licens, der tillader enhver form for brug og dermed er velegnet til at understøtte genbrug af modeller. Man kan dog også vælge en anden licens, og hvis man har brug for hjælp til at vælge, kan man fx benytte [Creative Commons licensvælger](https://www.google.com/url?q=https://creativecommons.org/choose/&sa=D&source=docs&ust=1709039583509040&usg=AOvVaw2QJ9pp3yDtcB0uTv_y_Y9K) eller [Joinup Licensing Assistant (EU)](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses). Derudover bruges modelmetadata (som beskrevet i Kapitel 6: Dokumentation af modellen) INDSÆT ANCHORLINK til at beskrive modeller i kataloget. Hvis de ikke allerede er udfyldt i modellen, må de meget gerne medsendes i det omfang det er muligt; især er det vigtigt at kende modelstatus.
