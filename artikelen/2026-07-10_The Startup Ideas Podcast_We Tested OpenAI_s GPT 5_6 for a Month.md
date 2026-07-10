<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01KWHY0CH7FAWF1655A23J4A8G
-->

# Piraten en Architecten: Hoe één man zijn hele werkende leven overdroeg aan een machine

*In de zomer van 2026 zat Dan Shipper een maand lang vrijwel permanent in één applicatie. Geen browser, geen inbox, geen aparte tools—alles liep via OpenAI's Codex Desktop met het nieuwe 5.6-model. Wat hij ontdekte, was geen productiviteitshack. Het was iets fundamentelers: een nieuw soort betrekking tussen mens en machine, waarbij de machine niet langer assistent is maar medewerker, mede-eigenaar van de agenda, en stille architect van het dagelijks werk. Dit is het verhaal van hoe dat eruitziet, waarom het werkt, en wat het betekent voor iedereen die software bouwt of gebruikt.*

---

Op een doordeweekse ochtend opent Dan Shipper zijn laptop. Geen e-mailclient, geen Slack, geen Notion. Hij opent Codex.

Het eerste dat hij ziet is geen leeg tekstvak of een flikkerende cursor, maar een reeks kaarten. Elke kaart vertegenwoordigt een ongelezen e-mail uit zijn inbox—samengevat, geannoteerd, klaargemaakt voor actie. Eén e-mail gaat over een domeinnaam die ergens op Namecheap staat en overgedragen moet worden. De kaart toont al een conceptreactie. Shipper leest hem, typt één correctie—"kun je ook wat latere tijden deze week zoeken?"—en is verder. Volgende kaart.

Het is, zegt hij zelf, precies zoals rijke zakenlieden in de jaren zestig hun correspondentie afhandelden. Een secretaresse die de post sorteerde, samenvatte, conceptbrieven schreef. Het verschil is dat nu iedereen het kan. En dat de secretaresse ook je Slack leest, je vergadernotities verwerkt, je bedrijfspuls bijhoudt, en tegelijkertijd op Facebook Marketplace zoekt naar meubels voor de nieuwe flat.

Shipper is de oprichter van Every, een mediabedrijf dat schrijft over de toekomst van werk en technologie. Hij is niet de typische vroege adopter die alles uitprobeert en nergens bij blijft. Hij is iemand die systemen bouwt, verfijnt, en uiteindelijk publiceert—zodat anderen zijn werk kunnen leren. Toen OpenAI's Codex Desktop uitkwam met het 5.6-model, begon hij te experimenteren. Een maand later was hij niet meer gestopt.

---

Om te begrijpen wat Codex is, moet je eerst weten wat het niet is.

Codex CLI—de command-line versie die eerder verscheen—was volgens Shipper "rommel." Te technisch, te gefragmenteerd, te ver verwijderd van hoe mensen daadwerkelijk werken. Je typt commando's in een zwart scherm, het model voert iets uit, en de verbinding met je dagelijkse werk voelt onnatuurlijk, alsof je een formulier invult terwijl je eigenlijk een gesprek wil voeren.

De Codex Desktop die daarna volgde was OpenAI's antwoord op een vraag die Anthropic al gedeeltelijk had beantwoord: hoe geef je een AI-agent een thuis op je computer? Anthropic had met Claude Code en de bijbehorende desktopapp laten zien dat het nieuwe paradigma—een agent die meekijkt op je scherm, bestanden opent, code schrijft, en taken uitvoert terwijl jij nadenkt—werkte. Maar de Claude-desktopapp had drie modi: chat, code, en coworking. Drie ingangen voor hetzelfde systeem. Welke kies je? Wanneer? Die vraag bleek verrassend verlammend in de praktijk.

OpenAI keek toe, leerde, en bouwde vervolgens wat Shipper omschrijft als de ideale implementatie: twee tabbladen, een schone interface, en een in-app browser die het hart vormt van het systeem. "OpenAI heeft door alle rommel heen gespoed en gebouwd wat ze dachten dat de ideale implementatie was," zegt Shipper. "Anthropic heeft op dit moment het mandaat van de hemel. En OpenAI is enorm onderschat. Codex is de reden waarom."

