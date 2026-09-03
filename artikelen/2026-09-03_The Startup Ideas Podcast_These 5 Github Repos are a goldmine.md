<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01M1HGMVD210P85FN5GWX5HEQG
-->

# De Gereedschappen Vóór de Markt Ze Een Naam Geeft

Wie vroeg genoeg op GitHub kijkt, ziet niet alleen code. Hij ziet onaffe gewoonten, beginnende bedrijven en hele categorieën werk die nog geen verkoopprijs hebben. De vijf projecten in dit verhaal — aangekondigd als zes, maar in de aflevering uiteindelijk als vijf behandeld — laten zien waar de voorsprong ligt: niet in wachten tot AI een keurige dienst met een logo wordt, maar in één klein proces eerder leren gebruiken dan de rest.

De spreker had de laatste tijd een nieuwe gewoonte ontwikkeld. Hij bracht meer uren door op GitHub, tussen de openstaande problemen, half afgemaakte handleidingen en mappen met namen die alleen voor de maker zelf logisch waren. Niet uit nostalgie voor programmeurswerk, maar omdat hij daar iets zag wat elders al schaarser werd: voorsprong.

“De toekomst is al hier,” luidt de vaak aangehaalde observatie van sciencefictionschrijver William Gibson. “Hij is alleen nog niet eerlijk verdeeld.” Voor de spreker was GitHub zo’n plek waar de toekomst zich ophoopte, nog voordat zij werd verpakt in abonnementen, verkoopdemo’s en gladde landingspagina’s. Gereedschappen waar mensen over zes maanden over zouden praten, lagen er nu al klaar. Veel ideeën die later zouden uitgroeien tot SaaS-bedrijven, bureaus, werkmethodes of start-ups begonnen hier: als open-sourceproject van een kleine ontwikkelaar die een probleem had opgelost en de oplossing online zette.

Hij had tientallen repositories doorgespit die in de voorafgaande dertig dagen veel aandacht hadden getrokken. Daaruit selecteerde hij, zo kondigde hij aan, zes projecten voor mensen die producten wilden bouwen, tijd wilden besparen, geld wilden verdienen of eenvoudigweg meer gedaan wilden krijgen met AI. “De laatste is van NVIDIA,” zei hij erbij, alsof hij zijn publiek alvast een herkenbare naam wilde geven tussen de kleinere ontwikkelaars.

Maar in de aflevering zelf behandelde hij uiteindelijk vijf repositories. Een zesde project werd niet genoemd en ook niet toegelicht; mogelijk viel het onderweg af, mogelijk bleef het steken in de voorbereiding. NVIDIA’s Skill Spectre kwam bovendien niet als laatste, maar als vierde aan bod. Wat overbleef, was geen lijstje van zes maar een bruikbare verzameling van vijf. Alle vijf waren gratis en open source — de broncode mocht worden bekeken, gebruikt en aangepast — al betekende gratis niet altijd kosteloos. Video Use kon bijvoorbeeld een koppeling met ElevenLabs nodig hebben, een betaalde dienst voor synthetische stemmen.

Voordat hij begon, deed hij nog wat iedere podcasthost in het tijdperk van aanbevelingsalgoritmen doet: hij vroeg luisteraars te liken, te reageren en zich te abonneren, “zodat het algoritme je meer waardevolle inhoud voorschotelt.” Daarna schoof hij de formaliteit opzij.

“Let’s go.”

Het eerste gereedschap begon niet met techniek, maar met een onderbuikgevoel. Een geur.

Iedereen die ChatGPT of Claude gebruikt om te schrijven, kent het moment waarop een tekst technisch nergens op stukloopt en toch niet overtuigt. Je vraagt om een LinkedIn-bericht, een tweet, een koude e-mail of copy voor een productpagina. De grammatica klopt. De zinnen zijn verzorgd. De structuur staat rechtop.

Maar de tekst lijkt nergens gewoond te hebben.

Hij is te glanzend, te symmetrisch, te tevreden met zijn eigen evenwicht. Hij zegt niet gewoon iets; hij kondigt aan dat hij iets gaat zeggen. Hij gebruikt tegenstellingen alsof ze uit een mal komen: *“Het is niet X, maar Y.”* Of hij strooit met woorden als *quietly*, alsof iedere ontwikkeling zich heimelijk moet voltrekken om belangrijk te klinken. “Het voelt,” zei de spreker, “alsof je een keynote leest van een nep-SaaS-conferentie.”

