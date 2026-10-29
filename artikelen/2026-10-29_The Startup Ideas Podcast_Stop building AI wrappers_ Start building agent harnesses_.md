<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01M61MK2ZDT7TV0CK7ZNF1HGT9
-->

# De Laag Boven de Modellen

Een presentatie die binnen een minuut op het scherm verschijnt, kan het eindpunt zijn van tweehonderd afzonderlijke beslissingen. Dat is de gedachte achter Gamma, het snelgroeiende bedrijf voor presentaties, documenten, websites en visuele communicatie. Maar achter die gedachte schuilt een grotere verschuiving: niet het taalmodel zelf wordt de onderneming, maar de laag eromheen. De gereedschappen, controles, voorkeuren en keuzes die een model veranderen in iets dat werkelijk werk voor iemand verricht. Jon Noronha noemt die laag een *agent harness*. Wie begrijpt hoe zo’n harnas werkt, begrijpt misschien waar de volgende generatie softwarebedrijven ontstaat.

Toen iemand Jon Noronha vroeg wat een gebruiker in de eerste dertig seconden na een prompt in Gamma eigenlijk teweegbrengt, begon hij niet over magie. Hij begon over een computer.

Stel: een gebruiker plakt een rommelig document, een verzameling notities of een pdf in Gamma en schrijft: maak hiervan een presentatie van twintig dia’s. Voor die gebruiker is het een klein gebaar, een opdracht van één zin. Voor Gamma begint er onder de oppervlakte een proces dat veel weg heeft van het optuigen van een tijdelijk kantoor.

Eerst start Gamma een volledige computer in de cloud op: een afgeschermde digitale omgeving waarin de agent kan werken. Zo’n omgeving heet een sandbox. Daarin krijgt de agent toegang tot de bestanden die de gebruiker heeft aangeleverd, de oorspronkelijke prompt en aanvullende context over die gebruiker. Vervolgens krijgt hij instructies: lees de informatie, bepaal wat ontbreekt, raadpleeg waar nodig andere bronnen en bereid een resultaat voor.

Gamma is in de eerste plaats bekend als presentatietool, maar het bedrijf begon niet als agentbedrijf. Het ontstond in 2020, ruim voordat iedereen over agents sprak, en kreeg in 2023 vaart. In het begin bouwde het team tamelijk klassieke AI-workflows. Een taalmodel schreef één dia. Een andere oproep maakte een opzet voor een deck. Engineers rijgden die losse modelaanroepen handmatig aaneen tot vaste processen: tien dia’s maken, tekst ordenen, beelden toevoegen.

Dat werkte. Maar het had een grens. De software volgde een route die van tevoren was bedacht.

De verandering van de afgelopen jaren zat niet alleen in krachtigere modellen, maar in een andere manier van denken over software. De beste AI-producten, zei Noronha, bestaan niet langer uit een reeks vooraf geprogrammeerde oproepen. Ze geven een model een hoger doel en laten het daarna in een lus werken: iets doen, het resultaat inspecteren, gereedschappen gebruiken, fouten herstellen, opnieuw proberen. Niet één antwoord, maar een keten van handelingen.

Daarvoor is een harnas nodig.

Het woord klinkt technisch, maar de kern is eenvoudig. Een agent harness is de verzameling gereedschappen, regels en controles waarmee een AI-agent in een omgeving kan handelen, zijn eigen werk kan beoordelen en iets bruikbaars kan opleveren. Het harnas bepaalt niet alleen wat de agent *kan* doen, maar ook wanneer hij moet pauzeren, wanneer hij iets moet controleren en wanneer hij de gebruiker om richting moet vragen.

Claude Code is het bekendste voorbeeld. Het model daarachter kan programmeren, maar zonder harnas weet het niet welke bestanden op iemands computer staan, hoe een test moet worden uitgevoerd of welke regels een ontwikkelteam hanteert. Claude Code leert de agent door een codebase te lopen, bestanden te lezen, tests te draaien, wijzigingen door te voeren, met GitHub te werken en soms eerst een plan te maken voordat het begint. De intelligentie zit deels in het model. Maar de bruikbaarheid ontstaat in alles daaromheen.

Gamma moest een ander soort harnas bouwen. Geen harnas voor code, maar voor creativiteit.

Een presentatie maken is geen optelsom van correcte zinnen. Je moet begrijpen voor wie het verhaal bedoeld is. Je moet aanvoelen wat er op een dia thuishoort en wat niet. Je moet beelden selecteren, kleuren laten samenwerken, ruimte laten rond tekst, een grafiek leesbaar maken en voorkomen dat iemands hoofd half uit een gegenereerde foto verdwijnt. Bij programmeren is een test vaak helder: de code werkt of werkt niet. Bij een presentatie ligt dat anders. Twee mensen kunnen naar dezelfde dia kijken en het hartgrondig oneens zijn over de vraag of hij goed is.

Daarom begint Gamma niet meteen met genereren. In de eerste seconden na de prompt probeert de agent te begrijpen wat de gebruiker werkelijk wil. Is dit een les voor kinderen of een presentatie voor volwassenen? Is het materiaal bedoeld voor een klant, een interne vergadering, een investeerder, een klaslokaal? De vragen lijken klein, maar ze veranderen alles. Een presentatie over tijgers voor een groep achtjarige kinderen vraagt om andere beelden, woorden en ritme dan een deck over biodiversiteit voor een raad van bestuur.

