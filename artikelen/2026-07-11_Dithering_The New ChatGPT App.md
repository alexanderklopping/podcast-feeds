<!--
podcast_name: Dithering
guid: https://dithering.passport.online/member/episode/the-new-chat-gpt-app
-->

# Het Zelfmoordmemo

*Op een vrijdagochtend in juli 2026 updaten miljoenen mensen hun ChatGPT-app. Wat ze aantreffen, is iets wat ze niet verwachten: hun vertrouwde chatbot is er niet meer. OpenAI heeft stilletjes een beslissing genomen die één van de meest gebruikte softwareproducten ter wereld fundamenteel verandert — en niet iedereen is er blij mee. Dit is het verhaal van een app-update die meer onthult over een bedrijf dan elk persbericht ooit zou kunnen.*

---

Er zijn correcties, en dan zijn er *correcties*.

John Siracusa wilde in de podcast eigenlijk een kleine technische vergissing rechtzetten. In een eerdere aflevering had hij gezegd dat de ChatGPT Codex-app voor Mac gebouwd was op Electron — het raamwerk waarmee ontwikkelaars webapplicaties verpakken als desktopsoftware. Dat klopte niet meer. OpenAI had de app de maand ervoor omgebouwd naar OWL, een eigen framework dat ze hadden ontwikkeld voor hun Atlas-webbrowser. Een bescheiden correctie. De soort fout die je netjes rechtzet en dan doorgaat.

Maar in de uren tussen de vorige aflevering en de opname van deze had OpenAI de hele discussie irrelevant gemaakt.

De super-app was gelanceerd. En het was niet goed.

"Het is eerlijk gezegd verbijsterend," zegt Siracusa. Geen woorden van iemand die licht teleurgesteld is — woorden van iemand die net iets heeft gezien wat hij nauwelijks kan bevatten.

---

Om te begrijpen wat er is misgegaan, helpt het te weten hoe de situatie eruitzag vóór die bewuste vrijdag.

OpenAI had twee Mac-apps naast elkaar laten bestaan. De eerste was de originele ChatGPT-app: gebouwd in SwiftUI en AppKit, Apple's eigen frameworks voor native Mac-software, en geliefd bij zijn gebruikers vanwege een slimme integratie met andere apps. Je kon het koppelen aan een BBEdit-tekstvenster of Apple Notes, en de AI kon rechtstreeks meelezen en -schrijven in die programma's. De tweede app was Codex — een tool primair gericht op ontwikkelaars, waarmee je code kon schrijven, debuggen en uitvoeren.

Op die vrijdag besloot OpenAI deze twee werelden samen te voegen. En in die samenvoeging ging iets grondig mis.

De nieuwe app heet voortaan gewoon ChatGPT. Maar wie hem opent, treft geen chatbot aan. Hij treft Codex aan — omgedoopt, met een breder mandaat. De app heeft nu twee modi: ChatGPT Codex, voor de ontwikkelaar die code wil schrijven, en ChatGPT Work, voor de professional die zijn Excel-bestanden, PowerPoint-presentaties, Gmail en Slack via AI wil aansturen. Wat er *niet* is, is een gewone chatmodus.

Nou ja, bijna niet.

Er is een klein knopje aan de linkerkant van de interface. Als je erop klikt, verschijnt er een mini-venster aan de rechterkant van het scherm. Een pop-up. Het soort hulpvenster dat je tegenkomt op de website van een verzekeringsmaatschappij als je drie minuten lang op dezelfde pagina blijft stilstaan en er een balletje opduikt met de vraag: *Kan ik u ergens mee helpen?*

"Je hebt nu klantenservice met jezelf," zegt Siracusa. "Het is werkelijk verbijsterend. Het voelt alsof ze ChatGPT gewoon hebben vermoord."

---

Een miljard gebruikers. Dat is het getal waar de techwereld al jaren over spreekt als de Heilige Graal van consumentenproducten. Mark Zuckerberg gebruikt het als zijn persoonlijke meetlat — bij de lancering van Threads zei hij publiekelijk dat het doel was om een miljard gebruikers te bereiken, wetende dat slechts een handvol producten in de geschiedenis dat niveau hebben gehaald. WhatsApp. YouTube. Instagram. En ChatGPT.