Die in-app browser is cruciaal. Het is de plek waar mens en machine samenkomen op hetzelfde oppervlak. Stel je voor: Shipper heeft een markdown-editor gebouwd die hij Proof noemt. Hij opent hem in de Codex-browser, plant zijn dag, schrijft ideeën op. Tegelijkertijd kan hij Codex vragen om onderzoek te doen, agenda's samen te stellen, context toe te voegen. De agent werkt in dezelfde omgeving als de gebruiker—hij ziet wat jij ziet, klikt waar jij klikt, begrijpt wat er op het scherm staat.

"Het model is alleen zo krachtig als de context die je het geeft," legt Shipper uit. "Dit ding is verbonden met je hele computer en het hele internet. Dat maakt een enorm verschil."

Dan is er de motor achter dat alles: het 5.6-model. Shipper beschrijft het als een Porsche. Geen tactische kernbom—dat is Fable, het zwaarste model van Anthropic. Fable is zo krachtig dat het bijna onhandelbaar is. "Met Fable waren we letterlijk onze hele bugbacklog leeg aan het werken," zegt Shipper. "Je kon het gewoon loslaten en het was leeg, zolang je bereid was het geld te betalen." Maar Fable is zo traag en duur dat het in de praktijk alleen zinvol is voor mensen die vloten van agents orkestreren of machine learning-pijplijnen draaien. Voor de rest van de wereld is het een Ferrari die je niet van de parkeerplaats af durft te rijden.

Vijf-zes is anders. Sneller, toegankelijker, en goed genoeg voor vrijwel alles wat je elke dag wilt doen. "Je gaat er geen NSA mee hacken," zegt Shipper, "maar het rijdt goed, het handelt goed, het gaat snel. Voor samenwerking is het geweldig." Hij typeert het als een A-model, niet S-plus zoals Fable, maar voor negentig procent van het dagelijks werk maakt dat verschil niet uit. "Met vijf-zes moet je soms nog nadenken om bugs te fixen. Maar het werkt voor alles wat je elke dag wilt doen. Het is gewoon waar ik al mijn tijd doorbreng."

---

Het systeem dat Shipper heeft gebouwd rond Codex bestaat uit drie lagen.

De eerste laag is wat hij *pulses* noemt—geautomatiseerde feeds die meerdere keren per dag worden bijgewerkt. Een pulse voor zijn inbox. Een pulse voor zijn bedrijf. Beide doen hetzelfde: ze doorzoeken een databron—e-mails, Slack-berichten, vergadernotities—en zetten alles om in kaarten met een duidelijke volgende actie.

De inbox-pulse werkt via een app die hij Tend heeft gebouwd. Voor elke ongelezen e-mail verschijnt er een kaart met een samenvatting en een conceptreactie. Shipper scrollt erdoorheen zoals iemand door een nieuwsfeed scrolt, maar dan met consequenties. Hij keurt goed, past aan, archiveert. In minuten is zijn inbox verwerkt. Tend komt beschikbaar als open-source bibliotheek, maar Shipper is ook de eerste om te zeggen dat je het niet nodig hebt: geef dit gesprek aan Codex, vraag het iets vergelijkbaars te bouwen, en het doet het. Kieran Classen—die ook de e-mailapp Quora leidt, een volwaardige inboxervaring ontworpen voor gebruik binnen Codex—heeft een groot deel van deze infrastructuur mede mogelijk gemaakt.