Gamma kan daarbij informatie ophalen uit systemen als Notion, Slack en Linear. Misschien staat de relevante projectcontext in een Slack-kanaal. Misschien zitten de bronnotities in Notion. Misschien vertelt een ticket in Linear welke beslissing de presentatie moet ondersteunen. Nog voordat de gebruiker een eerste outline ziet, heeft Gamma doorgaans drie of vier verschillende modellen aangeroepen: duurdere modellen voor ingewikkelde redeneringen, goedkopere modellen voor afgebakende taken. Het systeem verzamelt context, stelt vragen en bouwt de gebruikersinterface waarin die vragen verschijnen.

Daarna schrijft het een structuur voor de presentatie. Het kiest of vormt een visuele stijl. Gamma beschikt over duizenden sjablonen en gebruikt zoekembeddings — een techniek die inhoud en stijlen als betekenissen in een grote kaart van verwantschappen plaatst — om een passend vertrekpunt te vinden. Als een gebruiker zegt dat het deck rood of blauw moet zijn, is dat geen simpel kleurcommando. Het kan betekenen dat een bestaande stijl moet worden aangepast zonder haar karakter te verliezen.

Voordat er ook maar één volledige dia is gemaakt, zijn er vaak al dertig of veertig modelaanroepen geweest, verspreid over vier of vijf modellen.

Pas dan drukt de gebruiker op genereren.

Vanaf dat moment begint de presentatie voor zijn ogen te ontstaan. Er moeten teksten komen, maar ook layouts. Elementen moeten op de juiste plaats vallen. Soms maakt Gamma decoratieve beelden; soms inhoudelijke illustraties, diagrammen, infographics of grafieken. Elke categorie vraagt andere modellen, andere instructies en andere kwaliteitscontroles. Veel van die taken lopen parallel. Dat is niet louter een technische luxe. Als alles na elkaar gebeurde, zou een gebruiker zo lang wachten dat hij vertrok voordat het resultaat af was.

In ongeveer een minuut verschijnt het deck op het scherm. Tegen die tijd heeft Gamma waarschijnlijk bijna honderd modelaanroepen gedaan en ergens tussen de tien en vijftien AI-modellen ingezet.

Maar de eerste versie is niet het einde. Ook Gamma vertrouwt haar eerste versie niet.

Na het genereren laat het bedrijf visiemodellen — modellen die afbeeldingen en vormgeving kunnen interpreteren — elke dia inspecteren. Staat tekst scheef? Is het contrast te zwak? Ligt een afbeelding verkeerd uitgesneden? Is een kop te dicht tegen de rand geplaatst? Ontbreekt er ademruimte? Sommige fouten springen voor vrijwel ieder menselijk oog onmiddellijk naar voren. Andere ziet alleen iemand met de blik van een ontwerper. Gamma probeert die blik gedeeltelijk in modellen te vangen.

Dan volgen herstelrondes. Dia’s worden opnieuw bekeken, aangepast en opnieuw gecontroleerd. Wanneer de gebruiker uiteindelijk één ogenschijnlijk afgeronde presentatie ontvangt, hebben ongeveer twintig verschillende modellen mogelijk tweehonderd afzonderlijke aanroepen uitgevoerd.

Dat is de reden waarom Noronha voorzichtig is met de term *GPT-wrapper*, de populaire maar vaak neerbuigende aanduiding voor producten die slechts een dun laagje rond een bestaand model zouden leggen. Er zit volgens hem waarheid in de stelling dat agent harnesses de nieuwe wrappers zijn. Maar het oude woord suggereert dat negentig procent van de waarde in het model zit, en dat de onderneming eromheen hooguit een beetje verpakking levert.

Zijn ervaring wijst in de omgekeerde richting.

“Het harnas is het grootste deel van het werk,” is zijn essentie. De modellen lijken in hun kern steeds meer op elkaar. Natuurlijk verschillen ze in kwaliteit, snelheid, prijs en sterke kanten. Maar het omzetten van die algemene capaciteit in een product dat iemand daadwerkelijk dagelijks wil gebruiken, vraagt een wereld aan ontwerpwerk. Welke context krijgt het model? Welke keuzes legt het systeem aan de gebruiker voor? Welke gereedschappen mag het gebruiken? Welke fouten moet het zelf kunnen vinden? Wanneer is het verstandig om door te vragen, en wanneer wordt doorvragen hinderlijke bureaucratie?

Zelfs OpenAI en Anthropic, de bedrijven die de fundamentele modellen ontwikkelen, bouwen volgens Noronha voortdurend harnassen. Ook zij verpakken algemene intelligentie in toepassingen met specifieke regels en gereedschappen.

Voor oprichters die naar de volgende kans zoeken, ligt de vraag dus niet alleen bij het model. De vraag is: op welk terrein heeft een generiek model nog geen goed paar handen gekregen?

Noronha zoekt die terreinen vooral waar werk subjectief is en de gebruiker veel geeft om het eindresultaat. In zulke domeinen volstaat een model dat technisch correct is niet. De gebruiker wil invloed houden. Hij wil dat het resultaat niet alleen klopt, maar ook bij hem past.

Creatief werk is daarvan een duidelijk voorbeeld. De persoonlijke videogame zou er een ander kunnen zijn. Programmeeragents kunnen al verrassend goed eenvoudige games bouwen, maar ze zijn volgens Noronha nog niet goed in het voortdurend ophalen van de smaak en voorkeuren van de speler. Waar moet het spel naartoe? Welke wereld wil iemand bouwen? Welke sfeer moet een level oproepen? Roblox en Minecraft laten zien dat miljoenen niet-technische mensen graag werelden vormen, als de drempel maar laag genoeg is. Misschien ontstaat er een harnas dat niet in een tekstvenster leeft, maar rechtstreeks in een driedimensionale wereld.