En dan gebeurt er iets vervelends. “Once you notice it, you can’t unsee it.” Zodra je het ziet, kun je het niet meer níét zien.

Peter Yang — ontwikkelaar, schrijver en een vriend van de spreker — bouwde daarom *No AI Slop*. Het is een skill: een pakket instructies dat je toevoegt aan een AI-agent, zodat die een afgebakende taak volgens vaste regels uitvoert. In dit geval is die taak niet: schrijf beter. De taak is: haal de herkenbare machinale patronen uit een tekst, zonder de schrijver zelf weg te poetsen.

Dat onderscheid was cruciaal. Veel schrijfhulpmiddelen maken proza netter, maar vlakken het tegelijk af. Ze halen niet alleen kromme zinnen weg, maar ook de vreemde formulering die iemand eigen maakt. De harde observatie. Het ritme dat misschien niet volgens het handboek klopt, maar wel klinkt als een mens die ergens werkelijk iets van vindt.

“Als je hetzelfde klinkt als iedereen, is het moeilijk om op te vallen,” zei de spreker. “Je wilt juist het tegenovergestelde.”

Voor iemand die een bedrijf bouwt, is dat geen kwestie van literaire ijdelheid. Oprichters schrijven voortdurend: tweets, productpagina’s, koude e-mails, lanceringsteksten, productupdates, onboardingberichten. Wie investeerders heeft, schrijft ook updates voor investeerders. Wie klanten heeft, schrijft voorstellen, antwoorden, uitleg en excuses. Communicatie is geen laagje vernis over het werk. Vaak ís het werk.

Stel je een oprichter voor die laat op de avond aan een lanceringstekst zit. Op zijn scherm staat een ruwe alinea over een klant die iedere vrijdag uren kwijt was aan het kopiëren van gegevens tussen drie systemen. Er staat een zin in die nog niet mooi is, maar wel van hem: de frustratie van die klant, de reden waarom zijn team dit product überhaupt is gaan bouwen. Dan laat hij een taalmodel de hele tekst in één keer schrijven.

De volgende ochtend leest hij het terug en denkt: dit ziet er niet goed uit.

Dat is het probleem van de eenmalige worp, van het idee dat AI de tekst vanaf nul moet verzinnen en de mens daarna alleen nog fouten hoeft te zoeken. De spreker stelde een andere volgorde voor. Eerst de mens. Eerst de rommelige aantekeningen, de werkelijke details, de eigen overtuiging. Daarna de skill.

“Menselijke ideeën eerst,” was zijn praktische formule, “AI als opschoning daarna.”

*No AI Slop* zoekt dan naar de patronen die tekst doen klinken alsof hij door een model is gladgestreken. Niet om er literaire opsmuk van te maken, maar om de boodschap weer vertrouwenwekkend te laten klinken. Want de lezer schrijft zelden terug: *Dit is door AI geschreven.* Meestal gebeurt er niets. Hij scrolt door. Hij reageert niet op de e-mail. Hij gelooft een claim net iets minder gemakkelijk, omdat ergens onder de woorden een gedachte opkomt: *This is AI-written.*

De tool is te installeren met `npx skills add`, gevolgd door de GitHub-link van de repository. Daarna draait hij mee in de eigen agentomgeving, precies op het moment dat er al een eerste versie ligt.

De les was klein, maar scherp: laat AI niet bepalen wat je zegt. Laat het hooguit helpen voorkomen dat je klinkt als alle anderen.

Van woorden ging het verhaal naar namen. Naar mensen die ooit enthousiast reageerden, om een gesprek vroegen, prijzen wilden weten of beloofden na de zomer terug te komen — en die vervolgens langzaam verdwenen in inboxen, notitie-apps en het geheugen van iemand die te veel te doen had.

Een CRM, customer relationship management, klinkt als een systeem voor verkoopafdelingen met targets en dashboards. In wezen is het eenvoudiger: een geheugen voor zakelijke relaties. Het bewaart namen, e-mailadressen, gespreksnotities, kansen en vervolgafspraken. Wie zei wat? Wanneer moest je terugbellen? Welke introductie was warm, maar ligt inmiddels al zes maanden stil?

Het probleem is dat een gewoon CRM ervan uitgaat dat de drukste persoon in het bedrijf alles netjes blijft bijwerken.

Aanvankelijk voelt dat nog haalbaar. De pijplijn is schoon. De fases hebben kleuren. Er zijn notities bij ieder contact. Misschien staat er zelfs een slimme herinnering klaar. Dan komen de weken waarin alles tegelijk gebeurt. Een klant heeft haast. Een productlancering loopt uit. Iemand zegt dat hij over vijfenveertig dagen terugkomt. Een warme introductie verdwijnt onder een stapel nieuwe mails.

