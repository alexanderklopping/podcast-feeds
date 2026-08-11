<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01KZP88D049TEJW7KQN7C5TGKM
-->

# De Nieuwe Tolpoort

*Het internet is altijd gebouwd geweest op één simpele deal: jij geeft je content, wij sturen je bezoekers. Maar die deal is stilletjes stukgegaan. En in de stilte daarna bouwt Cloudflare iets wat de spelregels compleet herschrijft. Wie dat begrijpt—en snel handelt—kan meeprofiteren van een verschuiving die net zo groot is als de komst van de App Store in 2009.*

---

Er is een moment waarop een business model doodgaat, en het sluipende eraan is dat bijna niemand het ziet. Geen persbericht, geen aankondiging. Gewoon een stille erosie van de aannames waar een hele industrie op gebouwd was.

Dat moment is nu.

Stel je voor: je hebt jarenlang een website bijgehouden. Goede content, eerlijke adviezen, een trouwe lezerskring. Google crawlt je pagina's, indexeert alles braaf, en stuurt je in ruil voor die vrijwillige toegang een gestage stroom bezoekers. Bezoekers die je advertenties zien. Die zich inschrijven voor je nieuwsbrief. Die doorklikken op een affiliate link, of een abonnement afsluiten. De crawler krijgt de content, de website krijgt de bezoeker, de bezoeker krijgt het antwoord. Decennia lang was dit de stille belofte waarop het commerciële internet dreef.

Die belofte is nu eenzijdig opgezegd.

Een AI-systeem leest je pagina, trekt het nuttige antwoord eruit, geeft dat antwoord direct aan de gebruiker—en die gebruiker hoeft nergens meer op te klikken. De content heeft waarde gecreëerd. De website zag er niets van terug. Geen advertentie-impressie, geen email-capture, geen affiliate-klik. Niks.

Dit is waarom uitgevers boos zijn. Maar het echte verhaal begint precies op het moment dat die boosheid ophoudt. Want dit is geen uitgeverscrisis. Dit is de geboorte van een compleet nieuw economisch model—en Cloudflare heeft zojuist de infrastructuur daarvoor gelegd.

---

Om te begrijpen wat Cloudflare in de zomer van 2026 aankondigde, moet je eerst begrijpen hoe AI-agents het internet gebruiken. Niet zoals een mens. Een mens tolereert een rommelige website. Wij klikken rond, zoomen in op een PDF uit 2019, lezen de FAQ die nooit is bijgewerkt, en wroeten ons een weg door een checkout-flow met vier onnodige stappen. Mensen zijn goed in lijden. Wij doen het al jaren en we klagen er netjes over op X.

Een AI-agent kan dat niet. Een agent heeft schone deuren nodig. Gestructureerde informatie, betrouwbare bronnen, toegang die werkt. En cruciale: agents gaan het internet gebruiken zoals software infrastructuur gebruikt. Ze vragen dingen op, vergelijken producten, halen data op, roepen tools aan, nemen beslissingen. En in die werkwijze zit een fundamenteel andere economie verborgen.

Een mens wil echt geen 0,0003 cent betalen om een recept te lezen. Als ik op een saucepagina klik en er staat "betaal een derde cent voor de ingrediënten", sluit ik de laptop en bestel ik pizza. Maar een machine maakt dat niet uit. Als de data de agent helpt om een taak te voltooien, kan de agent betalen. Automatisch, onmiddellijk, frictionloos. De menselijke web monetiseerde aandacht. De agent-web monetiseert nuttige resources.

Dat is de mentale verschuiving waar alles om draait.

---

Cloudflare—een Amerikaans bedrijf dat de infrastructuur beheert waarop een groot deel van het internet draait, een soort verkeerstoren voor webverkeer—kondigde een reeks tools aan die precies op dit moment inspelen.

Het begint met **AI Crawl Control**: site-eigenaren kunnen nu precies zien welke AI-crawlers hun content opvragen, welke ze willen toelaten, en welke ze willen blokkeren. Simpel, maar essentieel. Eindelijk zichtbaarheid over wie er door je voordeur loopt.

Dan komt **Pay Per Crawl**, en dit is het deel dat mensen echt betaald gaat zetten. Een site-eigenaar kan nu een prijs vragen wanneer een AI-crawler zijn content opvraagt. De crawler stuurt een verzoek. De server antwoordt met een prijs—typisch een fractie van een cent. De crawler betaalt, probeert opnieuw, en krijgt toegang. Geen accountaanmaak, geen salesgesprek, geen enterprise-procurement traject van zes weken. Het verzoek ís de transactie.