De bedrijfspulse werkt anders. Die kijkt niet naar zijn e-mail, maar naar de Slack-berichten en vergadernotities die hij gemist heeft. "Het geeft me een beeld van de problemen die in mijn bedrijf spelen," zegt Shipper. "Ik besluit of het iets is waar ik me mee wil bemoeien. Als dat zo is, ping ik iemand. Zo niet, dan archiveer ik het." Maar er zit een dieper mechanisme onder. Elke keer dat Shipper een kaart archiveert, een reactie goedkeurt, of een onderwerp als relevant markeert, leert het systeem. Na een sessie compileert het de patronen—wat hij belangrijk vond, wat hij negeerde, welke reacties hij accepteerde en welke hij herschreef—en past zijn eigen prompts aan. De volgende ochtend weet het systeem iets beter wat zijn aandacht verdient dan de ochtend ervoor.

De tweede laag is Mailroom. Dit is een van de slimste onderdelen van zijn opzet, en ook het meest onderschatte. Codex heeft een eigen e-mailadres gekregen, dat via het plus-formaat in Gmail werkt—een geheime variant van zijn adres die hij uitdeelt aan agents in zijn systeem. Dat plus-formaat is een Gmail-truc waarbij je een plus-teken en een willekeurige string achter je gebruikersnaam plaatst. Berichten komen dan gewoon aan in je inbox, maar zijn te filteren en door te sturen. In Shippers geval stuurt het adres berichten direct naar zijn Codex.

Een interne Slack-agent in zijn bedrijf weet dat hij operationele vragen niet aan Shipper zelf moet stellen, maar aan zijn Codex-adres. De machine stuurt de machine een e-mail. Codex vangt die op, analyseert hem, en handelt af. Shipper ziet het resultaat—als het resultaat relevant is. "Gewoon je Codex verbinden met een e-mailadres is extreem krachtig en enorm onderschat," zegt hij.

De derde laag is de routerthread. Wanneer er iets binnenkomt—een e-mail, een Slack-bericht, een notificatie—beslist de router waar het naartoe moet. Gaat het naar de inbox-pulse? Naar de bedrijfspulse? Wordt het genegeerd? Shipper noemt ook het concept van *heartbeats*: threads die niet reageren op binnenkomende informatie, maar die op vaste tijdstippen vanzelf wakker worden, een taak uitvoeren, en dan weer slapengaan. Samen vormen routers en heartbeats de ruggegraat van zijn systeem. De router is de dirigent, en hij werkt op basis van regels die Shipper zelf heeft geschreven en die de machine ondertussen heeft verfijnd.

Samen vormen deze drie lagen iets dat Shipper een besturingssysteem noemt—niet metaforisch, maar letterlijk. Alles loopt er doorheen. Hij werkt er de hele dag in.

---

Maar Codex is niet alleen voor het beheren van bestaand werk. Het bouwt ook.

Op de dag dat Shipper zijn scherm deelt, begint hij aan een experiment. Hij wil een idee uitwerken dat al een tijdje in zijn hoofd ronddraait: een kleine SaaS-applicatie voor het AI-tijdperk, gericht op een probleem dat hij scherp heeft zien worden.

Het probleem is dit: in 2026 kan vrijwel iedereen in één prompt een eerste versie van een app bouwen. Wat voorheen maanden kostte—een werkend prototype, een landingspagina, een basis backend—duurt nu minuten. Maar dat heeft een bijwerking gecreëerd. Het internet stroomt vol met "one-shotted" software: apps die één keer zijn gegenereerd en daarna nooit meer zijn aangeraakt. Geen bugfixes, geen updates, geen onderhoud. Ze bestaan, maar ze leven niet.

"De waarde van SaaS zit niet in het bouwen van de eerste versie," zegt Shipper. "Het zit in het onderhoud. Dat is het schaarse ding geworden."

Zijn idee heet Turnaround. Een badge die je op je website kunt plaatsen—op je over-pagina, naast je prijzen—die laat zien dat jouw app actief wordt bijgehouden. Het aantal commits in de afgelopen dertig dagen. De gemiddelde tijd tussen een bugreport en een fix. Een levend signaal dat er een mens achter de machine zit die er echt mee bezig is.

