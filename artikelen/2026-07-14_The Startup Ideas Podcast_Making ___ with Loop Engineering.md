<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01KX706XG5YWJB60R0F50VJ5Q9
-->

# De Machine Die Zichzelf Bouwt: Hoe Loops het Werk van een Heel Bedrijf Kunnen Overnemen

*Het idee begon als een grap op Twitter. Maar achter de ironie school een serieuze vraag: wat als elk onderdeel van een bedrijf — de marketing, het product, de SEO, de advertenties — op zichzelf kon blijven verbeteren, dag en nacht, zonder dat er een mens aan te pas komt? Ondernemer Elie Steinbock besloot het te proberen. Wat hij ontdekte, veranderde de manier waarop hij zijn bedrijven runt.*

---

Het was een tweet van zijn vriend Dimitro die Elie aan het denken zette. Geschreven met de toon van iemand die de hele hype rondom AI-terminologie beu was, maar raak genoeg om te blijven hangen: *"In 2026 hoef je niet meer te prompten. Je software moet zichzelf kunnen bouwen en op eigen kracht product-market fit bereiken. Jouw enige taak is het vinden van geld om tokens te betalen en goed voor jezelf te zorgen."*

Dimitro bedoelde het sarcastisch. Het was een sneer naar de eindeloze stroom buzzwoorden die het AI-landschap overspoelde — prompt engineering, context engineering, harness engineering, en nu dit: loop engineering. Boris, verbonden aan Claude Code, had er een paar weken eerder over beginnen te tweeten. Peter Steinberger van OpenAI deed hetzelfde. Binnen dagen was het overal. Elke maand een nieuwe hype, een nieuwe term, een nieuw one-liner die op LinkedIn viral ging voordat hij door de volgende werd ingehaald. Dimitro's tweet maakte er grappend gehakt van. Het mooie was: het had nu een naam. Vroeger had je dit concept kunnen beschrijven en niemand had geweten hoe het te noemen. Nu heette het loop engineering, en iedereen deed plots mee.

Maar Elie las het en dacht: *wacht eens even*.

Niet omdat het plausibel klonk als marketingpraat. Maar omdat hij zichzelf de vraag stelde die niemand anders leek te stellen. Niet: *is dit hype?* Maar: *wat zou het er eigenlijk uitzien als je dit serieus probeerde?* Wat zou er nodig zijn om werkelijk elke laag van een bedrijf — niet alleen de code, maar de marketing, de SEO, de productbeslissingen, de advertenties, de sociale media — op een loop te zetten die zichzelf maandenlang in stand houdt en verbetert?

Die vraag leidde hem naar een praktisch experiment. En dat experiment begon, zoals zo veel dingen in de tech-wereld, niet met iets nieuws, maar met iets heel ouds.

---

**Wat Toyota en Eric Ries gemeen hebben**

Loop engineering als term dateert van een paar weken voor het gesprek dat Elie zou voeren. Maar het idee zelf was tientallen jaren oud — en dat is precies waarom het werkt.

"Het is eigenlijk hetzelfde als wat de Lean Startup beschrijft," zegt Elie. "Bouwen, meten, leren. Steeds opnieuw. Eric Ries heeft dat niet zelf verzonnen — hij keek naar Toyota."

De Toyota-connectie is de moeite waard om even bij stil te staan, want ze verankert het hele idee in iets tastbaars. In de jaren zeventig en tachtig stond Toyota bekend om auto's die betrouwbaarder waren en goedkoper geproduceerd werden dan die van de Amerikaanse concurrentie. Het geheim was geen superieure technologie — het was een productiefilosofie. De Japanners hadden een systeem waarbij elke fout direct werd onderzocht, elke stap op de assemblagelijn continu werd geoptimaliseerd, en waarbij leren van fouten niet een eenmalige exercitie was maar een permanent, ingebakken onderdeel van het proces. Lean manufacturing noemden ze het. Een systeem dat nooit stilstaat.

Eric Ries vertaalde dat principe naar startups. Voordat de Lean Startup-beweging in zwang raakte, bouwden ondernemers hun product alsof ze kunstenaars waren: met intuïtie, met ambitie, en met weinig systematische feedback. Ries zei: dat werkt niet. Bouw klein, meet wat er gebeurt, leer ervan, bouw opnieuw. De loop als strategie.

