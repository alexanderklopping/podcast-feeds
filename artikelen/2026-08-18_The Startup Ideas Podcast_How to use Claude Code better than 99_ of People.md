<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01M089CF1MY5R8Q3NYJ3HMA0A0
-->

# De medewerker die nooit naar huis gaat

Dit is het verhaal van een gereedschap dat pas werkelijk krachtig wordt wanneer je het niet behandelt als een slim chatvenster, maar als een nieuwe collega. Niet een collega die zelfstandig de koers van een bedrijf bepaalt, maar wel een die kan lezen, onthouden, voorbereiden, bouwen, controleren en iedere ochtend opnieuw kan beginnen. De belofte is groot. De discipline die ervoor nodig is, is opvallend alledaags.

De maker van deze werkwijze begon met een waarschuwing die bijna als een excuus klonk. „This episode might feel a little boring at times,” zei hij. Er zouden mappen komen. Instructiebestanden. Beoordelingslijsten. Terugkerende taken. Geen spectaculaire robot die in één nacht een miljardenbedrijf opricht.

Maar juist daar, in die ogenschijnlijk saaie voorbereiding, zat volgens hem de echte voorsprong. Hij bood de methode gratis aan, als onderdeel van een cursus over Claude Code, en beloofde „all the prompts and all the sauce” weg te geven. Anthropic, het bedrijf achter Claude, sponsorde de aflevering. Toch ging het betoog niet over een wondermiddel dat je moest kopen. Het ging over een ongemakkelijke waarheid: de meeste mensen gebruiken een buitengewoon krachtig systeem alsof het een veredelde tekstgenerator is.

Ze openen een leeg venster en typen: *Maak de app beter.* Of: *Maak dit opvallender.* Of, nog vager: *Voeg AI toe.*

Daarna wachten ze af.

Soms levert dat iets bruikbaars op. Vaker begint dan pas het echte werk: uitzoeken welke bestanden zijn veranderd, waarom het systeem bepaalde aannames deed, welke onderdelen ongemerkt zijn geraakt en of er ergens in de technische fundering een balk is doorgezaagd.

Dat is geen probleem van intelligentie. Het is een probleem van leidinggeven.

Stel je voor dat er op maandagochtend een nieuwe medewerker op kantoor verschijnt. Je geeft hem geen bureau, geen toegang tot de klantgesprekken, geen uitleg over het product en geen overzicht van de risico’s. Je vertelt hem niet wie er betaalt, wat er op het spel staat of welke fouten je je niet kunt veroorloven.

Dan zeg je: „Maak het bedrijf beter.”

Geen verstandige oprichter zou dat doen. Maar zo behandelen veel mensen Claude Code wel.

Claude Code kan een projectmap lezen, code aanpassen, tests uitvoeren, een toepassing openen en door een gebruikersstroom klikken alsof het een klant is. Juist daarom vraagt het om structuur. Een briljante medewerker zonder context, grenzen en duidelijke opdrachten is niet productief; hij is onvoorspelbaar. De vraag is dus niet welke magische opdracht je moet typen. De vraag is eenvoudiger: wat heeft een goede medewerker nodig om goed werk te leveren?

Het antwoord bestaat uit negen onderdelen: een werkplek, geheugen, een briefing, heldere opdrachten, ogen, beoordeling, routines, bevoegdheden en ten slotte herhaalbare vaardigheden, koppelingen en automatische controles. Samen vormen zij geen kunstje, maar een werksysteem. Claude krijgt een plaats om te werken, context om het bedrijf te begrijpen, een manier om plannen te maken, een beperkte taak, een mogelijkheid om het resultaat te zien, een kwaliteitslat en grenzen waar het niet overheen mag.

Dan voelt het minder als een gesprek met een machine en meer als een operationele laag onder het bedrijf.

De praktijk begint in een projectmap.

In software heet zo’n map vaak een *repository*, doorgaans afgekort tot *repo*: de plek waar broncode, documentatie en technische geschiedenis bijeenkomen. In de bureaubladapp van Claude Code kies je die map als werkomgeving. Het scherm oogt vriendelijker dan een terminal vol commando’s, maar de betekenis is dezelfde. Dit is het kantoor van de digitale medewerker.

Voor een demonstratie koos de maker een idee uit een weinig glamoureuze, maar lucratieve markt: medische en cosmetische klinieken, in de Verenigde Staten bekend als *med spas*. Iemand vult ’s avonds een formulier in. Stuurt via Instagram een vraag over een behandeling. Belt na sluitingstijd om prijzen te horen. Aan de andere kant blijft het stil.

