<!--
source_url: https://dithering.passport.online/member/episode/ben-gets-hacked?access_token=eyJhbGciOiJSUzI1NiIsImtpZCI6ImRpdGhlcmluZy5wYXNzcG9ydC5vbmxpbmUiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJkaXRoZXJpbmcucGFzc3BvcnQub25saW5lIiwiYXpwIjoiQ1lIQ3laV295UmhacDFiUEpIMmlYVSIsImVudCI6eyJ1cmkiOlsiaHR0cHM6Ly9kaXRoZXJpbmcucGFzc3BvcnQub25saW5lL21lbWJlci9lcGlzb2RlL2Jlbi1nZXRzLWhhY2tlZCJdfSwiZXhwIjoxNzkzOTQ4NDYyLCJpYXQiOjE3OTEzNTY0NjIsImlzcyI6Imh0dHBzOi8vYXBwLnBhc3Nwb3J0Lm9ubGluZS9vYXV0aCIsInNjb3BlIjoiZmVlZDpyZWFkIGFydGljbGU6cmVhZCBhc3NldDpyZWFkIGNhdGVnb3J5OnJlYWQgZW50aXRsZW1lbnRzIHBvZGNhc3QgcnNzIiwic3ViIjoiYWVhOWM5ZWUtMDY3MS00YWFjLTkzYzAtMzM0ZDU3NjViZTUxIiwidXNlIjoiYWNjZXNzIn0.Huxa1ChH1AitcxPxZMy5d1FDbxvXn1saTfHjAT4WAEkodBBX7SU1MwNXxF1P5gwjh1dVUpFmXuJcGi2J1YNPJq3d2o3bPmg-Is9hdXbcdM-T1NSkE1NEGmKk2R6lVv8N5i-4zLxYHV4sp1t0vcGVEnS6T2u0jMmdVkT0XERCgNQg6NRuyXRExXn3QdSHIWfmER9hmISh1tTt6SUo5lfd5lGVMYjr2kDx_70aWcHWxo_iyT9aZJlzLkZ04-4yYxk_K-NOLSOePD7vCjs03NE-xjQgA70qs1aGNRPL0bV21rNVu4SpBDVLSuhB6Sluuear4ZiwXSq-MlDRkFaQyVRdPw
podcast_name: Dithering
guid: https://dithering.passport.online/member/episode/ben-gets-hacked
-->

# De poort die openstond

Een Mac die van buitenaf bereikbaar was. Een schakelaar die verdween zodra een andere instelling werd aangezet. En een bedrijf dat een beveiligingsprobleem oploste voordat de eigenaar zelf begreep hoe het had kunnen ontstaan. Het gesprek begon met een hack, maar mondde uit in een ongemakkelijke vraag over Apple: wat blijft er over van een gebruiksvriendelijke computer wanneer zelfs ervaren gebruikers niet meer kunnen zien welke deuren openstaan?

‘Hallo, AppleCare. Hoe kan ik u helpen?’

Ben bracht de zin met het droge plezier van iemand die zijn eigen helpdeskmedewerker speelde. Hij had die ochtend zijn artikel over de hack van zijn Mac nog aangepast. Niet om Apple vrij te pleiten, juist om zijn eigen rol scherper te maken.

‘Het was mijn fout,’ zei hij. ‘Ik ben degene die poort 5900 naar internet had opengezet. Dat was dom.’

Poort 5900 is de ingang die macOS gebruikt voor Schermdeling, de functie waarmee iemand een andere Mac op afstand kan bedienen alsof hij erachter zit. De muis beweegt, het toetsenbord reageert, het scherm verschijnt op een andere computer. Handig voor een familielid dat hulp nodig heeft. Onmisbaar voor iemand met een Mac die ergens in een kast staat, zonder monitor, muis of toetsenbord.

Maar in dit geval zat er een ernstig lek in die voorziening. Als Schermdeling aanstond en poort 5900 vanaf internet bereikbaar was, kon een aanvaller die poort opsporen, een commando sturen en zich vrijwel onmiddellijk beheerdersrechten verschaffen.

‘Een directe escalatie naar admin,’ zei Ben. ‘En je merkt niet eens dat er iets gebeurt.’

Zijn gesprekspartner vond het nog altijd merkwaardig dat het lek zo weinig aandacht had gekregen. Schermdeling was geen obscure functie voor serverbeheerders. Zij zat op iedere Mac. Toch had het nieuws geen storm veroorzaakt, terwijl de gevolgen desastreus konden zijn.

