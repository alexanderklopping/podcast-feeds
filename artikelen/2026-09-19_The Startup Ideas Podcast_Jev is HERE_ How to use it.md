<!--
podcast_name: The Startup Ideas Podcast
guid: flightcast:01M2TVPD7JF23WA30637M194AD
-->

# De verkeersagent

*Jev kwam niet naar voren als de volgende, gladdere chatbot. Het was iets anders: een model dat niet praat, niet aarzelt en geen keurige alinea’s formuleert, maar in een oogwenk bepaalt wat informatie waard is en waar die heen moet. Voor iedereen die dagelijks leeft tussen e-mails, contactformulieren, klantvragen en verzoeken, schuilt daarin misschien wel een grotere belofte dan in een beter gesprek met een machine.*

“Like, comment, subscribe.”

Greg Isenberg sprak de woorden met de opgewekte ernst van iemand die wist dat het ritueel eraan voorafging. Geef het algoritme een duwtje, hield hij zijn kijkers voor. Zorg dat het je later opnieuw zulke ideeën voorschotelt — ideeën die je op een treinreis of onder de douche ineens aan het bouwen zetten.

“Happy Jev Day,” besloot hij.

Het klonk als een grap, maar ook als een kleine inauguratie. Jev was op dat moment nog niet vrij beschikbaar. Alleen wie een uitnodiging had, kon ermee werken. Toch beloofde Isenberg dat de kijker aan het eind van de aflevering een route zou krijgen om diezelfde dag toegang te regelen. Eerst moest duidelijk worden waarom iemand daar moeite voor zou doen.

Jev was ontwikkeld door Diogo Almeida, een onderzoeker wiens werk had bijgedragen aan de technische basis onder ChatGPT. Maar waar ChatGPT een machine was geworden die schrijft, samenvat, redeneert en soms met grote overtuiging onzin verkoopt, beloofde Jev iets veel beperkters — en misschien juist daarom iets bruikbaarders.

Ryan Vogel, lid van het oprichtende team van OpenCode, zat tegenover Isenberg met een opdracht die eenvoudig klonk en lastig was uit te voeren: leg uit wat Jev is, laat toepassingen zien die absurd goed voelen, en maak ondernemers duidelijk dat er nieuwe bedrijven mogelijk worden zodra je dit begrijpt.

Vogel wilde nog één belofte toevoegen.

“Niet alleen leg ik het uit,” zei hij. “Ik maak het ook vermakelijk, zodat mensen er echt enthousiast van worden.”

Hij opende zijn postvak.

Op het scherm stond een tabel met 1.700 e-mails. Onderwerpregels, afzenders, omschrijvingen, volledige berichtteksten: de rommelige geschiedenis van een digitaal leven. Betalingsmeldingen. Nieuwsbrieven. Verzoeken. Vermoedelijke fraude. Berichten die ooit dringend leken en daarna onder een laag nieuwe berichten waren verdwenen.

“Als je me een beetje kent,” zei Vogel, “weet je dat ik van e-mail houd. Volgens mij is dat probleem nog steeds niet opgelost.”

E-mail was ooit de belofte van eenvoud geweest: een elektronische brief, snel bezorgd, goedkoop verstuurd. Maar elk groeiend bedrijf ontdekte dezelfde keerzijde. Het postvak werd een voordeur zonder portier. Iedereen kon aanbellen: klanten, verkopers, fraudeurs, oude bekenden, automatische systemen en nieuwsbrieven waarvoor je je twee jaar eerder, in een moment van optimisme, had aangemeld.

“Hoeveel ongewenste e-mails krijg jij per dag?” vroeg Vogel.

“Te veel,” zei Isenberg.

“Te veel,” herhaalde Vogel. “Je kunt niet iedereen antwoorden.”