Vergelijkbaar met wat GitHub al laat zien voor open-source projecten, maar dan voor elke SaaS-app op het internet. Zichtbaar voor klanten, niet alleen voor ontwikkelaars. Mooi vormgegeven. Gekoppeld aan elke databron—GitHub, Linear, Notion—afhankelijk van wat het team gebruikt.

Hij typt de opdracht in Codex, maar niet zonder hulp. Hij gebruikt twee plugins: LFG en Goal. LFG is gebouwd door Kieran Classen en is een zogenaamde compound engineering-plugin—een plugin die door de volledige cyclus loopt: plannen, uitvoeren, reviewen, leren, en herhalen. De naam staat voor een uitdrukking die je liever niet in een krant ziet, maar de betekenis is duidelijk: ga. Goal is Codex's eigen functie voor langdurige taken. Je geeft het model een hoog-niveau doel en verifieerbare criteria voor wanneer het klaar is. Dan laat je het gaan. Uren, als het moet. Shipper heeft Goal-threads van twintig uur laten draaien in het weekend.

Hij lacht als hij het zegt: "Ik ben er enorm verslaafd aan de stream te bekijken terwijl het werkt. Wat ik haat aan mezelf. Maar ik doe het toch."

---

Terwijl Codex aan het bouwen is, vraagt het systeem om een eerste keuze. De badge kan drie dingen beloven: dat de app *alive* is, *responsive*, of *dependable*. Shipper kiest *dependable*, maar aarzelt. "Ik hou van alive," zegt hij. "Concreter. Eerlijker." En als de activiteit stopt? "De status verandert automatisch. Niet oordelend. Gewoon: één commit afgelopen dertig dagen, of geen."

Dat het model een voorkeur durft te hebben—een aanrader bij de opties plaatst, een mening heeft over welke richting de sterkste is—is nieuw. Eerdere versies misten dat. Ze hadden geen smaak, geen standpunt. Ze gaven opties en wachtten. Vijf-zes heeft een ander gevoel. Het durft iets te willen.

Wanneer Codex de eerste versie teruggeeft, is het een mockup van de badge op een over-pagina van de fictieve Quora-app: "26 commits afgelopen 30 dagen." De badge is er. Het concept is zichtbaar. Maar het ontwerp heeft een warme papieren achtergrond die Shipper niet heeft gevraagd—een neiging die blijkbaar diep in het 5.6-model zit ingesloten. "Het wil altijd die warm papieren tint," zegt Shipper lachend. "Ik weet niet waarom. Het is beter dan eerdere modellen, maar nog niet perfect. Ik geef het een B. Vorige modellen waren een C of D."

Voor het echte ontwerp zou hij naar Fable gaan, of naar Claude Opus. "Die hebben een betere ontwerpsmaak op dit moment," geeft hij eerlijk toe. "Maar dit is genoeg om te zien dat het idee werkt. Zeventig procent. En zeventig procent is soms precies wat je nodig hebt."

---

Dat woord—zeventig procent—is de ingang naar het belangrijkste conceptuele onderscheid dat Shipper in het gesprek maakt.

"Ik maak onderscheid tussen piraten en architecten."

Een piraat exploreert. Die wil zo snel mogelijk een idee aanraken, testen of het ergens op slaat, kijken of er waarde in zit. De piraat werkt naar zeventig procent en stopt dan—niet uit luiheid, maar omdat zeventig procent genoeg is om te beslissen of het de moeite waard is door te gaan. Een piraat is tolerant voor rommel, blij met ruwheid, aangetrokken door het nieuwe. De prikkeling zit in de ontdekking, niet in de voltooiing.

Een architect is anders. De architect ziet het onvoltooide werk en voelt ongemak. Niet vanwege de onvolmaaktheid zelf, maar vanwege het potentieel dat er nog in zit. Een architect wil de hoeken afvijlen, de randgevallen oplossen, het ding zo goed maken dat het echt werkt—niet alleen voor de maker, maar voor iedereen die het aanraakt. De architect haalt energie uit de overgang van zeventig naar honderd.

