<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01M2GC48TEYSXYAE7F98WCXJZ1
-->

# De fabriek zonder muren

Een softwarefabriek klinkt als het soort term dat snel genoeg wordt herhaald om zijn betekenis te verliezen. Maar achter de hype schuilt een nuchter idee: kunstmatige intelligentie kan pas betrouwbaar software bouwen wanneer je haar behandelt als een productielijn — met afzonderlijke werkplekken, vaste werkinstructies, kwaliteitscontrole en een deur die pas opengaat als het werk aantoonbaar goed is.

Greg Isenberg begon met de vraag die overal in de wereld van AI-start-ups rondzong: waarom ging dit zo hard rond?

Het antwoord, zei hij, lag besloten in een verleiding die bijna te mooi klonk om waar te zijn. Stel je een assemblagelijn voor. Geen staal, geen olie op de vloer, geen vonken van lasapparaten. Alleen software. De lijn neemt ideeën in ontvangst en levert toepassingen af: producten die mensen gebruiken, die omzet maken, die iets toevoegen aan het dagelijks leven. Niet één app, maar misschien tien. Of vijftig.

“Als je een fabriek kunt bouwen die waardevolle software produceert,” zei Isenberg, “klinkt dat mij behoorlijk goed in de oren.”

Dat was de haak. Niet: hoe schrijf je sneller code? Maar: hoe richt je een systeem in dat software kan voortbrengen zonder dat alles verandert in een berg haastig gegenereerde rommel?

Vóór die vraag serieus werd beantwoord, kwam de wereldlijke werkelijkheid even binnenrollen. Brex, de financiële dienst die Isenbergs bedrijf al anderhalf jaar gebruikte, passeerde de revue: hoge kaartlimieten, bankzaken, automatische declaraties. Vercel werkte ermee. OpenAI. Anthropic. Zelfs bedrijven die bezig waren de economie opnieuw uit te vinden met autonome agents, moesten nog steeds bonnetjes verwerken, kaarten uitgeven en rekeningen betalen.

Daarna verwelkomde Isenberg zijn gast terug: Mickey, bouwer, ontwikkelaar en iemand die met zichtbaar plezier een groot idee terugbracht tot een paar tekstbestanden.

“By the end of this episode,” zei Mickey, “you’re going to understand what this bizarre phrase, software factory, means.”

Hij zou laten zien hoe zijn eigen fabriek werkte. Niet als verkooppraatje voor een nieuw platform, benadrukte hij, maar als een methode die iedereen kon toepassen. De kijker kon na afloop zelf een softwarefabriek opzetten. Of besluiten: die Ross Mike en zijn fabrieken mogen het zonder mij doen.

Mickey vond beide uitkomsten prima.

De term werd inmiddels door start-ups met graagte geclaimd. Er verschenen producten, dashboards en beloftes van bedrijven die zeiden dat zij de fabriek hadden gebouwd. Maar volgens Mickey begon daar al de verwarring.

Een softwarefabriek was geen product dat je aanschafte. Geen exclusieve omgeving. Geen bijzonder model dat alleen in de handen van ingewijden werkte.

“Het is volledig onafhankelijk van model en werkomgeving,” zei hij. “Het maakt niet uit welk model je gebruikt. Het maakt niet uit welke werkomgeving je gebruikt.”

Met *werkomgeving* bedoelde hij de plek waarin een programmeeragent opereert: Claude Code, Codex, Cursor of een volgend systeem dat morgen alweer beter kon zijn. Het gereedschap veranderde voortdurend. De werkwijze moest blijven staan.

“Een softwarefabriek gaat over iemands workflow, vaardigheden en domeinkennis.”

Daarna hield Mickey halt, alsof hij zelf hoorde hoe lang de zin geworden was.

“That’s the long, bloated Michael Schimelist definition of software factory,” zei hij. “I haven’t lost anyone, hopefully, Greg.”

Isenberg lachte. De omschrijving was helder, zei hij. Maar waarom deed dit ertoe?

Omdat intelligentie snel toenam, antwoordde Mickey. Modellen als GPT-6 Astra konden steeds meer zelfstandig uitvoeren en maakten minder vaak dingen wijs. Wie ze gebruikte zoals de meeste mensen dat deden — een opdracht intypen, een resultaat bekijken, weer iets aanpassen, opnieuw proberen — liet een groot deel van hun kracht liggen.