Het punt is niet dat iedere goede kans op een presentatie-app moet lijken. Integendeel. Noronha’s bedrijfsfilosofie is juist om iets te maken dat niet lijkt op wat iedereen al maakt.

Dat is lastiger dan het klinkt. Zodra een product aanslaat, verschijnen er kopieën. Gamma kende die ervaring zelf. Een bedrijf kan proberen anders te zijn, een eigen vorm te vinden, een onverwachte combinatie van ontwerp en technologie te bouwen — en vervolgens zien hoe anderen dezelfde uitgangspunten overnemen. De kopieën lopen meestal drie tot zes maanden achter, maar ze komen wel.

Dat legt een bijzondere last op de oprichter. Hij moet zichzelf blijven afvragen: waar ga ik heen? Wat is mijn uitgesproken overtuiging over de toekomst? Welk deel van het probleem probeer ik te doorgronden dat anderen nog niet zien? Een modern softwarebedrijf lijkt in die zin steeds meer op een productstudio die elke twee weken opnieuw iets van nul naar één bouwt.

De eerste vorm van verdedigbaarheid is dan visie. Niet zomaar snelheid, maar snelheid in een richting die anderen niet hebben gekozen.

De tweede is data die anderen niet hebben. Een bedrijf met een bestaand platform kan beschikken over informatie die nieuwe toetreders niet eenvoudig kunnen verzamelen: gedrag, voorkeuren, historische keuzes, branchekennis, relaties met klanten.

De derde vorm ligt buiten software. Juist omdat pure software steeds drukker en onzekerder wordt, ziet Noronha kansen in hardware, fysieke diensten en bedrijven waarin AI deel wordt van een werkelijk, tastbaar proces. Hij zegt er meteen bij dat hij zelf een softwareman is en geen specialist in massagesalons, restaurants of ambachtelijke dienstverlening. Maar als hij dat wel was, zou hij nadenken over plekken waar AI een menselijke uitwisseling van waarde kan verdiepen: iemand die een maaltijd serveert, iemand die zorg verleent, iemand die een fysieke service uitvoert.

Niet elke kapperszaak of loodgieter heeft een eigen agent harness nodig. Maar veel echte bedrijven zijn nog nauwelijks opnieuw uitgevonden met AI in gedachten. De meest voor de hand liggende sectoren zijn inmiddels zichtbaar: juridische dienstverlening, medische technologie, boekhouding. Daar komen data, regelgeving, compliance en terugkerende professionele processen samen.

Juist daarom zou Noronha vandaag waarschijnlijk niet meer beginnen met een juridische AI-agent. Niet omdat de markt onbelangrijk is, maar omdat hij al volloopt. Hetzelfde geldt voor veel voor de hand liggende verticale niches. Wie een harnas voor een installatiebedrijf voor verwarming en airconditioning wil bouwen, moet verder kijken dan het etiket van de sector. De vraag is: welke unieke instrumenten kan ik daar maken of gebruiken die nog niet bestaan?

Dat is voor hem de eenvoudigste ontwerpregel voor een agent harness. Een harnas is een verzameling gereedschappen waarmee een agent een taak uitvoert. Zoek dus naar de gereedschappen die alleen jij hebt, of alleen jij overtuigend kunt bouwen.

Die vraag wordt persoonlijk. Wat weet iemand door zijn leven, zijn omgeving, zijn werkverleden, zijn netwerk? Welke wereld kent hij van binnenuit? De beste oprichters zouden niet alleen moeten vragen welke markt groot is, maar waarin zij zelf ongewoon geloofwaardig zijn.

Dat persoonlijke element wordt nog belangrijker door wat Noronha en veel gebruikers inmiddels het “AI-geurtje” noemen.

Iedereen kent het verschijnsel. Een e-mail klinkt grammaticaal vlekkeloos, maar de afzender gebruikt plotseling woorden die hij normaal nooit zou kiezen. Een afbeelding hangt aan de muur van een café of restaurant en verraadt zichzelf onmiddellijk: de gladde lichtval, de eigenaardige perfectie, de typische compositie van een bekend beeldmodel. Wie de modellen dagelijks gebruikt, herkent de herkomst soms op straat, op grote afstand.

Dat geurtje verspreidt zich sneller dan veel bouwers verwachten. Eerst merkten vooral technici en ontwerpers het. Nu beginnen gewone gebruikers het ook te zien. AI-output kan goedkoop, generiek of onpersoonlijk voelen — zelfs wanneer hij objectief indrukwekkend is.

Gamma werd daar, ironisch genoeg, slachtoffer van zijn eigen succes. In de beginperiode maakte een Gamma-presentatie indruk omdat bijna niemand wist hoe zoiets eruitzag. Maar zodra veel mensen hetzelfde gereedschap gebruikten, begon alles op Gamma te lijken. Gebruikers wilden niet dat hun werk onmiddellijk als AI-werk herkenbaar was.

De grote herlancering van Gamma had daarom een ambitie die verder ging dan betere tekst of snellere dia’s. Het bedrijf wilde zijn creatieve landschap radicaal verbreden. AI zal altijd bepaalde signaturen houden, erkent Noronha. Maar er kunnen duizend verschillende signaturen zijn in plaats van één monolithische stijl.

Hij vergelijkt het met mode. Ook mode heeft een geur. Iemand kan naar een shirt kijken en denken: dat is dat H&M-shirt, ik heb precies hetzelfde. Maar mode beweegt. Wijde jeans worden populair, verdwijnen weer en maken ooit plaats voor skinny jeans. Mensen wisselen stijlen af, merken veranderen hun beeldtaal, smaak verplaatst zich.