Daar lag het probleem dat hij wilde demonstreren. Bestaande spamfilters waren redelijk, zei hij, maar niet goed genoeg. Sommige bedrijven lieten een groot taalmodel — een model als het fictief genoemde GPT-5.6 Luna — iedere e-mail lezen en beoordelen. Maar dat kost tijd. Een taalmodel verwerkt tekst, bouwt een antwoord op en levert dat antwoord vaak woord voor woord af. Wie duizenden berichten erdoorheen haalt, koopt niet alleen begrip, maar ook wachttijd en een rekening.

Jev zou op drie fronten anders zijn: kwaliteit, snelheid en prijs.

“Dit,” zei Vogel, terwijl hij naar de tabel wees, “is Jev.”

Hij drukte nog niet op de knop. Eerst pakte hij een iPhone als voorbeeld. Stel dat de telefoon de invoer was. Vervolgens moest je bepalen wat Jev terug mocht geven. De kleur, bijvoorbeeld: blauw, oranje, rood, groen of geel.

Jev keek niet naar de telefoon om er een beschrijving van te schrijven. Het systeem zou niet antwoorden: *Dit lijkt een felgekleurde smartphone met een oranje behuizing.* Het kreeg een beperkt aantal mogelijke uitkomsten voorgelegd en verdeelde daar kansen over.

“Ik ben voor tachtig procent zeker dat hij oranje is,” zou het model zeggen. “Maar hij kan voor tien procent rood zijn of voor tien procent blauw.”

Tachtig procent oranje. Tien procent rood. Tien procent blauw. Samen precies honderd procent: de waarschijnlijkheden van de beschikbare keuzes.

Het model zei dus niet met de schijnzekerheid van een stempel: *Deze telefoon is oranje.* Het zei: dit is mijn beste inschatting, en dit is hoeveel twijfel daarin zit.

Vogel noemde Jev “in de kern een classificator”: een beslismodel dat gegevens in vooraf bepaalde vakken plaatst en daar een waarschijnlijkheid aan toevoegt. Geen absoluut oordeel, maar een berekende inschatting. Dat verschil leek klein, totdat je er een bedrijf op bouwde.

Een gewoon filter zegt: dit is spam. Jev zegt: de kans dat dit spam is, bedraagt negentig procent. Een verkoper kan op basis daarvan besluiten een potentiële klant meteen te bellen, of hem eerst in een automatische opvolging te zetten. Een klantenserviceteam kan een verzoek met 95 procent zekerheid naar het juiste productteam sturen en een twijfelgeval aan een mens voorleggen. Het model neemt de verantwoordelijkheid niet over. Het maakt de onzekerheid zichtbaar.

Vogel keek terug naar zijn scherm. Iedere rij in de tabel was een volledig e-mailobject: onderwerp, afzender, omschrijving, berichttekst en alle overige gegevens die aan een e-mail vastzaten. Die hele bundel ging het model in. Geen voorbewerking. Geen bijzondere behandeling.

Aan de andere kant lag het schema klaar.

Een schema, legde Vogel uit, is “gewoon een deftig woord voor hoe een database is georganiseerd”. Simpeler gezegd: het is de vaste indeling van het antwoord dat je wilt terugkrijgen. Zoals een formulier al vakken heeft voor naam, adres en postcode, zo bepaalt een schema welke uitkomsten Jev mag geven.

De eerste vraag was: bij welke categorie hoort dit bericht? Winkelen, werk, marketing, financiën, beveiliging — of een ander vooraf gekozen label. Voor een bedrijf betekende dat iets eenvoudigs maar belangrijks: een bericht hoefde niet langer in een algemene wachtrij te blijven liggen totdat iemand tijd had om het te lezen.

Dan kwam de prioriteit. Laag, gemiddeld, hoog, belangrijk of urgent. Een gemiste creditcardbetaling hoorde niet tussen een nieuwsbrief en een reclameactie terecht te komen. Die moest onmiddellijk bovenaan verschijnen.