Ben wist precies waarom hij de poort had opengelaten. Hij beheerde meerdere Mac mini’s, verspreid over de Verenigde Staten en daarbuiten, onder meer voor vrienden in Taiwan. Via die machines konden zij Amerikaanse televisie en sportwedstrijden bekijken die vanuit hun eigen land niet bereikbaar waren.

De computers stonden op verre plekken bij mensen thuis: naast een router, onder een bureau, soms in een kast. Onbemand — *headless*, zoals technici het noemen. Zolang alles werkte, waren ze nauwelijks zichtbaar. Maar wanneer een verbinding wegviel, werden ze ineens essentieel.

Normaal maakte Ben gebruik van Tailscale, een dienst die apparaten via een versleuteld netwerk met elkaar verbindt alsof ze in hetzelfde huis staan. Maar hij vertrouwde niet volledig op één toegangspoort. Eerder had een storing bij Tailscale hem buitengesloten. Toen had hij alsnog verbinding kunnen maken via Schermdeling en poort 5900.

Dat was zijn reserveplan geweest.

Als Tailscale uitviel, kon hij nog steeds bij zijn Mac mini’s.

Alleen werkte die redenering ook de andere kant op. Als Ben via die poort naar binnen kon, kon een aanvaller dat eveneens.

‘Natuurlijk,’ zei hij. ‘Als ik erin kon, kon iedereen erin.’

Na de ontdekking sloot hij de poorten. Niet alleen op zijn eigen machine. Meerdere Mac mini’s bleken gecompromitteerd. De handige noodoplossing had zich door zijn netwerk verspreid als een herhaalbare fout.

Daarna kocht Ben kleine KVM-apparaten: fysieke kastjes waarmee iemand op afstand toetsenbord, beeldscherm en muis kan overnemen. Wanneer zijn vrienden weer langskwamen, zouden zij de kastjes aansluiten. Het was omslachtiger dan een open poort. Ook duurder. Maar het gaf hem iets terug wat software alleen niet kon bieden: een fysieke uitweg.

‘Dat is uiteindelijk de realiteit,’ zei hij. ‘Je hebt fysieke én softwarematige oplossingen nodig. Je kunt niet alleen op software vertrouwen.’

Hij bleef benadrukken dat de fout bij hem lag. Maar onder die schuldbekentenis zat irritatie. Apple maakte Schermdeling vrijwel onmisbaar voor wie onbemande Macs wilde beheren, terwijl het bedrijf tegelijk steeds minder duidelijk maakte wat die functie precies deed, welke toegang openstond en waar de grens lag tussen een computer thuis bedienen en hem blootstellen aan het internet.

‘Wist je,’ vroeg Ben, ‘dat “automatisch beveiligingsupdates installeren” niet betekent dat je alle beveiligingsupdates krijgt?’

Dat was geen retorische vraag.

Een paar dagen eerder had Apple op zijn ontwikkelaarswebsite een korte verklaring geplaatst. Twee alinea’s, bijna zonder toelichting. De tekst ging over Volledige schijftoegang, in macOS bekend als *Full Disk Access*: een machtiging die een programma vrijwel overal op de computer laat kijken. Voor een reservekopieprogramma kan dat noodzakelijk zijn. Zo’n programma moet immers ieder bestand kunnen lezen om een volledige kopie te maken. Maar voor andere software is het een sleutelbos waar maar weinig sleutels aan zouden moeten hangen.

Apple’s mededeling kwam kort nadat Jason Aten, columnist bij *Inc.*, over Muse had geschreven, een AI-toepassing waarmee hij had gewerkt. Aten dacht dat hij Muse geen Volledige schijftoegang had gegeven. Zijn iMessages moesten dus buiten bereik blijven.

Toen begon Muse over een bericht dat Aten net had ontvangen.

‘Hé, Jason,’ schreef de software. ‘Ik zag net je iMessage van je redacteur over je volgende column.’

Aten reageerde zoals iemand reageert wanneer een onbekende stem ineens iets zegt wat alleen in zijn eigen kamer gezegd kan zijn.

‘Wacht even. Hoe weet jij iets over mijn iMessages? Ik dacht dat je daar geen toegang toe had.’

De schrik zat niet in een abstract debat over privacy. Hij zat in die ene zin. Een programma had iets gelezen waarvan de gebruiker dacht dat het afgeschermd was.

