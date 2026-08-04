<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01KZ49YPG8TF96B0HGF8DJW1HR
-->

# De Architecten van het Denkwerk

*Er verschijnt elke paar weken een nieuw begrip in de AI-wereld dat iedereen het gevoel geeft achter te lopen. Maar soms—niet altijd, maar soms—is zo'n term de moeite waard. Graph engineering is zo'n term. Het geeft je een fundamenteel andere manier om naar AI-werk te kijken: niet als een gesprek, maar als een ontwerp.*

---

Het patroon is inmiddels vertrouwd. Elke paar weken duikt er een nieuwe term op in de AI-wereld die als een lopend vuurtje door Twitter gaat. Prompt engineering. Context engineering. Vibe coding. Loop engineering. En nu: graph engineering.

Greg Eisenberg zag de term voor het eerst en voelde de bekende twijfel opkomen. Is dit iets echts, of hebben we zojuist weer een frase bedacht om iedereen het gevoel te geven dat ze iets missen? Want sommige van die termen zijn inderdaad grotendeels lucht—labels op luchtbellen. De eerlijke waarheid is dat de meeste ervan niet overleven. Maar graph engineering is anders. Het lost een probleem op dat iedereen heeft die AI serieus gebruikt, alleen had niemand er tot voor kort een naam voor.

Of toch? Die twijfel verdient een eerlijk antwoord—en dat antwoord begint met het begrijpen waar het alternatief tekortschiet.

Stel je voor dat je een nieuw startup-idee onderzoekt. De normale aanpak is simpel: je opent een chatvenster en je typt: *moet ik dit idee bouwen?* Het antwoord klinkt doordacht. Het model geeft je marktgrootte, een paar concurrenten, misschien een go-to-market strategie. Je leunt achterover en je hebt het gevoel dat je goed onderzoek hebt gedaan.

Maar als je even stilstaat, voel je een lichte ongemakkelijkheid. Één model heeft in één doorgang bepaald wat belangrijk was, de markt onderzocht, het bewijs geïnterpreteerd, de aanbeveling geschreven, én zijn eigen zekerheid beoordeeld. Dat is een hoop vertrouwen om in één blob tekst te stoppen. Zeker als je bedenkt dat mensen soms jaren van hun leven bouwen op basis van de uitkomst van zo'n vraag.

De graph-versie ziet er wezenlijk anders uit. Een planner breekt de vraag eerst op in afzonderlijke hoeken. Één onderzoeker kijkt naar de klant. Een andere naar concurrenten. Een derde naar distributie. Een vierde naar prijsstelling. Dan komt een scepticus die de zwakke bevindingen probeert te ontmantelen. Dan een merger die het overgebleven bewijs omzet in een eenpagina-aanbeveling. En daarna—pas daarna—keurt de mens de beslissing goed voordat er gehandeld wordt.

De uitkomst is nog steeds een geschreven rapport. Maar het werk erachter is fundamenteel anders ontworpen. Dat, in zijn kern, is graph engineering.

---

**Jobs, pijlen, en gedeeld geheugen**

Hier zat Eisenberg even met een glimlach bij stil. Want graph theory—hij kende het. Hij studeerde het in een van zijn eerste universitaire colleges, lang voordat iemand het woord AI in de mond nam. Een terugkeer naar de schoolbanken, maar dan plotseling bruikbaar op een manier die hij toen nooit had voorzien.

De basisvocabulaire klinkt technisch voor precies vijf seconden, en dan realiseer je je dat het gewoon beschrijft hoe werk in de echte wereld gedaan wordt.

Een graph bestaat uit drie elementen. *Jobs* zijn de stappen in het proces—de afzonderlijke taken. *Pijlen* laten zien wat er daarna gebeurt, hoe taken van elkaar afhangen. En *state* is het gedeelde geheugen: alles wat het systeem tot nu toe weet, de notities die van de ene stap naar de volgende meereizen.

Denk aan klantenservice. Wanneer een klant een bericht stuurt, is de echte workflow nooit simpelweg *beantwoord het ticket*. Eerst moet je begrijpen wat voor soort probleem het is. Dan controleer je de accountgeschiedenis. Misschien doorzoek je de documentatie voor het juiste beleid. Dan stel je een antwoord op. Dan besluit je of het risicovol genoeg is dat een mens het moet nakijken voordat het verstuurd wordt. Als je die stappen tekent en ze verbindt in de volgorde waarop ze van elkaar afhangen, heb je een graph.