Daarna volgde de spamscore. Niet een bot ja-of-nee, maar een kans tussen nul en één. Sommige berichten waren onmiskenbare rommel. Andere zaten in het grijze gebied, waar de meeste frustratie van een postvak zich ophoopt.

Vogel wees naar een e-mail van Kickstarter die hem opnieuw iets probeerde te verkopen.

“Ik heb me twee jaar geleden voor dat Kickstarter-ding ingeschreven,” zei hij, “en ik ben er nog steeds niet in geslaagd me van die lijst af te melden.”

Dat bericht droeg alle kenmerken van spam, maar het was niet hetzelfde als een frauduleuze e-mail. Hij had zich ooit zelf aangemeld. Precies voor die nuance was de score bedoeld.

Een bericht van Mercury vertelde een ander verhaal. Exxon Enterprise had 22 dollar ontvangen via Stripe. Niet spannend. Niet persoonlijk. Maar ook geen spam. Gewoon een zakelijke melding: er was iets gebeurd, en het systeem meldde het.

Het vierde veld moest de menselijke aandacht beschermen: het percentage dat aangaf in hoeverre een bericht een antwoord verdiende. Vogel klikte niet door op het echte bericht — daarvoor was de inhoud te persoonlijk — maar las de kern voor: “Mogelijke accountschending: 90 procent.” Iemand vermoedde dat er met diens account was geknoeid. Jev had het signaal herkend en er een hoge kans aan gekoppeld dat een mens moest reageren.

Concreet kwam er per bericht dus een pakket terug: categorie, prioriteit, spamscore en de kans dat een antwoord nodig was.

Toen maakte Vogel zijn demonstratie bewust somber.

Er waren 1.700 e-mails. Wie gewend was aan de logica van grote taalmodellen, wist hoe dit verhaal verderging. Het zou uren kosten. Misschien tien uur. Daarna moest iemand nog door de resultaten heen om de waardevolle informatie eruit te halen. En de rekening zou navenant zijn.

Hij keek naar het scherm alsof hij de wachttijd zelf ook verwachtte.

“Dit is het verdrietige deel,” zei hij. “Het kost zo veel tijd.”

Een seconde later veranderde zijn gezicht.

“O,” zei hij. “Hij is al klaar.”

Isenberg leunde naar voren.

“Wat kostte het?”

Vogel keek naar de uitvoer. “It cost 18 cents. Literally.”

Achttien cent. Letterlijk.

Niet achttien dollar. Niet achttien cent per bericht. Achttien cent voor de hele stapel: 1.700 e-mails, vier miljoen invoertokens, vijfhonderd uitvoertokens. Alles gecategoriseerd, gerangschikt en gescoord.

Het was een getal dat de kamer kort stil maakte. De verwachte tien uur waren verdwenen. De zware rekening was verdwenen. Er was alleen een tabel, een uitvoer en een bedrag dat lager lag dan de prijs van een postzegel.

Isenberg zocht naar een mentale kapstok.

“Jev is eigenlijk een AI-beslisser.”

Vogel knikte. “Ja.”

Maar vervolgens trok hij de definitie scherper.

“Dat is voor negentig procent juist,” zei hij. “Het maakt een waarschijnlijkheid van een beslissing.”

Stel dat een model teruggeeft dat een klant voor 83 procent waarschijnlijk koopt en voor 17 procent waarschijnlijk niet. De sterkste uitkomst — waarschijnlijk kopen — kun je gebruiken. Maar de machine beweert niet dat zij de toekomst kent. Ze laat zien hoeveel vertrouwen zij in die keuze heeft.

De gebruiker bepaalt vervolgens de grens. Boven de negentig procent gaat een potentiële klant rechtstreeks naar een verkoper. Rond de zestig procent volgt een automatische e-mail. Onder de tien procent gebeurt er niets.

Isenberg probeerde het nog één keer te vangen in de vertrouwde taal van ChatGPT en Claude. Je zou Jev toch kunnen vragen een e-mail te lezen en vervolgens te kiezen tussen antwoorden, escaleren, doorsturen of negeren?

