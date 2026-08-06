<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01KZ9Q7Q16YMBDA1CVVFC1251A
-->

# De Marketingmachine

*Marketing is altijd de achilleshiel geweest van de technische oprichter: iemand die moeiteloos een product bouwt, maar geen idee heeft hoe hij er klanten voor vindt. Cody Schneider heeft een antwoord op dat probleem—en het ziet eruit als code. In dit hoofdstuk bouwt hij live twee marketingagenten op, van strategie tot terminal, en laat hij zien dat het vinden van klanten geen kunst meer is maar een systeem.*

---

Er bestaat een specifiek soort stilte in de vroege ochtend van een startup. De productiviteit is er nog niet. De klanten zijn er nog niet. Alleen de oprichter, zijn laptop en de sluimerende vraag die elke ondernemer kent: hoe komen mensen erachter dat ik besta?

Cody Schneider heeft die stilte goed leren kennen. Als mede-oprichter van Graphed.com—een platform dat marketing-infrastructuur bouwt voor snelgroeiende bedrijven, en dat ook software-ingenieurs vooruitplaatst bij klanten die willen dat deze systemen écht worden geïmplementeerd—heeft hij de afgelopen jaren één ding geleerd dat de meeste technici nooit begrijpen: marketing is geen talent, het is een ingenieursprobleem. En ingenieursproblemen lossen zich op met code.

"Als ik een image genereer, is dat gewoon JSON onder de motorkap," zegt Schneider. "Als ik een video maak, is dat een LLM die Reddit heeft gescraped, een script heeft geschreven en een API-call heeft gedaan. Alles is nu code. Marketing is code."

Het is een uitspraak die vijf jaar geleden zou klinken als techno-utopisch waandenken. Vandaag klinkt het als een businessplan.

Wanneer Schneider terugkomt voor een tweede aflevering—zijn vorige bezoek over marketingagenten was een van de meest bekeken afleveringen ooit—is de belofte ditmaal groter. Niet één agent, maar twee. Gebouwd in real time, inclusief de volledige toolstack, van strategie tot terminal. En aan het einde, zegt hij, kan elke luisteraar stoppen met kijken en het gewoon gaan doen.

---

## Het handgebaar dat alles verandert

De koude e-mail is dood. Dat is niet pessimisme—dat zijn de cijfers. Reply rates zijn gekelderd. Elke marketingkanaal wordt overspoeld door AI-gegenereerde ruis. "AI slop," zoals Schneider het noemt, zonder enige ironie. "Het vloeit alle kanten op en maakt overal van een rode oceaan."

Maar er is een uitweg, en die begint met een simpele observatie over menselijk gedrag.

Wanneer iemand een bericht likt op LinkedIn, steekt hij zijn hand op. Dat is geen metafoor. Het is een koopsignaal—misschien het sterkste koopsignaal dat er bestaat in de moderne marketing. Niet de functietitel van iemand, niet het aantal werknemers bij zijn bedrijf, niet de branche waar hij in actief is. Maar het feit dat hij op dit moment, vandaag, actief betrokken is met content over een specifiek onderwerp.

"Dit zijn niet zomaar leads," legt Schneider uit. "Dit zijn mensen die laten zien dat ze interesse hebben in dit specifieke ding. Ze steken hun hand op en zeggen: ik wil dit. Dat is een signaal dat firmografics je nooit kunnen geven."

Firmografics is het traditionele jargon voor de objectieve kenmerken van een bedrijf—sector, omvang, locatie. Het is het equivalent van iemand targeten omdat hij in Amsterdam woont en veertig jaar oud is, in plaats van hem te benaderen omdat hij gisteren drie uur in een muziekwinkel heeft doorgebracht.

Het verschil is het verschil tussen hopen en weten.

---

## De blauwdruk: Agent Één

De eerste agent die Schneider opbouwt is een koud-outbound machine. Ze werkt als volgt: ze bewaakt de LinkedIn-posts van invloedrijke makers binnen een specifieke niche, haalt de namen op van iedereen die met die posts heeft geëngageerd, verrijkt die namen met e-mailadressen en telefoonnummers, en stuurt vervolgens gepersonaliseerde koude e-mails en LinkedIn-berichten. Een tweede laag beheert de antwoorden die binnenkomen—ook automatisch.

Het klinkt als vijf banen tegelijk. In de praktijk is het één stuk code op een server.

### Stap één: de juiste creators vinden

Alles begint bij LinkedIn. Niet met een geavanceerd algoritme, maar met de hand—door te scrollen door de feed en te zoeken naar makers die de content produceren waarop jouw doelklant zou reageren.

Schneider opent zijn scherm en typt "WordPress development" in de LinkedIn-zoekbalk. Het resultaat stelt teleur. Te breed, te versnipperd. Hij probeert het opnieuw: "AI marketing." Onmiddellijk: posts over video-editing voor marketeers, over groeistrategie, over het automatiseren van salesprocessen. Precies het soort content waarop zijn ideale klant zou klikken.

"De For You-pagina is je bondgenoot," zegt hij. "Al deze algoritmen zijn zo goed geworden dat ze je precies laten zien wat relevant is. Je hoeft dat niet te omzeilen—je moet er gebruik van maken."