Shipper is een piraat. Hij weet het, en hij heeft er vrede mee. Wat hij ook weet, is dat piraten hun architecten nodig hebben. "Ik koppel mezelf aan iemand die dat andere deel kan doen," zegt hij. "Iemand die energie krijgt van een piraat die binnenkomt met een opwindend nieuw idee, maar die ook geniet van het omzetten van dat zeventig procent geformde ding naar iets wat echt gepolijst is."

Dit onderscheid is, zegt Shipper, fundamenteler dan de oude verdeling van technisch versus niet-technisch. "Vroeger zeiden we: ik heb een technische medeoprichter nodig. Dat klopt niet meer, want iedereen kan nu coderen. Het gaat om je gevoeligheid—voor het nieuwe versus voor het perfecte. Beide zijn enorm belangrijk. Ze vullen elkaar aan."

Turnaround staat op zeventig procent. De mockup is er, het idee is bewezen, het raamwerk is aanwezig. Er ontbreekt nog een definitief ontwerp en een echte koppeling aan GitHub of Linear. Shipper weet al wie hij zal bellen.

---

Een zijlijn in het gesprek verdient aparte aandacht, want het gaat over iets dat de meeste mensen nog niet zien aankomen.

Shipper fine-tunet een model.

Fine-tuning—het verfijnen van een bestaand AI-model op basis van eigen data—was tot voor kort voorbehouden aan machine learning-ingenieurs met toegang tot GPU-clusters, datasets van honderdduizenden voorbeelden, en maanden van experimenteren. OpenAI en Anthropic bieden het nauwelijks meer aan voor hun topmodellen. De grens leek technisch en financieel onhaalbaar voor iedereen buiten de grote labs. Maar met open-source modellen en de rekenkracht van 5.6 om het proces zelf te begeleiden, is de drempel drastisch gedaald.

Every heeft in zes jaar honderdduizenden kopijredacties uitgevoerd. Elk artikel dat op het platform verschijnt, wordt bewerkt door een editor die toeziet op stijl, ritme, precisie. Dat zijn gestructureerde data: ruwe tekst in, bewerkte tekst uit. Inputen output, netjes gekoppeld. Een perfecte basis voor een getraind model.

"De grote modellen kunnen geen copy-editing op het niveau van een copy-editor," zegt Shipper. "Dat is gek, want het zou niet zo moeilijk moeten zijn. Maar ze missen de fijnmazigheid. We hebben die interne data. We kunnen dat omzetten in een product."

Hij laat tijdens het gesprek zien dat er een Goal-thread al vier uur heeft gedraaid—een machine learning-pipeline die data verzamelt, synthetische trainingsdata genereert, experimenten uitvoert, en rapporteert. Vier uur autonoom. In het weekend had hij twee sessies van twintig uur elk laten lopen. Terwijl hij sliep, trainde zijn systeem een model.

"Dit is de volgende stap na het bouwen van je eigen skills," zegt hij. "Als een skill niet helemaal werkt, is fine-tuning de volgende stap. Het is nu haalbaar voor mensen die geen machine learning-ingenieur zijn."

Het principe is breder dan Every. Elke organisatie die jarenlang menselijk werk heeft gedaan—beoordelingen, redacties, klantenservice, medische diagnoses—heeft data. Die data zat opgesloten in systemen, mappeen, spreadsheets. Nu kan die worden omgezet in een getraind model dat dat werk beter doet dan een generiek taalmodel ooit zou kunnen. Dat is een nieuwe categorie van productmogelijkheden die de meeste bedrijven nog niet hebben ontdekt, en die de meeste consultants nog niet benoemen.

---

Terug naar de grotere vraag: wat betekent dit voor de SaaS-industrie?

Shipper heeft er een uitgesproken mening over, en die wijkt af van de gangbare apocalyptische toon in technologiekringen.

"De SaaS-apocalyps is onzin."