Wat Elie nu deed, was precies hetzelfde — maar dan met AI-agenten als arbeiders op de assemblagelijn. Het principe was identiek. Alleen de uitvoering was radicaal anders.

En het bijzondere is hoe vertrouwd het aanvoelt zodra je het zo bekijkt. Iedereen die ooit serieus aan SEO heeft gedaan, heeft al een loop gedraaid. Je kijkt waar je rankt. Je analyseert wie er boven je staat. Je past een pagina aan. Een paar weken later kijk je opnieuw. Dat is geen technologische innovatie — dat is gewoon rationeel ondernemerschap. De vraag is alleen: moet jij degene zijn die die loop draait?

---

**Bouwen én verifiëren: de anatomie van een AI-loop**

Een loop met een AI-agent bestaat uit twee kernelementen, legt Elie uit: een bouwstap en een verificatiestap. Daartussenin zit wat hij een *stopconditie* noemt — de drempel waarop het systeem besluit dat het klaar is.

In technische termen: je vertelt de agent wat hij moet maken, en je geeft hem een objectieve maatstaf waaraan hij zijn eigen werk afmeet. Zo lang die maatstaf niet gehaald is, blijft hij proberen. Pas als hij over de streep gaat, stopt de loop.

Voor wie Claude Code gebruikt: het commando *slash goal* werkt precies op deze manier. Je geeft een doel op — zeg, maak de signup-functie werkend in de browser — en Claude Code start een tweede agent die controleert of het doel bereikt is. Is dat niet zo, dan instrueert die controlerende agent de bouwagent om door te gaan. De loop eindigt pas als de hoofdagent zijn eigen werk door de verificatielaag heeft gekregen. Dat is loop engineering in zijn puurste ingenieursvorm.

Een ander voorbeeld uit Elie's eigen praktijk: hij runt een product genaamd Inbox Zero, een AI die je e-mail beheert. Een cruciale vraag voor zo'n product is hoe goed het systeem e-mails categoriseert. Is dit een nieuwsbrief? Een factuur? Een persoonlijk bericht? Dat soort beslissingen worden getest via wat de industrie *evals* noemt — evaluaties, vergelijkbaar met unit tests maar dan voor AI-gedrag. Een eval meet hoeveel procent van de e-mails correct gecategoriseerd wordt.

Elie's loop ziet er dan zo uit: de agent past zijn prompt aan, draait de evals, en kijkt naar het resultaat. Als hij op 88 procent nauwkeurigheid zit, weet hij: nog niet goed genoeg. Hij past de prompt opnieuw aan, probeert een ander model, draait de evals opnieuw. Dat blijft doorgaan totdat de nauwkeurigheid boven de 90 procent uitkomt. Dat is de stopconditie. Dan is de loop klaar.

Het elegante aan evals is dat ze volledig objectief zijn. Er is geen discussie over of het systeem "goed genoeg" werkt. Het cijfer spreekt. En dat is precies wat je nodig hebt om een AI-agent autonoom te laten opereren: een maatstaf die geen interpretatie vereist.

Maar Elie's ambitie gaat verder dan engineering. De echte vraag is: wat als je deze structuur — bouwstap, verificatie, stopconditie — loslaat op de commerciële kant van een bedrijf? Op de marketing, de advertenties, de zoekmachineoptimalisatie?

---

**De SEO-loop: Google als scheidsrechter**

Van alle mogelijke toepassingen is SEO de meest voor de hand liggende startplaats. De reden is simpel: Google geeft je een getal. Je staat op positie 1, of positie 17, of positie 43 voor een bepaald zoekwoord. Die positie is objectief, meetbaar en openbaar beschikbaar via de Google Search Console API. Er is geen interpretatie nodig, geen subjectief oordeel — de machine kan de uitkomst zelf uitlezen.

"SEO is eigenlijk al een loop," zegt Elie. "Je kijkt waar je rankt. Je bedenkt wat je kunt verbeteren. Je voert wijzigingen door. En een paar weken later kijk je opnieuw. Dat is wat een goed SEO-bureau doet. De vraag is alleen: kun je een AI-agent dat zelfde proces laten uitvoeren?"

Het antwoord, zo blijkt uit zijn eigen experimenten, is: ja. Niet perfect, niet instant, maar aantoonbaar.