“Een beetje,” zei Vogel. “Maar de grote taalmodellen hebben ons denken bedorven.”

Hij bedoelde dat letterlijk.

“Je vraagt Jev eigenlijk niets,” zei hij. Daarna formuleerde hij het in een zin die de hele demonstratie op zijn plaats zette: “Jev isn't a text model. If you look at the specification, it doesn't generate any text at all.”

Jev is geen tekstmodel. Het genereert helemaal geen tekst.

Het was een correctie die hij niet terloops wilde laten passeren. Waar een chatbot woorden produceert, werkt Jev met een invoer en een vooraf gedefinieerde vorm voor de uitvoer. De tekst die in de demonstratie zichtbaar was, kwam niet voort uit een innerlijke monoloog van het model. Die velden waren vooraf bepaald.

Dat vereiste een tekening.

Vogel opende een digitaal whiteboard. Links tekende hij een e-mail. In het midden kwam een cirkel.

“Jev lijkt me een cirkeltype,” zei hij.

“Een kleine cirkel,” zei Isenberg onmiddellijk. “Omdat hij snel is.”

De e-mail ging de kleine cirkel in. Boven de cirkel stond het schema: de vaste vorm van de gewenste uitkomst. Niet de vraag: *Wat moet ik met deze e-mail doen?* Geen uitnodiging tot een betoog. Alleen invoer, structuur, resultaat.

Een veld kon bijvoorbeeld *is_spam* heten. Technisch heet zo’n veld vaak een boolean: een ja-of-neekeuze, waar of onwaar. Jev gaf die keuze niet terug als een hard stempel, maar als een schaal van nul tot één. Bij 0,31 achtte het model het bericht voor 31 procent spam. Bij 0,90 voor negentig procent.

Daarnaast kon er een categorieveld staan: marketing, financiën of spam. Jev verzon die labels niet. De bouwer had ze vooraf vastgelegd. Het model keek naar het bericht, keek naar de toegestane uitkomsten en stuurde de best passende combinatie terug.

Dat maakte de uitvoer onmiddellijk bruikbaar in software. Ontwikkelaars noemen dat *type-safe*: het model levert gegevens aan in een vaste vorm waar een programma direct mee kan werken. Geen zin waarin toevallig een getal staat dat software daarna nog moet uitpluizen, maar een echt getal op de plek waar een getal hoort.

Categorie: spam.  
Kans op spam: 90 procent.

“Het schiet het gewoon terug,” zei Isenberg.

“Het geeft je een beslissing,” antwoordde Vogel.

Daarmee stond Jev buiten het dominante beeld van kunstmatige intelligentie. De bekendste systemen van de voorgaande jaren waren taalmodellen geweest: machines die steeds voorspellen welk volgend woord waarschijnlijk het best past. Zo ontstaan gesprekken, essays, samenvattingen en stukjes code. Jev deed dat niet. Het wilde geen aangename gesprekspartner zijn. Het was een beslismodel, bedoeld om informatie langs een beperkte set mogelijkheden te leggen.

Vogel had natuurlijk geprobeerd die grens te tarten.

Als tekst uit een keten van keuzes bestond — eerst de H, dan de E, dan de L, nog een L en ten slotte de O — kon Jev dan ook schrijven? Hij voerde alle letters van A tot Z als mogelijke waarden in en liet het systeem telkens bepalen welke letter het best op de vorige volgde.

Hij stelde de vraag: wat is groter, een kat of een olifant?

Het antwoord verscheen letter voor letter. Niet met de soepelheid van een gespecialiseerd taalmodel, niet met de overtuiging van ChatGPT. Maar het werkte genoeg om de gedachte zichtbaar te maken. Tekst kon ook worden opgevat als een reeks beslissingen. Alleen was dat niet de taak waarvoor Jev gemaakt was.