Denk aan de laatste app die je hebt gebouwd, zei Mickey. Je opent Codex, Claude Code of Cursor. Je typt wat je wilt. De agent bouwt iets. Je ziet het scherm en denkt: nee, niet zo. Dan begint het heen en weer.

Maak die knop groter.

Waarom werkt dit niet?

Nee, ik bedoelde iets anders.

Misschien zet je het uiteindelijk online. Misschien blijf je urenlang bijsturen, alsof je een aannemer aanwijzingen geeft terwijl hij al midden in de muur staat te boren. Het resultaat kan bruikbaar zijn. Maar het proces blijft improvisatie.

Een fabriek moest juist het tegenovergestelde bieden: snelheid mét orde. Een transportband waarop werk vooruitging zonder dat kwaliteit onderweg van de band viel.

Mickey maakte de vaardigheden die hij daarvoor gebruikte gratis beschikbaar. Geen abonnement, geen betaalmuur. Toch wilde hij niet dat mensen zijn bestanden gedachteloos kopieerden.

“Mijn vaardigheden zijn gratis,” zei hij. “Maar ik wil niet dat mensen mij blind kopiëren. Ik wil dat ze het proces begrijpen en het vervolgens zelf toepassen.”

Zijn eigen fabriek bestond uit vijf of zes bestanden. Het belangrijkste droeg een naam die onopvallend genoeg was om bijna saai te klinken: AGENTS.md.

Een Markdown-bestand is niets meer dan een eenvoudig tekstdocument met kopjes, regels en opsommingen. Maar zodra het aan een agent wordt meegegeven, kan het functioneren als een werkinstructie die de agent leest vóór hij ook maar één regel code aanraakt.

“Every time I say hi,” zei Mickey, “if there’s an AGENTS.md file, before the hi is sent, the AGENTS.md file is sent.”

Nog voordat de begroeting bij de agent aankwam, lagen de regels al op tafel.

Veel mensen gebruikten zo’n document verkeerd, vond hij. Ze legden erin uit hoe hun codebase eruitzag: welke mappen waar stonden, welke functies in welke bestanden leefden. Maar een agent met toegang tot de code kon dat zelf uitzoeken. Dat was alsof je een timmerman de plattegrond van zijn werkplaats gaf, maar vergat te vertellen hoe het meubel moest worden gebouwd.

AGENTS.md moest niet uitleggen wat er in de code stond. Het moest vastleggen hoe er gewerkt werd.

Mickey had zijn aanpak teruggebracht tot vier stappen: isoleren, bouwen, bewijzen en verschepen.

De eerste stap — isoleren — begon met een regel die in zijn bestand stond alsof hij in steen was gebeiteld:

“Every new feature starts in the fresh Git worktree branched from origin main so agents can work in parallel without conflicts. Never build on main.”

Elke nieuwe functie begint in een verse *worktree*, afgeleid van de actuele hoofdversie. Nooit rechtstreeks bouwen in *main*.

Voor niet-programmeurs klonk dat misschien als jargon, maar Mickey maakte het tastbaar. Stel dat de hoofdversie van de app een oorspronkelijk document is. Iemand kopieert het document precies zoals het er op dat moment uitziet, plakt het in een nieuw bestand en gaat daarin werken. Pas wanneer het werk klaar en gecontroleerd is, voegt diegene de wijzigingen terug in het oorspronkelijke document.

Een *branch* was die aftakking in de geschiedenis van de code. Een *worktree* was de concrete, tijdelijke kopie waarin iemand werkte: een aparte werkplek, gebaseerd op precies het moment waarop de opdracht begon.

Dat verschil was belangrijk.

Isenberg stelde zich een app voor die onderweg was van eerste ingeving naar duizenden klanten. De meeste makers, zei Mickey, bewogen daar doorheen in een rechte lijn. Ze bouwden één functie. Daarna de volgende. Daarna nog één. Zodra zij verschillende dingen tegelijk wilden doen, ontstond de ellende die overal op sociale media opdook.

Mijn agent heeft bestanden verwijderd.

Mijn agent heeft mijn werk overschreven.

Gisteren werkte het nog.

Neem twee opdrachten die op het eerste gezicht niets met elkaar te maken hebben. Greg wil de landingspagina vernieuwen. Mickey wil dat de API-aanroepen sneller worden. De ene agent begint aan kleuren, tekst en ontwerp. De andere onderzoekt waarom de pagina zo traag reageert, ziet gebrekkige aanroepen naar de achterliggende systemen en besluit bestanden te verwijderen en functies opnieuw te schrijven.