Om het concreet te maken, deelt Elie zijn Google Search Console van Draft Fantasy — een fantasiesportplatform dat hij twaalf jaar geleden bouwde en dat tot op de dag van vandaag draait. Niet zijn hoofdfocus, maar de recente FIFA Wereldkampioenschappen zorgden voor een significante opstoot in verkeer. In de afgelopen drie maanden genereerde de site tien miljoen impressies op Google zoeken. Het zoekwoord *38 zero* alleen al leverde 120.000 klikken op en een miljoen vertoningen. De gemiddelde positie voor dat woord: vier.

Elie's redenering is onverbiddelijk helder. Als hij die positie van vier naar drie kan tillen — of zelfs naar twee — dan verdubbelt of verdrievoudigt het aantal klikken. Niet omdat de content beter wordt, maar simpelweg omdat hoger ranken exponentieel meer verkeer oplevert. Positie vier geeft je 120.000 klikken. Positie twee of drie geeft je misschien een half miljoen. Dat is de natuur van zoekmachines: positie één pakt het leeuwenaandeel, alles daaronder verdient kruimels.

Twee dagen voor het gesprek gaf Elie zijn Claude Code-instantie een opdracht: doe voor Draft Fantasy hetzelfde als je al doet voor Inbox Zero. Zet een SEO-loop op. Maandelijks. Analyseer de data, voer verbeteringen door, documenteer wat je hebt gedaan, en begin volgende maand opnieuw vanaf waar je gebleven bent.

"Ik hoef er verder niet over na te denken," zegt hij. "Het draait in de achtergrond. En ik kijk er blij van op als ik op een dag zie dat we van pagina drie naar pagina twee zijn gegaan voor een zoekwoord waar we écht iets mee willen."

---

**De gereedschapskist: wat de agent nodig heeft**

Zoals een SEO-bureau niet zonder data kan werken, heeft ook de agent toegang nodig tot de juiste bronnen. Elie beschrijft twee onmisbare tools.

De eerste is Google Search Console. Dit is Googles eigen rapportagetool — gratis beschikbaar voor elke website-eigenaar — die laat zien voor welke zoektermen je rankt, op welke positie, hoeveel impressies je genereert en hoeveel mensen er daadwerkelijk op klikken. De tool heeft een API, wat betekent dat de agent er rechtstreeks mee kan communiceren. Geen scherm scrapen, geen handmatig kopiëren: de agent trekt de ruwe data op en verwerkt die.

De tweede tool is Data for SEO — een betaalde API die vergelijkbaar is met diensten als Ahrefs of Semrush. Waar Google Search Console je vertelt hoe jij scoort, vertelt Data for SEO je wie er bóven je staat en waarom. Welke artikelen ranken op positie één voor jouw doelzoekwoord? Hoe zijn die opgebouwd? Wat doen zij dat jij niet doet? Die context is goud waard voor een agent die moet beslissen waar hij zijn energie in steekt.

Elie benadrukt ook het belang van een goede eerste audit — iets wat elke website-eigenaar zou moeten doen, los van loops. Laat de AI door je site heen gaan en een volledige inventarisatie maken. Mis je een sitemap? Zijn je meta-descriptions optimaal? Zijn er JSON-LD-elementen die je een kleine rankingboost kunnen geven? Dit zijn directe quick wins die een agent in één sessie kan afhandelen. De loop zelf begint pas daarna, als het laaghangend fruit geplukt is en de echte iteratieve verbetering begint.

Met toegang tot beide bronnen kan de loop elke maand opnieuw het volgende doen: de huidige rankings ophalen, vergelijken met de vorige run, analyseren welke wijzigingen effect hebben gehad, bepalen wat er verbeterd kan worden, die verbeteringen doorvoeren in de blog of op de website, en alles nauwkeurig documenteren in een markdown-bestand dat de volgende run als startpunt gebruikt.

Dat laatste — het geheugen — is cruciaal. Zonder vastgelegde context begint de agent elke maand opnieuw bij nul. Met een goed bijgehouden logboek weet hij: vorige maand hebben we de meta-description van pagina X aangepast. Heeft dat geholpen? Als de ranking is gestegen, zet je door. Als die gedaald is, draai je de wijziging terug en probeer je iets anders. Precies zoals een menselijke SEO-specialist zou redeneren, maar zonder het uurtarief.

De loop heeft ook een logistieke staart: je wilt weten wanneer hij draait. Elie laat zijn agent hem een bericht sturen via Slack zodra een run is afgerond. Dat geeft hem de mogelijkheid om snel door de aanbevelingen te scrollen en, als hij iets ziet wat hem niet bevalt, zijn goedkeuring in te houden. De loop is autonoom, maar niet blind. Er is altijd een menselijke vinger boven de stopknop.