Het eerste resultaat op zijn feed is een post over AI-videobewerking voor marketing. Perfect. Iedereen die daarmee heeft geïnteracteerd, is een potentiële klant. Schneider markeert het account.

"Je doelklant weet je zelf het beste," zegt hij. "Je hoeft niet alles te vinden. Je hebt tien tot twintig accounts nodig en je hebt tachtig procent dekking van je hele industrie. De marginale waarde van méér is er niet."

Dat inzicht is contraïntuïtief maar klopt. Elke niche heeft een handvol dominante stemmen—een paar creators of bedrijven waaromheen alle relevante conversaties plaatsvinden. Als je die bewaakt, zie je bijna iedereen die er echt toe doet. De rest is ruis.

Het resultaat is een spreadsheet. Tien, vijftien, misschien twintig LinkedIn-accounts—van individuele makers én van bedrijven—waarvan de posts de magneet zijn voor jouw ideale klant. Clay als voorbeeld. Een bekende AI-marketeer. Een bekende AI-marketeer met tienduizend volgers. Het dataplatform dat jouw doelklant dagelijks gebruikt. Iedereen die de mensen bereikt die jij wilt bereiken.

Belangrijk: dit is handwerk. Schneider gebruikt hier geen agent voor, geen automatisering. "Het bedrijf weet al wie zijn doelklant volgt. Dit is een uur werk met een spreadsheet en een LinkedIn-feed. Daarna neemt de machine het over."

### Stap twee: de engagers eruit halen

Met die spreadsheet in de hand komt Apify in beeld.

Apify is een scraping-API—een dienst die met één API-sleutel toegang geeft tot webscrapers voor LinkedIn, Twitter, Reddit en tientallen andere platforms. Denk eraan als een universele stekker: je plugt hem in, geeft hem een URL, en hij geeft je de data terug die je nodig hebt. Er zijn tientallen onafhankelijke bouwers die scrapers ontwikkelen voor specifieke doeleinden en die via Apify beschikbaar stellen.

De meest stabiele voor LinkedIn, volgens Schneider, zijn die van een bouwer onder de naam API Maestro. Die biedt scrapers voor bijna alles wat LinkedIn heeft: profielen, posts, reacties, likes, comments. De twee die in dit systeem centraal staan zijn de post reactions scraper en de post comments scraper. Stop er een LinkedIn post-URL in, en ze geven je een lijst van iedereen die ermee heeft geëngageerd.

Schneider opent zijn terminal—een donker scherm met witte tekst, de thuisbasis van de moderne marketingingenieur. Hij heeft de Apify API-sleutel al lokaal opgeslagen in de directory waar hij al zijn groeiwerkzaamheden uitvoert. "Als je dit zelf wilt opzetten, heb ik een video op mijn kanaal die het hele proces in tien minuten doorloopt. Daarna werkt dit precies zo."

Hij vraagt Claude Code—Anthropic's coding agent—om een script te schrijven dat de Apify API aanroept, de engagementdata van een specifieke post ophaalt en de resultaten opslaat. Hij geeft Claude de documentatie van het Apify-endpoint. Minuten later begint de terminal te scrollen. Ruwe data stroomt binnen. Drieënzestig profielen, klaar om verrijkt te worden.

Het tempo is ontnuchterend. Wat vroeger een werkdag kostte voor een SDR—een Sales Development Representative, de salesprofessional die koude leads kwalificeert en voorbereidt voor een verkoper—doet de code in drie minuten.

### De vraag die iedereen stelt: is dit een agent of een automatisering?

Op het moment dat de terminal klaar is met scrapen, stelt Schneider zichzelf de vraag die hij naar eigen zeggen elke salesgesprek hoort: wat is het verschil tussen een agent en een automatisering?

Zijn antwoord is verfrissend nuchter.

"Een agent is code. Een denkloop, misschien. En een live datastroom. Dat is het. Iedereen probeerde God in een doos te stoppen en hem toegang te geven tot een Facebook Ads-account. We hebben geleerd dat dat niet de goede aanpak is."

De juiste aanpak is simpeler: kijk naar wat een mens deed, en bouw software die datzelfde proces uitvoert. Een goede mediakoper onderzocht creatieve invalshoeken, maakte nieuw materiaal, testte het, snoeide de verliezers weg en schoof de winnaars naar voren. Dat is een lineair proces. Dat is code.

Waar het LLM—het grote taalmodel zoals Claude of GPT—wél van pas komt, is bij beslissingen die oordeel vereisen. Voordat een lead in de verrijkingsfase belandt, kan de agent de persoon en zijn bedrijf onderzoeken: hoeveel werknemers heeft het bedrijf? In welke sector opereert het? Groeit het? Past dit bij het ideale klantprofiel? Als het antwoord ja is, gaat de lead door de pijplijn. Als het nee is, valt hij eruit, en wordt er geen cent besteed aan outreach naar iemand die nooit zou kopen.

Dát is een denkloop. Dát is waar het LLM zijn waarde verdient.

