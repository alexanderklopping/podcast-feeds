<!--
podcast_name: Dithering
guid: https://dithering.passport.online/member/episode/vibe-porting-and-meta-enterprise
-->

# De Tarmac, de Robots en het Bedrijfsgeheim van Silicon Valley

*Soms wordt de beste technologische vindingrijkheid niet geboren in een vergaderzaal of een lab, maar op een stilstaand vliegtuig op het asfalt van O'Hare. En soms onthult een kwartaalcijfer van een techgigant iets fundamentelers dan welke analist ook durft te zeggen: dat de grens tussen consumentenbedrijf en ondernemingssoftware niet alleen een strategische keuze is, maar een cultuurkloof zo diep als de Grote Oceaan.*

---

Het begon allemaal verkeerd. United Airlines vertraagde, Ben pakte zijn koffers en stapte over op American Airlines — wat hem er, zoals hij zelf zei, snel aan herinnerde dat dingen altijd erger kunnen. Op de taxibaan van O'Hare stond hij stil. Een sleepstang op een American Airlines-toestel was gebroken en blokkeerde het gangpad. Meer dan een uur lang bewoog er niets.

De meeste mensen scrollen in zo'n situatie lusteloos door hun telefoon. Ben schreef zijn eerste Mac-app.

De aanleiding was een stukje software dat ooit geliefd was in een kleine maar fervent getrouwe kring van Mac-gebruikers: Notational Velocity. Het origineel was gemaakt door een man genaamd Zachary. Het concept klonk absurd totdat je het had uitgeprobeerd. Er was één tekstveld bovenin een lijst van notities. Begin je te typen, dan filtert de app razendsnel alle notities die die tekst bevatten. Typ iets dat niet bestaat en druk je op enter, dan begint er meteen een nieuwe notitie met precies die zoekterm als titel. Zoeken en aanmaken waren hetzelfde. Eén handeling, twee functies, nul wrijving.

John herinnerde het zich meteen: "One of the all-time paradigms for using an app."

Het oorspronkelijke Notational Velocity was al jaren geleden verlaten. Brett Terpstra — een Mac-ontwikkelaar met een reputatie voor onmisbare, licht excentrieke tools — had het leven ingeblazen met een fork genaamd NVAlt. Dat was de versie die Ben jarenlang had gebruikt. NVAlt synchroniseert via SimpleNote, een notitiedienst inmiddels in handen van Automattic — handig, maar volstrekt onversleuteld, meer een plek om dingen snel te dumpen dan een kluis voor gevoelige gedachten. Het grotere probleem was een andere: NVAlt was voor het laatste bijgewerkt in 2013. Het draaide alleen op Intel. En nu vroeg zijn nieuwe MacBook Air hem om Rosetta te installeren — de vertaalsoftware waarmee Apple oudere Intel-apps op zijn eigen silicium laat draaien — enkel en alleen voor deze ene app.

Rosetta is zelf ook met pensioen. In de volgende versie van macOS verdwijnt het. De klok tikt.

"Ik wilde Rosetta niet installeren," zei Ben. "Dit was letterlijk de enige app."

Dus terwijl het vliegtuig stilstond en de sleepstang niemand iets uitmaakte, deed Ben iets wat een paar jaar geleden nog ondenkbaar was geweest: hij forkte de GitHub-repository van NVAlt — de broncode is vrij beschikbaar, met een permissieve licentie — en vroeg zijn AI-tools om de zaak om te bouwen naar Apple Silicon. Hij begon op het vliegtuig, maakte het af tijdens de rit van O'Hare naar huis in Wisconsin, negentig minuten door de nacht.

De aanpak die hij gebruikte, illustreert iets dat steeds meer ontwikkelaars ontdekken: Claude en ChatGPT Codex vullen elkaar verrassend goed aan, maar op tegengestelde wijzen. Claude doet te weinig. Het instrueert, het redeneert, het plant — en vergeet dan halverwege iets te implementeren. Condescending ook, merkte Ben droogjes op, maar dat neemt hij er gratis bij. ChatGPT Codex doet te veel: het stormt vooruit, past dingen aan die je niet had gevraagd en creëert nieuwe problemen. Samen, met Claude als architect en Codex als bouwer, werken ze buitengewoon goed. Een vriend van Ben had er zelfs een installatie van gemaakt waarbij de twee systemen gewoon met elkaar praten, over en weer, terwijl ze een taak uitvoeren. Je kijkt ernaar als naar een schaakpartij in slow motion.

