<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01KVTG145HBGSNKBRAYCWC5N9N
-->

# De Vijfvoudige Kloof: Hoe Open Source AI de Rekening Herschrijft

*In het voorjaar van 2026 werd een Chinees open source model viral op X. Niet omdat het de beste was. Maar omdat het goed genoeg was — voor een fractie van de prijs. Voor iedereen die dagelijks met AI bouwde, stelde GLM 5.2 een ongemakkelijke vraag: hoeveel betaal je eigenlijk te veel?*

---

Er is een moment in elke technologische golf waarop het speelgoed serieus wordt. Toen Zhipu AI in juni 2026 zijn GLM 5.2-model uitbracht, vergeleek vrijwel iedereen op X het met de introductie van ChatGPT — maar dan voor lokale AI. Dat is een grote claim. Maar Amir, ontwikkelaar en AI-practitioner, begrijpt precies waarom die vergelijking aanslaat.

"We hebben lang gezien dat lokale modellen of te veel opslagruimte vraten, of te veel GPU-geheugen vroegen om überhaupt op je computer te draaien," vertelt hij. "GLM 5.2 is ook resource-intensief, maar het verschil is dat open source providers zoals OpenRouter het nu in de cloud draaien — en je effectief minder betaalt voor input- en outputtokens dan bij de grote gesloten modellen."

OpenRouter is als een tussenhandelaar voor AI-modellen: in plaats van rechtstreeks een abonnement op OpenAI of Anthropic te nemen, laad je credits en roep je via één API elk model aan dat je wilt — van de nieuwste Claude tot open source alternatieven als GLM 5.2. Het platform rekent op basis van daadwerkelijk gebruik, in tokens. Geen maandabonnement, geen vaste kosten. Je laadt twintig dollar, stelt het in, en je bent er.

GLM 5.2 heeft een contextvenster van één miljoen tokens — ruwweg het equivalent van tien dikke romans die het model tegelijkertijd kan "lezen" — en scoort 81 punten op Terminal Bench 2.1, een gangbare maatstaf voor hoe goed een model langlopende, samengestelde taken afhandelt. Dat is vier punten minder dan Claude Opus 4.8, Anthropics zwaarste model. Op een andere brede benchmark, die de algemene intelligentie meet, haalt GLM 62,1 procent tegenover OpenAI's 69,2. De kloof bestaat. Maar wat die kloof werkelijk betekent voor iemand die een startup bouwt of dagelijks code schrijft, is een andere vraag.

"Eerlijk gezegd ben ik niet slim genoeg om te begrijpen wat benchmarks precies zeggen," zegt Amir. "Voor mij is het: laten we het bouwen, gebruiken, en kijken hoe het aanvoelt. En als GLM 5.2 sterk is in één deel maar zwak in een ander, dan denk ik na over hoe ik andere modellen kan inzetten om dat samen op te lossen."

Amir heeft 5.1 nooit uitgebreid getest — hij stapte direct in op 5.2. Maar uit wat hij op X ziet en hoort van collega-bouwers is de sprong groot, met name op het vlak van frontend-taken en instruction-following. De versie daarvoor was veelbelovend in theorie maar wispelturig in de praktijk. 5.2 voelt anders. Strakker. Betrouwbaarder.

---

Die pragmatische houding brengt hem bij het idee dat de komende maanden de AI-markt zal domineren: model chaining, ook wel de fusion-aanpak genoemd — een term die OpenRouter zelf heeft gemunt. Het principe is eenvoudig maar krachtig. Je sequenst modellen: het ene plant, het andere voert uit, het derde controleert. Je laat elk model doen waar het het best in is, in plaats van alles door één duur frontiermodel te jagen.

Denk aan internationale handel. Canada maakt de beste maple syrup, Florida kweekt de beste sinaasappels. Je haalt niet alles uit één land omdat dat toevallig het dichtstbijzijnde is — je betrekt elk product uit de regio die het het best produceert. Model chaining is hetzelfde principe, toegepast op rekenkracht. Gebruik het zware model voor de beslissingen die zwaar denkvermogen vragen. Gebruik het lichte, goedkopere model voor de executie. Gebruik een snel model voor de review. Elk onderdeel van de keten kost wat het waard is — niet meer.