De volgende ochtend heeft die potentiële klant misschien al bij een concurrent geboekt.

In die stilte zat het productidee: software die gemiste aanvragen opvangt en onmiddellijk opvolgt. De koper is de eigenaar of bedrijfsleider van zo’n kliniek. Het probleem is scherp omlijnd: inkomende aanvragen worden koud doordat het team te laat reageert. De belofte nog scherper: „Respond to every missed lead before they book somewhere else.”

Reageer op iedere gemiste potentiële klant voordat die elders reserveert.

Een goede projectmap bevat daarom niet alleen code. Zij legt ook uit waarom die code bestaat.

In `/app` staat het product zelf: pagina’s, formulieren, logica en de zichtbare onderdelen van de toepassing. In `/context` leeft het zakelijke geheugen: marktinzichten, genomen besluiten, lessen en samenvattingen. In `/customers` komen verkoopgesprekken, ondersteuningsnotities, bezwaren en vooral de letterlijke taal van klanten terecht.

Verder zijn er `/specs`, met beschrijvingen van wat gebouwd moet worden; `/demos`, voor demonstratiestromen, Loom-scripts en schermafbeeldingen; en `/routines`, voor de terugkerende opdrachten die Claude op vaste momenten uitvoert.

In de hoofdmap liggen drie bescheiden tekstbestanden. `CLAUDE.md` is het medewerkershandboek: zo werken we hier, dit vinden we belangrijk, hier liggen de grenzen. `roadmap.md` legt vast wat nu telt. Niet alles wat ooit mogelijk is, maar de actuele koers. `review.md` bevat de kwaliteitslat waarlangs werk wordt gelegd voordat het verder mag.

Markdown-bestanden, aangeduid met `.md`, zijn gewone leesbare tekstbestanden met lichte opmaak. Juist dat maakt ze geschikt: een mens kan ze snel aanpassen en Claude kan ze goed verwerken.

De eerste opdracht aan Claude hoeft niet ingewikkeld te zijn:

> “Help me set up this repo as an AI employee workspace. Create or update `CLAUDE.md`, `roadmap.md`, `review.md`, `/context`, `/customers`, `/specs`, `/demos`, `/routines`.”

Daarna volgt de zakelijke context:

> “Product: missed-lead response for med spas. Buyer: med spa owner and operator. Pain: inbound leads are going cold when the team replies too late. Promise: Respond to every missed lead before they book somewhere else. Current goal: build a simple landing page and demo flow.”

En dan volgt de cruciale zin:

> “Before writing, ask me for any missing context that would materially change the setup and keep the first version simple.”

Die instructie geeft Claude toestemming om niet te doen alsof het alles al weet. Het mag vragen stellen. Gaat het om een schermdemonstratie of om echte berichten? Richt de eerste versie zich op zelfstandige klinieken of ketens? Moeten ingevulde formulieren werkelijk worden opgeslagen? Komen aanvragen vooral binnen via telefoon, via formulieren of via sociale media?

„I’ll ask you a few high-leverage questions first,” kan Claude dan antwoorden. „The answers change how I structure the demo flow and the customer spec folder. Everything else I’ll fill with sensible defaults and keep v1.”

Dat is geen vertraging. Dat is inwerken.

Zonder geheugen begint iedere taak in een vacuüm. Dan moet Claude telkens opnieuw gokken wie de klant is, welk probleem urgent is en welke zijpaden bewust buiten beeld moeten blijven. Een goed ingerichte projectmap is geen administratieve last; zij is het voorlopige brein van het bedrijf.

Maar een medewerker heeft meer nodig dan een kantoor en een geheugen. Hij moet weten hoe hij geacht wordt te werken.

Wie een junior ontwikkelaar aanneemt, zegt niet alleen welk resultaat er aan het eind van de week moet liggen. Je legt uit dat je kleine, controleerbare wijzigingen wilt. Dat grote aanpassingen eerst worden besproken. Dat bestaande stijlregels tellen. Dat tests worden uitgevoerd. Dat een overdracht niet eindigt met het woord *klaar*, maar met een overzicht: dit veranderde ik, dit heb ik getest, hier zit nog onzekerheid, hier moet een mens kijken.

Daarom kan de volgende vraag aan Claude luiden:

> “How do you optimize a `CLAUDE.md` file so it actually feels more like an AI employee?”