"Betaal Anthropic niet om API-calls te maken," zegt Schneider. "Betaal ze om de software te bouwen die de API-call maakt. Waarom zou je elke keer tokens verbranden voor iets wat gewoon code kan zijn? Gebruik inference alleen waar je het nodig hebt."

Het is een onderscheid dat de meeste mensen die over AI praten missen. Tokens kosten geld. Code draaien op een server kost een paar cent per uur. Als de beslissing altijd hetzelfde is—scrape deze URL, sla de data op, stuur door naar de volgende stap—is er geen reden om daar een taalmodel bij te betrekken. Het taalmodel is kostbaar gereedschap. Gebruik het alleen als menselijk oordeel nodig is, niet als eenvoudige if-else-logica het ook kan.

### Stap drie: waterfall enrichment

Nu de lijst met LinkedIn-profielen klaar is, begint de volgende fase: e-mailadressen en telefoonnummers vinden. Dit gaat via een methode die Schneider waterfall enrichment noemt.

De logica is die van een trechter, van goedkoop naar duur. Je begint met de goedkoopste databron, haalt eruit wat je kunt, en stuurt de rest door naar de volgende. Zo betaal je nooit meer dan nodig voor data die je al had kunnen vinden via een goedkopere route.

De eerste stop is GetLeads.io. GetLeads is een database van B2B-contacten—een aggregator die gegevens van tientallen databronnen samenvoegt en via een API beschikbaar maakt. Van een lijst van vijftig LinkedIn-profielen vindt GetLeads er misschien tweeëndertig tot vijfendertig. Die treffer vind je terug in het terminalscherm als Schneider het script laat draaien: de namen verschijnen één voor één, elk met een bijbehorend e-mailadres en soms een telefoonnummer.

De overgebleven achttien gaan naar Apollo—een bekendere naam in de saleswereld, uitgebreider in zijn database maar duurder per lookup. Apollo vindt er misschien tien van de achttien.

De rest gaat naar Origami of Prospeo—specialistischere tools die dieper graven en meer kosten, maar die de laatste gaten kunnen opvullen. Origami, noemenswaardig om zijn team dat actief met gebruikers meedenkt, aggregeert bovendien de waterfall intern: stuur hem een LinkedIn-profiel en hij doorzoekt automatisch meerdere bronnen in volgorde. Voor wie de pijplijn liever niet zelf in serie schakelt, is dat een elegante oplossing.

Voor telefoonnummers is er LeadMagic, een tool die zich specifiek op mobiele nummers richt en die Schneider regelmatig inzet voor campagnes die ook via de telefoon lopen. Niet elke campagne vereist dat, maar voor sectoren waar bellen nog werkt—en dat zijn er meer dan technici denken—is de aanvulling waardevol.

"Je kunt er zoveel in serie schakelen als je wilt," zegt Schneider. "Het hangt af van je budget. Maar met deze aanpak haal je typisch een vondstratio van tachtig procent. Dat is meer dan genoeg om het kanaal winstgevend te maken."

Een cruciaal onderdeel van dit proces is e-mailvalidatie. De adressen die uit deze databases komen zijn niet altijd actief. Sommige zijn verlopen. Andere zijn catch-all-adressen—inboxen die alles ontvangen wat naar een domein wordt gestuurd, maar die misschien nooit door een mens worden gelezen en dus geen reële kans op respons bieden.

Voor validatie gebruikt Schneider Million Verifier. Die service analyseert elk e-mailadres en geeft het een label: goed, riskant, of slecht—in meer technische termen: valid, catch-all, of invalid. Alleen de goede adressen gaan de volgende fase in. De reden is simpel maar cruciaal: wie naar ongeldige adressen stuurt, beschadigt de deliverability van zijn eigen e-mailinfrastructuur. Deliverability is het vermogen van e-mails om daadwerkelijk in iemands inbox te belanden, in plaats van te verdwijnen in de spammap of te stuiteren op een niet-bestaand adres. Te veel fouten, en e-mailproviders beginnen alle mail van dat domein te wantrouwen.

"Doe de dubbele validatie," adviseert Schneider. "GetLeads en Apollo doen zelf ook checks, maar niet diep genoeg. Million Verifier geeft je de zekerheid. Je wilt alleen sturen naar mensen van wie je weet dat de e-mail aankomt."

### Een noot over compliance

Hier steekt een vraag de kop op die elke marketeer bezighoudt: is dit allemaal legaal?

Het antwoord is genuanceerd. In de Verenigde Staten is koude e-mail toegestaan, mits je voldoet aan de CAN-SPAM-regelgeving: een duidelijke afzender, een werkende uitschrijflink, geen misleidende onderwerpregels. Het ophalen van contactgegevens via databureaus—wat GetLeads en Apollo in essentie zijn—is legaal. Dit zijn bedrijven die lijsten aggregeren van publiek beschikbare bronnen en andere databureaus, een praktijk die al decennia bestaat en juridisch erkend is.

In de Europese Unie liggen de regels strenger, met name door de AVG. Wie vanuit Europa opereert of Europeanen benadert, heeft doorgaans een geldige rechtsgrondslag nodig voordat hij e-mails verstuurt—en expliciete toestemming is daarvoor de meest gangbare route.