Voor wie de technische implementatie wil vermijden: Elie heeft een werkende versie van dit systeem uitgeschreven en gepubliceerd op atomeve.dev — een open prompt-template dat je kunt kopiëren en aanpassen voor je eigen situatie. De structuur is helder: hier zijn je tools, hier zijn je doelstellingen, hier is hoe je je bevindingen documenteert, en hier is de metric waarop je beoordeeld wordt. Wie liever direct aan de slag gaat in Claude Code of Codex, kan de URL simpelweg in de terminal plakken en de agent laten begrijpen wat er van hem verwacht wordt. Voor websites op WordPress geldt daarbij dat je de agent toegang geeft tot je WordPress-backend; voor sites op GitHub werkt een directe repository-koppeling het makkelijkst.

Om de loop terugkerend te laten draaien zonder dat je er elke keer aan hoeft te denken: Anthropic biedt routines aan in Claude, Cursor heeft zijn eigen automatiseringsmodus, en Codex noemt het gewoon automations. In elk geval is het principe hetzelfde — je stelt in dat de loop elke twee weken of maandelijks opnieuw opstart, en de agent pakt het op precies waar hij de vorige keer gebleven was.

---

**Goedkoper dan een bureau, trager dan je hoopt**

Elie's vriend Ross Mikey — een front-end engineer — bracht tijdens een eerder gesprek een populaire scepsis naar voren: de echte winnaars van de loop-hype zijn de token-leveranciers. Terwijl ondernemers dromen van zelfverbeterende bedrijven, verbrand het draaien van al die loops simpelweg geld. Peter Steinberger van OpenAI besteedt naar verluidt 1,3 miljoen dollar per maand aan AI-rekenkracht — en dat getal stijgt nog steeds. Niet elk bedrijf heeft dat budget.

Elie begrijpt de kritiek. Ross had het over engineering-loops, waarbij een agent zichzelf in een snelle cyclus repeteert en bij elke iteratie opnieuw tokens verbruikt. Die loops kunnen inderdaad duur worden. Maar voor de SEO-loop geldt een fundamenteel ander model.

"Een maandelijkse run kost je waarschijnlijk minder dan vijf dollar aan tokens. Het is niet zo dat de agent zichzelf de hele dag in een oneindige lus draait. Het is één run per maand, goed gedocumenteerd, en dan is het klaar tot de volgende cyclus."

Ter vergelijking: een goed SEO-bureau rekent al snel duizend tot vierduizend euro per maand. Zelfs als de loop maar tien procent van dat resultaat haalt, is de verhouding tussen kosten en opbrengst dramatisch anders. En de resultaten zijn, in Elie's eigen praktijk, hoger dan tien procent. Bepaalde rankings bewegen aantoonbaar in de juiste richting. Sommige zoekwoorden schuiven van pagina drie naar pagina twee. Dat vertaalt zich niet meteen in duizenden extra bezoekers — maar het legt het fundament.

Voor wie op een goedkoper abonnement zit en de tokenkosten nauwlettend in de gaten wil houden: open source-modellen als GLM 5.2 bieden een alternatief. Ze zijn minder krachtig dan Claude of GPT-4, maar voor de repetitieve, gestructureerde aard van een SEO-loop zijn ze vaak voldoende. En wie op een Max-abonnement zit — Anthropics 100- of 200-dollaroptie — heeft volgens Elie meer dan genoeg speelruimte. "Dan hoef je je over kosten echt geen zorgen te maken. Je hebt tienduizenden dollars aan tokenwaarde per maand. Gebruik het."

Over de tijdshorizon is hij eerlijk: verwacht geen wonder in de eerste weken. "SEO werkt altijd zo. Je doet de goede dingen, maanden lang, en dan slaat het omslagpunt toe. Ineens staat je ranking er anders voor." Hij vergelijkt het met een spaarrekening die jaren lang nauwelijks rente lijkt op te leveren — totdat het samengesteld effect zichtbaar wordt en je je afvraagt waarom je niet eerder bent begonnen.