Het antwoord hoort niet in een vluchtig chatgesprek te blijven hangen. Het moet in het handboek terechtkomen. Daarin staat bijvoorbeeld dat de toepassing klinieken helpt sneller te reageren op gemiste aanvragen; dat de koper een eigenaar of bedrijfsleider is; dat de belofte draait om het terugwinnen van potentiële klanten voordat zij naar een concurrent verdwijnen.

Ook staat er een kwaliteitsnorm: de landingspagina moet binnen vijf seconden duidelijk maken wat zij biedt. De demonstratiestroom moet werken op een groot scherm én op een telefoon. De tekst moet klinken als de klant, niet als de maker.

Dat laatste verschil is groter dan het lijkt. Veel jonge producten praten over hun technologie. Hun klanten denken aan een overvolle receptie, omzet die weglekt en een bericht dat te lang onbeantwoord bleef. De sterkste tekst begint niet bij wat het systeem kan. Hij begint bij wat de koper vreest.

`roadmap.md` beschermt vervolgens tegen de natuurlijke neiging van zowel mens als model om elk logisch vervolg meteen mee te nemen. Voor de komende week kan daarin staan: bouw een eenvoudige demonstratie die laat zien hoe een kliniek gemiste aanvragen terugwint. Richt je op een landingspagina, een wachtlijstformulier, een demonstratiestroom en Loom-video’s voor tien eigenaren.

Maar de belangrijkste regels staan vaak onder één kopje: buiten reikwijdte.

Geen betalingen. Geen koppeling met een klantbeheersysteem. Geen beheerdersomgeving. Geen rechtenstructuur voor meerdere gebruikers.

Zonder die grenzen groeit een eenvoudig formulier als vanzelf uit tot gebruikersaccounts, databases, facturering en abonnementen. Aan het einde is er veel gebouwd, maar weinig geleerd. Een eerste versie is geen verkleind bedrijf. Het is het kleinste mogelijke experiment dat antwoord geeft op een serieuze vraag: vindt iemand dit probleem belangrijk genoeg om er tijd, aandacht of geld aan te besteden?

`review.md` bewaakt dat snelheid niet wordt verward met kwaliteit. Daarin staan vragen als: past deze wijziging bij de actuele koers? Is zij klein genoeg om goed te beoordelen? Werkt de belangrijkste gebruikersstroom nog? Zijn fouten in formulieren begrijpelijk afgehandeld? Zijn er risico’s rond betalingen of echte klantgegevens? Is er onnodige ingewikkeldheid toegevoegd?

Voor een landingspagina komen daar andere vragen bij. Begrijpt een bezoeker het aanbod binnen vijf seconden? Is de oproep tot actie zichtbaar? Spreekt de tekst de juiste koper aan? Gebruikt de pagina de woorden die klanten zelf bezigen?

Zo voorkom je wat de maker „AI slop” noemde: gladde, technisch correcte uitvoer zonder werkelijk nut. In het Nederlands: digitale brij die er af uitziet, maar niemand vooruithelpt.

De keuze van het model doet ertoe, maar is niet beslissend. Voor een eerste verkenning van een taak gaf hij soms de voorkeur aan Fable boven Opus. Toch vatte hij zijn punt samen in een zin die de kern van de hele methode raakt: „The beauty about Opus 4.8 or Fable 5, with the right MD files, the right structure, and the right brain, is that it does such a good job. But it does need these guardrails.”

Sterke modellen worden beter wanneer de organisatie om hen heen beter is.

Pas daarna volgt de briefing: eerst plannen, dan veranderen.

Wie een belangrijk project aan een mens geeft, gooit het niet over de schutting en hoopt op begrip. Je bespreekt wat je probeert te bereiken, welke beperkingen gelden, waar het risico zit en wanneer het resultaat goed genoeg is. In Claude Code heet die fase *plan mode*. De essentie is eenvoudig: Claude leest eerst de context, onderzoekt het project en laat zien hoe het de opdracht wil aanpakken voordat het bestanden wijzigt.

Voor het wachtlijstformulier luidt de opdracht:

> “Use plan mode. I want to add a waitlist form to the landing page. First inspect the current app, the `CLAUDE.md`, the `roadmap.md`, and `review.md`.”

Daarna:

> “Then give me the files that need to change, the smallest clean implementation, the user experience, the risks, how we will verify it, and what you are intentionally leaving out for the first version. Wait for my approval before editing.”