"We hebben geen tijd om vandaag alle details door te nemen," erkent Schneider eerlijk. "Maar het vinden van contactgegevens en het benaderen van mensen bevindt zich aan de witte kant van het spectrum. Verdiep je in de specifieke regels die voor jouw situatie gelden, want de VS en de EU zijn totaal anders."

Het is een voetnoot die ertoe doet. De technische mogelijkheden van deze systemen lopen ver voor op de juridische bewustwording bij de mensen die ze bouwen.

### Stap vier: de verzendinfrastructuur

De e-mailadressen zijn gevonden, gevalideerd en klaargelegd. Nu moeten ze ook daadwerkelijk verstuurd worden—maar niet vanuit het primaire domein van het bedrijf.

Dit is een punt dat veel beginners missen, en het is de reden dat koude e-mailcampagnes zo vaak mislukken voordat ze beginnen.

E-maildomein-reputatie werkt als een kredietscore. Als je vanuit je hoofddomein tienduizend koude e-mails verstuurt, waarvan een deel naar ongeldige adressen gaat, waarvan een deel als spam wordt gemarkeerd, en waarvan een groot deel nooit wordt geopend—dan betaal je daarvoor met je deliverability. Toekomstige e-mails van jouw echte bedrijfsdomein belanden dan in de spammap. Ook de e-mails die je naar klanten, investeerders en partners stuurt. Het is een vergissing die bedrijven maanden kost om te herstellen.

De oplossing is radicale scheiding. Schneider onderscheidt vier typen domeinen, elk met een specifiek doel. Er is het transactionele e-maildomein—voor automatische berichten vanuit het product zelf, zoals wachtwoordresets en bevestigingen. Er is het e-marketingdomein—voor nieuwsbrieven en campagnes naar bestaande klanten. Er is het zakelijke domein—het adres dat medewerkers dagelijks gebruiken om met de buitenwereld te communiceren. En er zijn de zogeheten burner domains, de wegwerpbare domeinen waarop alle koude outbound-campagnes draaien.

Die laatste categorie wordt aangemaakt via diensten als InboxKit, via Instantly AI's eigen inbox-aanbod, of via HyperTide—de partner die Graphed.com het meest inzet en waarmee ze een nauw samenwerkingsverband hebben. De domeinen worden geconfigureerd, de inboxen worden aangemaakt, en de reputatie van het moederbedrijf blijft onaangeroerd.

De kosten zijn opmerkelijk laag. Voor het verzenden van tienduizend koude e-mails per maand bedragen de inboxkosten bij HyperTide ruwweg honderd dollar. InboxKit heeft vergelijkbare tarieven en gooit regelmatig promoties uit waar je op moet letten. Daarboven komt Instantly.ai—het platform dat de campagnes beheert, personalisatie toepast, de timing van verzending optimaliseert en resultaten bijhoudt—voor ongeveer 97 dollar per maand. Totale infrastructuurkosten voor een volledig functionerende koud-outbound machine: tweehonderd dollar per maand.

"Voor tweehonderd dollar heb je een volledig draaiende outbound-machine," zegt Schneider. "Dat is minder dan één uur van een freelance SDR."

Voor LinkedIn DMs gebruikt hij Hayreach of BotDog—tools die LinkedIn DM-campagnes beheren via een API, zodat ook dat kanaal geautomatiseerd kan worden zonder dat de oprichter elke boodschap zelf typt. LinkedIn InMail, het officiële betaalkanaal van het platform, is ook een optie. Schneider ziet daar momenteel uitstekende resultaten mee, met name voor B2B-doelgroepen die hun LinkedIn-inbox serieus nemen.

### De agent die de inbox beheert

Het laatste stuk van de puzzel is het meest elegant.

Instantly.ai heeft een API en webhooks—triggers die een seintje sturen naar een externe server zodra er iets gebeurt in een campagne. Als iemand een positief antwoord stuurt op een koude e-mail, vuurt Instantly een webhook af. Die webhook bereikt de agent op de server. De agent—gewapend met context over het bedrijf, het product, de propositie, het ideale klantprofiel—analyseert het antwoord en schrijft een reactie.

Het doel is simpel: push de persoon richting een demo. Beantwoord vragen. Wees behulpzaam. Wees menselijk. En als het gesprek na een week stil is gevallen, stuur zes maanden later een follow-up—dat is ook gewoon een instructie aan de agent.

"Het kan ook verbonden worden met je agendaboekingssoftware," zegt Schneider. "Calendly of Cal.com. Dan weet de agent of iemand daadwerkelijk een gesprek heeft geboekt. Heeft hij dat? Dan stopt de sequentie. Heeft hij dat niet? Dan gaat de follow-up door. Op het juiste moment, automatisch."

De volledige pijplijn is dan klaar: van LinkedIn-post naar gesigneerde lead, volledig autonoom, voor tweehonderd dollar per maand. En toch benadrukt Schneider keer op keer: dit is geen magie. Het is code.

"Wanneer ik zeg agent, bedoel ik gewoon code met een LLM eraan vast waar oordeel nodig is," zegt hij, bijna alsof hij wil voorkomen dat zijn toehoorders te veel mysterie in het systeem projecteren. "De agent die de inbox beheert: dat is code met een LLM. De scraper: dat is gewoon code. Meer is het niet. Je hoeft dit niet ingewikkeld te maken."