De **Monetization Gateway** gaat nog een stap verder. Cloudflare zegt in feite: dit principe—betalen voor toegang—moet niet alleen gelden voor crawlers die pagina's lezen. Elk resource achter Cloudflare kan betalingsregels krijgen. Een dataset. Een API. Een zoekindex. Een bestand. Een MCP-tool call—dat is een gestandaardiseerde manier waarop AI-systemen externe tools aanroepen, vergelijk het met een stekker die in elk stopcontact past.

En de betalingsrail die dit allemaal mogelijk maakt heet **X402**. Het gebruikt HTTP-statuscode 402—"Payment Required"—een code die al in 1991 in de internetstandaarden zat maar nooit serieus werd gebruikt, omdat niemand een manier had om er iets mee te doen. Cloudflare verifieert de betaling aan de rand van het netwerk, voordat het verzoek überhaupt de server bereikt. Snel, schaalbaar, onzichtbaar voor de eindgebruiker.

De implicatie is enorm. Een dataset kan per zoekopdracht rekenen. Een API per succesvolle aanroep. Een onderzoeksarchief per antwoord. Een productcatalogus per vergelijking. En iemand in de comments zal ongetwijfeld opmerpen: maar agents hebben toch geen portemonnee? Dat klopt—nog niet. Maar het begint al te gebeuren. Agents krijgen email-adressen. Ze voeren transacties uit. De infrastructuur voor een agent-economie is in opbouw, en Cloudflare legt er nu de betalingsvloer voor.

---

Er is een stack aan het ontstaan. Geen ingewikkelde stack—eigenlijk verbazend eenvoudig als je hem uittekent.

Laag één is het rommelige internet zoals het nu bestaat: PDFs, verouderde prijspagina's, Wordpress-blogs die er uitzien alsof ze zijn ontworpen toen people nog zonder ironie "Web 2.0" zeiden, YouTube-video's, support-documenten, review-sites, vergelijkingspagina's. De grondstof is er. In overvloed.

Laag twee is schoonmaken: iemand haalt die rommelige data op en structureert hem. Valide, betrouwbaar, actueel.

Laag drie is toegang: iemand maakt die gestructureerde data bereikbaar via een API, een MCP-tool, een zoekindex, een llms.txt-bestand—een soort sitemap, maar dan voor AI-systemen—of een andere schone toegangspoort.

Laag vier is betaling: sommige resources blijven gratis, want gratis creëert distributie. Sommige resources kosten geld, want ze zijn waardevol. Sommige zijn afgesloten, want ze zijn privé.

Laag vijf is vertrouwen en analytics: is de data vers? Is de bron betrouwbaar? Welke agents gebruiken het? Welke requests leveren geld op? Welke resources sturen echt resultaten?

Die vijf lagen vormen samen het fundament voor duizenden nieuwe bedrijven. En de centrale vraag voor elke founder die dit leest is precies dezelfde: welke resource heeft een agent hard genoeg, vaak genoeg en betrouwbaar genoeg nodig om er voor te betalen?

---

Ergens op X schreef Pieter Levels—de Nederlander die als indie hacker meerdere winstgevende solo-producten bouwde—over hoe moeilijk het nu is om een bedrijf op te bouwen. Traffic is gedaald. Simpele tools worden zelf gevibecoded. De concurrentie is overal en nergens. Het is een gevoel dat veel founders herkennen.

Maar de conclusie dat het klaar is met ondernemerschap is precies de verkeerde. De kaart is veranderd, niet de bestemming. De bedrijven die nu kansen zien zijn geen kleine tooletjes die iemand in een middag namaakt. Het zijn bedrijven met echte grondstoffen, echte klanten, en een moat die dieper wordt naarmate je langer graaft. Bedrijven die dag één winstgevend kunnen zijn.

Drie van zulke bedrijven.

---

**Het eerste idee: de niche-dataraffinaderij**

De gedachte is eenvoudig. Kies één niche waar waardevolle informatie rommelig, versnipperd, veranderlijk en vervelend te verzamelen is. Zet die informatie om in schone brandstof voor agents.

Het heet een raffinaderij omdat de grondstof al bestaat. Het internet heeft de data al. Die zit in Google Maps, in vacatureposten, in reviews, in lokale directories, in prijspagina's, in PDF's. Je taak is raffineren.

Neem medspa's als voorbeeld—een sector die in de VS snel groeit. Een medspa-eigenaar wil weten wat concurrenten rekenen voor Botox, welke behandelingen ze aanbieden, waarover reviews klagen, welke klinieken personeel zoeken, welke services trending zijn. Die informatie bestaat vandaag op tientallen plekken. Google reviews. Concurrerende websites. Instagram. Vacaturebanken. Meta's advertentiebibliotheek.