“Het begint altijd opwindend,” zei de spreker. “En na een paar weken zijn de gegevens verouderd, zijn de notities rommelig en houd je het niet meer bij.”

Daarna wordt de database die kansen had moeten bewaken een archief dat niemand nog opent.

“Leads are a mess.”

“I forgot to follow up.”

Achter die korte zinnen zat dezelfde ongemakkelijke bekentenis: er ligt geld op tafel, maar niemand weet meer precies waar.

De open-source-CRM van TriCompAI probeert die verhouding om te draaien. Het is niet gebouwd als een dossierkast waar een ondernemer gegevens in moet stoppen, maar als een werkplek voor een agent. Die agent kan contactdossiers lezen, mensen onderzoeken, bedrijfsinformatie aanvullen, vervolgacties inplannen en notities actueel houden. Hij bewaart niet alleen losse gegevens. Hij onderhoudt de verbanden ertussen — de relatiekaart van een bedrijf.

Dat hoeft geen poging te zijn om Salesforce te vervangen. De spreker zag juist waarde in een kleinere, hanteerbare toepassing. Hij zou het gebruiken voor de sponsorpijplijn van zijn podcast, voor contacten bij bureaus, voor investeerdersupdates, voor mensen op de wachtlijst van iets dat hij snel in elkaar had gebouwd, of voor klantvragen bij een kleine SaaS-dienst.

Als proef zou hij één pijplijn maken: *warme leads die ik me niet kan veroorloven te vergeten.*

Daarin zouden alleen mensen komen die een signaal van koopbereidheid hadden gegeven. Iemand die op een e-mail reageerde. Iemand die een gesprek boekte. Iemand die naar prijzen vroeg. Iemand die zei: bel me na Kerstmis, na de zomer, zodra het budget weer vrij is.

Dan kon de agent het saaie maar kostbare werk doen. Wie verdient vandaag aandacht? Wat moet er in dat bericht staan? Wat is er bij dat bedrijf veranderd sinds het laatste gesprek? Heeft het nieuwe financiering opgehaald, een vacature geplaatst, een product gelanceerd?

Dat is iets anders dan iedereen automatisch dezelfde opvolgmail sturen. Een goede follow-up bewijst dat iemand het vorige gesprek nog kent.

De installatie is minder elegant dan die van een schrijfhulp. Je hebt Bun nodig, een omgeving voor JavaScript-programma’s, en Docker, waarmee alle onderdelen van een toepassing in afgeschermde containers draaien. Daarna haal je de repository op, installeer je de onderdelen, start je de database en open je de toepassing lokaal. Gewoonlijk draait de interface op `localhost:3000` en de technische achterlaag op `localhost:3001`.

Wie wil inloggen, e-mail wil verbinden of de agenda wil koppelen, heeft daarnaast een Google- of Microsoft-OAuth-client nodig. OAuth is een veilige manier om een toepassing beperkte toestemming te geven, bijvoorbeeld voor een agenda, zonder een wachtwoord prijs te geven.

Het is geen product dat je met één knop aanzet. Maar het is ook geen speelgoed. Het heeft de vorm van een echt product, nog met zichtbare naden.

En het wees naar een probleem dat ondernemers zelden zo benoemen: veel bedrijven hebben geen gebrek aan kansen. Ze hebben gebrek aan een systeem dat onthoudt.

De derde repository begon waar veel makers hun moed verliezen: bij een map vol ruwe video.

Een podcastaflevering van een uur. Een Loom-opname van een productdemo. Een gesprek waarin zes sterke minuten verstopt zitten tussen aarzelingen, stiltes en omwegen. Het materiaal bestaat al. Maar tussen opname en publicatie wacht het werk waar bijna niemand om vraagt: stopwoorden schrappen, dode ruimte inkorten, ondertitels maken, geluid en beeld gelijk trekken, grafische lagen toevoegen, renderen, terugkijken — en hopen dat er niet ineens een halve zin ontbreekt.

*Video Use*, van Browser Use, geeft programmeeragents zoals Claude Code en Codex de mogelijkheid om dat werk uit te voeren. De agent kan een transcript lezen, tijdcodes beoordelen, een montagestrategie voorstellen, beelden knippen, ondertitels en overlays toevoegen, de video renderen en het resultaat controleren.