Op hetzelfde moment werkt de eerste agent aan precies die pagina.

Er ontstaat geen mysterie. Er ontstaat een botsing.

“De agent doet wat je hem opdraagt,” zei Mickey. “Bijna altijd gaat het mis omdat mensen agents op verschillende functies laten werken binnen dezelfde branch.”

Isenberg zag hierin iets groters dan een technisch trucje. De nieuwe lichting app-bouwers bestond uit ondernemers, ontwerpers, marketeers en generalisten die nooit hadden geleerd wat ontwikkelteams allang vanzelfsprekend vonden.

“Als je een team van engineers had dat aan een app werkte,” zei hij, “zou je niet iedereen op *main* laten bouwen en iedereen rechtstreeks naar *main* laten pushen. That just doesn’t make sense.”

Hij maakte de schade scherp: “95 procent van de tijd” dat agents bestanden overschreven of werk kapotmaakten, kwam het doordat verschillende agents tegelijk op dezelfde versie aan het werk waren gezet.

De echte vraag luidde daarom: hoe structureer je het werken met agents zodat het meer op een team lijkt?

“More like a team,” zei Mickey.

Isenberg grijnsde. Misschien was *team* zelfs een betere naam dan *isolate*.

“Daarom ben jij de marketeer en ik de engineer,” zei Mickey.

Maar de naam deed er minder toe dan de discipline. Elke agent kreeg zijn eigen afgebakende werkplek. Daardoor konden Greg, Mickey — of vijftig agents tegelijk — aan afzonderlijke functies werken zonder in elkaars bestanden te snijden. Was het werk uiteindelijk samengevoegd met de hoofdversie, dan volgde ook de opruiming: de tijdelijke *worktree* werd verwijderd. Geen vergeten kopieën. Geen oude zijpaden waarin weken later nog onduidelijke wijzigingen rondzwierven.

Op Mickey’s scherm stond dat systeem al te draaien. Vier tabbladen voor zijn toepassing Bezos. Drie taken waren klaar. Eén liep nog. Een agent bouwde een e-mailclient. Een andere werkte aan een afgebakende Linux-omgeving, een digitale computer waarin een agent zelfstandig taken kon uitvoeren. Een derde vernieuwde de landingspagina.

Vier functies. Eén product. Geen agent die de ander in de weg zat.

Maar isolatie beschermde vooral tegen chaos. Zij maakte slechte code niet goed.

Daarvoor kwam stap twee: bouwen.

Mickey gebruikte hiervoor een vaardigheid die hij *code structure* noemde. De agent kreeg niet alleen de opdracht om iets te maken, maar ook instructies over de manier waarop de code moest worden georganiseerd. Mickey werkte met een zogeheten service-laagarchitectuur: een vaste indeling waarin de kernlogica van een toepassing niet verspreid raakt over losse schermen, knoppen en tijdelijke oplossingen. Voor de lezer is het voldoende om het te zien als de bedrading achter een huis: als die ordelijk is aangelegd, kan iemand later een probleem vinden zonder eerst muren open te breken.

Modellen waren uitstekend geworden in het afleveren van iets dat werkte. Fable, zei Mickey, was een van de eerste modellen waarvan hij soms dacht dat het betere code schreef dan de beste engineers die hij had meegemaakt. Astra was zijn werkpaard, zijn favoriete model.

Toch maakte zelfs een sterk model soms keuzes die een ervaren ontwikkelaar liever niet zag.

“Het is niet dat het model het niet kan,” zei Mickey. “Het model krijgt het gewoon af. En als het dat op een slordige manier kan doen, doet het het op een slordige manier.”

Hij had GPT-5.6 Sol eens een functie laten schrijven. De code werkte. Ze deed wat ze moest doen. Daarna liet hij Fable ernaar kijken.

“This is disgusting,” was het oordeel.

Duplicaties. Functies die overal verspreid stonden. Dode code: oude resten die niets meer uitvoerden, maar wel in het project bleven liggen.

Werkende code was niet automatisch goede code. Een deur kan moeiteloos openen terwijl achter de muur een kluwen onafgewerkte draden hangt. Het probleem verschijnt pas wanneer iemand later iets moet aanpassen — of wanneer je een menselijke ontwikkelaar inhuurt die eerst moet uitzoeken waar alles gebleven is.