Daarmee verandert de verhouding. De oprichter krijgt iets terug waarop hij kan reageren. Misschien stelt Claude voor om alleen de voorkant te bouwen, omdat het product voorlopig een demonstratie is. Dan kan de oprichter zeggen: prima, nog geen opslag van gegevens. Of: verbind het met Supabase, een dienst die onder meer een database kan leveren, want ik wil echte aanmeldingen bewaren. Of: vraag uitsluitend naar naam, e-mailadres en bedrijfsnaam. Raak geen inloggen, betalingen of database aan.

Het plan hoeft niet volmaakt te zijn. Het moet de juiste vragen zichtbaar maken.

In dit geval stelt Claude wellicht Next.js en TypeScript voor. Voor de kliniekeigenaar achter het scherm zijn dat irrelevante namen; voor het team zijn ze praktische bouwstenen. Next.js helpt bij het maken van webtoepassingen. TypeScript dwingt ontwikkelaars om nauwkeuriger vast te leggen welke gegevens een programma verwacht, zodat fouten eerder aan het licht komen.

Op het scherm blijft uiteindelijk weinig over: een belofte, een formulier en een bevestiging.

Dan verschijnt de knop: *Accept*.

Het is een klein moment, bijna banaal. Maar het is een keerpunt. Tot dat moment heeft Claude alleen gekeken en voorgesteld. Vanaf dat moment mag het handelen. De gebruiker klikt op accepteren, en de digitale medewerker verandert bestanden.

Dat is waarom de oude timmermanswijsheid hier nog steeds geldt: twee keer meten, één keer zagen.

Na goedkeuring volgt het ticket: een kleine, heldere opdracht met een zichtbare finishlijn.

Een ticket is niet heroïsch. Het is concreet. „Voeg een wachtlijstformulier toe aan de landingspagina. Vraag om naam, e-mailadres en bedrijfsnaam. Toon na verzending een eenvoudige bevestiging. Houd de vormgeving in lijn met de bestaande merkstijl.”

Daarin zitten taak, reikwijdte, gewenste ervaring en grens.

Vergelijk dat met: *Maak de app beter.* Of: *Maak dit viraal.* Of: *Bouw alles.*

Zodra de opdracht vaag wordt, moet Claude gokken wat telt. En zodra het gokt, verandert het werk van de oprichter. Hij leidt niet langer een medewerker; hij ruimt de aannames van die medewerker op.

Een gericht ticket kan ook luiden:

> “Create a pricing page using the existing design system and keep it consistent with the homepage.”

Of:

> “Fix the onboarding redirect bug after email verification.”

Of:

> “Turn these five customer objections into a sharper landing page section.”

Na het plan volgt een tweede instructie, even belangrijk als de eerste:

> “Implement the approved plan as one focused change. Keep the change small enough that I can review it in the diff view. After editing, run the relevant checks, open up the app in the desktop preview, summarize what’s changed, tell me what you tested, and tell me what still needs human review.”

De *diff view* is de verschillenweergave: een overzicht van wat er vóór en na de wijziging in de bestanden staat. Welke regels kwamen erbij? Welke verdwenen? Welke bestanden zijn geraakt? In de bureaubladapp kun je die wijzigingen openen, opmerkingen achterlaten en Claude vragen iets opnieuw te doen.

De omvang van de taak doet ertoe omdat een kleine wijziging bestuurbaar blijft. Als Claude een formulier moest toevoegen en ineens de navigatie, toegangscontrole en databasestructuur heeft veranderd, is dat geen teken van initiatief. Het is een reden om stil te vallen.

Eén helder ticket tegelijk. Eén taak, één finishlijn, één wijziging die een mens werkelijk kan beoordelen.

Maar zelfs een nette verschillenweergave vertelt nog niet of een klant begrijpt wat er op het scherm gebeurt. Daarvoor zijn ogen nodig.

„The eyes: underrated.”

Die korte zin was misschien de scherpste samenvatting van de hele demonstratie. Ogen betekenen niet alleen dat Claude een voorvertoning kan openen. Ze betekenen dat het zijn eigen werk moet beleven zoals een klant dat beleeft. Een goede medewerker voert een taak niet uit en loopt vervolgens weg. Hij opent het product. Hij klikt door de stroom. Hij probeert iets verkeerd te doen. Hij leest foutmeldingen. Hij bekijkt technische logboeken. Hij zoekt de randvoorwaarde op die niemand in de vergadering had genoemd.

De lus is eenvoudig: bouwen, starten, gebruiken, testen, verbeteren.