Een agent kan ongelooflijk goed werk leveren voor een medspa-eigenaar—als hij die informatie gestructureerd heeft. Hij zou kunnen zeggen: jouw Botox-prijs ligt boven de lokale mediaan, maar je reviews ondersteunen premium-positionering nog niet. Of: drie concurrenten in jouw buurt begonnen in de afgelopen zestig dagen met het promoten van exosoombehandelingen. Of: de meest voorkomende klacht in lokale reviews is onduidelijke prijsstelling—laat je aanbod leiden met eenvoud. Of: twee snelgroeiende concurrenten werven injectors, wat waarschijnlijk betekent dat ze capaciteit uitbreiden.

Allemaal waardevolle informatie. En de waarde zit in de data, niet in een generieke AI-wrapper eromheen.

Zo bouw je de wig: kies één niche, kies één stad, volg honderd bedrijven—niet meer. Doe het handmatig. Een spreadsheet met bedrijfsnaam, website, services, prijzen, reviewcount, reviewrating, top review-klachten, Instagram-link, recente posts, zichtbare advertentiewijzigingen, aanwervingssignalen, boekingsflow.

Maak van die data tien outputs. Een lokale prijskaart. Een concurrentiekloof-rapport. Een lijst met aanbiedingsideeën. Een review-klachtsamenvatting. Een aanwervingssignaalrapport. Een maandelijks marktbewegingenrapport. Nu heb je iets te verkopen.

En hier zit een subtiliteit die de meeste mensen missen: je eerste klant is waarschijnlijk niet de medspa-eigenaar zelf. In de vroege fase verkoop je het gemakkelijkst aan mensen die al aan die niche verkopen. Medspa-marketingbureaus. Consultants. Freelancers. Software-bedrijven. Je verkooppitch: ik heb lokale marktintelligentie voor medspa's gebouwd, en jij kunt die gebruiken om betere audits, betere aanbiedingen, betere landingspagina's en betere campagnes te maken voor je klanten.

Een medspa-marketingbureau verkoopt een klant misschien voor vijfduizend euro per maand. Als jouw data hen helpt één extra klant te sluiten, of hun bestaand werk beter te maken, betalen ze jou drie-, vijf- of achthonderd euro per maand zonder te aarzelen.

Daarna volgt het stappenplan: eerst een rapport, dan een dashboard, dan een API, dan misschien een MCP-tool. Op het moment dat agents per zoekopdracht kunnen betalen, ben jij er al lang. Je hebt de data, je hebt de structuur, je hebt de klanten.

Het hoeven geen medspa's te zijn. Dakdekkersbedrijven: volg stormgebeurtenissen, vergunningdata, verzekeringsignalen, concurrerende aanbiedingen. Vastgoedinvesteringen: bestemmingsplanwijzigingen, bouwvergunningen, eigendomsrecords, huurvergelijkingen, belastingachterstand. E-commerce: SKU-wijzigingen bij concurrenten, prijsveranderingen, review-klachten, UGC-hooks. Advocatenkantoren: lokale concurrenten, praktijkgebied-positionering, advertentietekst, reviews, intakeprocedures.

Het filter is altijd hetzelfde. De data moet waardevol zijn—betere beslissingen besparen of verdienen geld. De data moet herhalend zijn—de klant heeft hem steeds opnieuw nodig. De data moet veranderen—actualiteit heeft waarde. De data moet versnipperd zijn—zodat je voordeel hebt door hem samen te brengen. En de data moet vervelend te verzamelen zijn—want dat is waar je marge zit.

Één niche, rommelig internet, omzetten in schone brandstof voor agents. Onthoud die zin.

---

**Het tweede idee: agent-gereedheid voor bedrijven**

Dit is SEO voor het agent-internet. Maar "AI-SEO" is al een buzzword geworden dat overal en nergens op slaat, dus laten we preciezer zijn. De echte business is bedrijven helpen om begrijpelijk, betrouwbaar, vergelijkbaar en aanbevelenswaardig te worden voor AI-agents.

Denk aan een B2B SaaS-bedrijf. Een menselijke koper landt op de homepage, leest de hero-tekst, klikt rond, bekijkt de prijspagina, leest wat documentatie, boekt misschien een demo, bekijkt een case study. Agents comprimeren dat hele proces. Als iemand zijn AI-assistent vraagt "vind de beste salarisadministratiesoftware voor een bedrijf van vijftien mensen in Nederland", moet de agent het marktlandschap begrijpen. Voor wie is dit product? Wat kost het? Wat vervangt het? Welke integraties? Wat zeggen klanten? Hoe vergelijkt het met alternatieven?