De relevante vraag was dus niet of Jev ChatGPT kon vervangen. De vraag was waar organisaties iedere dag duizenden kleine beslissingen namen die nu te langzaam, te duur of te slordig gebeurden.

Vogel dacht dat de drempel laag genoeg was om mensen anders te laten bouwen. Andere AI-systemen konden honderden of duizenden dollars per maand aan rekenkosten vragen voordat ze werkelijk bruikbaar werden. Het team van OpenCode kreeg vijf dollar aan starttegoed voor Jev. Twee dagen lang draaiden ze demonstraties en experimenten zonder de limiet te raken — en ze gebruikten het intensief.

“Je kunt er waarschijnlijk tien dollar op zetten,” zei Vogel, “en daar drie maanden mee vooruit.”

Zijn eerste voorbeeld kwam uit de directe omgeving. Zijn vriendin runde een grafisch ontwerpbureau. Via haar contactformulier kwamen aanvragen binnen: echte potentiële klanten, mensen met een vaag idee, verkopers die iets wilden aansmeren en gewone spam.

Jev kon als poortwachter fungeren. Een aanvraag met 98 procent kans op een goede klant moest snel bij haar terechtkomen. Iemand die schreef: *Misschien heb ik grafisch ontwerp nodig, maar ik weet het nog niet zeker*, was niet waardeloos, maar vroeg meer tijd en meer verkoopwerk. Het model hoefde niet te beslissen wie een klant verdiende. Het kon wel laten zien waar de kostbare aandacht het eerst naartoe moest.

Dat gold ook voor oude postvakken. Welke potentiële klant was ooit gemist? Welke voormalige klant zou opnieuw interessant kunnen zijn? Voor ondersteuningsverzoeken: welk productteam moest dit probleem zien? Voor ieder formulier dat binnenkwam zonder dat iemand wist wie het moest oppakken.

“Overal waar je naar data kijkt en denkt: ik moet hier een beslissing over nemen,” zei Vogel, “moet je waarschijnlijk overwegen Jev op die laag toe te voegen.”

Hij voegde er meteen een voorbehoud aan toe. Niet iedere interactie moest automatisch verlopen. Jev moest vooral een zwaarwegend adviesmiddel zijn: snel, goedkoop en consequent, maar niet almachtig.

Daar lag ook zijn natuurlijke terrein.

“Jev is echt goed in interacties die in een fractie van een seconde moeten gebeuren,” zei Vogel.

Ongeveer tweehonderd milliseconden per aanvraag, ongeacht de structuur van invoer of uitvoer. Dat was geen cosmetisch verschil. Een groot taalmodel kon voor sommige taken dertig seconden nodig hebben. Je moest wachten tot het antwoord klaar was, soms de tekst al tijdens het genereren laten binnenkomen en een mechanisme bouwen dat de voortgang volgde. Met Jev deed je één korte systeemaanroep. Dan kwam het antwoord terug.

Isenberg vond uiteindelijk de beste zin van de aflevering.

“Jev is basically an AI traffic cop.”

Een AI-verkeersagent.

Informatie kwam binnen. De verkeersagent keek ernaar en bepaalde waar die heen moest, hoe belangrijk die was en wat er daarna moest gebeuren. Een uitstekende potentiële klant naar een mens, onmiddellijk. Een twijfelgeval naar een automatisch systeem dat eventueel een taalmodel een conceptantwoord liet schrijven. Een bericht met een lage score: negeren.

“Klopt dat?” vroeg Isenberg.

“Dat klopt helemaal,” zei Vogel.

Alles waarvoor snel een beslissing nodig was — en misschien meteen feedback aan een gebruiker — kon op die manier worden ingericht.

Isenbergs gedachten gingen onmiddellijk naar start-ups. Niet naar een bedrijf dat één afdeling een beetje efficiënter maakte, maar naar ondernemingen die pas mogelijk werden wanneer een wachtrij van informatie vrijwel gratis en onmiddellijk kon worden beoordeeld.