Een landingspagina kan technisch foutloos laden en toch verwarrend zijn. Een formulier kan gegevens verzenden en toch ongemakkelijk voelen. Een knop kan bestaan, maar zo weinig opvallen dat niemand erop klikt. Een kop kan precies uitleggen wat het product doet en toch de angst van de koper missen.

Daarom luidt de inspectieopdracht:

> “Start the app and inspect the waitlist flow. Open the landing page in desktop preview. Check the experience from the perspective of a med spa owner seeing this for the first time. Then verify the implementation. Tell me what the buyer understands in the first five seconds, what feels confusing or low trust, whether the waitlist form works, and what happens after submission. Make one focused change to improve the highest-impact issue.”

Claude opent de pagina. De landingspagina verschijnt. Een bezoeker ziet de belofte, het formulier, de knop.

Dan kiest Claude niet voor de comfortabele route. Het begint waar echte gebruikers vaak beginnen: met een fout.

> “Empty submit first: click Join the Waitlist with nothing filled.”

De knop wordt ingedrukt zonder dat een veld is ingevuld. Verschijnt er een foutmelding? Is die duidelijk? Staat zij bij het juiste veld? Daarna vult Claude gegevens in en verzendt het formulier opnieuw. De succesmelding verschijnt. Het systeem controleert of er werkelijk een record is opgeslagen, als die koppeling al bestaat. Het leest de technische foutmeldingen en het netwerkverkeer na.

Dan volgt de belangrijkere ontdekking.

Niet de code blijkt de grootste belemmering. De grootste belemmering is vertrouwen.

> “The highest-impact issue: The page asks a cold med spa owner to hand over their email with no reassurance about what the waitlist is or whether they’ll get spam. This is the single biggest friction point on the action. Add expectation-setting microcopy at the CTA.”

Een onbekende kliniekeigenaar wordt gevraagd een e-mailadres achter te laten, maar krijgt niet te horen wat de wachtlijst inhoudt, wanneer hij iets ontvangt of of zijn inbox straks volloopt met ongevraagde berichten.

De oplossing is klein: een regel onder de knop. *Ontvang een korte demonstratie en vroege toegang. Geen spam.*

Maar de betekenis is groter. Claude heeft niet alleen vastgesteld dat het formulier werkt. Het heeft onderzocht waarom iemand misschien niet wil klikken. Dat is het verschil tussen software die draait en een product dat overtuigt.

Naarmate Claude sneller bouwt, verschuift de flessenhals. Niet productiecapaciteit vormt dan het grootste probleem, maar oordeel. Loste het systeem het juiste probleem op? Veranderde het de juiste bestanden? Schiep het een vreemde randvoorwaarde? Maakte het de ervaring helderder?

Daarom is beoordeling geen laatste formaliteit. Zij is het mechanisme dat snelheid bruikbaar houdt.

De eerste laag is menselijk. Open de verschillenweergave. Bekijk de aangeraakte bestanden. Leg ze naast het ticket en het goedgekeurde plan. Vraag: zit hier iets verrassends tussen?

Verrassingen zijn vaak de plek waar risico woont. Een formulier dat opeens wijzigingen veroorzaakt in de databasestructuur verdient aandacht. Een kleine tekstaanpassing die de hele route door de toepassing herschrijft eveneens. Niet iedere onverwachte verandering is verkeerd. Maar iedere onverwachte verandering verdient uitleg.

De tweede laag is Claude dat zijn eigen werk langs de afgesproken kwaliteitslat legt:

> “Use `review.md` as the standard. Review the current changes for production issues, broken edge cases, and confusing user flows. Separate issues into must fix, should fix, and okay to ship. Focus on bugs, user confusion, security risks, unnecessary complexity, files changed outside the scope of the ticket, and anything that violates the roadmap.”

Die driedeling — moet worden opgelost, zou moeten worden opgelost, kan worden uitgebracht — geeft taal aan nuance. Niet ieder onvolmaakt detail hoeft een uitgave tegen te houden. Maar een beveiligingslek, een fout in betalingen of een gebruiker die in een kapotte stroom terechtkomt, mag nooit als cosmetisch worden afgedaan.

Voor een gewone controle kan `/review` genoeg zijn. Maar bij werk met hogere inzet — toegangscontrole, betalingen, gevoelige gegevens of een grote nieuwe functie — is een zwaardere beoordeling verstandig:

> “Launch a remote ultra review session for this repository.”