Apple’s korte nota leek op dat moment geen technische toelichting maar een haastig opgetrokken scherm. Gebruikers, schreef het bedrijf in essentie, begrepen niet goed wat Volledige schijftoegang betekende. De machtiging was bedoeld voor krachtige toepassingen zoals reservekopiesoftware. Tegelijk kon zij de veiligheid van berichten aantasten. Apple wilde gebruikers voortaan duidelijker maken welke toestemming zij gaven.

Maar wat betekende ‘duidelijker’?

Kwam er een betere beveiliging? Of alleen een nieuw venster met nog zwaardere taal?

‘Ik denk dat het gewoon een engere waarschuwing wordt,’ zei Bens gesprekspartner. ‘Of weer iets extra’s dat je moet aanvinken.’

Ben hoorde in Apple’s formulering een ouder conflict binnen het bedrijf. Aan de ene kant stonden de ingenieurs die de Mac nog zagen als een Unix-werkstation: een krachtige computer waarop mensen scripts schrijven, processen automatiseren, eigen hulpmiddelen bouwen en systemen naar hun hand zetten. Aan de andere kant stonden de mensen die het merk moesten beschermen tegen één eenvoudig, vernietigend verhaal: een AI-programma leest iMessages mee.

‘Meta is altijd Apple’s oogappel,’ zei Ben, met een woordspeling die zuur genoeg klonk om serieus te zijn.

Het patroon was vreemd. Enkele maanden eerder was er ophef geweest over OpenAI en toegang tot iMessages. Daarvoor hadden gebruikers van Claude en andere AI-diensten soortgelijke mogelijkheden gezien. Maar niet ieder incident groeide uit tot een crisis. Sommige verhalen bleven in technische kringen hangen. Andere bereikten de grote, onrustige buitenwereld.

Wat de meeste mensen zouden onthouden, was niet het onderscheid tussen lokale toegang, versleuteling of systeemmachtigingen. Zij zouden alleen lezen: iMessage is niet veilig.

‘Niemand begrijpt encryptie,’ zei Bens gesprekspartner.

Het klonk hard, maar het was niet onjuist. Berichten kunnen versleuteld op een schijf staan. Maar zodra macOS ze op het scherm toont, moeten ze leesbaar zijn. Een programma dat op diezelfde Mac draait en voldoende rechten heeft, probeert niet noodzakelijk van buitenaf binnen te breken. Het bevindt zich al in het huis.

Ben herinnerde zich hoe Apple in de jaren 2000 reageerde toen ontwikkelaars alternatieven wilden bouwen rond de iTunes-bibliotheek. Apple versleutelde de database. Misschien, dacht hij, zou het bedrijf hetzelfde doen met iMessage: berichten op systeemniveau sterker afschermen, zelfs voor programma’s met Volledige schijftoegang.

Maar ook dan bleef er een fundamenteel probleem. De sleutel moest ergens op de Mac bestaan. En waar een sleutel bestaat, kan een programma met genoeg rechten hem misschien vinden.

Voor Ben leidde de kwestie terug naar zijn eigen hack. Niet omdat Muse en poort 5900 technisch hetzelfde probleem waren, maar omdat beide gevallen draaiden om een gebruiker die niet meer goed kon zien wat zijn computer toestond.

‘De hele schermdelingstoestand is een godvergeten puinhoop,’ zei hij.

Zijn gesprekspartner grinnikte. Hij had Bens artikel gelezen en dacht aanvankelijk dat hij al wist wat er gebeurd was.

‘Nee,’ onderbrak Ben hem. ‘Jij had het verhaal bij *Ars Technica* gevonden. Je gaf mij alleen geen krediet.’

‘Sorry. Jij schreef je update. Ik vond dat verhaal.’

‘Ik kan het hebben, Ben. Echt.’

Het was een klein conflictje, bijna huiselijk. Maar het toonde hoe dicht zij op het onderwerp zaten. Dit was geen gesprek over de fouten van een bedrijf op veilige afstand. Het waren twee mensen die hun eigen Macs openden, instellingen naplozen en zich afvroegen welke keuzes zij jaren geleden hadden gemaakt zonder nog te weten wat die precies betekenden.

Bens acute probleem was inmiddels al opgelost door Apple’s President’s Office, de hoogste escalatielaag van de klantenservice.

‘Het President’s Office had het probleem opgelost voordat ik zelf doorhad wat er aan de hand was,’ zei hij.