Gamma wilde niet één eeuwige smaak opleggen. Het moest een systeem bouwen dat voortdurend nieuwe creatieve richtingen verkent en gebruikers helpt zich aan te passen aan die cycli. Ook dat is een harnas: niet alleen een mechanisme dat werk produceert, maar een systeem dat voorkomt dat alle gebruikers dezelfde visuele uniform dragen.

De vraag is dan onvermijdelijk: kun je smaak testen?

In AI wordt veel gesproken over *evals*, afkorting voor evaluaties. Een eval lijkt op een softwaretest: je formuleert een vaste vraag en kijkt of het systeem het verwachte antwoord geeft. Als een gebruiker zegt: “Maak een presentatie over tijgers”, dan kan Gamma als regel hebben dat de agent eerst moet vragen of die presentatie voor kinderen of volwassenen bedoeld is. Als het model die vraag stelt, scoort het goed op die eval. Als het meteen begint te schrijven, scoort het slecht.

Ontwikkelaars gebruiken duizenden van zulke tests om prompts en modellen te vergelijken. Model B haalt misschien drie procent hogere scores dan model A. Wanneer een laboratorium een nieuw model uitbrengt, pronkt het met benchmarks waarop zijn nieuwste versie vorige generaties verslaat.

Voor objectieve taken zijn evals onmisbaar. Maar creatieve kwaliteit laat zich niet zo makkelijk vastpinnen. “Ziet dit er goed uit?” is geen harde vraag. “Klinkt dit als mij?” nog minder. Een model kan de huisstijlregels perfect volgen en toch iets maken dat doods aanvoelt.

Gamma probeert daarom meetbare tussenstappen te formuleren. Als een gebruiker merkrichtlijnen aanlevert, kan het systeem testen of kleuren, lettertypen en elementen daaraan voldoen. Dat is objectief genoeg. Maar Noronha wil het bedrijf niet reduceren tot wat zich gemakkelijk laat meten.

Daar ziet hij juist ruimte voor oprichters met smaak. Hoe minder verifieerbaar een domein is, hoe meer plaats er overblijft voor een eigen perspectief. Nike zou bijvoorbeeld een ander creatief harnas moeten bouwen dan Adidas, niet omdat de een technisch betere modellen heeft, maar omdat beide merken een andere opvatting hebben over vorm, energie, sport en identiteit.

Gamma bedient een brede gebruikersgroep en kiest daarom vaak voor grootschalige A/B-tests. Twee prompts of twee modellen krijgen ieder een deel van de gebruikers te zien. Vervolgens kijkt het team niet alleen naar wat mensen zeggen, maar naar wat ze doen. Blijven ze hun presentatie bewerken? Delen ze haar? Exporteren ze haar? Investeren ze tijd in het resultaat?

De sterkste graadmeter is uiteindelijk geld. Gamma werkt met een freemiummodel: iedereen kan beginnen zonder te betalen, maar wie meer waarde ervaart, kan upgraden. Betalen is lastig te faken. Iemand kan op een knop klikken uit nieuwsgierigheid, maar wie een abonnement afsluit, geeft meestal een geloofwaardig signaal af dat het product werkelijk helpt.

Daarna volgt retentie: komen mensen een week later terug? Een maand later? Dat duurt langer om te meten, maar het is evenmin makkelijk te vervalsen.

Dat slechts een klein deel van consumenten betaalt voor AI-tools verbaast Noronha niet. Consumenten houden niet van abonnementen. Iedereen probeert wel ergens mee te liften op het Netflix-account van een ander. Werk ligt anders. De SaaS-golf van de afgelopen tien tot vijftien jaar dreef op professionele abonnementen: gereedschappen waarvoor mensen of bedrijven betalen omdat ze er beter, sneller of winstgevender mee kunnen werken.

Daarom richten veel AI-bedrijven zich op de zogenoemde prosumer: de professionele consument. Iemand die niet noodzakelijk een grote onderneming vertegenwoordigt, maar wel serieus werkt en bereid is te betalen voor een tool die hem beter maakt. Daarna wacht de B2B-markt, waar uitgaven en besluitvorming volgens andere regels verlopen.

Wie “de Gamma voor X” wil bouwen, krijgt van Noronha geen kant-en-klaar antwoord. Als hij zelf precies wist welk idee onweerstaanbaar was, zou hij het al bouwen. Het betere advies is ongemakkelijker: bouw voor een wereld die jij begrijpt en hij niet begrijpt. Pokémonkaarten. Sneakers. Mode. Een obscure beroepsgroep. Een hobby waarin anderen slechts ruis zien, maar jij de onuitgesproken problemen kent.

Zelf heeft Noronha wel één productwens die hij morgen zou gebruiken: een echt Slack-harnas.

Slack en Microsoft Teams hebben werk veranderd in een voortdurende vloedgolf van meldingen, threads en half-afgemaakte gesprekken. Bestaande functies kunnen dertig berichten samenvatten tot één alinea. Maar dat is volgens Noronha slechts knabbelen aan de rand. Hij wil een agent die het hele communicatielandschap voor hem beheert. Een agent die leert welke berichten werkelijk aandacht vragen. Een agent die in elke thread waarin hij is genoemd alvast een eerste antwoord klaarzet.

Niet na een lange onboarding met vragenlijsten. Niet nadat hij een persoonlijkheidstest heeft ingevuld. De agent zou hem moeten leren kennen door te observeren.

“Ik heb ongeveer een miljard Slack-berichten verstuurd,” is zijn redenering. “Dat zou alles moeten zijn wat je nodig hebt om te weten hoe ik reageer.”