Er zijn al talloze AI-videoproducten. Maar daar lag volgens de spreker niet het interessante punt. “The editing workflow becomes something your agent can understand and repeat.”

Dat veranderde de vraag.

Iedere maker ontwikkelt na verloop van tijd een eigen montagegrammatica. De ondertitels zien er steeds ongeveer hetzelfde uit. Stiltes worden op een herkenbare manier geknipt. Een video opent in een bepaald tempo. Een lang gesprek wordt opgesplitst in korte fragmenten, middellange clips en misschien één hoofdvideo. Wie vaak genoeg naar een kanaal kijkt, herkent die regels zonder ze ooit op papier te hebben gezien.

Normaal leven ze in de handen en het hoofd van een editor. Met *Video Use* kunnen ze zichtbaar worden gemaakt. De agent leest het transcript, ziet waar de tijdcodes liggen, stelt een aanpak voor, bouwt de montage en controleert de knippunten.

Voor een oprichter is dat geen luxe. Je kunt een uitstekend product hebben en toch verliezen als niemand het ziet. Content is vaak de afstand tussen een goed idee en de mensen die er iets aan kunnen hebben.

Het kantelpunt zat opnieuw in zelfbeheersing. Wie zo’n tool voor het eerst ziet, wil al snel zeggen: neem mijn hele YouTube-kanaal over. Maar juist dan lopen dit soort projecten vast. De opdracht wordt te groot, de verwachtingen worden vaag en het resultaat valt tegen.

Begin kleiner.

Neem één Loom-video van een oprichter en maak er een lanceringclip van zestig seconden van. Of geef een podcastopname aan de agent met een duidelijke opdracht: zoek drie sterke fragmenten, open elk fragment scherp en gebruik telkens dezelfde ondertitelstijl.

Eén werkend format is genoeg. Zodra dat format betrouwbaar wordt, ontstaat een systeem. En een systeem kun je zelf herhalen of aan anderen verkopen.

Makelaars hebben woningvideo’s nodig. SaaS-oprichters willen productdemo’s. Coaches willen korte clips. Bureaus produceren advertentievarianten alsof ze aan een lopende band staan. Vrijwel iedere branche heeft content nodig; vrijwel niemand wil elke avond zelf monteren.

De installatie sluit aan bij de gedachte achter het project. In plaats van zelf alle stappen af te lopen, kan de gebruiker Claude Code of Codex — mits die toegang heeft tot de terminal — vragen eerst `INSTALL.md` te lezen en daarna de installatie uit te voeren. De agent haalt de repository op, koppelt FFmpeg voor audio- en videobewerking, registreert de skill en voegt waar nodig een sleutel voor ElevenLabs toe.

Handmatig kan het ook. Met `git clone`, configuratiebestanden en symbolische koppelingen kom je een eind. Maar de spreker was daar nuchter over: voor vijfennegentig procent van de mensen is het logischer om de agent het installatiewerk te laten doen.

Dat is meteen de eerste test. Niet alleen: kan de agent de video monteren? Maar ook: kan hij het proces leren waarmee die montage mogelijk wordt?

Automatiseer niet je hele creatieve bedrijf. Automatiseer eerst één terugkerende knip.

Daarna kwam NVIDIA. Niet als het zesde project dat aan het begin was beloofd, maar als vierde repository in de daadwerkelijke aflevering. En juist omdat het gereedschap minder glansrijk was dan de vorige drie, droeg het misschien een zwaardere boodschap.

*Skill Spectre* gaat over wantrouwen.

Steeds meer mensen installeren skills, plug-ins, MCP-servers en andere hulpmiddelen rechtstreeks van GitHub. MCP, voluit Model Context Protocol, is een standaard die een taalmodel met externe toepassingen en gegevensbronnen laat samenwerken. Het model krijgt dan niet alleen informatie om te lezen, maar ook toegang tot gereedschap: bestanden, agenda’s, browsers, diensten en soms systemen waar iets mis kan gaan.

Dat is precies wat agents nuttig maakt. Het is ook precies waarom voorzichtigheid nodig wordt.

Een skill is niet slechts een blok tekst. Hij kan instructies bevatten, scripts, afhankelijkheden en rechten om bestanden te lezen, programma’s aan te roepen of verbinding te maken met externe diensten. Een kwaadwillende skill kan verborgen opdrachten meedragen, gegevens wegsluizen of een zwakke plek uitbuiten in de softwareketen waarop een agent vertrouwt.

“Before you hand your AI a new tool, scan the tool.”