Dat was geruststellend, maar ook onbevredigend. De wond was gehecht voordat de patiënt wist hoe hij hem had opgelopen. Ben wist dat zijn Mac kwetsbaar was geweest. Hij wist dat Apple had ingegrepen. Maar hij had nog steeds geen helder beeld van de instellingenketen die hem daar had gebracht.

Zijn gesprekspartner besloot zijn eigen Schermdeling-instellingen te controleren.

Wat hij zag, maakte de verwarring alleen groter.

Schermdeling stond uit. Dat leek duidelijk. Maar ergens anders in Systeeminstellingen stond Externe bediening aan — *Remote Control* in de Engelstalige interface. Dat was volgens Apple een andere functie, al lag zij in hetzelfde gebied van de computer. Toen hij naar Schermdeling doorklikte, vond hij niet eens meer de schakelaar die hij verwachtte.

‘Ik heb Schermdeling uitstaan, maar Externe bediening aan,’ zei hij. ‘Dat is een andere instelling.’

De gebruikelijke schakelaar voor Schermdeling was verdwenen.

‘Ik heb niet eens dat selectievakje meer — of hoe die moderne schakelaars ook heten — omdat die andere instelling het overschrijft.’

Op zijn scherm stond in feite: deze functie is hier niet beschikbaar; ga naar Externe bediening. De instelling die hij zocht, was niet uitgeschakeld omdat hij haar had uitgezet. Zij was uit beeld verdwenen omdat een andere keuze haar had overruled.

Hij probeerde het probleem terug te brengen tot een gewone vraag.

Stel dat deze Mac thuis staat, aangesloten op zijn eigen wifi. Hij wil hem kunnen bedienen vanaf een andere computer in huis. Kan dat zonder meer? En als hij de Mac op reis wil bereiken, hoe doet hij dat dan? Moet hij iets in zijn router veranderen? Staat toegang van buitenaf misschien al open?

Apple’s interface gaf geen antwoord.

Er stond niet: deze computer is alleen bereikbaar binnen uw thuisnetwerk.

Er stond evenmin: deze dienst wordt van buitenaf bereikbaar wanneer uw router verkeer doorstuurt naar poort 5900.

De gebruiker moest zelf begrijpen hoe Schermdeling, Externe bediening, netwerkpoorten en routerinstellingen op elkaar inwerkten. Hij moest weten dat een instelling op de Mac iets anders kon betekenen dan een open deur in de router. En hij moest begrijpen dat een verdwenen schakelaar niet per se betekende dat het risico verdwenen was.

Dat was precies het soort verwarring dat Apple vroeger beter wist op te lossen dan wie ook.

‘Het probleem is niet dat je iets ingewikkelds kunt doen,’ zei Bens gesprekspartner. ‘Het probleem is dat Apple je niet laat zien wat er aanstaat en hoe je het weer uitzet.’

Ben had Apple-bestuurders in het verleden zelf aangesproken op de wildgroei in de instellingen van macOS. Wat was dit voor rommel? Het antwoord was telkens geruststellend geweest: het zou beter worden.

‘Het is niet beter,’ zei hij.

Dezelfde mist hing rond Apple’s beveiligingsupdates. Ben gebruikte al meer dan tien jaar Macs. Hij had altijd aangenomen dat de optie voor automatische beveiligingsupdates betekende wat de woorden beloofden: belangrijke reparaties zouden vanzelf worden geïnstalleerd.

Dat bleek niet altijd zo te zijn.

Sommige veiligheidsreparaties kwamen mee in kleine macOS-updates, de zogeheten puntreleases. Wie die niet automatisch liet installeren, kon dus een belangrijk lek missen, ook al stond de voor de hand liggende beveiligingsoptie aan.

‘Op mijn Linux-computers ben ik veel strenger,’ zei Ben. ‘Daar ben ik veel alerter op beveiliging dan ik op de Mac bleek te zijn.’

Apple had hem in slaap gesust, vond hij.

Zijn gesprekspartner opende dezelfde instellingen en las ze hardop voor. Nieuwe updates downloaden wanneer beschikbaar: aan. macOS-updates automatisch installeren: uit, omdat hij niet wilde dat een volledige systeemupdate zich zonder waarschuwing installeerde. Systeemgegevens en beveiligingsupdates installeren: aan.

Apple waarschuwde gebruikers wanneer zij die laatste optie wilden uitschakelen. Laat dit aanstaan, zei het systeem in essentie. Het was belangrijk.

Ben had die optie aanstaan. Zijn gesprekspartner ook.