Amir demonstreert dit aan de hand van een eigen project. Hij bouwde een kleine webapp in Opus 4.8 en begon de frontend daarna te verfijnen met GLM 5.2. Eén prompt: herontwerp de hero-sectie, voeg een carrousel toe voor de afbeeldingen, bouw een bento grid voor de features. Het resultaat? Geen perfecte, smetteloze code — "je kunt zien dat het een beetje vibe-coded is, met die zijbadges en labels" — maar voor een model dat je voor minder dan de helft van de prijs draait, is het verrassend precies.

"Ik denk niet dat lokale modellen eerder deze mate van verfijning hadden," zegt hij. "GLM 5.2 volgt instructies op een manier die ik niet eerder zag bij de vorige generatie."

Maar er is een beperking: GLM 5.2 ondersteunt geen afbeeldingen. Het model kan geen screenshots zien en begrijpen. Amir's oplossing is pragmatisch tot op het bot. Hij opent Opus 4.8, laadt zijn screenshot, en vraagt het model zijn hero-sectie nauwkeurig te beschrijven — kleur, opbouw, elementen, verhoudingen. Vervolgens kopieert hij die beschrijving naar GLM 5.2 en laat dat model de daadwerkelijke code aanpassen op basis van wat Opus heeft "gezien."

"Je traint het dure model om na te denken over het plan," legt hij uit, "en vervolgens lever je hetzelfde resultaat op frontierniveau maar voor een veel lagere prijs." Het is een omweg. Maar het werkt.

---

De prijs. Dat is waar het gesprek pas echt zijn tanden toont.

Amir heeft de cijfers doorgerekend op basis van een representatieve coding-taak: vijftigduizend inputtokens, vijfentachtigduizend outputtokens — genoeg om een serieuze codeeropgave te voltooien op een kwaliteitsniveau dicht bij Opus 4.8. Met GLM 5.2 via OpenRouter kost dat 44 cent. Met Opus 4.8 kost diezelfde taak 2,38 dollar.

Een factor vijf.

"Als je zegt: het is twee dollar hier en 44 cent daar, klinkt het niet als veel," geeft Amir toe. "Maar als je dit de hele dag door doet, grote taken aanpakt, en niet wilt worden afgeknepen door tokenbedragen, is het enorm. Vijf keer is een groot verschil."

En dat verschil groeit. Niet omdat de modellen duurder worden — integendeel, de rekenkracht per token wordt goedkoper met de maand. Maar omdat de manier waarop mensen AI inzetten radicaal verandert. Amir omschrijft het als het verschil tussen token-maximalisatie en output-maximalisatie. Vroeger mat je AI-adoptie af aan het aantal tokens dat je team doorjaagde. Zoveel mogelijk door de machine pompen was het signaal dat je serieus was. Nu kijk je naar wat er daadwerkelijk uit komt — en wat het kost om dat te bereiken. De maatstaf verschuift van volume naar waarde.

"Intern bij bedrijven zie ik dit al gebeuren," vertelt hij. "Het eerste jaar gold het mandaat: word AI-native, gebruik zoveel mogelijk. Nu zeggen diezelfde bedrijven: wacht even, we geven te veel uit. Hoe worden we nu effectief?"

---

Satya Nadella noemde het vorig jaar al in een interview: menselijk kapitaal plus tokengebruik is de nieuwe meetlat voor productiviteit binnen grote technologiebedrijven. Het klinkt abstract totdat je het van dichtbij ziet. Amir ziet het van dichtbij.

Bedrijven die een jaar geleden Cloud Code-licenties aan hun hele team uitrolden, trekken die nu terug. Niet omdat het niet werkt — maar omdat het te goed werkt, en te duur. Engineers met directe toegang tot de API draaiden uren lang zware taken. Dat is precies waarvoor het gebouwd is. Maar hetzelfde gold plotseling voor de rest van het bedrijf: marketeers, communicatiemedewerkers, salesteams. Iedereen had toegang. Iedereen gebruikte het. En niemand begreep wat het kostte.

Het probleem zit hem niet alleen in de engineers die zware modellen inzetten voor complexe taken. Het probleem zit hem in Jan van Marketing die Opus 4.8 in hoge denkstand gebruikt om een e-mail op te maken. Dat is governance-chaos. Amir heeft op het moment van dit gesprek actieve gesprekken met bedrijven die hem vragen te helpen bij precies dat: welk model gebruik je wanneer, en wie in het team mag wat inzetten?

"Model chaining is een groot onderdeel van dat antwoord," zegt hij. "Snap je? Misschien moet Jan van Marketing niet Opus 4.8 gebruiken om zijn e-mail te formatteren."