---

## Software als marketingfilosofie

Halverwege het gesprek maakt Schneider een zijsprong die méér zegt over de toekomst van marketing dan welke specifieke tool ook.

"We zitten allemaal in de software factory business," zegt hij. "We produceren software om taken uit te voeren. En zodra iets software is, kan ik het deployen naar een server, het draaien op een cron job, en er nooit meer naar omkijken."

Een cron job is een geplande taak op een server—vergelijkbaar met een wekker die elke ochtend om zeven uur afloopt, maar dan voor code die elke dag om middernacht nieuwe LinkedIn-engagements ophaalt, verrijkt en klaarstoomt voor outreach. De server slaapt niet. Hij neemt geen vakantie. Hij vergeet geen follow-up.

Voor de implementatie gebruikt Schneider Railway—een platform voor het deployen van applicaties in de cloud, zonder de complexiteit van grote cloudproviders als AWS of Google Cloud. De agents draaien als processen op die server, worden getriggerd door cron jobs of webhooks, en communiceren met de datastroom via Airbyte en ClickHouse.

Airbyte is een open source datapijplijn—een systeem dat data van externe bronnen zoals LinkedIn, Apify, Gong en Slack verzamelt en op één plek samenvoegt, zodat de agent altijd toegang heeft tot actuele informatie. ClickHouse is een razendsnel analytics-database—de opslagruimte waar alle data naartoe stroomt en waar de agent uit put om beslissingen te nemen. Samen vormen ze de ruggengraat van de infrastructuur: het geheugen en het zenuwstelsel van de marketingmachine.

"Zodra je die infrastructuur hebt staan, is de rest gewoon code die je erin laadt," zegt Schneider. "Een script dat scrapet. Een script dat verrijkt. Een script dat verstuurt. De agent is de dirigent die ze in de goede volgorde aanroept."

Zijn co-founder Max brengt dat principe nog scherper onder woorden. "Max zegt altijd: er bestaat maar één agent, en dat is de coding agent. Alles andere is software die door de coding agent wordt gemaakt," vertelt Schneider. "Ik denk dat hij gelijk heeft. En ik denk dat iedereen die anders denkt, geld verspilt aan tokens die ze niet hoeven te verbranden."

De implicatie is verstrekkend. Als koude outbound code is, als contentcreatie code is, als inboxbeheer code is—dan is de marketeer van de toekomst iemand die weet hoe systemen worden gebouwd. Niet iemand die e-mails schrijft en posts plant.

---

## Agent Twee: De Organische Contentketen

Niet iedereen wil koude e-mails sturen. Sommige oprichters gruwelen bij het idee. Anderen willen hun merkidentiteit beschermen, of opereren in niches waar koude outreach cultureel niet past. Voor hen—en voor de bedrijven die organische geloofwaardigheid belangrijker vinden dan directe bereikbaarheid—heeft Schneider een tweede systeem gebouwd.

Het is even elegant in zijn eenvoud. De naam is wat beschrijvend, maar de ambitie niet: een organische LinkedIn-contentketen voor een heel team.

### Het probleem met AI-content

Voordat hij het systeem uitlegt, waarschuwt Schneider voor de meest gemaakte fout—een fout die hij bij bijna elk bedrijf ziet wanneer ze dit voor het eerst proberen.

"Als je een agent vraagt om gewoon goede LinkedIn-content te schrijven, krijg je het meest gemiddelde wat je ooit hebt gelezen," zegt hij. "Je verspilt de tijd van je lezer. En LinkedIn heeft net een nieuwe feature gelanceerd waarmee het AI-slop markeert. Je kunt gecategoriseerd worden als onechte content. Dan heb je het ergste van twee werelden."

Het probleem is bronmateriaal. Een LLM dat uit het niets content moet maken, put uit de gemiddelde van alles wat het heeft gelezen. Het resultaat is gladgestreken, voorspelbaar, onmemorable. Content die lijkt op duizend andere posts, geschreven door duizend andere tools, over duizend andere onderwerpen.

De oplossing is verankering in echte menselijke conversaties. Interviews met teamleden. Salesgesprekken opgenomen via Gong of een vergelijkbare tool. Interne Slack-berichten. Notion-documenten. Podcast-transcripten. Dit is het ruwe materiaal waaruit originele ideeën komen—onverwachte observaties, klantuitspraken die blijven hangen, inzichten die alleen ontstaan als twee mensen echt met elkaar praten, zonder agenda, zonder voorbereiding.

"De beste content is gevangen in de data die je al hebt," zegt Schneider. "In de Gong-transcripten van je salesgesprekken. In je Notion. In je Slack. Een klant die vertelde waarom hij het product niet kocht—dat kan een ongelooflijk stuk content worden. Die eerlijkheid, die frictie, dat conflict—dat is wat mensen willen lezen. Niet een gesaniteerde samenvatting van wat jij geweldig vindt aan je eigen product."