De meeste websites maken dit moeilijker dan nodig. Prijzen zijn verborgen. Documentatie is begraven. Websites zijn verouderd. Beleid is onvindbaar. En de teksten staan vol met frases als "ontgrendel operationele excellentie"—marketingproza dat voor een mens al irritant is, maar voor een AI-systeem volstrekt onbruikbaar.

De wedge: begin met een betaalde audit. Kies één verticaal—B2B SaaS, Shopify-apps, advocatenkantoren, financieel adviseurs, thuiszorgdiensten, wat je ook kent. Voer twintig tot vijftig vragen uit via de grote AI-tools. Vragen als: wat is de beste software voor dit gebruik? Vergelijk dit bedrijf met de top-alternatieven. Wat kost dit product? Wie is dit het beste voor? Wat zijn de risico's? Welke integraties ondersteunt het?

Dan kom je bij de founder terug met de screenshots. En dát is het verkoopmoment.

Niet omdat je een verhaal vertelt over de toekomst van AI. Maar omdat je laat zien wat er vandaag misgaat. De AI noemt de concurrent omdat die betere documentatie heeft. Of de AI weet de prijs niet—staat wel op de website, maar in een PDF uit 2018. Of het bedrijf verschijnt helemaal niet als een koper vraagt naar hun categorie. Dat trekt meteen de aandacht.

Dan verkoop je de oplossing: een agent-leesbare source of truth. Dat kan een schone llms.txt zijn. Betere documentatiestructuur. Een prijspagina die een AI kan verwerken. Eerlijke vergelijkingspagina's. Use-case pagina's in gewone taal. Klantbewijzen georganiseerd per segment. Gestructureerde FAQ's rondom echte kopersvragen. Schema-markup. Een productfeed. Een changelog.

Het terugkerende product is de meetlus. Elke maand run je de prompts opnieuw. Je ziet wat er veranderd is—zijn de AI-antwoorden nauwkeuriger? Verschijnt het bedrijf vaker? Zijn de concurrentievergelijkingen verbeterd of verslechterd?

Als dienstverlening start je met drieduizend tot tienduizend euro voor de audit en opschoning. Voor grotere B2B-bedrijven kan dat oplopen naar vijftien of twintigduizend. Na tien klanten in dezelfde niche zie je patronen: dezelfde documentatie ontbreekt steeds, dezelfde prijspagina's zijn onduidelijk, dezelfde vragen worden steeds gesteld, hetzelfde maandrapport moet steeds worden geleverd. Dan bouw je software.

Voor lokale bedrijven evolueert het naar: laat AI-assistenten bij u afspraken boeken. Voor e-commerce: maak uw productcatalogus begrijpelijk voor shopping-agents. Voor B2B SaaS: maak uw product evalueerbaar voor procurement-agents. Voor uitgevers: maak uw archief toegankelijk en licentieerbaar voor AI-systemen.

Er komen ongetwijfeld venture-backed bedrijven die dit horizontaal doen. De kans voor jou zit in de verticale diepte. B2B SaaS is te breed. Kies één specifieke niche, ga er diep in, word de autoriteit.

De verkooppitch is altijd hetzelfde: geen toekomstige beloften, maar een screenshot van wat er vandaag misgaat.

---

**Het derde idee: expertarchieven als agent-tools**

Dit is het meest creatieve van de drie—en waarschijnlijk het leukst voor mensen die al jaren waardevolle content produceren of toegang hebben tot mensen die dat doen.

Denk aan wat er beschikbaar is: YouTube-kanalen met honderden afleveringen, podcastarchieven van tienduizenden minuten, nieuwsbrieven van jaren, community-posts, templates, frameworks. Al die content verdient nu geld via advertenties, sponsorships, soms abonnementen of consultancy. Maar in het agent-internet kan dat archief iets anders worden: een tool.

Stel je een AI-agent voor die toegang heeft tot het complete archief van een gerenommeerde salesktrainer en jouw cold email herschrijft volgens zijn specifieke methodiek, met bronvermelding. Of een fitnessgent die het trainingsfilosofie van een specifieke coach gebruikt om een gepersonaliseerd plan te bouwen. Of een startup-agent die het feedback-systeem van een bekende investeerder toepast op jouw idee.

Het bedrijf heet: archief naar API.

De kern van dit idee is beginnen met één taak. Ga niet naar een creator met de boodschap "we gaan jouw hele brein in AI zetten." Dat klinkt vaag en enigszins griezelig, als een SaaS-landingspagina die verboden zou moeten worden. Zeg iets specifieks.