Het klinkt triviaal. Maar vermenigvuldig die verspilling over honderd medewerkers, honderd e-mails per dag, vijf werkdagen per week — en je hebt een kostenpost die de CFO graag zou willen zien verdwijnen. AI-governance is geen bureaucratisch vraagstuk. Het is gewoon goed beheer.

---

Hier komt het Uber-argument om de hoek, en het snijdt hout.

Toen Uber lanceerde, subsidieerde het bedrijf ritprijzen agressief. Gebruikers werden verslaafd aan de app voordat ze beseften wat een niet-gesubsidieerde rit zou kosten. Toen de subsidies afbouwden — naarmate aandeelhouders rendementen eisten en het bedrijf naar de beurs ging — stegen de prijzen. Het product was al onmisbaar geworden. Je staptijd terug was geen optie meer.

De AI-industrie doet hetzelfde. OpenAI, Anthropic, Google — ze rekenen momenteel ver onder de werkelijke kostprijs. Ze willen dat je workflows bouwt op hun modellen, dat je processen, teams en producten om hun API's heen organiseert. En dat werkt. Amir merkt het zelf: zijn usage-limieten worden sneller bereikt dan een jaar geleden. Toen Grok uitkwam, had hij zijn maandlimiet binnen één dag opgebruikt. Eén dag.

"De AI-subsidie op tokens wordt zichtbaar kleiner," zegt hij. "En ik vraag me af: in hoeverre bouwen we ons in een afhankelijkheid in waarvan de prijs straks veel hoger uitvalt?"

De strategische conclusie die Amir trekt is dit: als je nu investeert in een machine die lokale modellen kan draaien — een Mac Studio, een dedicated GPU-rig, wat het ook is — betaal je eenmalig voor rekenkracht die je daarna kunt inzetten zonder tokenmeter. GLM 5.3 komt. GLM 5.5 komt. De hardware die je vandaag koopt, draait die modellen morgen. En als de frontiermodellen twee keer zo duur zijn geworden, heb jij al geïnvesteerd in de infrastructuur om ze te omzeilen.

"Ik denk niet in termen van: hoe bespaar ik nu 1,94 dollar per taak," legt Amir uit. "Ik denk in termen van: welke infrastructuur wil ik hebben als de subsidies verdwijnen en de frontiermodellen twee keer zo duur zijn?"

---

Maar hier is het nuancerende geluid dat dit gesprek zijn eerlijkheid geeft: je hebt die hardware helemaal niet nodig om vandaag te beginnen.

Op X verschijnen wekelijks threads van mensen die aanraden een Mac Studio van vijfduizend dollar te kopen, of een dedicated GPU-rig op te zetten in je thuiskantoor. Alsof lokale AI alleen bereikbaar is voor wie bereid is flink te investeren in ijzer. Amir haalt zijn schouders op bij die redenering.

"OpenRouter doet dat voor je," zegt hij. "Zij draaien de modellen in de cloud. Jij betaalt per gebruik. Laad twintig dollar, stel het in, en je bent er. Je hebt geen Mac Mini voor vijfduizend dollar voor nodig."

De opzet in Cursor — de populaire AI-gedreven code-editor — is opmerkelijk direct. Je gaat naar Zhipu AI, haalt een API-sleutel op, plakt die in de OpenAI-velden van Cursor, overschrijft het API-eindpunt met dat van Zhipu, voegt GLM 5.2 toe als custom model, en je bent klaar. Voor wie Cloud Code via de CLI gebruikt — Anthropics terminal-gebaseerde coding-omgeving — werkt het vergelijkbaar: je maakt een profiel aan via OpenRouter, geeft de modeldetails op inclusief contextvenster, en kunt voortaan schakelen tussen Claude en GLM 5.2 binnen dezelfde omgeving.

De kracht van dit alles is modelneutraliteit. Cursor is niet gebonden aan één provider. Cloud Code ook niet. Je kunt in één codeertaak beginnen met Opus om een architecturale beslissing te nemen, doorgeven aan GLM 5.2 voor de uitvoering, en reviewen met Composer 2.5. Of je plant met Opus, executeert met GLM 5.2, en laat GPT-4.5 de review doen. De combinaties zijn eindeloos, en elk ervan heeft een ander kostenprofiel. Elke stap kost wat hij waard is — niet meer.