Of neem contentcreatie. Een goede aflevering begint met onderzoek, een these, voorbeelden, een haak, een script, titelideeën, thumbnailrichtingen, en ten slotte een laatste check: klinkt dit als een mens, of klinkt dit als iemand die vastzit in de onboardingflow van een SaaS-product? Sommige van die stappen moeten in volgorde. Maar andere kunnen tegelijkertijd. Één onderzoeker zoekt voorbeelden terwijl een andere tegenargumenten verzamelt. Die uitkomsten vloeien daarna samen in het script.

En dat is precies waar de graph zijn waarde bewijst. De meeste mensen gebruiken AI in een rechte lijn—omdat chat alles sequentieel laat voelen. Voor simpele taken werkt dat. Maar zodra het werk meerdere lagen heeft, wordt die rechte lijn traag, wazig, en moeilijk te vertrouwen.

Een graph laat je het werk ontwerpen als een klein team. Eén deel plant. Een paar delen werken parallel. Een ander controleert. Een volgend deel voegt samen. De mens keurt de laatste stap goed. Zodra die gedachte is ingesleten, wordt het allemaal een stuk minder mysterieus.

---

**Twee soorten graphs—en waarom het onderscheid ertoe doet**

Hier keert de oorspronkelijke twijfel terug in een andere gedaante: want wie de term *graph engineering* serieus bestudeert, stoot al snel op een verwarring die bijna iedereen maakt. Wanneer mensen in de AI-wereld over graphs spreken, bedoelen ze soms twee fundamenteel verschillende dingen. En als je dat niet begrijpt, kan het hele concept eerder als hype aanvoelen dan als gereedschap.

De eerste is de *knowledge graph*. Die helpt AI redeneren over relaties tussen informatie. Deze klant werkt bij dit bedrijf. Dit bedrijf gebruikt dit product. Dit product hangt samen met dit ondersteuningsprobleem. Gewone AI-zoekopdrachten—waarbij het systeem tekstfragmenten ophaalt die lijken op de vraag—worstelen soms wanneer het antwoord het verbinden van informatie vereist over mensen, bedrijven en gebeurtenissen heen. Knowledge graphs pakken dat aan. Microsoft's GraphRAG is een voorbeeld: AI helpen relaties te begrijpen binnen een kennisbasis, niet alleen de dichtstbijzijnde alinea ophalen.

De tweede is de *agent graph*. Die gaat over hoe werk beweegt. Een planner geeft werk door aan onderzoekers. De onderzoekers werken parallel. Een scepticus controleert de bevindingen. Een synthesizer voegt de delen samen. Een mens keurt het eindresultaat goed.

De kortste manier om het verschil te onthouden: knowledge graphs helpen AI begrijpen hoe informatie samenhangt. Agent graphs helpen AI begrijpen hoe werk moet bewegen. De beste systemen gebruiken uiteindelijk allebei. Maar als je vandaag begint als oprichter, creator, of operator, is de agent graph het deel dat je direct kunt toepassen.

En daarmee keert de vraag waarmee dit begon terug—is dit echte of hype?—en krijgt eindelijk een definitief antwoord: het is echt. Maar alleen als je begrijpt welke graph je bedoelt, en hoe je hem bouwt.

---

**Het diamantpatroon: een volledig voorbeeld**

De eenvoudigste graph-structuur die de meeste taken goed bedient is het diamantpatroon. Je begint met één vraag, splitst die op in meerdere parallelle paden, controleert het werk, en voegt alles samen in één antwoord.

Neem een concreet geval: *moet ik een AI-boekhoudproduct lanceren voor Shopify-merchants?*

De chat-versie is één grote vraag met één groot antwoord. De graph-versie begint met een planner. Die zegt: om dit goed te beantwoorden, hebben we inzicht nodig in de klantpijn, het competitieve landschap, de distributiemogelijkheden, de prijsdruk, en de risico's. Dan splitst het werk.