"Jij hebt driehonderd video's over cold email. We gaan die omzetten in een tool waarmee jouw publiek cold emails kan verbeteren." Of: "Jij hebt vijfhonderd podcast-afleveringen over startups. We bouwen daar een startup-feedback tool van." Of: "Jij hebt tien jaar aan design-teardowns. We maken er een landingspagina-kritiektool van."

Eén archief. Één pijnlijke taak. Één workflow.

De opbouw is methodisch. Eerst kies je een expert met een diep archief en een specifiek publiek—iemand bekend om cold email, Shopify-groei, lokale bedrijfsovernames, belastingstrategie, fitnessprogrammering, of die design-teardowns. Geen algemene business-creator; te breed. Specifiek werkt.

Dan verzamel je het archief: transcribeer video's en podcasts, haal nieuwsbrieven op, maak documentatie schoon.

Dan de stap waar de meeste mensen slordig worden: taggen. Niet alles in een vectordatabase gooien en "klaar" roepen. Dat geeft je een zoekbox met zelfvertrouwen, maar geen echt product. Voor een salesarchief: tag per prospecting, onderwerpregel, aanbod, bezwaar, follow-up, personalisatie, aflevering, afsluiting. Voor een startuparchief: tag per idee, markt, wedge, distributie, prijsstelling, MVP, community, moat, voorbeelden. Structuur is wat het verschil maakt tussen een chat-demo en een bruikbaar product.

Dan bouw je één nuttige workflow. Voor een salesexpert: plak je cold email, de agent critiseert hem op basis van de principes van de expert, citeert de bronlessen, herschrijft de email, geeft een score, suggereert één test. Dat is het product. Voor een startup-expert: plak je idee, de agent geeft de wedge, de eerste klant, het eerste aanbod, het eerste distributiekanaal, en wat je deze week moet valideren.

Het mooie aan dit model is dat de creator de distributie al heeft. Je hoeft de marketing niet te bouwen. Het publiek vertrouwt de expertise al. En de creator kan niet met iedereen persoonlijk aan de slag—dus dit democratiseert die expertise, voor twintig of vijftig euro per maand, of gebundeld in een betaalde community, of als lead magnet voor consultancy.

Hier wordt de Cloudflare-monetisatie pas echt interessant. Als het archief een metered resource wordt en agents per request kunnen betalen, krijgt de creator betaald op het moment dat zijn kennis wordt gebruikt. Dat is fundamenteel anders—en beter—dan hopen dat iemand een pre-roll advertentie bekijkt voor een interview van zeven jaar geleden.

De grootste fout in deze categorie: "chat met de expert"-producten zijn te vaag. De specifieke use case is wat werkt. Niet "praat met de salescreator." Maar: "herschrijf je cold email via het verkoopsysteem van deze trainer."

---

Drie ideeën, maar één rode draad: agents hebben schone, betrouwbare en nuttige resources nodig om goed werk te leveren. Die resource kan data zijn, structuur, toegang, expertise, een tool, of een betalingsregel. En je hoeft niet te wachten tot de agent-betalingsinfrastructuur volledig volwassen is.

Start met de handmatige versie. Verkoop de menselijke versie nu. Bouw de data nu. Structureer nu. Als agents steeds capabeler worden en agent-betalingen normaler, ben jij er al. Je bent niet aan het inhalen—jij hebt de deuren al gebouwd.

De vragen om jezelf te stellen bij het zoeken naar ideeën in deze ruimte: Welke beslissing is duur? Welke informatie is rommelig? Wat verandert vaak? Wie betaalt er al voor hulp? Wat heeft een agent nodig om de klus te klaren?

Dat is de kaart.

In 2009 opende Apple de App Store. De bedrijven die toen bouwden—niet de grootste, niet de best-gefinancierde, maar de snelste en de vroegste—definiëren nog steeds hoe we onze telefoons gebruiken. Het cohort van founders dat nu bouwt, in 2026 en 2027, terwijl de meeste mensen nog denken dat Cloudflare gewoon iets heeft aangekondigd voor publishers, zal over tien jaar terugkijken op dit moment als het begin.

Het internet verschuift van pagina's die mensen bezoeken naar resources die agents gebruiken. De grootste kansen zien er nu klein uit, omdat het agent-internet klein is relatief aan wat het gaat worden. Maar zo begonnen bijna alle grote bedrijven—als iets wat niemand serieus nam, op precies het moment dat het serieus nemen het verschil maakte.

De volgende grote internet-businesses zijn misschien kleine betaalde deuren waar agents de hele dag doorlopen. Deuren die jij kunt bezitten. Jij kunt de tolpoort zijn.