Ook e-mail voelt nog niet opgelost. Gmail kan wel een voorgesteld antwoord geven als: “Donderdag zou ik graag naar de tandarts gaan.” Maar wie nooit zo zou spreken, ervaart geen hulp. Hij ervaart een imitatie van zichzelf door iemand die hem niet kent.

Daar ligt volgens Noronha een van de moeilijkste, maar waardevolste opgaven voor persoonlijke agents: professionele representatie. Niet enkel tekst produceren, maar iemand authentiek vertegenwoordigen. Gamma raakt aan hetzelfde probleem. Een goede creatieve agent moet niet zomaar mooie dingen maken; hij moet leren welke mooie dingen *voor deze gebruiker* juist zijn.

Dat vereist personalisatie, en personalisatie is moeilijk. Misschien is dat precies waarom het nog niet volledig is gekraakt.

Voor een jonge oprichter die op bestaande modellen bouwt, heeft Noronha een geruststellend standpunt: er is geen schande in het gebruiken van andermans modellen. Gamma wisselde vanaf het begin tussen modellen van Anthropic, OpenAI en Google. De techwereld spreekt graag over een verdedigbare gracht en concludeert dan al snel dat een bedrijf zijn eigen model moet trainen of ten minste diep moet finetunen.

Voor vroege startups is dat vaak fantasie. Zelf modellen trainen kost veel geld. Belangrijker: de bestaande modellen worden voortdurend beter. Waarom zou een klein bedrijf meteen willen concurreren met laboratoria die miljarden investeren in basisonderzoek, chips en infrastructuur?

Eerst komt gebruik. Echte gebruikers verzamelen is de hoofdstrijd. Pas wanneer een bedrijf een substantiële stroom van gebruik heeft, ontstaan er unieke mogelijkheden. Dan kan het fijn afgestelde modellen trainen om kosten te drukken of om personalisatie te verbeteren. Dan kan het gespecialiseerde taken ontdekken waarop de grote modellen slecht presteren.

Gamma kent zo’n taak: de kwaliteitscontrole van een dia. Is deze dia werkelijk goed? Niet alleen grammaticaal correct, maar visueel geslaagd? Op dat gebied leverden de algemene modellen niet altijd de gewenste resultaten. Daarom onderzoekt Gamma eigen modellen voor specifieke kwaliteitschecks.

Dat is een ambitie waar startups naartoe kunnen groeien. Maar het is geen voorwaarde om te beginnen.

Noronha is even duidelijk over open modellen en gesloten modellen die via de cloud worden aangeboden. Open source krijgt veel enthousiasme, maar volgens hem moet je het geld volgen. De grootste investeringen gaan naar de gesloten modellen, omdat die momenteel zeer goed zijn. Ze nemen veel zwaar werk uit handen.

Tegelijk is de concurrentie tussen de grote aanbieders precies wat applicatiebedrijven nodig hebben. Als één laboratorium definitief was weggelopen, zou de situatie gevaarlijker zijn. Maar OpenAI, Google en Anthropic zitten dicht genoeg bij elkaar om elkaar onder druk te houden. Elke paar maanden schuift er iets. Voor een bedrijf als Gamma betekent dat keuzevrijheid en voortdurende verbetering.

De eigen AI-stack van Gamma noemt Noronha daarom breed maar ondiep. Het bedrijf gebruikt veel modellen, vaak op relatief eenvoudige manieren. Niet iedere taak vraagt om een monumentaal redeneermodel. Sommige taken zijn klein: een template kiezen, een outline opstellen, een micro-aanpassing op een dia uitvoeren.

Het echte werk zit volgens hem in context engineering. Niet: hoe schrijf ik één briljante prompt? Maar: hoe verzamel ik de juiste informatie van de gebruiker, hoe structureer ik die, hoe geef ik het model precies genoeg context, en hoe presenteer ik de uitkomst op een manier die voor de gebruiker vanzelfsprekend voelt?

Als je het model zijn werk gemakkelijk maakt, kun je met bijna elk goed model ver komen.

Daarom komt bij Gamma naar schatting achtennegentig procent van de waarde uit prompts en context. Prompting is draaglijk, snel en overdraagbaar. Bovendien schrijft bijna niemand die prompts nog volledig met de hand; Claude kan helpen om prompts voor Claude of andere modellen te formuleren. Veel problemen zijn op te lossen door een prompt op te delen in kleinere stappen.

Finetuning komt later. Het is vooral optimalisatie: kosten verlagen, een paar procent kwaliteit winnen, een specifieke eigenschap consistenter maken.

Wanneer een nieuw model verschijnt, wacht Gamma niet weken op consensus. Als Anthropic of OpenAI iets uitbrengt waarvan Noronha vermoedt dat het relevant is, wordt het vaak binnen een uur getest. De organisatie heeft in haar harnas talloze verschillende banen. Sommige vereisen een frontiermodel, het krachtigste en duurste soort. Andere kunnen draaien op een kleiner, sneller en goedkoper model, zoals een Haiku- of Gemini Flash-variant. Elk nieuw model dat een betere plek op die afweging tussen prijs, snelheid en kwaliteit kan innemen, verdient een proef.

Gamma begint met evals, maar laat het model daarna ook los op een steekproef van echte gebruikers. Dankzij de schaal van het product kan het team binnen een uur een experiment opzetten en twee uur later al eerste gedragsdata zien.

Dat vermogen tot experimenteren komt niet uit de lucht vallen. Voor Gamma werkte Noronha bij Optimizely, een bedrijf dat A/B-testen en personalisatie tot product had gemaakt. Daar groeide zijn liefde voor experimenten.