Eén onderzoeker bestudeert Shopify-merchants en hun boekhoudpijn. Gebruiken ze QuickBooks? Spreadsheets? Huren ze een boekhouder in? Zijn ze gefrustreerd tijdens belastingseizoen? Een tweede onderzoeker kijkt naar concurrenten. Bestaan er al Shopify-boekhoudtools? Lossen freelancers op Upwork of Fiverr dit op op een manier die software deels zou kunnen overnemen? Een derde bestudeert distributie. Waar hangen Shopify-merchants eigenlijk? Welke nieuwsbrieven lezen ze? Welke zoektermen onthullen koopintentie?

Die drie onderzoeken kunnen tegelijkertijd plaatsvinden, want ze zijn niet van elkaar afhankelijk. Dan komt de scepticus.

De scepticus stelt de harde vragen. Welke claims worden echt ondersteund door bewijs? Welke data is verouderd? Waar verwarren we pijn met betalingsbereidheid? Waar klonk de AI zelfverzekerd zonder iets te bewijzen?

Dit is de stap die mensen het vaakst overslaan, en het is de stap die er het meest toe doet. Het fundamentele probleem met de meeste AI-onderzoeken is dat hetzelfde model dat het antwoord schrijft ook de beoordeling schrijft. In de woorden van Eisenberg: *"That is like asking someone to write their own performance review and then being shocked when they describe themselves as a visionary."* Een goed ontworpen graph behandelt controleren als een aparte functie—juist omdat geen enkel systeem zijn eigen werk betrouwbaar kan beoordelen.

Dan komt de merge. Die stap neemt het overgebleven bewijs en vertaalt het naar een aanbeveling. Gaan we dit verkennen? Pauzeren? Stoppen? Wat is de opening? Wie is de eerste klant? Wat testen we deze week? En welk bewijs zou ons van gedachten doen veranderen?

En ten slotte de menselijke gate. Jij beslist wat er daarna gebeurt. Misschien ga je tien Shopify-agencyeigenaren interviewen. Misschien bouw je een simpele calculator die de kosten van boekhoudopruiming schat. Misschien besluit je dat het idee te druk is en ga je verder. Dat is het punt. Graph engineering maakt de beslissing niet voor je. Het geeft je een betere manier om het bewijs te produceren waarmee jij die beslissing maakt.

---

**Drie niveaus van implementatie**

Hier is de grootste valkuil voor mensen die graph engineering ontdekken: ze willen meteen beginnen met LangGraph, Autogen, of een ander custom framework. Dat is de verkeerde volgorde.

Begin met level één: handmatig. Geef elke job zijn eigen laan. Één laan doet klantonderzoek. Een andere doet concurrentieonderzoek. Een derde doet distributieonderzoek. De controllaan valt de bevindingen aan. De mergelaan zet het overgebleven bewijs om in een aanbeveling. Dat is al graph engineering—alleen langzamer. En als de handmatige versie niet aantoonbaar beter werk oplevert, zal het automatiseren ervan alleen maar sneller middelmatig werk produceren.

Teken de graph voordat je hem automatiseert. Een leeg Excalidraw-bord is genoeg. Schrijf de einduitkomst bovenaan. Teken de jobs: planner, klantonderzoeker, concurrentieonderzoeker, distributieonderzoeker, scepticus, merge, menselijke goedkeuring. Teken de pijlen. Dat is genoeg.

Level twee is een codebase waar elke stap bestanden schrijft. De planner schrijft `plan.md`. De onderzoekers schrijven `klant.md`, `concurrenten.md`, en `distributie.md`. De scepticus schrijft `review.md`. De merge schrijft `aanbeveling.md`. Dat laat een papieren spoor achter. Je kunt zien wat er is gebeurd. Je kunt versies vergelijken. Je kunt de structuur de week daarna opnieuw gebruiken.

Level drie is pas automatisering: LangGraph, Autogen, N8N, Make.com, of je eigen scripts. LangGraph is nuttig wanneer je state-checkpoints wilt, persistentie, menselijke goedkeuring middenin het proces, en betrouwbare controle over hoe een agent-workflow loopt. N8N en Make.com zijn nuttig wanneer de graph alledaagse bedrijfssystemen raakt—Slack, e-mail, Airtable, je CRM. De tool is niet het punt. De tool komt na de workflow. Als je een workflow automatiseert die je niet begrijpt, krijg je een goed geautomatiseerde puinhoop.

---

**Drie graphs die meteen werken**