“Hoe vind ik een bedrijf met een dure rij binnenkomende informatie,” vroeg hij, “en zet ik Jev vooraan in die rij?”

Een lokale marktplaats was een voor de hand liggend voorbeeld. Iemand vulde in: *Mijn oprit moet met een hogedrukreiniger worden schoongemaakt.* Achter die ene zin bevond zich een wirwar van kleine bedrijven met verschillende werkgebieden, prijzen, beschikbaarheid en specialismen.

Hier kon een formulier ineens meer worden dan een formulier.

Een platform kon Jev de aanvraag laten vergelijken met gegevens over al die bedrijven en vrijwel direct teruggeven welke partij waarschijnlijk het best paste. Niet als magische vervanging van een goede database of betrouwbare aanbieders, maar als het beslissende scharnierpunt tussen vraag en aanbod.

Hetzelfde gold voor de leugen die op zoveel websites stond: *Vraag direct een offerte aan.* Meestal volgde daarna de mededeling dat iemand “voor het einde van de dag” contact zou opnemen.

Een goed ingericht systeem kon werkelijk direct beoordelen of een aanvraag paste, welke informatie nog ontbrak, in welke prijsband die viel en welk bedrijf de juiste partij was.

Een echte directe offerte bespaarde niet alleen tijd. Ze vertelde de klant ook iets over het bedrijf: wij verspillen uw tijd niet, en de onze evenmin.

Niet iedere toepassing bleek echter verstandig.

Vogel had Jev gekoppeld aan een Bitcoin-signaal. Elke minuut kreeg het model dezelfde beslismatrix voorgelegd: kopen, vasthouden of verkopen. Het experiment had een verleidelijke eenvoud. Als Jev in milliseconden e-mails kon rangschikken, kon het misschien ook een marktstandpunt kiezen.

Maar toen kwamen de resultaten.

“Het lijkt niet goed te gaan,” zei Vogel.

Dat was de conclusie. Niet: een beetje wisselvallig. Niet: nog wat verfijnen. Het model leverde signalen, maar geen resultaat dat vertrouwen verdiende.

Daar zat een les in. Jev kon een keuze classificeren, maar een Bitcoinmarkt veranderde onder invloed van nieuws, liquiditeit, sentiment, macro-economie en gedrag dat zich niet netjes in een beperkt schema liet vangen. Dit was geen model dat je voor je aandelenportefeuille of je Bitcoin moest zetten. Het was bedoeld voor routering en andere beslissingen waarvoor je geen extreme modelintelligentie nodig had.

Vogel probeerde dezelfde proef met GPT-6 Astra, het nieuwste geavanceerde model van OpenAI. Dat deed het iets beter, vooral omdat het nieuwsinformatie kon meewegen. Maar, zei hij, het was geen eerlijke wedstrijd.

“Dat zijn appels en sinaasappels.”

Verschillende modellen, verschillende taken. Een classificator kon een handelsbeslissing helpen structureren, maar was niet automatisch het juiste gereedschap zodra er geld op het spel stond.

Daarna verschoof Vogel naar een probleem dat iedere videomaker kende. Een lange YouTube-video opnemen was één ding. Daarna moest iemand de sterke momenten terugvinden, knippen en omzetten in korte fragmenten voor andere platforms. Dat kostte uren, soms dagen. Het grootste deel van die tijd ging op aan zoeken.

In zijn demonstratie sleepte Vogel een videobestand naar een venster. Het systeem maakte een transcript op woordniveau en stuurde de volledige tekst naar Jev. Niet met de opdracht om een samenvatting te schrijven, maar met een vraag die het model wel begreep: welke passages zijn interessant? Waar begint een bruikbaar fragment? Welke stukken zijn vooral opvulling?

De uitvoer werd een reeks mogelijke clips: momenten waarop, volgens het model, de aandacht piekte.