"Het is geweldig," zei Ben. "Ik heb nu gewoon die flow."

Terwijl dit gesprek werd opgenomen, bracht Brett Terpstra een nieuwe app uit: Terminal Widget. Gratis, open source, direct gelinkt op Daring Fireball. John kon het niet laten: "Brett, I've been waiting on NVAlt for years. You say you're almost done." De ironie was compleet. Terpstra had jaren geleden beloofd dat NVAlt bijna klaar was voor een update. In de tussentijd had Ben, op een vliegtuig en in een huurauto midden in de nacht, de port al zelf gedaan.

De nieuwe NVAlt-fork lijkt te werken. Duizenden notities — een platte map van tekstbestanden, de meest elegante keuze van de oorspronkelijke ontwerpers, want dat betekent dat de data nooit gebonden is aan een eigen database of formaat — staan nog keurig op hun plek. Ben had ze al in een back-up, gesynchroniseerd via Dropbox. Hij is er voorzichtig optimistisch over, hoewel hij er snel bij voegt: "Het kan zijn dat ik terugkom met het bericht dat al mijn notities zijn verdwenen."

Hij gaat de port niet publiceren. Zijn naam hangen aan AI-gegenereerde code die andermans notities beheert is een verantwoordelijkheid hij niet wil. Maar de boodschap voor iedereen die ook NVAlt gebruikt en Rosetta wil vermijden is helder: fork de repository, vraag je eigen AI om het werk, en volg het pad. Het duurt een dag.

Het gesprek over Maestral liep in dezelfde richting. Maestral is een open source Dropbox-client die doet wat Dropbox vroeger deed: je geeft het een map, het synchroniseert die map met je Dropbox-account, en daarmee is de kous af. Geen bestanden die in de cloud zweven en in de Finder zichtbaar zijn maar niet echt gedownload zijn, geen wolkicoontje waarop je moet klikken voordat je iets kan openen. Gewoon bestanden op je schijf, altijd bijgewerkt.

De maker ervan is opgehouden met Dropbox en heeft de app feitelijk verlaten. Het werkt nog, maar certificaten verlopen, Dropbox past zijn API's aan, en niemand staat te trappelen om de rol over te nemen. Ben weet dit en is er onrustig van.

"Klinkt als dat jij dat bent," zei John. "Jij moet Maestral overnemen."

Ben wees dat af — maar het punt dat hij eigenlijk maakte is interessanter dan de afwijzing. Dit is precies het soort taak waarvoor AI-tools zijn gemaakt: geen nieuw idee, geen creatief ontwerp, maar een bestaande, werkende applicatie in de lucht houden terwijl de wereld eronder doorbeweegt. Niet uitvinden, maar conserveren. Robots zijn daar goed in. Misschien is dit de nieuwe vorm van open source onderhoud: niet één toegewijde ontwikkelaar die zijn vrije avonden opoffert, maar een willekeurige gebruiker die de AI instrueert om de zaak draaiende te houden.

---

Zes en een half uur had Ben besteed aan zijn stuk over Meta's kwartaalcijfers. John begreep pas na het lezen van Stratechery waarom de resultaten zo ongewoon waren — en waarom de aankondiging dat Meta zich op enterprise-software zou richten zo merkwaardig aanvoelt.

"Het is zoals figuring out a food allergy," zei John. Je weet niet precies wat er mis is, maar je elimineert systematisch alles wat je weet dat niet klopt — en wat overblijft moet de waarheid zijn, hoe onwaarschijnlijk ook. Het Sherlock Holmes-principe.

Meta bouwt een astronomisch bedrag aan eigen datacenters. De investeerders zijn ongeduldig. Ze begrijpen het advertentiebedrijf — het is winstgevend, veerkrachtig, en Meta beheert het met een soort meedogenloze efficiëntie die zijn gelijke nauwelijks kent. Maar al die capex voor GPU-clusters en energieinfrastructuur? Dat wringt. Dus wat doe je als investeerder de vraag stelt: waarvoor is dit allemaal?

Je zegt: we gaan de overcapaciteit verkopen aan bedrijven. We bouwen dit toch al voor onszelf, dus we kunnen het ook aan anderen aanbieden.