Klantenservice is het meest voor de hand liggende startpunt. Een goede supportgraph begint met classificeren: is het een factureringsprobleem, productverwarring, een bug, een risico op opzegging? Dan controleert het systeem de accountcontext: is het een nieuwe klant, een hoogwaardige gebruiker, iemand die al eerder heeft geschreven? Dan doorzoekt het de documentatie of het interne beleid. Dan stelt het een antwoord op. Dan keurt een mens alles goed wat terugbetalingen, accountwijzigingen, gefrustreerde klanten, juridisch risico, of toezeggingen omvat die je later kunt betreuren. Dat is beter dan zeggen: AI, beantwoord het ticket—want het ticket is niet de echte workflow.

Contentcreatie is het tweede model. Begin met onderzoek, dan de these, dan voorbeelden, dan de haak, dan het script. En dan—cruciaal—een checker die vraagt of de voorbeelden specifiek zijn, of het ritme klopt, en of de tekst klinkt als een mens. Of, in de formulering die Eisenberg zelf gebruikt: *"does this sound like a human being or does this sound like someone trapped inside a SaaS onboarding flow?"* Die vraag, gesteld als aparte stap in de graph, is het verschil tussen content die voelt als contact en content die aanvoelt als documentatie.

Het derde model is code. Een codinggraph begint met een plan, dan bewerkt één agent de code, een andere reviewt de diff, een derde draait de tests, een vierde controleert de interface in de browser, een vijfde kijkt naar randgevallen, en dan keurt de mens het pull request goed. De modellen die code schrijven zijn slechts één onderdeel van de workflow. De echte leverage zit in al het plannen, testen, reviewen, inspecteren, en beslissen wat veilig is om te deployen.

---

**De ene valkuil die alles verpest**

Er is één misvatting die mensen steeds opnieuw maakt: meer agents betekent automatisch betere output. Dat klopt niet. Soms betekent meer agents meer ruis. Soms besteedt het systeem meer tijd aan coördineren dan aan denken. Soms herhalen vijf AI-werkers vol vertrouwen hetzelfde verkeerde idee.

Het doel is niet de grootste graph mogelijk. Het doel is de kleinste graph die de kwaliteit van het werk verhoogt. Dat is een wezenlijk verschil.

Een goede graph verwijdert nep-wachttijd. Hij scheidt werkers van checkers. Hij plaatst menselijke goedkeuring waar fouten duur zijn. Hij stopt wanneer het antwoord goed genoeg is. En hij laat het nuttige geheugen achter: de notities, het bewijs, de concepten, de bronnen, de beslissing—zodat je ze later kunt gebruiken.

Dat laatste punt is onderschat. De echte samengestelde waarde van graph engineering is niet alleen dat één taak beter wordt. Het is dat je werk geheugen begint te produceren. Elk klantonderzoek levert betere klantnotities op. Elke contentgraph levert betere voorbeelden en publieks-inzichten op. Elke supportgraph levert betere productfeedback op. De graph produceert het werk—maar hij produceert ook het geheugen dat de volgende graph slimmer maakt.

---

**Hoe te beginnen**

Kies één workflow die je al elke week met AI uitvoert. Misschien is het ideeënonderzoek, het voorbereiden van vergaderingen, het reviewen van landingspagina's, het analyseren van klantfeedback. Schrijf de einduitkomst in één zin. Beschrijf dan de jobs die een goede medewerker zou doen. Teken pijlen waar het ene werk echt van het andere afhangt. Identificeer de stappen die tegelijkertijd kunnen. Voeg één menselijke gate toe vóór de dure beslissing. En voer het dan één keer handmatig uit.

Na die eerste doorgang begint er iets te verschuiven in hoe je AI-werk bekijkt. Je stopt met denken: wat is de perfecte prompt voor deze taak? Je begint te denken: wat is de perfecte workflow? Je begint een pad te ontwerpen dat het antwoord produceert in plaats van te hopen dat één vraag het goed doet.

De mensen die het meest uit AI halen, zijn niet degenen met de perfectste prompts. Het zijn de mensen die weten hoe ze werk kunnen opsplitsen in de juiste stukken, elk stuk de juiste context geven, de uitkomst controleren, en zichzelf op de juiste plek in het proces houden. Op dat moment doe je iets wezenlijk anders dan typen in een chatvenster.

Je geeft geen prompts meer aan een AI. Je beheert AI-werk.