Maar er is nog een dimensie die de tijdshorizon-discussie interessanter maakt: LLM-zoekopdrachten. Wie minder op Google en meer op ChatGPT of Perplexity zoekt, leeft in een wereld waar het concept *LEO* — Large Language Model Engine Optimization — langzaam relevant wordt naast de klassieke SEO. Alles wat je doet om je rankings in Google te verbeteren, verbetert tegelijkertijd je zichtbaarheid in AI-zoekresultaten. Het zijn communicerende vaten. Je investeert in één loop en de vruchten dalen neer op meerdere kanalen.

---

**Advertenties, sociale media en de hybride benadering**

De SEO-loop is het meest tastbare voorbeeld, maar Elie ziet hetzelfde patroon overal terugkomen. Bij Facebook-advertenties werkt de logica identiek: je hebt een doelstelling (winstgevendheid op je advertentie-uitgaven), een meetbare uitkomst (kosten per conversie, return on ad spend), en een agent die varianten test — andere teksten, andere afbeeldingen, andere doelgroepen — en na elke ronde kijkt wat werkte en wat niet.

Elie benadrukt daarbij een nuance die het verschil maakt tussen een goed systeem en een floploop: voor advertenties wil je menselijke tussenkomst behouden op het creatieve vlak. "AI is goed in het optimaliseren van kopij en in het analyseren van welke variant beter presteert. Maar de haak — het eerste moment dat iemand reden heeft om niet weg te scrollen — dat is nog altijd iets waarvoor de menselijke touch het verschil maakt." De loop in advertenties is dus een hybride: menselijke creativiteit als input, AI-optimalisatie als motor.

Dan is er sociale media. Op het eerste gezicht lijkt een loop voor Twitter of LinkedIn minder voor de hand liggend — er is geen simpele API die je positie terugkoppelt, zoals Google Search Console dat doet. Maar de data is er wel. Impressies per bericht. Likes per week. Het gemiddelde bereik over de afgelopen maand. Dat zijn stuk voor stuk objectieve getallen die een agent kan inlezen en waarop hij kan sturen.

Elie lacht even bij de gedachte aan een agent die honderdduizend volgers als stopconditie meekrijgt. "Dat is te ver. Je wilt beginnen met: heeft dit bericht tien likes gehaald? Dat is al een verifieerbare uitkomst." De redenering die hij zelf toepast is dezelfde die elke goede contentstrateg hanteert: je publiceert tien berichten, neegt doen niets, één scoort. Waarom scoorde die ene? Wat was anders — de toon, het moment, het onderwerp, de structuur? Dat is de leerinput voor de volgende cyclus. Een agent kan precies datzelfde proces uitvoeren, alleen sneller en systematischer dan jij het ooit zou bijhouden.

---

**De productfeedbackloop: de meest ambitieuze toepassing**

De meest ambitieuze toepassing is wat Elie de *productfeedbackloop* noemt — en wat hij rustig de ultieme versie van dit alles durft te noemen. In dit scenario leest de agent niet alleen rankingdata of advertentiemetrics, maar ook klantbeoordelingen, supporttickets, gebruiksanalyses en systeemlogboeken. Op basis van al die signalen prioriteert hij bugs, identificeert hij de meest gevraagde features, en stelt hij een roadmap voor — of voert die deels zelf uit.

Dit is het dichtst bij Dimitro's tweet. Een bedrijf dat zichzelf in stand houdt en verbetert. Niet volledig autonoom — niet nog. Maar dichter bij dan de meeste ondernemers denken. De agent wordt in dit scenario niet alleen een uitvoerder maar ook een prioriteringssysteem: hij weegt klachten af tegen featureaanvragen, vergelijkt ze met de technische complexiteit van een oplossing, en brengt de meest impactvolle wijzigingen als eerste aan.

"Dat is het dichtst bij Dimitro's tweet," zegt Elie. "Een bedrijf dat zichzelf in stand houdt en verbetert. Niet volledig autonoom — niet nog. Maar je kunt er al heel ver mee komen."

---

**De minimale leefbare loop**

Voor wie nog geen enkel geautomatiseerd proces heeft draaien, is de verleiding groot om te overweldigd te raken. Elie's advies is even simpel als het moeilijk is om na te volgen: begin klein.

Kies één kanaal. Kies één meetbaar getal. En begin daarmee.

De drempel hoeft niet hoog te zijn. Niet tienduizend volgers als einddoel, niet pagina één van Google als eerste stap. Begin met: heeft dit artikel meer impressies gekregen dan vorige maand? Heeft dit bericht tien likes gehaald? Dat is een verifieerbare uitkomst die de agent kan aansturen op, en die klein genoeg is om snel feedback te genereren.