Bij Gamma lopen er op ieder moment waarschijnlijk tien tot twintig tests. Sommige duren minder dan een dag. Op een ochtend, onderweg in een Uber, zette Noronha acht experimenten klaar omdat de dag ervoor Claude Haiku 5.5 was verschenen. Het team wilde weten of dat model taken kon overnemen die geen frontiermodel vereisten: een template uit een bibliotheek kiezen, een outline schrijven op basis van bronmateriaal, kleine wijzigingen op een dia uitvoeren.

Na het gesprek zou hij de resultaten bekijken en vermoedelijk vier tests direct stopzetten. Niet omdat ze rampzalig waren, maar omdat het systeem voortdurend keuzes maakt. Soms blijkt een model dat de helft kost exact hetzelfde resultaat te leveren. Soms blijkt juist dat alleen het grote, dure model een taak betrouwbaar genoeg uitvoert.

Een van de leerzaamste experimenten ging over snelheid.

Gamma testte een snelle modus die verschillende stappen oversloeg: geen vragen vooraf, geen outline ter controle, minder momenten waarop een gebruiker moest kiezen. De hypothese was overtuigend. Minder frictie zou gebruikers sneller naar het magische moment brengen waarop de presentatie verschijnt.

Noronha hoopte dat het experiment zou winnen.

Dat gebeurde niet.

De kleine vertragingen — de outline bekijken, de verhaallijn kiezen, een paar vragen beantwoorden — bleken waardevolle frictie. Gebruikers die die stappen doorliepen, waren tevredener. Ze voelden zich meer betrokken bij het resultaat, deden er meer mee en betaalden uiteindelijk vaker voor Gamma.

Een test levert zelden slechts ja of nee op. Gamma bracht een versie van de snelle modus wel uit voor nieuwe mobiele gebruikers. Op een telefoon wil niemand lange antwoorden typen voordat er iets gebeurt. De juiste frictie hangt af van de context.

Die les reikt verder dan productontwerp. Ze raakt aan een veranderende rol in marketing.

Vroeger, in het tijdperk van Madison Avenue, draaide marketing om één grote campagne of televisiespot per jaar. In de jaren negentig en tweeduizend ontstond de digitale marketeer, met meer kanalen en meer meetbaarheid. Daarna kwam de growth hacker, die elke week nieuwe experimenten uitvoerde. Vervolgens de AI-ondersteunde marketeer.

De volgende figuur zou de marketing engineer kunnen zijn: iemand die met AI-agents tientallen experimenten per dag runt.

Noronha begrijpt de aantrekkingskracht van die term. Hij klinkt als een tegenstelling, net als “go-to-market engineer” aanvankelijk als een tegenstelling klonk. Marketing en techniek golden lang als afzonderlijke afdelingen. Nu vervagen de grenzen.

Maar hij plaatst er een waarschuwing bij. Bij Optimizely droomde men al van vergaande personalisatie: honderd kleine varianten van een website, elk afgestemd op een andere bezoeker, allemaal geoptimaliseerd op conversie. Die droom is opvallend weinig werkelijkheid geworden. Websites zijn meestal nog altijd grotendeels one-size-fits-all, net als mobiele apps.

De uitzonderingen zijn systemen waarin personalisatie het product zelf is: de TikTok-feed, Instagram Reels, grote oppervlakken waarop bedrijven miljarden uitgeven om iedere extra seconde aandacht en iedere extra euro omzet te optimaliseren.

Gepersonaliseerde prijzen tonen waarom de rest van de wereld terughoudend is. McDonald’s zou experimenteren met zulke prijzen. Maar het idee roept onmiddellijk weerstand op. Als twee mensen hetzelfde vliegticket kopen en de een vijf dollar meer betaalt omdat hij in San Francisco woont, voelt dat niet als intelligente service. Het voelt als onrecht. Zelfs surge pricing bij een rit naar huis kan een nare smaak achterlaten.

In een tijd van hypergeoptimaliseerde performancemarketing kan juist het tegenovergestelde winnen: bedrijven die koppig in hun merk investeren en het beschermen zoals Apple dat doet. Niet ieder contactmoment moet worden uitgeknepen voor conversie.

Toch gelooft Noronha dat de marketing engineer opkomt. De beste versie van die persoon is niet alleen marketeer, maar ook datawetenschapper. Iemand die extreem datagedreven werkt en voortdurend kijkt waar prestaties achterblijven, welke zoektermen kansen bieden, welke advertenties aanslaan, welke creatieve richtingen uitgeput raken.

AI maakt dat bereik groter. “Claude is mijn datawetenschapper,” zegt Noronha in wezen. Mensen in zijn team kunnen zich laten voeden met gedetailleerde analyses van mislukte processen, kansen, verkeersstromen en gedrag. Eén persoon kan SEO, generative-engine optimization, sociale content, betaalde advertenties, creatief werk en merkuitingen tegelijk overzien — niet door alles zelf te maken, maar door een leger van agents aan te sturen.

Zo iemand is geen individuele medewerker meer. Hij is een afdeling.

Gamma ziet die verschuiving bij klanten. Sommige gebruiken het product niet langer voor één presentatie. Ze bouwen automatiseringen. Wanneer in Salesforce een nieuwe verkoopkans ontstaat, kan een proces automatisch een pitchdeck samenstellen op basis van notities uit het verkoopgesprek. Gamma bouwt connectoren voor zulke koppelingen, maar er is nog steeds technische leidingenwerk nodig. Tools als n8n of Zapier verbinden systemen en triggers met elkaar.

Dat werk ligt nu vaak bij specialisten en bureaus. Precies daar ziet Noronha weer ruimte: praktijken die nu alleen de slimste één of twee procent van bedrijven beheersen, omzetten in iets dat voor iedereen toegankelijk wordt.