Alex Lieberman, mede-oprichter van het mediabedrijf Morning Brew, heeft dit principe al breed uitgedragen. Zijn team put dagelijks uit interne communicatie voor externe content—de inzichten die in een Slack-thread leven, de observaties die in een teammeeting werden gedeeld, de vragen die klanten stellen die niemand had verwacht. De informatie is er al. Ze hoeft alleen gevonden, geformatteerd en gepubliceerd te worden.

### De opbouw van het systeem

De werking van de tweede agent is architecturaal eenvoudig, maar vereist één menselijke handeling die niet geautomatiseerd kan worden: het gesprek zelf.

Schneider heeft wekelijkse een-op-een-gesprekken met de teamleden van de bedrijven waarvoor hij dit bouwt. Geen gestructureerd interview. Geen voorbereidende vragen. Gewoon een open gesprek van twintig minuten. "Vertel me wat je deze week hebt geleerd. Wat viel je op tijdens salesgesprekken? Wat verraste je? Wat hoorde je van een klant dat je niet had verwacht?"

Die gesprekken worden opgenomen en getranscribeerd. Hetzelfde geldt voor alle andere bronnen die het bedrijf toch al genereert: salesgesprekken via Gong, interne vergaderingen, Slack-conversaties, podcasts waaraan teamleden deelnemen. De transcript van deze aflevering zelf is een voorbeeld: die bevat genoeg inzichten voor weken aan LinkedIn-posts over marketingautomatisering, AI-tools en groeistrategie.

"De bron kan alles zijn," zegt Schneider. "Het kan een gesprek met Naval Ravikant zijn. Het kan een interview zijn dat iemand anders heeft gegeven. Zolang je er expliciete ideeën uithaalt die menselijk zijn en niet door honderd andere mensen zijn gebruikt—dan heb je goud."

Die transcripten gaan via een API-call naar een taalmodel. Claude Sonnet is goed genoeg voor het schrijfwerk, zegt Schneider. Geen overvloed aan parameters, geen ingewikkelde instrueringen. Het model krijgt de transcript, de schrijfstijl van de persoon—ontleend aan eerdere posts die goed hebben gepresteerd—en de instructie om een batch LinkedIn-posts te produceren die de kernideeën uit het gesprek vertalen naar concrete, bruikbare inzichten voor de lezer.

Die content wordt vervolgens via de API van Ordinal gepland en gepubliceerd. Ordinal is een platform voor het beheren van meerdere LinkedIn-accounts tegelijk—ideaal voor bedrijven die willen dat hun hele salesteam zeven personen dagelijks actief is op LinkedIn, zonder dat iemand elke ochtend handmatig hoeft te posten. Bovendien laat Ordinal posts vanuit verschillende accounts met elkaar interageren: likes, reacties, het beginnetje van een gespreksdraad dat het LinkedIn-algoritme als signaal gebruikt om de post breder te verspreiden.

Het platform heeft ook een analytics-dashboard dat bijhoudt welke posts presteren—hoeveel impressies, hoeveel reacties, welke onderwerpen aanslaan bij welk publiek. Die prestatiedata gaat terug naar de agent als nieuwe context voor de volgende schrijfcyclus. Welke thema's genereren de meeste impressies? Welke invalshoeken raken een snaar? Op basis van die informatie schaaft de agent de volgende batch bij.

"Dit is precies wat een goede social media manager deed," zegt Schneider. "Ideeën prospecteren. Content maken. Publiceren. Analyseren. De winnaars herhalen. Het systeem doet dat nu. Sneller, goedkoper, en zonder vrije dag."

### De dode professional

Dan zegt Schneider iets dat de lucht even stilzet.

"De social media manager als beroep is al dood."

Hij corrigeert zichzelf onmiddellijk—maar slechts gedeeltelijk. Misschien niet dood, maar fundamenteel getransformeerd. Geëvolueerd in een andere functie. Want een persoon die dag in dag uit handmatig posts plant, ideeën bedenkt, resultaten analyseert en een contentkalender bijhoudt—dat is nu een systeem. Geen baanrol meer, maar een set instructies die een server uitvoert.

"Als je luistert en dit is jouw beroep," zegt Schneider, met een zeldzaam moment van directheid richting zijn publiek, "leer dan hoe je content op schaal kunt maken en beheren via meerdere accounts. Met agents. Want dat is de meta nu. Één persoon die tien, twintig, honderd accounts beheert—niet door elke post zelf te schrijven, maar door de systemen te ontwerpen die dat doen. Dát is de nieuwe functie."

De nieuwe social media professional is een systeemarchitect. Iemand die de bronnen identificeert, de schrijfstijl definieert, de analytics interpreteert en de agents bijstuurt. Het creatieve oordeel blijft menselijk. De uitvoering is code.

### De earned media rekenmachine

Schneider geeft vervolgens een getal dat de toon van het gesprek permanent verandert.

"LinkedIn kost gemiddeld tweeëntwintig dollar per duizend impressies als je betaalt voor advertenties."

Dat is het CPM—de cost per mille, de standaardmaatstaf in advertentiemarketing voor de prijs van duizend weergaven. Op LinkedIn is dat cijfer historisch hoog, omdat de doelgroep zakelijk is en daarmee uitzonderlijk waardevol voor B2B-adverteerders. Tweeëntwintig dollar per duizend is geen uitzondering—het is het gemiddelde.