Het argument gaat als volgt: ja, iedereen kan nu één versie van een app in één prompt genereren. Maar dat betekent niet dat mensen stoppen met betalen voor software. Het betekent dat de waarde verschuift. Vroeger betaalde je voor de eerste versie—voor de initiële bouw, de architectuur, de opzet. Nu is die eerste versie gratis. Maar wat nog steeds schaars en duur is: alles wat daarna komt.

Bugs die worden opgespoord en verholpen. Features die worden toegevoegd omdat klanten erom vragen. Randgevallen die worden afgehandeld. Systemen die stabiel blijven als ze groeien. Dat is onderhoud, en onderhoud is nu het echte product.

"Mensen betalen voor onderhoud," zegt Shipper. "Dat is de inzicht. Als dit ding werkt, betaal ik er graag voor. De zeldzame, moeilijke vaardigheid is doorgaan—iets over tijd bouwen en onderhouden. Dat is nog steeds duur en moeilijk."

Hij geeft een voorbeeld uit zijn eigen bedrijf. Every heeft een consultancypraktijk. Ze probeerden een eigen CRM te vibe-coden—een combinatie van agents en spreadsheets. Het werkte gedeeltelijk. Een paar weken lang voelde het slim. Maar het werd snel een puinhoop. Randgevallen stapelden zich op. Gegevens raakten door elkaar. Ze zijn overgestapt op een CRM-leverancier die een CLI biedt, goed nagedacht heeft over randgevallen, en die blijft doorontwikkelen. "We doen nu het werk dat we eigenlijk willen doen, in plaats van klantrecords te vibe-coden."

Maar er is een tweede inzicht, en dat is subtieler en mogelijk groter.

Shipper denkt dat er een nieuwe categorie SaaS-software gaat ontstaan: Codex-native apps. Software die niet gebouwd is om zelfstandig te worden gebruikt, maar om te worden gebruikt *samen met een agent*, in de Codex in-app browser, terwijl mens en machine naast elkaar op hetzelfde oppervlak werken.

"De in-app browser bestaat om een reden," legt hij uit. "Als je een app bouwt, wil je hem kunnen gebruiken op dezelfde plek waar je agent hem gebruikt. De feedbackloop is korter. Hetzelfde geldt voor kenniswerk. Er is een enorme kans voor iedereen die begrijpt hoe je apps bouwt die op die manier zijn ontworpen."

De meeste bestaande SaaS-bedrijven installeren nu AI-agents in hun producten. Dat kost geld—token per token, query per query, prompt per prompt. De marges slinken. Maar een SaaS-bedrijf dat alleen hosting en software levert, zonder token-kosten, heeft de marges van de klassieke softwarebusiness terug. Geen AI-rekeningen. Gewoon software.

"Dat is interessant voor mensen die een bedrijf van tien miljoen dollar per jaar willen bouwen met lage kosten," zegt Shipper. "Een bedrijf dat tachtig miljoen omzet maakt maar zestig miljoen aan tokens uitgeeft—dat is interessant voor sommigen, maar niet voor iedereen."

Hij verwacht dat OpenAI en Anthropic binnen een jaar app stores lanceren voor Codex-native software. Niet voor het eerst—OpenAI heeft al drie of vier app store-pogingen gedaan. Maar deze keer met de wind mee, omdat het ecosysteem er klaar voor is. "Het is gewoon een te goed businessmodel om te negeren als je hebt gezien hoe goed de App Store werkte," zegt Shipper. "Misschien Cursor ook. Ik heb geen inzicht in hun plannen. Maar het is gewoon een logische stap als je bent opgegroeid in het app-tijdperk en hebt gezien hoe krachtig zo'n ecosysteem kan zijn."

---

Dan is er Chronicle.

Chronicle is een optionele functie in Codex die automatisch schermafbeeldingen maakt van je computer en die lokaal verwerkt tot een feed. Geen cloud, geen externe servers—alles blijft op je machine. Het resultaat is een doorlopend logboek van waar je aan werkt: welke apps je gebruikt, welke gesprekken je voert, welke documenten je opent. Welke vergadering je zojuist hebt gehad. Met wie je hebt gesproken en over wat.