Voor je je AI een nieuw stuk gereedschap geeft, onderzoek je dat gereedschap eerst.

*Skill Spectre* scant AI-skills op promptinjectie, verborgen instructies, verdachte patronen, datadiefstal, risico’s in afhankelijkheden en gevaren rond MCP-koppelingen. De snelle installatie verloopt via `uv`, een hulpmiddel voor Python-omgevingen. Daarna kun je een lokale skillmap of een volledige GitHub-repository controleren. Wie met gevoelige bestanden werkt, kan een statische scan uitvoeren met `--no-llm`; dan gaan de bestandsinhoud en de code niet naar een leverancier van taalmodellen. Er bestaat ook een Docker-versie voor wie Python liever niet lokaal installeert.

De spreker benadrukte dat hij geen band had met NVIDIA. Maar hij vond de naam wel betekenisvol. Dat juist NVIDIA zich aan een dergelijk project verbond, maakte duidelijk dat veiligheid geen bijzaak meer was voor grote ondernemingen met aparte beveiligingsteams. Het werd een probleem voor iedere bouwer die zijn eigen verzameling AI-gereedschappen in elkaar zette.

De meeste mensen gebruiken nog één chatbot in een browservenster. Maar anderen bouwen al een persoonlijke werkomgeving: een programmeeragent, een onderzoeksskill, een ontwerphulpmiddel, een browseragent, een videoverwerker. Langzaam ontstaat zoiets als een klein besturingssysteem voor het eigen werk.

En een besturingssysteem zonder sloten is geen werkomgeving, maar een uitnodiging.

“Skills, MCP-servers, plug-ins — het is spannend,” zei de spreker in essentie. “Maar je moet voorzichtig zijn.” Hij zag er zelfs nieuwe bedrijven in: een vertrouwde marktplaats voor skills, een veiligheidscontrole vóór installatie, een toegangslaag voor teams of een standaardfunctie in ieder agentplatform.

Maar de regel bleef klein genoeg om vandaag al toe te passen.

Scan eerst de tool.

De laatste repository bracht de agent vervolgens naar de plek waar de meeste mensen vaker kijken dan naar hun laptop: hun telefoon.

Een groot deel van het moderne werk gebeurt op een scherm waar geen nette technische koppeling voor bestaat. Bankieren. Berichten. Sociale media. Bezorgapps. Klantenservice. Bestellingen. Veel van die processen hebben geen API — geen officiële digitale deur waardoor software gegevens kan uitwisselen. Er is alleen het scherm, en gewoonlijk een duim die erop tikt.

*Phone Harness* verbindt een agent als Codex of Claude Code met een echte iPhone of Android-telefoon. Op een iPhone gebruikt het iPhone Mirroring op de Mac; op Android werkt het via ADB, de ontwikkelaarsverbinding waarmee een computer een toestel kan bedienen. Geen jailbreak. Geen Xcode. Geen aparte app op de telefoon.

De agent ziet wat er op het scherm gebeurt. Hij tikt, typt, scrolt, opent apps en controleert het resultaat.

Het meest voor de hand liggende voorbeeld is mobiele kwaliteitscontrole. Een agent opent een app, maakt een account aan, doorloopt de onboarding, probeert af te rekenen, maakt schermafbeeldingen en noteert waar het proces verwarrend wordt of vastloopt.

Iedere mobiele ploeg zou dat voortdurend moeten doen. De meeste doen het niet. Het is saai, herhalend en foutgevoelig. Niemand wil er steeds iemand voor inhuren, en toch kunnen een paar haperingen in een aanmeldproces klanten kosten voordat verkoop of klantenservice überhaupt de kans krijgt om in te grijpen.

Maar het bereik ging verder. Wie automatisering bouwt, kan via *Phone Harness* mobiele apps openen die geen API aanbieden. En voor makers of operationele teams lonkte een nog groter terrein: terugkerende handelingen op verschillende mobiele platforms, van TikTok tot Instagram. Niet omdat een agent morgen elk sociaal kanaal autonoom moet beheren, maar omdat juist daar veel repetitief werk ligt dat nu nog aan menselijke vingers vastzit.

De repository bevat een installatieopdracht die de gebruiker rechtstreeks aan zijn agent kan geven: haal de GitHub-repository op, lees `INSTALL.md`, installeer Phone Harness, zet het programma op het systeempad, registreer het als skill en lees vervolgens `ONBOARDING.md` om de installatie stap voor stap te doorlopen.