‘Als die schermdelingsbug daar niet onder valt,’ vroeg Ben, ‘wat valt er dan in hemelsnaam wel onder?’

Het ging niet meer om één fout vinkje. Het ging om vertrouwen. Apple had jarenlang de belofte gedaan dat de Mac ingewikkelde techniek toegankelijk maakte. Nu bleek die toegankelijkheid soms te bestaan uit woorden die geruststellend klonken, maar iets anders deden dan een gebruiker redelijkerwijs mocht verwachten.

Volgens Ben lag een deel van de oorzaak bij de herbouw van Systeeminstellingen, ongeveer drie jaar eerder. In de oude versie van macOS waren afzonderlijke voorkeurspanelen in wezen kleine, zelfstandige programma’s. Apple kon voor elke taak een eigen scherm ontwerpen.

Time Machine, de reservekopiefunctie van de Mac, was daarvan het mooiste voorbeeld. Een groot icoon. Een grote schakelaar. Eén eenvoudige vraag: wilt u Time Machine gebruiken?

Hier zet u het aan.

Schermdeling had zo’n scherm nodig. Geen verzameling instellingen die elkaar stilzwijgend overschreven, maar een overzicht waarop iemand onmiddellijk kon zien: dit staat open. Deze gebruikers mogen erbij. Vanaf deze netwerken is toegang mogelijk. Zo sluit u het weer af.

In plaats daarvan moesten zelfs deskundige gebruikers raden.

Diezelfde verwarring had zich volgens Ben verspreid door het hele toestemmingssysteem van macOS. Apps vroegen toegang tot foto’s, documenten, camera, microfoon, schermopnames, automatisering en het bureaublad. Elk verzoek afzonderlijk was verdedigbaar. Een programma dat ongemerkt de camera aanzette of persoonlijke bestanden doorzocht, was geen denkbeeldig gevaar.

Maar de optelsom maakte gebruikers murw.

Ben behoorde naar eigen zeggen tot de mensen die van alles op hun bureaublad bewaarden: tijdelijke bestanden, afbeeldingen, documenten die tussen programma’s heen en weer gingen. Voor hem was het bureaublad geen kluis. Het was een werkbank.

‘Dat is gewoon een plek waar ik tussen apps werk,’ zei hij. ‘Dat je daar toestemming voor moet vragen, is krankzinnig.’

Zijn gesprekspartner zag de andere kant. Voor veel mensen was het bureaublad wel degelijk een ongeordende kluis: belastingaangiften, contracten, familiefoto’s, soms zelfs wachtwoordbestanden die daar nooit hadden mogen belanden, maar er toch lagen. Als iedere app daar zomaar mocht rondkijken, was dat een reëel privacyprobleem.

Ben bestreed dat niet. Zijn bezwaar ging over de schaal waarop Apple toestemming organiseerde. macOS vroeg die per afzonderlijk programma. Voor de meeste mensen klonk dat veilig. Voor Ben, die werkte met AI-agenten die voortdurend nieuwe kleine hulpmiddelen schreven, was het een eindeloze val.

Een agent schreef een Python-script voor één taak. Daarna een kleine app voor de volgende. Elk programma was technisch nieuw. Dus moest ieder programma opnieuw toestemming krijgen.

‘Mijn agenten schrijven voortdurend apps en programma’s,’ zei Ben. ‘Je moet ieder afzonderlijk programma toestemming geven. Het loopt volledig uit de hand.’

Hij wilde de beveiliging niet afschaffen. Hij wilde haar anders indelen.

‘Ik heb een categorie nodig waaraan ik toestemmingen kan geven. Prima, ik regel die toestemmingen wel. Maar laat me het één keer doen.’

In theorie bood macOS een spoor van controle. Het systeem registreerde wanneer een programma toegang vroeg. Maar om dat praktisch te benutten, zou Ben een bewakingsprogramma moeten bouwen dat dat logboek volgde, hem een bericht stuurde en hem vervolgens de kans gaf op afstand in te loggen, Schermdeling in te schakelen en op ‘ja’ te drukken.

Toen hij die procedure uitsprak, werd de absurditeit zichtbaar.

‘Zó veel waarschuwingen,’ zei hij. ‘Ik let op geen enkele meer. Het zijn er gewoon te veel.’

Een waarschuwing kan iemand wakker maken. Tien waarschuwingen maken hem ongevoelig. Honderd veranderen beveiliging in achtergrondgeluid.

‘Ze verliezen het bos uit het oog en blijven bomen toevoegen,’ zei zijn gesprekspartner.