Mickey werkte aan een opslagplaats voor vaardigheden, een systeem waarin verschillende agents instructies konden bewaren en ophalen. Zijn opdracht was eenvoudig geweest: bouw dit. Maar tijdens het werk verwees de agent voortdurend terug naar de regels voor structuur.

Dat was het punt. De code moest niet alleen begrijpelijk zijn voor Mickey. Ook een ontwikkelaar die later werd ingehuurd moest ermee uit de voeten kunnen. En een nieuwe agent, zonder enig geheugen van eerdere gesprekken, moest de logica kunnen volgen.

Anders, zei Mickey, kreeg je de *slop cannon*: een kanon dat eindeloze hoeveelheden min of meer bruikbare, maar chaotische code de wereld in schiet. Wie zo’n systeem later moest repareren, raakte niet alleen verdwaald. Hij stuurde ook een rekening.

Eerst isoleren. Dan bouwen.

Maar hier dook het echte probleem op: vertrouwen.

Een softwarefabriek met tientallen agents kon alleen werken als degene die haar leidde wist wanneer iets werkelijk af was. Niet wanneer een agent zei dat het af was. Niet wanneer het verslag er professioneel uitzag. Wanneer het bewijs er lag.

“Agents can’t pinky-promise.”

Agenten kunnen geen pinky promise doen — geen kinderlijke plechtige belofte afleggen die voldoende reden is om hen te geloven. Zelfs GPT-6 Astra, dat Mickey als uitzonderlijk betrouwbaar beschouwde, kon een test overslaan of een verkeerde conclusie trekken. Andere modellen konden ronduit beweren dat een taak was uitgevoerd, om later toe te geven dat ze het werk niet hadden afgemaakt.

Daarom volgde stap drie: bewijzen.

De eerste vaardigheid heette *evidence-driven testing*: testen die niet eindigen met een bewering, maar met zichtbaar bewijs. Als een machine video kon opnemen, legde de agent eerst de beginsituatie vast. Bij een fout registreerde hij hoe de fout zich voordeed. Daarna herstelde hij de code en voerde exact dezelfde handeling opnieuw uit.

Niet: de bug is opgelost.

Maar: kijk. Hier ging het mis. En hier werkt dezelfde handeling wel.

Kon de machine geen video maken, dan gebruikte Mickey een tweede vaardigheid: *before and after*. Voor iedere wijziging die klaarstond om te worden samengevoegd, moest de agent een duidelijke voor- en nasituatie tonen.

Mickey opende een wijzigingsvoorstel dat geheel door een agent was gemaakt. Hij had gevraagd om een beheerderspagina voor e-mail, verbonden met een eigen e-maildienst. In het eerste beeld was die pagina er niet. Geen verborgen knop. Geen onaf scherm. Alleen afwezigheid.

In het tweede beeld stond de pagina er wel.

Voor iemand die geen code las, veranderde alles. De beoordeling werd plotseling menselijk. Je hoefde geen honderden regels te ontcijferen. Je kon kijken: verschijnt het scherm? Werkt de verbinding? Is de fout verdwenen?

Isenberg zag onmiddellijk de vorm ervan. Het leek op Instagram Stories of Snapchat Stories: korte, opeenvolgende fragmenten die je zonder technische voorkennis begreep.

“Exactly,” zei Mickey. “It’s bite-sized.”

De kracht van die werkwijze werd het duidelijkst in een mislukking.

Mickey wilde zijn agent toegang geven tot een computeromgeving. Een afgebakende Linux-machine waarin de agent zelfstandig zou kunnen handelen. De eerste poging deed hij op een andere computer, buiten zijn eigen fabriek, zonder de bijbehorende vaardigheden.

De agent schreef de code. De wijziging werd doorgestuurd. Alles leek gereed.

Toen keek Mickey naar het scherm.

Niets.

Geen muis die bewoog.

Geen venster dat opstartte.

Geen computeromgeving.

Alleen een dood scherm.

Hij zei tegen de agent dat de functie niet werkte. Ditmaal voegde hij iets toe: gebruik de vaardigheden. Gebruik de fabriek.

Daarna kwam de tweede opname.

Eerst stilte.

Toen beweging.

De agent werkte zichtbaar in de toepassing. De computeromgeving deed wat zij moest doen.