Hetzelfde geldt voor persoonlijke agents. Er zijn systemen als Muse en Instinct die een laag boven complexere technologie proberen te leggen. Onder de motorkap kun je indrukwekkende dingen doen met OpenClaw of Hermes, mits je een Linux-machine goed instelt en voorkomt dat je wordt gehackt. Noronha sloeg die golf voorlopig over. Hij is druk; hij heeft geen tijd om zelf een Mac mini in te richten als privé-AI-server. Hij wacht liever een paar maanden tot iemand het eenvoudig maakt. Daarna melden de toegankelijke producten zich vanzelf op zijn telefoon.

Hij zegt dat bijna iedereen die deze gereedschappen serieus gebruikt, de afgelopen jaren een reeks versnelde promoties heeft doorgemaakt. Eerst was je een individuele uitvoerder. Toen werd je manager. Daarna directeur. Nu ben je misschien de vicevoorzitter van je eigen kleine agentenorganisatie.

Onder je hangen lagen van digitale medewerkers. Dat klinkt bevrijdend, maar het is ook zwaar. Een leidinggevende krijgt informatie uit alle richtingen, moet voortdurend kiezen, moet begrijpen wat urgent is en wat ruis. Daarom hebben echte leidinggevenden chefs de cabinet, assistenten en teams die de wereld voor hen helpen ordenen.

De gemiddelde persoon heeft straks misschien ook zulke hulpmiddelen nodig: een chief of staff voor zijn eigen leven. De Slack-agent die Noronha mist, is daar een voorproefje van.

Wie daarin goed wil worden, moet een experimenteerspier ontwikkelen. Bij Optimizely leerde Noronha dat het aantal pogingen vaak belangrijker is dan de grootsheid van één poging. Experimenteren is een getallenspel, zoals verkoop, daten en veel andere dingen in het leven. Niet één perfecte test ontsluit ineens een onderneming. Je moet vaak genoeg aan slag komen.

Die spier is trainbaar. Sommige mensen beginnen sterker dan andere, maar wie herhaaldelijk oefent, wordt beter. De eerste test zal waarschijnlijk niet werken. Wie een lichaam wil opbouwen, krijgt ook niet na één dag een zichtbaar resultaat. Eerst komt de routine, dan de vermoeidheid, daarna pas misschien de spier.

Noronha noemt het een dal van verdriet. Veel mensen haken daar af en vertrouwen liever op hun onderbuik. Datzelfde dal bestaat bij sociale media, blogs, koude e-mails en vrijwel elke vorm van zichtbaarheid. Succes vraagt vaak dat iemand erdoorheen zwemt voordat er iets terugkomt.

Ondertussen ziet hij een technologie die juist ondergewaardeerd raakt omdat zij zo gewoon begint te voelen: AI-beeldmodellen.

Dat klinkt bijna als een anticlimax. Sinds Stable Diffusion in 2022 zijn beeldmodellen voortdurend onderwerp van gesprek geweest. Mensen maakten spectaculaire plaatjes, rare fantasiewerelden en virale beelden. Maar juist toen de modellen beter werden en minder vaak gênante fouten maakten, verdween een deel van de opwinding. Ze werden onderdeel van de achtergrond.

Daarmee vergeten veel mensen hoe uitzonderlijk de technologie is geworden.

De meeste gebruikers beperken zich nog altijd tot enkele voorspelbare toepassingen: een menu voor een kleine onderneming, een logo voor het bijproject van hun vader, een snelle illustratie. Gamma werkt met ongeveer tien verschillende beeldmodellen voor uiteenlopende taken en ziet hoeveel onontgonnen mogelijkheden er zijn. Mooie diagrammen en infographics. Texturen voor achtergronden. Eigen iconen. Beelden die niet alleen decoratie zijn, maar informatie dragen.

Bijna elk creatief domein kan volgens Noronha opnieuw bekeken worden met die mogelijkheden in gedachten. Kleding. Woondecoratie. Productontwerp. Interieur.

Een bank kopen is een goed voorbeeld. De huidige modellen kunnen overtuigend laten zien hoe een bank in iemands woonkamer zou ogen. Maar uiterlijk is niet genoeg. Het verschil tussen een bank van 58 inch en een van 68 inch kan beslissend zijn wanneer een muur een bepaalde lengte heeft. Een goede toepassing zou de bank niet alleen in de kamer kunnen plaatsen, maar ook de afmetingen zichtbaar en betrouwbaar maken.

Dat is opnieuw een harnasprobleem. Een model kan de bank in de ruimte renderen. Traditionele software kan daarna een lijn over de afbeelding trekken, pixels meten en controleren of de schaal klopt. Als de afmeting niet klopt, kan het model opnieuw worden aangestuurd.

De grote modellaboratoria zullen zo’n specifieke ervaring vermoedelijk niet snel bouwen. Hun doel is een algemeen systeem. Een verticaal product kan veel dieper gaan. Het kan bovendien zeggen: deze bank past niet goed bij jouw ruimte; hier is een alternatief van Restoration Hardware dat beter past, en dit zijn de redenen.

Wie ooit online naar een bank zocht, kent de frustratie. Honderden websites, kleine knopjes, eindeloze productpagina’s, uiteindelijk Google Shopping als toevluchtsoord. De consumentervaring is niet ontworpen als een goed begeleid besluit.

Er zijn al producten die in die richting bewegen, maar volgens Noronha blijft er ruimte, juist naarmate beeldmodellen beter worden en het idee van een harnas volwassener. De economie helpt ook. Een bank is een aankoop met hoge waarde en marge. Een platform dat de juiste klant naar de juiste retailer brengt, zou mogelijk commissie kunnen ontvangen.