Een LinkedIn-post van een persoonlijk account met vijfhonderd volgers haalt makkelijk duizend impressies. Dat is tweeëntwintig dollar aan bereik—gratis. Een post die viraal gaat en honderdduizend impressies haalt, vertegenwoordigt 2.200 dollar aan mediabereik, zonder een cent te betalen aan het platform.

"Ik word betaald om leadpijplijn te bouwen," zegt Schneider. "Denk daar even over na. En dan bedoel ik niet metaforisch. YouTube betaalt je letterlijk voor views. LinkedIn geeft je gratis what advertisers duizenden euros voor betalen. Wat voor wereld is dit?"

De ironie is volledig: terwijl corporaties tientallen miljoenen euro's uitgeven aan LinkedIn-advertenties, bouwen oprichters met een goed organisch systeem hetzelfde bereik op. Gratis. Consistent. En met een hogere geloofwaardigheid, omdat het van een persoon komt, niet van een merk.

### De themapagina als alternatief

Voor de oprichters die geen persoonlijk merk willen opbouwen—en die er zijn, en dat is volkomen legitiem—is er een alternatieve strategie die minstens even krachtig is.

Julian Shapiro, oprichter van het groeiagentschap Demand Curve en auteur van een van de bekendste marketingblogs op het internet, gaf hier het perfecte voorbeeld. In plaats van een account aan te maken onder de naam Demand Curve te bouwen, creëerde hij een X-account genaamd Growth Tactics. Geen persoonsnaam. Geen bedrijfsnaam. Een topic.

Mensen die geïnteresseerd zijn in groeistrategie volgen Growth Tactics. Via dat platform leren ze Demand Curve kennen. De aandacht wordt organisch geleid, zonder de oprichter zelf in de spotlight te zetten, zonder de kwetsbaarheid van een persoonlijk merk.

"Het kan anoniem zijn," zegt Schneider. "Het kan een meme-account zijn. Het kan een aggregator zijn die gewoon de beste content over een onderwerp verzamelt en curateerd. Zolang het waarde levert aan de juiste mensen, kan het aandacht trekken die je kunt inzetten voor wat je ook bouwt."

Chase Passive Income is een ander voorbeeld—een account dat meme-achtige content combineert met serieuze informatie over financiële vrijheid, dat ondertussen een enorme gemeenschap heeft opgebouwd en die aandacht heeft omgezet in producten en diensten. Niemand weet wie er achter het account zit. Dat maakt niet uit. De aandacht is er, en de aandacht is waardevol.

Het eigenlijke principe achter beide agents is hetzelfde: aandacht als bezit. Of die aandacht via koude outbound wordt verkregen—door mensen te bereiken die al interesse tonen—of via organische content die de juiste mensen aantrekt. De kanalen zijn anders. De filosofie is identiek: vind de mensen die al hun hand opsteken, en verschijn in hun leven op het juiste moment.

---

## De architectuur van een marketingmachine

Aan het einde legt Schneider de infrastructuurlaag bloot die beide systemen verbindt—de motor achter het gordijn.

Alles draait op een server. Railway is zijn voorkeur: een platform voor het deployen van applicaties in de cloud, zonder de complexiteit en de steile leercurve van grote cloudproviders als AWS of Google Cloud. Je schrijft je code, je pusht hem naar Railway, en de applicatie draait. De agents draaien als processen op die server, worden getriggerd door cron jobs of webhooks, en communiceren met de datastroom via Airbyte en ClickHouse.

Airbyte verzamelt data van externe bronnen—LinkedIn via Apify, salesgesprekken via Gong, interne communicatie via Slack—en voegt die samen op één plek. ClickHouse slaat die data razendsnel op en maakt ze doorzoekbaar. Samen vormen ze het collectieve geheugen van de machine: alles wat de agent nodig heeft om slimme beslissingen te nemen, staat klaar in een database die hij elke seconde kan bevragen.

"Zodra je die infrastructuur hebt staan, is de rest gewoon code die je erin laadt," zegt Schneider. "Een script dat scrapet. Een script dat verrijkt. Een script dat verstuurt. De agent is de dirigent die ze in de goede volgorde aanroept."

Het klinkt technisch. Maar het is in wezen hetzelfde als een assembly line in een fabriek: elk station doet één ding, in de juiste volgorde, op het juiste moment. De fabriek draait dag en nacht. De oprichter slaapt.

Voor wie dit zelf wil opzetten, zijn de stappen helder. Gebruik Claude Code of Codex om de scripts te schrijven. Gebruik Apify voor het scrapen van LinkedIn-engagements. Gebruik GetLeads als eerste stop voor verrijking, Apollo als tweede, Origami of Prospeo als derde. Gebruik LeadMagic voor telefoonnummers. Gebruik Million Verifier om e-mails te valideren. Gebruik HyperTide of InboxKit voor de inbox-infrastructuur op burner domains. Gebruik Instantly.ai voor het versturen en beheren van campagnes. Gebruik Hayreach of BotDog voor LinkedIn DMs. Gebruik Ordinal voor organische contentplanning en analytics. Deploy alles naar Railway. Stel cron jobs in. Sluit de feedbackloop.