Er is iets troostends in de manier waarop Elie het kader verwoordt. "Elke dag als je opstaat, loop jij ook een loop," zegt hij. "Je vraagt je af: hoe kan ik mijn bedrijf vandaag iets beter maken? Je checkt je metrics. Je past iets aan. Je gaat weer slapen. Dat is precies wat we de AI willen laten doen — maar dan zonder de slaap."

En misschien is dat de scherpste formulering van het hele idee. Jij bent al een agent. Je hebt al een stopconditie (genoeg omzet om de huur te betalen, genoeg gebruikers om te valideren). Je hebt al een bouwstap en een verificatiestap. De vraag is niet of je een loop draait — de vraag is of jij de enige bent die hem draait.

Het krachtige van dit idee is dat het exponentieel schaalt zodra het werkt. Eén loop voor SEO, één loop voor advertenties, één loop voor productfeedback, één loop voor sociale media — elk onafhankelijk, elk op zijn eigen ritme, elk lerend van zijn eigen historische data. Je bouwt geen machine. Je bouwt een ecosysteem van machines die zichzelf onderhouden.

En als een loop terugloop oplevert — als de SEO-ranking daalt in plaats van stijgt, als de advertentiekosten omhooggaan — dan is er weinig verloren. Elke wijziging die een agent doorvoert, is traceerbaar en omkeerbaar. Dat is het voordeel van goed gedocumenteerde experimenten boven intuïtieve beslissingen: je weet exact wat er veranderd is, en je kunt het terugdraaien. De markdown-log is niet alleen een geheugensteun voor de volgende run — het is ook een undo-knop voor de vorige.

---

**Wat er overblijft**

Loop engineering is geen magie. Het is geen garantie dat je bedrijf op de automatische piloot naar succes vliegt terwijl jij op het strand zit. Elie is daar eerlijk over. Agenten maken fouten. Rankings kunnen dalen. Advertenties kunnen floppen. En voor sommige taken — het bouwen van een echt publiek, het creëren van inhoud die mensen raakt, het formuleren van een strategie die verdere tijdshorizonnen overspant — is menselijk oordeel voorlopig onvervangbaar.

Maar dat is niet de vraag die centraal staat. De vraag is: welke delen van je bedrijf zijn al een loop — repetitief, meetbaar, gebaseerd op iteratieve verbetering — maar worden nu nog handmatig uitgevoerd, door jou of door iemand die je daarvoor betaalt?

Want voor die delen, zo blijkt, is de technologie er al. Niet als belofte, maar als iets wat Elie vandaag in productie draait. Zijn Draft Fantasy-site genereert tien miljoen impressies per kwartaal, deels aangestuurd door een systeem dat hij twee dagen eerder simpelweg aan de loop heeft toegevoegd. Zijn Inbox Zero-evals worden maandelijks bijgesteld door een agent die zichzelf verbetert totdat de nauwkeurigheidsdrempel gehaald is. En ergens op zijn computer draait een terminal met Codex open, klaar voor de volgende instructie.

Inmiddels weet Elie ook wat de Inbox Zero-site rankt voor de zoekterm *AI email assistant* — positie dertig of daaromtrent. Dat is nog ver van pagina één. Maar er is nu een loop aan het werk die elke maand een stap in de goede richting zet. Geen bureau, geen freelancer, geen wekelijks overleg. Alleen een agent die zijn eigen logboek bijhoudt, zijn eigen resultaten vergelijkt, en bij elke run iets slimmer wordt dan de vorige keer.

Dimitro's tweet was een grap. Maar de beste grappen bevatten altijd een kern van waarheid die te ongemakkelijk was om serieus te nemen. In 2026, zo lijkt het, hoef je inderdaad niet meer alles zelf te doen. Je hoeft alleen maar te weten welke loops je moet bouwen — en dan de machine zijn werk te laten doen.

Het enige wat je daarvoor nodig hebt, is een objectieve metric, een goede stopconditie, en de bereidheid om iets los te laten.

---

*Elie Steinbock bouwde Inbox Zero als tool om zijn eigen overvolle inbox te temmen. Draft Fantasy bestaat al twaalf jaar. Beiden draaien nu, mede, op loops. Het atomeve.dev-sjabloon dat hij deelde is publiek beschikbaar — een werkende versie van de SEO-loop die iedereen vandaag kan kopiëren en uitrollen.*