Dat was het keerpunt, niet alleen in die ene opdracht, maar in Mickey’s hele betoog. Een agent had niet gefaald omdat hij onvoldoende intelligent was. Hij had gefaald omdat niemand hem had gedwongen zijn werk te controleren. De tweede keer kreeg hij niet slechts een nieuwe opdracht. Hij kreeg een systeem.

Ook prestaties konden bewijs leveren, al lieten ze zich minder gemakkelijk filmen. Mickey had een toepassing waarvan de knoppen niet scherp genoeg reageerden. Een klik bleef net te lang hangen. De pagina kwam traag op gang. Hij gaf de agent de opdracht het te herstellen.

De agent leverde schermafbeeldingen, maar belangrijker: metingen.

Een pagina laadde vóór de wijziging in 850 milliseconden.

“This is a sin in web development,” zei Mickey.

De oorspronkelijke code kwam uit GPT-5.6 Sol, een model dat hij goed vond. Maar gebruikers ervaren geen waardering voor een goed model. Zij ervaren vertraging.

Na de aanpassing stond de laadtijd op 60 milliseconden. In een andere meting zakte de tijd van 817 naar 61 milliseconden.

Dat was bewijs waarover nauwelijks te onderhandelen viel.

Soms ontdekte een agent door zijn eigen bewijs dat hij nog niet klaar was. Hij maakte een opname van de eindsituatie, bekeek die en zag dat de functie niet werkelijk deed wat hij moest doen. Dan hoefde Mickey niet terug te komen met een geïrriteerd bevel. De werkwijze bepaalde al wat er gebeurde: terug naar bouwen.

Hier bracht Isenberg de gedachte onder woorden die onder de hele methode lag.

“Als je een softwarefabriek probeert te bouwen,” zei hij, “wordt vertrouwen vanzelf een groot onderdeel daarvan.”

Mickey was in dit systeem niet meer voortdurend de programmeur. Hij was de manager van agents. Hij keek naar wat er gebeurde, beoordeelde het bewijs en besloot wanneer iets verder mocht.

Dat leek, merkte Mickey op, sterk op hoe goede organisaties altijd al hadden gewerkt. Een ontwikkelaar bouwde een functie. Daarna bekeek een senior engineer de wijziging, de toelichting en de tests die moesten aantonen dat alles werkte.

Alleen waren het nu deels machines die die rollen vervulden.

Mickey las nauwelijks nog alle code. Hij bekeek de structuur vluchtig. Vervolgens keek hij naar beelden, video’s en meetwaarden. In een opname van Claude Code Cloud Agents stond boven de video: *Proof of improvement*. De agent gebruikte de toepassing zichtbaar voor degene die moest goedkeuren.

Zo kon Mickey samenvoegen, naar buiten gaan en, zoals hij het zelf zei, “touch grass”.

Maar ook dat vertrouwen kende een grens. Een agent die zijn eigen werk test, blijft degene die het werk heeft gemaakt. Hij kan iets missen. Hij kan een foutloze schermafbeelding tonen terwijl elders in het systeem schade is ontstaan.

Daarom volgde stap vier: verschepen.

Verschepen betekende niet: zonder nadenken live zetten. Het betekende dat een onafhankelijke beoordelaar de wijziging onderzocht voordat die deel werd van de hoofdversie.

Mickey gebruikte daarvoor Greptile, een dienst met een aparte codebeoordelende agent. Hij noemde ook CodeRabbit en Macroscope. De precieze leverancier interesseerde hem minder dan het principe. Wie software bouwde die echte mensen zouden gebruiken, moest onafhankelijke controle organiseren.

“I don’t understand why you wouldn’t use Greptile, CodeRabbit, or one of these tools.”

Aan de andere kant van een kapotte toepassing zat altijd een gebruiker. Iemand die tijd verloor. Iemand die gegevens invoerde in een systeem dat op een cruciaal moment niet reageerde. Iemand die op een knop drukte en naar een leeg scherm keek.

Dat vereiste, vond Isenberg, een minimum aan empathie.

Ondertussen waren de drempels laag. Veel van deze jonge, rijk gefinancierde bedrijven boden gratis instapmogelijkheden. Er was weinig reden om geen tweede paar ogen naar je code te laten kijken, zelfs als die ogen van een machine waren.

Mickey had zijn procedure *GrepLoop* genoemd. De naam vertelde precies wat hij deed: een lus vormen tussen de agent die de code schreef en de agent die haar beoordeelde.