Dat klinkt ongemakkelijk. Shipper erkent dat. Maar hij heeft het aanstaan.

"Ik geef er de voorkeur aan dat het meer context over mij heeft, zodat de antwoorden beter worden," zegt hij. "Je kunt het aan- en uitzetten. Het is een onderzoekspreview, volledig optioneel. Maar ik heb het aan omdat het lokaal is en omdat ik wil dat het systeem beter wordt."

Chronicle is de reden waarom Codex weet dat Shipper aan een specifiek project werkt als hij een vraag stelt. Waarom het begrijpt dat een vergadering die hij zojuist heeft gehad relevant is voor de e-mail die hij nu moet beantwoorden. Context—zo herhaalt Shipper door het gesprek—is de vermenigvuldiger. Een krachtig model zonder context is een Ferrari op een parkeerplaats. Een goed model met volledige context is een stadsauto die elke weg kent.

"De eerste stap is Codex downloaden," zegt hij. "De tweede stap is het toegang geven tot je computer. De derde stap is vragen: wat kun jij voor mij doen op basis van hoe ik mijn computer gebruik? En dan kijken wat er uitkomt. Dat is een goede oefening."

Een vergelijkbare logica geldt voor Record and Replay, een plugin die Codex recent heeft uitgebracht. Het werkt eenvoudig: je zegt tegen je agent "kijk hoe ik dit doe," voert een taak uit terwijl hij meekijkt, en de plugin zet die demonstratie automatisch om in een herbruikbare skill. De volgende keer dat de taak zich voordoet, weet Codex hoe het moet—omdat hij het van jou heeft gezien. Geen handmatige instructies, geen prompts schrijven. Je laat het gewoon zien.

"Elke repetitieve taak die je op je computer doet, doe je in Codex," adviseert Shipper. "En elke keer dat je werk op je computer doet buiten Codex, vraag ik mezelf af: hoe zou ik dit hier kunnen doen?"

Dat is de mentaliteitsshift waar het uiteindelijk om gaat. Niet leren hoe je een AI-tool gebruikt, maar leren hoe je een systeem aanstuurt dat het werk voor je doet. "Het gaat niet om één individuele e-mail. Het gaat om het systeem dat mijn e-mail doet. Dat is mijn werk."

Het is dezelfde overgang die managers maken als ze hun eerste medewerkers aannemen. Je doet het werk niet meer zelf—je beheert degene die het doet. Die overgang is moeilijker dan ze klinkt. Het vereist een ander soort aandacht, een ander soort discipline. Maar wie hem maakt, werkt op een fundamenteel ander niveau dan wie hem niet maakt.

---

Er is ook een eerlijk gesprek over de grenzen van het systeem.

Shipper gebruikt open-source modellen nauwelijks, op dit moment. Hij wil aan de frontier zitten—Fable maxen, vijf-zes gebruiken, de beste beschikbare intelligentie inzetten voor elk probleem. Maar hij ziet aankomen wanneer dat verandert. "We naderen een plafond waar extra verbeteringen in ruwe intelligentie moeilijk te consumeren zijn," zegt hij. "Ik kan Fable niet overal voor gebruiken. Ik heb geen groot genoeg probleem. Op het moment dat ik dat plafond raak, wordt snelheid en kostenefficiëntie belangrijker. Dan worden open-source modellen interessant."

Voor fine-tuning is het al onvermijdelijk. De grote modellabs—OpenAI en Anthropic—bieden fine-tuning nauwelijks meer aan voor hun beste modellen. Wie zijn eigen model wil trainen, moet naar open-source alternatieven. Dat is precies wat Shipper doet met zijn copy-editing pipeline. Vier uur, twintig uur, de machine draait terwijl hij slaapt.

---

Aan het einde van het gesprek doet Shipper iets opvallends. Hij waarschuwt.