Ben wilde daarom een hoofdschakelaar voor mensen die bewust meer vrijheid kozen. Niet een systeem dat iedere nieuwe app behandelde alsof zij uit vijandig gebied kwam, maar een mogelijkheid om te zeggen: ik begrijp de risico’s. Vertrouw mij.

‘Er zou een manier moeten zijn om te zeggen: “Vertrouw me. Ik wil dat elke app die ik uitvoer mijn bureaublad kan zien. Doe niet steeds alsof dat iets uitzonderlijks is.”’

Hij wilde, zoals hij het formuleerde, een gewone gebruiker kunnen zijn die met scherpe messen mocht spelen.

Het sterkste tegenargument tegen zijn eigen pleidooi kende hij echter al.

‘Als je mijn artikel zo gunstig mogelijk voor Apple wilt uitleggen,’ zei hij, ‘dan is het antwoord: ik had niet met scherpe messen moeten spelen. Mijn computer is gehackt. Uiteindelijk was dat mijn fout.’

Dat maakte zijn punt niet zwakker. Het maakte het preciezer. Ben vroeg Apple niet om roekeloosheid zonder gevolgen mogelijk te maken. Hij vroeg om zichtbaarheid. Wie bescherming nodig had, moest die zonder moeite kunnen krijgen. Wie meer vrijheid wilde, moest die bewust kunnen kiezen — niet verdwalen in een systeem waarvan zelfs kenners niet meer konden uitleggen welke instelling welke deur opende.

Hij kondigde geen dramatische breuk aan. Hij zou zijn MacBook niet verkopen. En hij zou ook niet, zoals DHA hem en zijn gesprekspartner voortdurend bleef berichten, gaan beleggen met geleend geld.

‘Ik ga niet op margin,’ zei hij droog.

Maar toen Mark Gurman berichtte dat Apple werkte aan een nieuwe, lichtere MacBook Pro met oledscherm, merkte Ben hoe ver zijn twijfel inmiddels reikte. Hij gebruikte een M2 MacBook Pro en had bewust gewacht op dit model. Onder normale omstandigheden had het nieuws hem enthousiast gemaakt.

Nu dacht hij: ik weet niet of ik mij nog langer aan dit ecosysteem wil vastleggen.

‘Ik had nooit gedacht dat ik dat zou zeggen,’ zei hij.

Niet vanwege die ene hack. Die fout bleef hij als de zijne erkennen.

Het ging om de manier waarop hij zijn computer wilde gebruiken: als een open, krachtige machine die hij kon beheren, automatiseren en uitbreiden. Steeds vaker kreeg hij het gevoel dat Apple liever zag dat hij dat niet deed.

Daarom kwam hij terug op een oude beslissing van het bedrijf. Ooit verkocht Apple Mac OS X Server, een aparte versie van het besturingssysteem voor machines die als server draaiden. Toen Apple stopte met de Xserve, zijn eigen serverhardware, was dat te begrijpen. Hardware die niets oplevert, hoeft een bedrijf niet uit sentiment te blijven maken.

Maar Apple hield aanvankelijk nog een deur open. Gebruikers konden de serverversie van Mac OS X installeren op een Mac mini of Mac Pro en hun eigen systeem beheren. Geen product voor grote datacentra, maar voor mensen die een computer wilden laten werken zonder dat er voortdurend iemand naast zat.

Later verdween ook die software. Apple beëindigde macOS Server op 21 april 2022, ongeveer een halfjaar voordat ChatGPT de verwachtingen rond computers opnieuw veranderde.

Achteraf vond Ben dat een slechte beslissing.

Dit was precies het systeem dat hij nu nodig had gehad voor zijn Mac mini’s in Taiwan en elders: een versie van macOS voor computers zonder scherm en muis, zonder de aanname dat iedere machine een persoonlijke laptop was. Noem het geen server, desnoods. Noem het macOS voor onbemande machines.

‘Slechte timing,’ zei Ben.

De open poorten waren gesloten. De KVM-apparaten waren besteld. Het onmiddellijke gevaar was bezworen.

Maar de grotere vraag bleef staan. Hoeveel vrijheid kan een computerbedrijf zijn gebruikers geven zonder hen onbeschermd achter te laten? En hoeveel bescherming verdraagt een gebruiker voordat zijn computer niet langer voelt als een instrument in zijn handen, maar als een apparaat dat hem beleefd, zorgvuldig en volkomen ondoorgrondelijk op afstand houdt?