Zo’n uitgebreide beoordelingssessie vervangt geen menselijk oordeel. Zij vormt een extra verdedigingslinie.

Daarna verschuift Claude van reagerende assistent naar proactieve medewerker. Dat gebeurt met routines: terugkerende taken die niet wachten tot iemand er expliciet om vraagt.

Ieder bedrijf kent werk dat zelden op een podium belandt. Iemand moet klantnotities lezen. Iemand moet zien welke klachten terugkomen. Iemand moet openstaande kwesties ordenen en benoemen welk probleem vandaag het meeste aandacht verdient.

Het is saai werk. Precies daarom blijft het vaak liggen.

De eerste routine moet niet zijn: zet vannacht zelfstandig nieuwe code in productie. Begin gecontroleerd:

> “Every weekday morning at 7 a.m., read `/customers` and `/context`, open GitHub issues if it’s connected, and then create or update `/context/morning-brief.md` with the top customer pain point from the latest notes, one product risk, one recommended build task for today, and one question I should ask customers today. Don’t edit production code, don’t open a pull request, and keep it under 500 words.”

GitHub is een platform waar softwareteams code, wijzigingen en foutmeldingen organiseren. Deze routine leest dus klantfeedback en openstaande problemen, en zet die om in een heldere ochtendbriefing.

Daarna kan een tweede routine op vrijdagmiddag draaien:

> “Every Friday at 3 p.m., review open issues and recent customer notes, group issues or identify duplicates, suggest the single highest-leverage fix for the week, and post the summary to `/context/weekly-ops.md`. Do not edit code.”

Vijf losse klachten kunnen dan één patroon blijken te zijn. Misschien worstelen klanten allemaal met dezelfde stap in de eerste gebruikerservaring. Misschien gebruiken zij steeds hetzelfde woord voor een frustratie die het team nog niet als probleem had herkend.

De routine wordt een soort stafchef. Niet degene die beslist, maar degene die de rommel ordent en zichtbaar maakt waar aandacht het meeste oplevert.

De kringloop sluit wanneer nieuwe wijzigingsvoorstellen ook langs die kwaliteitslat gaan. Een *pull request* is een voorstel om wijzigingen op te nemen in de gezamenlijke codebasis. De instructie kan luiden:

> “When a pull request opens, review it using `review.md`. Leave comments only on issues that could create bugs, broken user flows, security problems, or confusing behavior, and then post a short summary with what looks good, what needs attention, and whether this is ready for human review.”

Dat is de nachtploeg waar mensen over spreken wanneer ze zeggen dat Claude vierentwintig uur per dag werkt. Niet een systeem dat zonder toezicht een bedrijf bestuurt, maar een systeem dat feedback ordent, patronen zichtbaar maakt, risico’s naar boven haalt en de volgende nuttige stap steeds iets scherper formuleert.

Zodra die basis staat, kan werk parallel lopen.

In de bureaubladapp kunnen afzonderlijke sessies naast elkaar bestaan. Dankzij gescheiden werkomgevingen — in technische kring *worktree isolation* genoemd — lopen wijzigingen niet door elkaar heen alsof vijf mensen tegelijk dezelfde muur proberen te verplaatsen.

Stel dat er op een ochtend drie problemen wachten.

De eerste is technisch: na e-mailverificatie belandt een nieuwe gebruiker op de verkeerde pagina. De tweede gaat over producthelderheid: de openingssectie van de landingspagina is te vaag; een kliniekeigenaar begrijpt niet binnen vijf seconden waarom het product relevant is. De derde is commercieel: klantnotities liggen verspreid, maar niemand heeft ze omgezet in een demonstratie die de werkelijke bezwaren wegneemt.

In de oude werkwijze behandelt een oprichter die zaken na elkaar. Eerst de fout oplossen. Dan de tekst herschrijven. Daarna de demonstratie voorbereiden.

In de nieuwe werkwijze krijgt ieder spoor een eigen sessie, dezelfde projectcontext en een heldere overdracht.

Voor de foutmelding luidt de opdracht bijvoorbeeld:

> “Work on the onboarding redirect bug after email verification. Use the project context files before you propose a fix. Start by explaining what you think is causing the bug and which files you need to inspect. After I approve the plan, implement the smallest clean fix. When you’re done, give me the root cause, the files you changed, the checks or tests you ran, what I should review in the diff, and anything that feels uncertain.”

Voor de landingspagina:

> “Improve the landing page hero so a med spa owner understands the value in five seconds. Use `CLAUDE.md`, `roadmap.md`, `review.md`, and the latest customer notes. Keep the change focused on the hero section unless a small supporting change is necessary. When you’re done, give me the before and after copy, the customer language you used, what changed in the preview, and why the new version is clearer.”

En voor de verkoopdemonstratie:

> “Read the latest customer notes and turn them into a short demo script for the missed-lead responder. Use the customer’s actual language where possible. The demo should show the pain, the product moment, and the payoff. When you’re done, give me the demo script, the objection it addresses, and what I should review before recording.”

Dat zijn geen algemene wensen. Het zijn overdrachten die je letterlijk kunt kopiëren. Iedere sessie krijgt een duidelijke taak, dezelfde bedrijfscontext en een specifiek format voor de terugkoppeling.

Het doel is niet dat kunstmatige intelligentie werk in alle richtingen spuit. Het doel is dat je aan het eind van de dag drie kleine pakketten ontvangt die je kunt inspecteren, accepteren, aanpassen of afwijzen.

Meer autonomie zonder grenzen is geen schaalbaarheid. Het is roekeloosheid.

Daarom moeten bevoegdheden expliciet worden verdeeld in drie groepen: veilige handelingen, handelingen waarvoor eerst toestemming nodig is en handelingen die bij de mens blijven.

Veilige handelingen mag Claude zelfstandig uitvoeren: bestanden lezen, code onderzoeken, plannen voorstellen, lokale tests draaien, een kleine functietak aanpassen, documentatie bijwerken en een concept voor een wijzigingsvoorstel maken.

Voor andere handelingen moet het eerst toestemming vragen: nieuwe afhankelijkheden installeren, de structuur van een database aanpassen, toegangscontrole aanraken, betalingslogica wijzigen of bestanden verwijderen.

En dan zijn er de beslissingen die mens-gedreven blijven: een uitrol naar de productieomgeving, besluiten over klantgegevens, factureringskeuzes en beveiligingsgevoelige wijzigingen.

„Going YOLO mode is a bit too risky,” waarschuwde de maker. De gedachte dat je alles kunt toestaan en snelheid vanzelf de fouten compenseert, is geen moed. „Thinking about permissions as a strategy” is volgens hem de enige volwassen benadering.

Dat managementmodel is eenvoudig: geef ruimte én grenzen. Begin voorzichtig. Gebruik de planningsfase bij grotere veranderingen. Beoordeel handmatig terwijl je het systeem leert kennen. Geef pas meer vrijheid wanneer het geheugen van de projectmap, de beoordelingslijst en de afbakening van taken sterk genoeg zijn.

De laatste laag maakt Claude minder algemeen en meer eigen aan het bedrijf: vaardigheden, koppelingen en automatische controles.

Een vaardigheid is een herhaalbare manier van werken. Als je merkt dat je steeds opnieuw dezelfde opdracht typt, is het waarschijnlijk geen losse vraag meer. Dan is het tijd om die werkwijze vast te leggen.

Voor de kliniektoepassing kan er bijvoorbeeld een vaste analyse van de landingspagina bestaan. Iedere keer dat Claude die uitvoert, bekijkt het de pagina als een kliniekeigenaar: begrijpt deze persoon de belofte binnen vijf seconden? Welke tekst blijft vaag? Welke signalen van vertrouwen ontbreken? Is de oproep tot actie zichtbaar? Wat is de ene verbetering met de grootste impact?

Een tweede vaardigheid analyseert klantnotities. Zij haalt letterlijke formuleringen uit gesprekken, herkent terugkerende bezwaren en zoekt kooptriggers: de momenten waarop iemand laat merken waarom hij juist nu in beweging wil komen.

Dan bouwt Claude niet alleen vanuit de mening van de oprichter, maar vanuit de taal van de markt. Diezelfde vaardigheid kan later helpen bij advertenties, e-mails en verkoopmateriaal.

Een derde vaardigheid maakt een demoscript. Neem de huidige productstaat en de nieuwste klantnotities; zet ze om in drie delen: hier is de pijn, hier is het productmoment, hier is de opbrengst.

Koppelingen doen iets anders. Zij geven Claude gecontroleerde toegang tot bronnen buiten de projectmap: GitHub, Linear, Google Drive, Slack en vergelijkbare systemen. Linear is een hulpmiddel waarmee teams hun taken en productwerk bijhouden. Een koppeling is in wezen een beveiligde verbinding tussen Claude en een bron van bedrijfsinformatie.