Eerst opende de programmeeragent een wijzigingsvoorstel. In de beschrijving zette hij het voor-en-na-bewijs. Was de verandering zichtbaar, dan voegde hij afbeeldingen of video’s toe. Ging het om snelheid, berekeningen of andere zaken die zich niet goed in een scherm lieten vangen, dan leverde hij meetwaarden, testresultaten of uitvoerparen aan.

Daarna kwam Greptile.

Bij een wijziging die Mickey liet zien, vond de beoordelende agent twee problemen. De paginering werkte niet goed. In een menu bleef de benodigde ruimte niet behouden. Kleine gebreken, misschien. Maar precies zulke gebreken vormden het verschil tussen een demo die één keer overtuigt en een product dat mensen elke dag moeten kunnen vertrouwen.

Greptile gaf niet alleen opmerkingen. Het gaf ook een betrouwbaarheidsscore.

Drie van de vijf.

Dat was geen eindpunt. Het was het begin van de lus.

Drie van de vijf betekende: terug naar bouwen.

De agent las de opmerkingen, herstelde de paginering, paste het menu aan en controleerde de rest van de wijziging. Daarna ging hij terug naar bewijzen. Nieuwe beelden. Nieuwe tests. Nieuwe meetwaarden, waar nodig. Vervolgens bood hij het werk opnieuw aan voor beoordeling.

De score steeg naar vier van de vijf.

Bijna goed.

Maar bijna goed ging in deze fabriek niet naar buiten.

Dus terug naar bouwen. Terug naar bewijzen. Opnieuw ter beoordeling aanbieden.

Pas bij de derde ronde kwam de score die Mickey wilde zien: vijf van de vijf.

De regel in zijn instructies was kort en onverbiddelijk:

“Greptile reports five out of five until resolved. Comments finished by presenting PR URL.”

Greptile blijft rapporteren totdat alles is opgelost. Pas daarna presenteert de agent de link naar het wijzigingsvoorstel.

Bij grote veranderingen — vanaf ongeveer 10.000 regels gewijzigde code — trad die procedure automatisch in werking. Mickey hoefde niet langer opmerkingen uit een scherm te kopiëren en die om te zetten in nieuwe opdrachten. De lus was onderdeel geworden van de fabriek zelf.

Drie van de vijf: terug naar bouwen.

Vier van de vijf: terug naar bouwen.

Vijf van de vijf: nu kwam de mens weer nadrukkelijk in beeld.

Mickey klikte op samenvoegen.

De wijziging keerde terug naar de hoofdversie. De tijdelijke *worktree* werd opgeruimd. En ondertussen draaiden vijftien functies tegelijk: vijftien verschillende opdrachten, uitgevoerd door agents en subagents, ieder in een eigen afgeschermde werkruimte.

De schaal kwam niet voort uit vijftien keer harder werken.

Ze kwam voort uit volgorde.

Aan het einde vatte Isenberg de methode samen aan de hand van het beeld waarmee hij was begonnen. Isoleren was een fabriek die een maatwerkopdracht een eigen werkstation gaf, zodat de rest van de productie onaangeroerd bleef. Bouwen was de assemblagelijn: snijden, lassen, bedraden en monteren, maar dan met bestanden, functies en structuur. Bewijzen was kwaliteitscontrole: testen, logbestanden, video’s, schermafbeeldingen en metingen. Verschepen was de laatste controle vóór het product de deur uitging — en, als die controle faalde, de terugkeer naar het begin van de lus.

Mickey luisterde en lachte. Misschien, zei hij, moest hij zijn eigen namen inderdaad vervangen door die van Greg.

Maar de kern bleef staan.

Een softwarefabriek was niet het nieuwste model. Niet een bijzondere werkomgeving. Niet een product met een glanzend prijskaartje. In de meest nuchtere vorm was zij een handvol Markdown-bestanden waarin stond hoe agents moesten werken, hoe zij hun resultaten moesten aantonen en wanneer zij moesten terugkeren naar de werkbank.

De mens bepaalde nog altijd de norm. Hij besloot wat voldoende bewijs was. Hij koos de structuur. Hij drukte uiteindelijk op de knop om samen te voegen.

Maar hij hoefde niet langer iedere schroef zelf vast te draaien.

Mickey had zijn fabriek niet gebouwd door een magische machine te vinden. Hij had haar gebouwd door intelligente, ongeduldige machines regels te geven.

En juist daarom kwam zijn slotzin zo scherp aan.

“Notice we didn’t talk about the model. We didn’t talk about the harness.”