Maar de duurzamere kans ligt vaak nog hoger in de waardeketen. De consument wil hulp bij één bank. De prosumer is een parttime-interieurontwerper met twee kinderen, die per uur werkt en betere tools wil om klanten te helpen. De professional werkt bij een meubelketen of een architectenbureau en heeft systemen nodig die meer kunnen dan een losse ChatGPT-chat.

Voor die gebruikers is een abonnement logisch, omdat het gereedschap direct hun werk verbetert. En daar, bij de beste professionals en grotere organisaties, kunnen duurzame bedrijven ontstaan.

Het idee dat verticale SaaS of verticale AI nauwelijks nog kansen biedt, vindt Noronha daarom misleidend. De wereld is te groot. Gamma zelf bewijst dat. Veel mensen maken presentaties, maar zij doen dat om volstrekt verschillende redenen. Minder dan een kwart van Gamma’s omzet komt uit de Verenigde Staten. De gebruikers zijn consultants, docenten, marketeers, verkopers, juristen en vele anderen.

Ook juristen maken presentaties, zo bleek.

Een groot bedrijf is in zekere zin duizend kleine niches die op elkaar zijn gestapeld. Je hoeft niet breed te beginnen. Begin met één groep die je begrijpt. Zoek daarna aangrenzende groepen. Misschien ontdek je dat juristen een onverwacht groot deel van je gebruikers vormen. Misschien ontstaat daaruit een specifieke toepassing die op haar beurt een grote bedrijfstak wordt.

Dat kun je niet volledig bedenken achter een bureau. Je moet iets uitbrengen.

Experimenteren betekent niet alleen een A/B-test draaien met tienduizend mensen in elke groep. Het kan ook een landingspagina zijn, een eerste prototype, een product dat iemand één middag kan proberen. Nog nooit was het zo eenvoudig om iets in handen van echte gebruikers te leggen.

Als Noronha Gamma ooit zou verlaten, zou hij waarschijnlijk opnieuw dichtbij creativiteit blijven. Hij is gefascineerd door wat na vibe coding komt. Eerder dat jaar gebeurde het telkens weer wanneer hij een vriend sprak die hij een paar maanden niet had gezien. Wat ben je aan het doen? Het antwoord luidde dan: kijk eens naar de app die ik heb gemaakt.

Als mensen bijna alles kunnen maken, wat gaan ze dan maken?

Video wordt een voor de hand liggende grens. Beeldmodellen worden beter, stemmodellen worden beter, en generatieve video nadert mogelijk haar eigen vibe-codingmoment. De interessante vraag is niet alleen welke video’s technisch mogelijk worden. Het is welke soorten video’s mensen gaan maken wanneer productie niet langer het voorrecht is van studio’s met budgetten en crews.

Games trekken hem ook. De videogame-industrie lijkt rijp voor verstoring, al zegt hij eerlijk dat hij nog niet heeft uitgevonden hoe die verstoring er precies uit moet zien.

Maar zelfs daar keert hij terug naar hetzelfde punt. De modellen worden krachtiger. De grondstoffen worden overvloediger. De blijvende vraag is welk harnas iemand eromheen bouwt.

Aan het eind blijft Noronha niet hangen bij modellen, benchmarks of marktkansen. Hij komt terug bij een hardere, menselijkere waarheid over ondernemerschap. Een bedrijf beginnen is lang en soms eenzaam. Daarom moet een oprichter houden van het probleem waaraan hij werkt.

Voordat Gamma begon, had hij een regel: het moest iets zijn dat hij zelf wilde gebruiken. Iets dat hij kon *dogfooden* — niet als abstracte klant, maar als oprechte dagelijkse gebruiker. Hij moest erin geloven en bereid zijn er uren per dag mee door te brengen.

Dat sluit veel saaie bedrijven uit. Maar voor hem was het goed voor de ziel.

De juiste vraag is niet alleen: waar zit geld? De vraag is: waar wil ik acht uur per dag aan besteden terwijl mijn vrienden dat niet willen? Welk onderwerp ken ik zo goed dat het voor anderen niche lijkt, maar voor mij een bron van aanhoudende nieuwsgierigheid is?

Daar ligt een bruikbare ondernemersregel: trouw met de niche, date met het product.

Een product zal veranderen. In een tijd van snelle iteratie kan het over een jaar nauwelijks lijken op de eerste versie. Wie verliefd wordt op één specifieke feature, raakt gemakkelijk verdwaald wanneer de markt een andere richting op duwt. Maar wie houdt van de mensen die hij probeert te dienen, kan blijven leren. Hij kan media maken voor die gemeenschap, een publiek opbouwen, nieuwe producten proberen en telkens terugkeren naar hetzelfde begrip van hun problemen.

Jeff Bezos formuleerde ooit een verwante gedachte: wees koppig op de visie en flexibel in de details.

Dat is ook de kern van het harnas. Niet een dun laagje rond een model, maar een manier om algemene intelligentie vast te maken aan een specifieke wereld. Aan echte gebruikers, eigen smaak, onhandige processen, bijzondere gereedschappen en menselijke voorkeuren. De modellen zullen blijven wisselen. De kosten zullen dalen. De benchmarks zullen stijgen.

Maar ergens tussen een rommelige pdf en een overtuigende presentatie, tussen een Slack-thread en een antwoord dat werkelijk als jij klinkt, tussen een bank op een website en een bank die precies in je woonkamer past, ligt nog altijd het werk dat niemand anders voor je heeft ontworpen.