Automatische controles vormen de derde categorie. In technische taal heten ze vaak *hooks*. Na een codewijziging kan zo’n controle de opmaak herstellen. Vóór een samenvatting van een wijzigingsvoorstel kan het eerst tests afdwingen. En voordat een wijziging wordt samengevoegd of uitgebracht, kunnen precies die controles draaien die voor dit project onmisbaar zijn.

Vaardigheden maken werk herhaalbaar. Koppelingen maken context rijker. Automatische controles maken uitvoering veiliger.

Samen met de actuele koers, de kwaliteitsnormen, klantnotities en routines vormen ze iets dat een concurrent niet zomaar kopieert. Het basismodel is voor velen beschikbaar. Maar de verzamelde context, de feedbacklussen, de gewoonten en de discipline zijn eigen werk. Daar ontstaat het verdedigbare voordeel.

Wie deze aanpak wil proberen, hoeft er geen groot veranderprogramma van te maken. Het kan in zeven uur, zeventig minuten, zeven dagen of eenendertig dagen, afhankelijk van ervaring, tijd en de rest van het leven. Maar een week biedt een bruikbaar ritme.

Op de eerste dag richt je het brein van de projectmap in: `CLAUDE.md`, `roadmap.md`, `review.md`, `/context`, `/customers` en de overige mappen. Je schrijft op wie de klant is, welk probleem centraal staat, wat het huidige doel is en wanneer iets als afgerond geldt.

Op de tweede dag gebruik je de planningsfase. Kies één kleine producttaak en laat Claude eerst de projectmap onderzoeken. De opbrengst is nog geen code, maar een plan: bestanden, risico’s en controlestappen.

Op de derde dag bouw je één zichtbare verbetering: een wachtlijstformulier, een prijspagina, een demonstratiestroom of een oplossing voor een fout in de eerste gebruikerservaring. Klein genoeg om te beoordelen, echt genoeg om aan een klant te laten zien.

Op de vierde dag gebruik je de kijk- en testlus. Laat Claude de toepassing openen, door de stroom klikken, de mobiele versie controleren en de grootste bron van verwarring aanpakken.

Op de vijfde dag beoordeel je het werk. Open de verschillenweergave. Lees wat er veranderde. Laat Claude het resultaat langs `review.md` leggen. Gebruik bij serieuze veranderingen, zoals betalingen of toegangscontrole, een zwaardere beoordeling.

Op de zesde dag stuur je het resultaat naar tien mensen die er mogelijk om geven. Verstuur de Loom-video, de demonstratie of de landingspagina. Maar laat hun antwoorden niet verdwijnen in een inbox of in je geheugen. Zet ze in `/customers`, waar zij de volgende briefing en productbeslissing kunnen beïnvloeden.

Op de zevende dag stel je de eerste routine in. Begin met de ochtendbriefing. Laat Claude klantnotities en openstaande kwesties lezen en één nuttige bouwtaak aanbevelen.

Dan sluit de lus.

Klantfeedback gaat naar `/customers`. Productrichting naar `roadmap.md`. Werkstijl naar `CLAUDE.md`. Kwaliteitsnormen naar `review.md`. Kleine taken beginnen met een plan. Wijzigingen gaan door voorvertoning en beoordeling. Terugkerend werk wordt een routine.

Dat is de medewerker die nooit naar huis gaat.

Niet omdat hij alle verantwoordelijkheden van een bedrijf kan dragen. Niet omdat menselijk oordeel overbodig wordt. Eerder het tegenovergestelde: deze werkwijze maakt zichtbaar waar dat oordeel onmisbaar blijft — bij richting, prioriteit, risico, gevoelige gegevens, geld en vooral bij de vraag wat klanten werkelijk waardevol vinden.

Maar zij verkleint wel de afstand tussen weten en doen. Het product, de feedback, de documenten, de demonstraties, de beoordelingen en het terugkerende werk leven in één operationele kringloop. Die kringloop wordt nooit perfect. Hij moet worden gevoed, aangescherpt en bewaakt.

Wie eenmaal zo bouwt, ziet het oude chatvenster moeilijk nog als vanzelfsprekend. Een systeem dat af en toe een antwoord geeft, voelt dan plotseling klein.

De interessantere vraag wordt: welke medewerker zou je aannemen als hij nooit moe werd, alles kon lezen, iedere ochtend een briefing kon schrijven, iedere wijziging kon controleren — en alleen nog moest leren hoe jouw bedrijf werkt?