"Ik wil niet verrast worden," zegt Amir. "Ik wil weten: als ik Opus gebruik voor de planning, en GLM voor de executie, en daarna nog een licht model voor de review, wat kost dat hele traject? En kan ik dat keer honderd doen zonder dat mijn kaart wordt geweigerd?"

---

Er is een segment van de AI-wereld dat deze rekensommen irrelevant vindt. De token-maximalisten: de mensen die zeggen dat de opportunity cost van niet-gebruik altijd groter is dan de cost of gebruik. Bouw maar, jaag tokens door de machine, de ROI rechtvaardigt alles. Als je tweehonderd dollar uitgeeft maar duizend verdient, is er geen probleem. Schaal maar op.

Amir was daar zelf één van.

"In ons eerste gesprek vroeg jij me wat alles kostte," herinnert hij zich. "Ik zei: geen idee, man, ik ben gewoon aan het uitgeven." Hij glimlacht bij de herinnering. "Vibe spending." Die mentaliteit is veranderd. Zijn team groeit. Zijn usage-limieten worden sneller bereikt. En hij levert dezelfde harnesses en modellen aan niet-technische teams die Opus 4.8 in hoge denkstand gebruiken om een e-mail op te maken.

Voor een solist is token-maximalisatie makkelijk te verdedigen. De kosten zijn overzichtelijk, de output direct zichtbaar. Maar Amir draait het argument om: je moet niet token-maximaliseren. Je moet token-minimaliseren en output-maximaliseren. Het gaat niet om hoeveel je door de machine jaagt — het gaat om wat eruit komt, en wat je daarvoor betaalt. Dat is een subtiel maar fundamenteel verschil.

"Als je direct een ROI kunt laten zien — ik heb tweehonderd dollar uitgegeven en duizend verdiend — prima," zegt hij. "Maar anders: de subsidie loopt op een dag af. En dan wil je al weten hoe je zonder rijdt."

---

De verschuiving die Amir beschrijft is de volwassenheid van de markt. In het eerste jaar van AI-adoptie was enthousiasme de maatstaf. In het tweede jaar wordt efficiëntie de maatstaf. Bedrijven die AI serieus nemen, vragen zich niet meer af of ze het moeten gebruiken — ze vragen zich af hoe ze er grip op krijgen.

En voor de solist, de indie-bouwer, de eenpitter die een startup opzet zonder honderd medewerkers: het argument is nog dwingender. "Je kunt nu bouwen alsof je een groot team hebt," zegt Amir. "Maar dan moet je wel nadenken over hoe je dat team inzet. Niet alles hoeft via het duurste model. Geef elk model de taak waarvoor het gemaakt is."

---

De les die GLM 5.2 eigenlijk leert, is niet specifiek over dit model. Over zes maanden is er een 5.3. Over een jaar een 5.5. Het model zal beter zijn, de benchmarks zullen dichter bij de frontiermodellen liggen, de beperkingen rondom vision en toolgebruik zullen kleiner worden. Dat is onvermijdelijk. Modellen verouderen snel in dit tijdperk. Architectuurkeuzes niet.

De infrastructuurkeuze die je nu maakt — of je een model-agnostische harness opzet, of je leert denken in sequenties van modellen, of je begrijpt welke taken zwaar denkvermogen vereisen en welke gewoon executie — die keuze bepaalt hoe goed jij straks bent gepositioneerd als de markt er heel anders uitziet. De bedrijven die een jaar geleden hun workflows volledig rondom één provider bouwden, zitten nu vast. De bedrijven die modelneutraal bleven, kunnen morgen overstappen.

"Wat ik wil dat mensen meenemen is niet zozeer GLM 5.2 zelf," zegt Amir. "Het gaat om de aanpak. Stel je harness in op een manier dat je modellen kunt wisselen zonder alles opnieuw te bouwen. Ga naar OpenRouter. Laad twintig dollar. Experimenteer met wat het kan. En begin na te denken over welke stap in je workflow welk model verdient."

Dat is geen revolutionaire gedachte. Het is eigenlijk gewoon goed beheer — de soort discipline die ieder bedrijf al toepast op elk ander inkoopbudget. Maar in een wereld waar AI zo snel beweegt, en waar de tarieven zo snel kunnen veranderen, is die discipline jonger dan de technologie zelf.

De Uber-subsidie loopt op een dag af. De vraag is niet óf. De vraag is alleen wanneer — en of jij dan al weet hoe je zonder rijdt.