Vogel had er naar eigen zeggen tien minuten aan gewerkt. Toch zag je het product al voor je. Met verfijning, een goede interface en aanvullende AI-agenten kon iemand een overtuigende videofragmentendienst bouwen. Jev zou dan niet de editor zijn, maar de onvermoeibare eerste kijker die zei: hier moet je zijn.

Er zouden volgens Vogel nog veel meer toepassingen opduiken zodra mensen een nacht over het model nadachten. De volgende ochtend, voorspelde hij, zouden de ideeën zich aandienen. *Dit zou ermee kunnen. Dat ook.*

Zijn laatste demonstratie maakte die snelheid zichtbaar op een manier die geen tabel kon evenaren. Jev bestuurde een browser en moest een vlucht vinden van Zürich naar Londen. Op het scherm selecteerde het systeem data, navigeerde door de opties en zocht tussen de vluchten.

Een traditionele zoekagent die een browser bedient, zou daar een minuut, twee minuten, misschien drie minuten voor nodig hebben gehad, zei Vogel.

Dan verscheen de tijd.

7,1 seconden.

Alles gebeurde in realtime.

“Dat is een groot verschil,” zei Isenberg.

“Een heel groot verschil,” zei Vogel.

Voor een mens leek dat verschil klein zolang het om één taak ging. Maar voor software die geacht werd namens mensen te handelen, veranderde het alles. Een agent die traag denkt, voelt als software die je in de gaten moet houden. Een agent die bijna onmiddellijk handelt, begint op infrastructuur te lijken.

Aan het einde kwam de toegangsvraag terug. Jev stond op dat moment nog op een wachtlijst; mogelijk zou het model tegen de publicatie van de aflevering algemeen beschikbaar zijn. Maar via Vercel Gateway konden ontwikkelaars er al direct mee werken. Jev was toegevoegd aan het AI-pakket van Vercel, waardoor testen niet hoefde te wachten op een uitnodiging.

Voor mensen zonder technische achtergrond had Vogel een pragmatischer advies. Geef je eigen AI-agent de link naar TypeSafe AI en vraag eenvoudig: hoe kan ik met Jev experimenteren? Beschrijf vervolgens je bedrijf. Welke dagelijkse werkstromen bevatten steeds dezelfde kleine beslissingen? Waar komt informatie binnen die nu eerst door een mens moet worden bekeken voordat die verder kan?

Isenberg beloofde de verwijzingen naar Vercel, TypeSafe AI en Vogel zelf in de beschrijving en aantekeningen bij de aflevering te zetten. Ook wees hij op Vogels YouTube-kanaal, dat volgens hem met ongeveer duizend abonnees “crimineel weinig gevolgd” werd.

Maar Isenberg wist al wat hij na het gesprek ging doen. Hij zou naar de Vercel-link gaan, met Jev spelen, dingen classificeren.

Vogel glimlachte, maar waarschuwde hem.

“Het is gevaarlijk verslavend.”

Hij bedoelde niet de verslaving van een chatbot die steeds menselijker klinkt. Die aantrekkingskracht kende iedereen inmiddels. Dit was een andere roes: het moment waarop een probleem dat altijd zwaar, duur en traag had gevoeld, plotseling bijna gratis bleek.

“Zodra je de snelheid en de prijs ziet,” zei Vogel, “denk je: ‘Holy cow.’”

Wie het alleen wilde uitproberen, hoefde nauwelijks geld mee te nemen.

“Het kost zoiets als een duizendste van een cent om het te testen.”

Daarmee keerde het gesprek terug naar waar het begonnen was: niet bij een grote theorie over kunstmatige intelligentie, maar bij een postvak. Bij een rij van 1.700 berichten. Bij tien uur verwachte wachttijd die oploste in seconden, en bij achttien cent.

Vanaf dat moment werd het moeilijk om nog naar een formulier, een ondersteuningswachtrij, een stapel potentiële klanten of een lange video te kijken zonder dezelfde gedachte.

Wat komt hier binnen?

Wat betekent het?

En waar moet het heen?