Niet voor de technologie. Niet voor de risico's van AI of de privacyimplicaties van Chronicle. Hij waarschuwt voor de verkeerde motivatie om te beginnen.

"FOMO is nooit de juiste manier om nieuwe technologie te leren kennen," zegt hij. "Als je dit ziet en je eerste gedachte is: ik kan niet achterblijven—stop dan. Dat is de verkeerde brandstof. Je eindigt met een systeem dat je weken heeft gekost en dat je nooit echt gebruikt."

En vervolgens, met meer nadruk: "Kijk niet naar mijn setup en denk: ik moet dat allemaal bouwen. Begin met één ding dat je leven beter maakt, iets waar je écht in geïnteresseerd bent, en doe dat. Bouw het daarna op. Ik ben ook niet zo begonnen."

Het is een ongebruikelijk advies van iemand die urenlang zijn uitgebreide systeem heeft gedemonstreerd—Mailroom, pulses, router-threads, fine-tuning pipelines, Record and Replay, Chronicle. Maar het is eerlijk. Shipper heeft zijn setup niet in een week gebouwd. Hij is begonnen met één probleem. Zijn inbox lag hem dwars. Hij heeft het opgelost. Daarna heeft hij het volgende probleem aangepakt. Het systeem van vandaag is het resultaat van maanden experimenteren, falen, en herbouwen.

"Er is altijd de verleiding," zegt hij, "om meer tijd te besteden aan het systeem dan aan het werk. Dat is de klassieke fout met productiviteitssoftware—Notion, Roam, wat dan ook. Mensen bouwen gigantische, complexe systemen en doen intussen niets. Wat over het algemeen beter werkt: begin eenvoudig. Bouw wat je nodig hebt om het hoofdding te doen, niet het bijding."

Hij en zijn gesprekspartner lachen allebei om de zelfherkenning. Ze zijn, zeggen ze, de grootste nerds die ze kennen. Ze duwen dit alles tot het uiterste. Maar wat voor hen werkt, werkt niet voor iedereen. "Jouw versie ziet er waarschijnlijk anders uit dan die van mij," zegt Shipper. "Misschien zijn het drie dingen. Misschien vier. Als het goed genoeg is, is het goed."

---

Wat blijft hangen na dit gesprek, is niet de technologie. Die is indrukwekkend, maar technologie verandert snel. Vijf-zes wordt straks zes-nul. Codex krijgt een concurrent. De app stores komen, of ze komen niet. Wat blijft, is het raamwerk.

Shipper heeft een manier gevonden om te denken over wat AI doet met het werk—niet als vervanging, maar als systeem. Het verschil tussen piraten en architecten heeft altijd bestaan, maar was nooit zo scherp. Vroeger had je een piraat nodig die ook redelijk kon coderen. Nu hoeft een piraat alleen maar te weten wat hij wil. En een architect hoeft niet meer van nul te beginnen—hij verfijnt wat de piraat in minuten heeft neergezet.

Onderhoud als product. Context als vermenigvuldiger. Systeem boven taak. Nieuwsgierigheid boven angst.

Turnaround—de badge die aantoont dat een app leeft—staat inmiddels op zeventig procent. De mockup is er, het idee is bewezen, het raamwerk aanwezig. Een architect gaat hem afmaken.

Shipper weet al wie hij zal bellen. Hij heeft hem al in zijn telefoon staan.

---

*Dan Shipper is de oprichter van Every, een mediabedrijf dat schrijft over de toekomst van werk en technologie. Zijn inbox-app Tend is beschikbaar als open-source bibliotheek. De e-mailapp Quora, gebouwd door Kieran Classen, biedt een volwaardige inboxervaring ontworpen voor gebruik binnen Codex. De LFG compound engineering-plugin is eveneens van Classen. Het Record and Replay-plugin van Codex is beschikbaar als onderdeel van de desktopapplicatie. Chronicle is een optionele onderzoekspreview die lokaal op je machine draait. Codex is gratis te downloaden via de website van OpenAI.*