Het probleem is dat "compute verkopen" iets anders is dan "enterprise software verkopen." Als je rekenkracht verkoopt, verkoop je chips en bandbreedte. Maar Meta heeft het over het verkopen van daadwerkelijke enterprise-producten — tools die gebouwd zijn voor intern gebruik en nu extern aangeboden worden. Ze deden dit eerder al: een interne nieuwsfeedachtige tool voor bedrijfscommunicatie werd in de markt gezet. Het liep op niets uit.

Enterprise is geen productprobleem. Het is een cultuurprobleem.

"Consumer vereist een gezichtspunt," legde Ben uit. "Je kunt niet naar alle miljarden gebruikers luisteren. Je moet opiniëren. De steely resolve van Zuckerberg past daar perfect bij — hij doet wat hij denkt dat goed is, ongeacht wat Twitter erover zegt. En veel consumentenproducten lopen vast omdat ze zich te druk maken om die buitenwereld."

Enterprise is het tegenovergestelde. Je gaat bij de klant aan tafel. Je belegt diners, je geeft garanties, je belooft ondersteuning voor de komende veertig jaar — ook als je privately denkt dat dat bedrijf over tien jaar niet meer bestaat. Je spreekt een andere taal. Je hebt een go-to-market functie, wat in essentie betekent: een complete organisatie die is ingericht op het binnenhalen, bedienen en behouden van zakelijke klanten, met salesteams, accountmanagers, implementatiespecialisten en ondersteuningscontracten. Ben bekende met zeldzame zelfspot dat hij niet zeker weet of hij het begrip zelf ook echt beheerst: "I don't even know if I know it. I just know that I don't know it."

Het is alsof je een succesvol bedrijf in het ene land hebt en besluit dat je dat model gewoon kan kopiëren naar een land met een compleet andere cultuur. Dezelfde logica, andere regels, andere verwachtingen — en bedrijven die dit onderschatten betalen daar een hoge prijs voor. Google had hier jarenlang moeite mee. Google's cultuur was consumer, net als Meta's. De manier waarop je zoekresultaten verbetert, is niet de manier waarop je een CTO overtuigt zijn bedrijfssystemen aan jou toe te vertrouwen.

Er is nog een ironische dimensie aan dit verhaal. Apple en Meta liggen elkaar niet. Ze zijn op de oppervlakte elkaars tegenpolen — Apple verkoopt producten, Meta geeft diensten gratis weg — maar in hun kern zijn ze verrassend gelijkaardig: beide fanatiek consumentgericht, beide gedreven door designbeslissingen die van bovenaf worden opgelegd, beide gebouwd op de intuïtie van één dominante figuur. Bedrijven die het meest op elkaar lijken, botsen het hardst. Apple en Microsoft vinden elkaar nu beter dan ooit, want de overlap is verdwenen. Met Meta blijft de wrijving.

En toch is het Apple dat precies datgene heeft bereikt waar Meta nu naar grijpt, zonder er ooit voor te hoeven gaan staan. De iPhone sijpelde het bedrijfsleven binnen via de voordeur van de consument. Medewerkers wilden het apparaat, en bedrijven volgden. Apple hoefde nooit een salesforce op te bouwen, nooit een enterprise contract te tekenen, nooit een implementatiespecialist in te huren. Het product deed het werk.

Dat is de echte innovatie die Meta niet kan kopiëren: niet de technologie, maar de route.

Over de enterprise-aankondiging was Ben botweg: "They believe it and they're insane. Or they don't believe it and they're just throwing out slop to get investors off their back." Een van die twee. En dat tweede, voegde hij eraan toe, is een gebrek aan respect voor de mensen op die call — je gooit hun iets voor de voeten en rekent erop dat ze het slikken.

Wat overblijft, na al het elimineren, is een eenvoudige conclusie: Meta heeft een enorme kapitaaluitgave nodig om zijn AI-ambities te realiseren, de rechtvaardiging daarvoor is nog in ontwikkeling, en "enterprise" klinkt als een antwoord op een vraag die niemand goed weet te beantwoorden.

Ergens boven het Midwesten, op een stilstaand vliegtuig met een kapotte sleepstang, had Ben in dezelfde tijdspanne zijn eigen probleem wél opgelost. Niet met een groot verhaal, maar met een fork, een prompt en een flat folder vol tekstbestanden.