ChatGPT bereikte een miljard gebruikers in een tempo dat Silicon Valley nog nooit had gezien. En nu heeft OpenAI de desktopversie van dat product omgebouwd tot iets wat — op het moment van schrijven — geen duidelijke plek heeft voor die miljard mensen.

"Ze zijn geen chatbotbedrijf meer," concludeert Ben Thompson, Siracusa's gesprekspartner. Het klinkt als een observatie, maar het is eigenlijk een aanklacht.

---

De chaos begint al bij de installatie — of liever gezegd: bij de poging tot installatie.

Wie de nieuwe app downloadt en opent, ervaart een migratie die lijkt ontworpen door iemand die nog nooit zelf software heeft geïnstalleerd. In theorie werkt het zo: je downloadt de nieuwe app, dubbelklikt op het schijfkopie-bestand, en het systeem installeert de nieuwe mega-super-app in je programmamap. De oude ChatGPT-app wordt vervolgens automatisch omgedoopt naar "ChatGPT Classic" en mag blijven bestaan.

In de praktijk belandde bij Siracusa de oude app in de prullenbak.

"Ik heb het niet gedaan op mijn echte werkmachine," bekent hij, "die draait nog steeds op Classic." Een technisch journalist met jarenlange ervaring in het recenseren van Apple-software besluit voorzichtigheidshalve zijn productieve mac te sparen. Dat zegt genoeg.

En hoe download je ChatGPT Classic als standalone app, voor mensen die de nieuwe versie niet willen? Het antwoord — ook volgens ChatGPT zelf, al was het een uitdaging om überhaupt bij een chatvenster te komen — is dat er geen afzonderlijke installer bestaat. Je krijgt Classic alleen als bijproduct van het migratieproces van de nieuwe app. Die nieuwe app weegt anderhalf gigabyte.

De app-identifier in het macOS-bundelpakket — de technische vingerafdruk waarmee het systeem elke app uniek identificeert — is `com.openai.codex`. Er bestaat geen twijfel over wat deze app in zijn vorige leven was.

---

Er is een oud gezegde in de techwereld, van toepassing geweest op Microsoft en op Google: *a company ships its org chart*. Je kunt zien hoe een bedrijf intern is georganiseerd door naar de software te kijken die het aflevert. Afdelingen die niet met elkaar praten, bouwen features die niet met elkaar praten. Managers die hun domein beschermen, bouwen producten die hun grenzen bewaken.

"OpenAI heeft hier hun org chart verscheept," zegt Thompson droogjes. "En als je ooit het gevoel had dat die org chart een bende leek, dan is dit wat ze hebben opgeleverd."

De interface is het bewijs. De instellingenpagina — in elke normale Mac-app een apart venster dat je opent en sluit — wist in deze app het volledige hoofdvenster en vervangt het door een instellingenscherm. Je keert terug via een knop rechtsboven: *Terug naar app*. Er zijn meer opties in het instellingenscherm dan er functies zijn in de hoofdinterface. De chatlijst — de vertrouwde sidebar met al je vorige gesprekken, geordend in mappen — is verdwenen als zelfstandig element. Het chatvenster dat je kunt oproepen via dat kleine knopje links opent als een sub-venster, losgemaakt van de rest van de app, zonder sidebar, zonder geschiedenis, zonder context.

"Het voelt als een koortsdroom," zegt Siracusa.

In een Electron-app — waarbij de interface eigenlijk een ingekapselde Chrome-browser is — kun je niet buiten de grenzen van het hoofdvenster treden. Alles bestaat binnen die rechthoek. OWL, het framework dat OpenAI heeft gebouwd, werkt anders: het is Chromium-gebaseerd, maar scheidt de runtime af zodat vensters echt native Mac-vensters worden. Je kunt het chatvenster losslepen en het wordt een zelfstandig venster. Goed. Maar dan staat het daar: leeg, zonder je chatgeschiedenis, zonder de structuur die miljarden gesprekken heeft georganiseerd.

---

Het meest intrigerende aan deze update is niet wat er technisch misgaat. Het is de vraag *waarom*.

"Ik kan de logica een klein beetje begrijpen," zegt Thompson voorzichtig. "De overgrote meerderheid van mensen heeft geen idee wat AI werkelijk kan. Ze denken dat het een chatbot is — een slimmere Google. Dit is een poging om die mogelijkheden in hun gezicht te duwen."