Voor iPhone-gebruikers zijn macOS Sequoia of nieuwer, iPhone Mirroring en toestemming voor toegankelijkheid en schermopname nodig. Android-gebruikers schakelen de ontwikkelaarsopties in en verbinden hun toestel via USB of draadloos met ADB. Daarna controleert één opdracht of alles klaarstaat:

```bash
phone-harness --doctor
```

De beperkingen zijn nog zichtbaar. Een vergrendelde telefoon vraagt om de eigenaar. Face ID en camerastappen zijn lastig. Sommige processen zullen eenvoudigweg breken.

Maar de richting was helder. Agents verschuiven van systemen die vragen beantwoorden naar systemen die handelingen verrichten. En de telefoon is een van de grootste oppervlakken waarop nog gehandeld moet worden.

Daar zat ook een zakelijke rekensom in verscholen. Stel dat je mobiele kwaliteitscontrole betrouwbaar kunt verpakken voor kleine teams. “Zou iemand daar honderd of vijfhonderd dollar per maand voor betalen?” vroeg de spreker. En daarna, met de nuchterheid die goede ideeën nodig hebben: “Hoeveel klanten heb je nodig om op tienduizend dollar per maand uit te komen?”

Niet veel.

Dat was de rode draad van de vijf repositories die de aflevering uiteindelijk opleverde. *No AI Slop* liet zien hoe AI menselijke communicatie kan ondersteunen zonder de eigen stem uit te wissen. TriCompAI’s CRM wees naar relatiesystemen die niet alleen opslaan, maar ook onthouden en opvolgen. *Video Use* maakte montage tot een werkwijze die een agent kan leren herhalen. *Skill Spectre* herinnerde eraan dat iedere nieuwe mogelijkheid een nieuw risico meebrengt. *Phone Harness* gaf een agent toegang tot het scherm waarop een groot deel van het dagelijks werk nog altijd vastzit.

De volgorde na installatie deed er misschien nog meer toe dan de tools zelf.

Eerst kies je één klein proces. Niet een volledige mediastudio, maar drie clips uit één podcast. Niet een wereldwijd verkoopapparaat, maar een lijst met warme leads. Niet alle mobiele automatisering, maar één aanmeldstroom die elke week wordt getest.

Dan kijk je of het werkt. Of het tijd bespaart. Of het fouten voorkomt. Of het iets mogelijk maakt wat gisteren nog te duur, te traag of te omslachtig was.

Pas daarna komt de vraag die van een handig hulpmiddel een bedrijf kan maken: moet ik dit voor anderen verpakken? Of houd ik het in mijn eigen werkwijze, zodat ik sneller werk, meer waarde lever en misschien meer verdien?

Daarvoor hoef je geen programmeur te zijn. Juist door een repository te installeren — of een agent te vragen dat voor je te doen — ontdek je waar de frictie zit. Wat ontbreekt er? Waar loopt het vast? Welk handmatig proces slokt telkens tijd op, veroorzaakt fouten of laat omzet ongemerkt weglekken?

Soms ligt daar een bedrijf te wachten.

Aan het einde van de aflevering maakte de spreker geen grootse belofte. Hij wilde geen voltijdse analist van open-sourceprojecten worden. Maar hij geloofde wel dat GitHub een van de weinige plekken bleef waar bruikbare gereedschappen zichtbaar worden voordat ze gemeengoed zijn.

Niet alles daar is goed. Niet alles is af. Niet alles verdient installatie.

Maar wie er regelmatig kijkt, ziet eerder welke ideeën blijven hangen. Hij leert sneller bouwen. Hij legt verbanden die anderen nog niet zien, omdat zij wachten op de versie met een merknaam, een prijskaartje en een verkoopteam.

Maak er daarom een ritueel van, stelde hij voor. Eens per maand. Misschien eens per twee weken. Zoek een paar nieuwe repositories, installeer er een of twee en vraag niet alleen wat ze kunnen, maar wat ze voor jouw werk zouden kunnen betekenen.

Waar zit de wrijving? Wat mist er? Kun je het zelf gebruiken? Kun je het voor iemand anders oplossen?

Of de reeks elke maand terug moest komen, elke zes weken, of nooit meer, legde hij bij zijn publiek neer. Laat weten wat je ervan vindt, zei hij. Zijn werk draaide uiteindelijk om één ding: de kans vergroten dat zijn luisteraars in dit nieuwe tijdperk zouden slagen — met ideeën, gereedschappen en denkkaders.

Het klonk niet als een afscheid.

Eerder als een aansporing om zelf die GitHub-map te openen.