Totale kosten voor de outbound-infrastructuur: tweehonderd dollar per maand. Totale kosten voor de organische content-keten: Ordinal, Claude Sonnet API-kosten, en de tijd van één wekelijks gesprek per teamlid.

---

## De winnende contentstrategie

Er is één aanvullend principe in Schneiders benadering van organische content dat het systeem écht duurzaam maakt—en dat hij onthult wanneer hij zijn eigen werkwijze beschrijft.

Hij heeft een handvol posts die hij al twee jaar gebruikt. Elke keer als hij ze publiceert, weet hij op voorhand dat ze viraal gaan. Niet omdat ze nieuw zijn, maar omdat ze bewezen hebben dat ze resoneren. De truc: hij post ze niet vaker dan eens per negentig dagen. Binnen die termijn is het merendeel van zijn volgers de post vergeten, of heeft een nieuwe golf van volgers hem nog nooit gezien.

"Mijn Twitter en LinkedIn zijn in essentie steeds dezelfde ideeën, opnieuw geformuleerd," zegt hij. "Dat is alles. Als je weet wat werkt, is het dom om het niet te herhalen. Varieer de formulering, varieer het format, maar blijf in de buurt van de thema's die aanslaan."

De implicatie voor het systeem is direct: de analytics-data die Ordinal terugkoppelt aan de agent is niet alleen informatie over de afgelopen week. Het is het fundament van een contentarchief dat zichzelf versterkt. Winnaars worden geïdentificeerd. Winnaars worden hernomen. De machine leert niet alleen te schrijven—ze leert te onthouden wat al heeft gewerkt.

Dit is ook de reden waarom Schneider zo sterk gelooft in de vergelijking met product development. De beste oprichters vragen niet: hoe overtuig ik de markt van mijn product? Ze vragen: wat wil de markt kopen, en kan ik dat bouwen? Dezelfde logica geldt voor content: niet welke content wil ik maken, maar welke content wil mijn publiek consumeren—en hoe maak ik daar structureel meer van?

"Als je dat principe eenmaal begrijpt," zegt Schneider, "dan is marketing niet meer iets wat je doet naast je echte werk. Het is het systeem dat je eenmalig bouwt, dat daarna voor je werkt."

---

## Wat dit betekent

Er is een dieper punt in alles wat Schneider beschrijft, en het gaat verder dan marketingtools.

Het gaat over de eliminatie van de kloof tussen bouwen en verkopen.

De meeste technici zijn superieure bouwers en gebrekkige verkopers. Ze begrijpen stapels, architectuur, schaalbaarheid. Ze begrijpen niet hoe ze in een kamer vol potentiële klanten terechtkomen. Marketing voelt chaotisch aan, oncontroleerbaar, afhankelijk van talent en geluk en persoonlijkheid—eigenschappen die een ingenieur niet kan debuggen.

Maar als marketing code is—als het een systeem is dat je ontwerpt, test en optimaliseert—dan is het plotseling hetzelfde werk als het bouwen van het product zelf. Je definieert inputs. Je bouwt de pijplijn. Je meet outputs. Je schaalt op wat werkt. Je snijdt weg wat niet werkt. Hetzelfde denkraam dat een goede ingenieur toepast op een codebase, werkt ook op een marketing-architectuur.

"Je hebt die vrijheid als je dit systeem hebt," zegt Schneider. "Je focust op het bouwen van een geweldig product. De marketingmachine draait."

Die belofte is conditioneel. De machine draait alleen als ze goed is gebouwd. De strategie werkt alleen als je de juiste creators volgt, de juiste ICP-filters instelt, de juiste copy schrijft en de juiste context aan de agent meegeeft. Een slecht geconfigureerde agent stuurt slechte e-mails. Een agent zonder goed bronmateriaal schrijft gemiddelde content. Garbage in, garbage out—ook hier.

Maar het vertrekpunt is anders dan het ooit was. Voor het eerst in de geschiedenis van startups kan een team van twee mensen een marketingsysteem bouwen dat presteert alsof er vijf SDRs, twee content marketeers en een social media manager fulltime werken. Voor tweehonderd dollar per maand aan infrastructuur, aangevuld met een handvol kleinere abonnementen voor enrichment-tools, analytics en contentplanning.

Schneider sluit af met de gedachte die alles samenvat: "In een wereld waar AI-slop overal is, win je niet door meer te sturen. Je wint door te sturen naar de mensen die al hun hand hebben opgestoken."

De hand die omhoog gaat is het signaal. De agent is degene die het ziet. En de code die beide verbindt, is de marketingmachine die elke technische oprichter eindelijk begrijpt.

---

*Cody Schneider is mede-oprichter van Graphed.com, een platform dat marketing-agents bouwt en implementeert voor snelgroeiende bedrijven, en dat software-ingenieurs vooruitplaatst bij klanten die diepgaande implementaties nodig hebben. Hij deelt dagelijkse inzichten over marketing als engineering op X en LinkedIn.*