De redenering gaat zo: ChatGPT heeft een miljard gebruikers bereikt, maar die gebruikers gebruiken het voor relatief eenvoudige taken. Vragen stellen. Teksten herschrijven. Recepten zoeken. Ondertussen kan moderne AI spreadsheets besturen, e-mails afhandelen, software schrijven, vergaderingen plannen en volledige workflows automatiseren. Als OpenAI zijn gebruikers wil laten zien wat er mogelijk is, moet het ze misschien een duw geven.

Maar de uitvoering ondermijnt de ambitie. Een duw die aanvoelt als een duw werkt. Een duw die aanvoelt als vallen van een trap, werkt niet.

"Het is een eenmalige weddenschap," erkent Siracusa. "Veel mensen gaan dit openen, achteruitdeinzen, en de app nooit meer aanraken."

---

Er is ook een cynischer lezing mogelijk. ChatGPT, de chatbot, verbruikt enorme hoeveelheden GPU-rekenkracht voor elke conversatie. Als OpenAI geen advertentiemodel heeft — en dat heeft het niet, althans niet voor de chatbot — dan is elke vraag die een gebruiker stelt een nettokost. Een chatbot met een miljard gebruikers is ook een kostenpost met een miljard gebruikers.

De verschuiving naar Work en Codex is de verschuiving naar producten waarvoor mensen betalen. Abonnementen. Enterprise-contracten. Bedrijven die maandelijks betalen voor geautomatiseerde workflows zijn een ander businessmodel dan consumenten die gratis vragen stellen over het weer.

"Zouden ze ChatGPT gewoon laten vallen?" vraagt Thompson hardop. "Ik begin het me af te vragen."

En dan, bijna als naschrift: "Maar als ze dat doen, waarom bouwen ze dan ondertussen een advertentiebedrijf?"

Het antwoord blijft uit. Want het antwoord is er misschien niet — of als het er is, woont het op een plek in het bedrijf die niet communiceert met de plek waar de productbeslissingen worden genomen.

---

De iPhone-app, zo blijkt, is vooralsnog onaangetast. Wie op vrijdagochtend zijn app-updates handmatig installeert en de nieuwe versie binnenhaalt, merkt niets bijzonders. Gewone chatinterface. Vertrouwde lay-out. Siracusa controleert zijn telefoon na de update op zijn testmachine, bang dat zijn account nu gesynchroniseerd is met de nieuwe desktopervaring.

Niets. De telefoon is Classic. De desktop is chaos. Ze praten niet met elkaar.

"Je kunt nauwelijks geloven dat het hetzelfde product is," zegt hij.

Er is één verbetering, voor de volledigheid: de knop waarmee je op afstand toegang hebt tot je computer via de app heette voorheen 'Codex Remote'. Nu heet hij gewoon 'Remote'. Duidelijker. Beter.

Één duim omhoog.

---

Tegen het einde van de opname vraagt Thompson of OpenAI misschien gewoon bang is geworden voor Apple's vernieuwde Siri. De nieuwe Siri-app — die later dat jaar zou verschijnen — doet duidelijk dienst als concurrent voor de Mac ChatGPT-app, zelfs het zwart-wit kleurenschema is bijna identiek. Maar Siri doet bij lange na niet wat de native ChatGPT-app deed: rechtstreeks integreren met andere apps, meelezen in documenten, meedenken in teksteditors.

"Het voelt niet als iets waar ChatGPT bang voor zou moeten zijn," zegt Siracusa.

En toch is de native app weg. Misschien niet voor altijd — Siracusa vermoedt dat OpenAI al voor het einde van de dag een update pusht die een derde hoofdtab toevoegt aan de interface: naast Work en Codex gewoon een tab genaamd Chat. Logisch. Voor de hand liggend. Precies het soort ding dat eruitziet als iets wat iemand vergeten is te bouwen voordat de baas zei dat het live moest.

"Het lijkt echt op iets wat ze vergeten zijn," zegt Thompson.

"Ja," beaamt Siracusa. "Dat is precies wat het lijkt."

En daarin schuilt misschien de meest verontrustende gedachte van allemaal — niet dat OpenAI bewust heeft besloten zijn chatbot op te offeren voor een groter doel, maar dat niemand in het bedrijf aan tafel zat en zei: *Wacht even. Waar is de chat?*

Een miljard gebruikers. En de chat zat in de prullenbak.