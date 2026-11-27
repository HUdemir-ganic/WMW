[← Terug naar de inhoudsopgave](../README.md)

# 6. User stories

## 6.1 Werkwijze

Elke user story schrijven wij in dezelfde vorm:

> **Als** {actor} **wil ik** {functionaliteit} **zodat** {doel}.

| Onderdeel | Hoe wij het doen |
|---|---|
| **Prioriteit** | MoSCoW: Must have (moet erin, anders werkt de app niet), Should have (belangrijk, maar het kan even zonder), Could have (als er tijd over is), Won't have (niet in deze versie) |
| **Inschatting** | T-shirtmaat: S, M, L of XL. Het gaat om complexiteit, niet om tijd. S is één scherm zonder koppeling. M is een paar schermen of één koppeling. L is meerdere koppelingen of veel logica. XL is te groot en splitsen wij op. |
| **Acceptatiecriteria** | Per user story: waaraan moet het resultaat voldoen voordat de product owner akkoord geeft? |

De user stories hebben wij gegroepeerd per onderdeel van de app (epic). De inschatting in dit document is een eerste versie. Bij de refinement voor elke sprint schat het ontwikkelteam de stories opnieuw samen in met planning poker. Iedereen legt tegelijk een kaart met een maat neer. Zijn de maten verschillend, dan leggen de hoogste en de laagste uit waarom, en schatten wij opnieuw.

## 6.2 Product backlog

De user stories staan op volgorde van prioriteit. De stories die in het MVP zitten, zijn vetgedrukt.

| Nr. | Epic | User story | Prioriteit | Inschatting |
|---|---|---|---|---|
| **1** | Account en privacy | Als klant wil ik inloggen met tweefactorauthenticatie, zodat alleen ik bij mijn gegevens kan. | Must | M |
| **2** | Account en privacy | Als klant wil ik per soort gegevens kiezen of ik toestemming geef, zodat ik zelf bepaal wat Watch My Watch met mijn gezondheidsgegevens doet. | Must | M |
| **3** | Apparaten | Als klant wil ik mijn wearable registreren door de QR-code op de verpakking te scannen, zodat ik geen serienummer hoef over te typen. | Must | M |
| **4** | Apparaten | Als klant wil ik op een dashboard al mijn apparaten zien met garantie, batterij en softwareversie, zodat ik weet hoe mijn apparaat ervoor staat. | Must | M |
| **5** | Garantie en reparatie | Als klant wil ik een probleem melden met foto's of een video, zodat de klantenservice meteen ziet wat er mis is. | Must | M |
| **6** | Garantie en reparatie | Als klantenservicemedewerker wil ik dat een melding uit de app als ticket in Odoo binnenkomt met de klant, het apparaat en de garantie, zodat ik niet opnieuw naar gegevens hoef te vragen. | Must | L |
| **7** | Garantie en reparatie | Als klant wil ik de status van mijn melding of reparatie volgen, zodat ik niet hoef te bellen om te vragen hoe ver het is. | Must | M |
| **8** | Hulp | Als klant wil ik dag en nacht vragen stellen aan een chatbot, zodat ik niet hoef te wachten tot de klantenservice open is. | Must | L |
| **9** | AI-coach | Als klant wil ik een weekplan van de AI-coach op basis van mijn doel en mijn gegevens, zodat ik gericht aan mijn doel kan werken. | Must | L |
| **10** | Toegankelijkheid | Als slechtziende klant wil ik de tekst groter maken en de app met een schermlezer gebruiken, zodat ik de app zelf kan gebruiken. | Must | M |
| 11 | Hulp | Als klant wil ik vanuit de chatbot een live chat met een medewerker starten, zodat ik geholpen word als de chatbot het antwoord niet weet. | Should | M |
| 12 | Hulp | Als klant wil ik zoeken in de handleidingen van mijn eigen apparaat, zodat ik zelf snel een antwoord vind. | Should | M |
| 13 | AI-coach | Als klant wil ik dat de AI-coach zijn advies aanpast aan mijn slaap en herstel, zodat ik niet te zwaar train. | Should | L |
| 14 | Koppelingen | Als klant wil ik mijn gegevens koppelen met Apple Gezondheid, Google Health Connect of Strava, zodat al mijn sportgegevens op één plek staan. | Should | L |
| 15 | Apparaten | Als klant wil ik een pushbericht krijgen als er een software-update voor mijn apparaat is, zodat mijn wearable veilig blijft en goed werkt. | Should | S |
| 16 | Bestellen | Als klant wil ik accessoires en onderdelen voor mijn eigen apparaat bestellen in de app, zodat ik zeker weet dat ze passen. | Should | L |
| 17 | Instellingen | Als klant wil ik per onderwerp kiezen welke meldingen ik krijg en niet-storen-tijden instellen, zodat ik 's nachts geen berichten krijg. | Should | S |
| 18 | Zakelijk | Als zakelijke beheerder wil ik alle apparaten van onze medewerkers in één overzicht zien, zodat ik weet welke apparaten aan vervanging toe zijn. | Should | L |
| 19 | Rapportage | Als medewerker van productie wil ik in Power BI zien welke problemen het vaakst gemeld worden per product, zodat wij onze producten kunnen verbeteren. | Should | M |
| 20 | Garantie en reparatie | Als klant wil ik dat de app eerst een controle op mijn apparaat doet, zodat een bekend probleem meteen wordt opgelost. | Could | L |
| 21 | Aanbevelingen | Als klant wil ik zelf kiezen over welke onderwerpen ik aanbevelingen krijg, zodat ik alleen aanbiedingen zie die bij mij passen. | Could | S |
| 22 | Community | Als klant wil ik meedoen aan maandelijkse uitdagingen en badges verdienen, zodat ik gemotiveerd blijf. | Could | M |
| 23 | Community | Als klant wil ik stemmen op ideeën voor nieuwe functies, zodat Watch My Watch maakt wat klanten willen. | Could | S |
| 24 | Winkels en servicepunten | Als klant wil ik de dichtstbijzijnde winkel of het dichtstbijzijnde servicepunt op een kaart zien, zodat ik mijn apparaat ergens kan brengen. | Could | M |
| 25 | Evenementen | Als klant wil ik me aanmelden voor een workshop of sportevenement, zodat ik mijn wearable beter leer gebruiken. | Won't | M |
| 26 | Talen | Als Franstalige of Duitstalige klant wil ik de app in mijn eigen taal gebruiken, zodat ik alles goed begrijp. | Won't | M |

Story 25 en 26 zitten niet in deze versie. Wij beginnen in Nederland, in het Nederlands en het Engels. Evenementen en meer talen voegen wij toe als de app in meer landen beschikbaar komt.

## 6.3 User stories met acceptatiecriteria

Hieronder staan de stories van het MVP met hun acceptatiecriteria, en daarna drie stories die direct na het MVP komen.

### User story 1 – Inloggen met tweefactorauthenticatie

> **Als** klant **wil ik** inloggen met tweefactorauthenticatie, **zodat** alleen ik bij mijn gegevens kan.

| | |
|---|---|
| **Epic** | Account en privacy |
| **Prioriteit** | Must |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] De klant kan een account maken met zijn e-mailadres. Bestaat het e-mailadres al als klant in Odoo, dan wordt het account aan die klant gekoppeld.
- [ ] Bij het eerste inloggen stelt de klant een tweede stap in: een code via een authenticator-app of sms.
- [ ] Na vijf foute pogingen wordt het account 15 minuten geblokkeerd.
- [ ] De klant kan inloggen met vingerafdruk of gezichtsherkenning als zijn telefoon dat ondersteunt.

---

### User story 2 – Toestemming per soort gegevens

> **Als** klant **wil ik** per soort gegevens kiezen of ik toestemming geef, **zodat** ik zelf bepaal wat Watch My Watch met mijn gezondheidsgegevens doet.

| | |
|---|---|
| **Epic** | Account en privacy |
| **Prioriteit** | Must |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] Bij het eerste gebruik ziet de klant per soort gegevens (activiteit, hartslag, slaap, locatie) een aparte schakelaar. Alle schakelaars staan standaard uit.
- [ ] Per schakelaar staat in één zin waarvoor wij de gegevens gebruiken.
- [ ] De klant kan zijn keuze altijd aanpassen in de instellingen. Trekt hij zijn toestemming in, dan gebruikt de app die gegevens vanaf dat moment niet meer.
- [ ] De klant kan al zijn gegevens downloaden en een verzoek doen om ze te laten verwijderen.

---

### User story 3 – Apparaat registreren met een QR-code

> **Als** klant **wil ik** mijn wearable registreren door de QR-code op de verpakking te scannen, **zodat** ik geen serienummer hoef over te typen.

| | |
|---|---|
| **Epic** | Apparaten |
| **Prioriteit** | Must |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] Na het scannen van de QR-code toont de app het model en het serienummer, en vraagt de klant om te bevestigen.
- [ ] Werkt de camera niet, dan kan de klant het serienummer ook met de hand invoeren.
- [ ] De app haalt de aankoopdatum en de garantietermijn uit Odoo. Staat de aankoop niet in Odoo, bijvoorbeeld bij een aankoop bij een webshop, dan kan de klant een foto van de aankoopbon toevoegen.
- [ ] Een apparaat dat al op naam van een andere klant staat, kan niet nog een keer geregistreerd worden. De app verwijst de klant dan naar de klantenservice.

---

### User story 4 – Dashboard met mijn apparaten

> **Als** klant **wil ik** op een dashboard al mijn apparaten zien met garantie, batterij en softwareversie, **zodat** ik weet hoe mijn apparaat ervoor staat.

| | |
|---|---|
| **Epic** | Apparaten |
| **Prioriteit** | Must |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] Per apparaat ziet de klant de naam, de aankoopdatum, de einddatum van de garantie, de batterijstatus en de softwareversie.
- [ ] De batterijstatus en de softwareversie worden bijgewerkt zodra de wearable via Bluetooth met de telefoon verbonden is.
- [ ] Verloopt de garantie binnen 30 dagen, dan staat dat met een duidelijke markering bij het apparaat.
- [ ] Vanaf het dashboard kan de klant met één tik een probleem melden voor dat apparaat.

---

### User story 5 – Probleem melden met foto's

> **Als** klant **wil ik** een probleem melden met foto's of een video, **zodat** de klantenservice meteen ziet wat er mis is.

| | |
|---|---|
| **Epic** | Garantie en reparatie |
| **Prioriteit** | Must |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] De klant kiest het apparaat en een soort probleem uit een lijst (bijvoorbeeld batterij, scherm, verbinding, sensor of iets anders). De lijst sluit aan op de redencodes in Odoo.
- [ ] De klant kan een omschrijving en maximaal vijf foto's of één video van maximaal 30 seconden toevoegen.
- [ ] Na het versturen ziet de klant een bevestiging met een meldingsnummer en hoe lang het naar verwachting duurt.
- [ ] Zonder internet bewaart de app de melding en verstuurt hij die zodra er weer verbinding is.

---

### User story 6 – Melding komt als ticket in Odoo

> **Als** klantenservicemedewerker **wil ik** dat een melding uit de app als ticket in Odoo binnenkomt met de klant, het apparaat en de garantie, **zodat** ik niet opnieuw naar gegevens hoef te vragen.

| | |
|---|---|
| **Epic** | Garantie en reparatie |
| **Prioriteit** | Must |
| **Inschatting** | L |

**Acceptatiecriteria**

- [ ] Binnen één minuut na het versturen staat de melding als ticket in Odoo Helpdesk.
- [ ] Het ticket is gekoppeld aan de klant en het apparaat, en toont of er garantie is.
- [ ] De foto's of de video staan als bijlage bij het ticket.
- [ ] Voor het ticket geldt de servicetermijn van 24 uur die al in Helpdesk is ingesteld.

---

### User story 7 – Status van mijn melding volgen

> **Als** klant **wil ik** de status van mijn melding of reparatie volgen, **zodat** ik niet hoef te bellen om te vragen hoe ver het is.

| | |
|---|---|
| **Epic** | Garantie en reparatie |
| **Prioriteit** | Must |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] De klant ziet een tijdlijn met de stappen: ontvangen, in behandeling, in reparatie, verzonden en afgerond. De huidige stap is gemarkeerd.
- [ ] Verandert de status in Odoo, dan krijgt de klant binnen vijf minuten een pushbericht.
- [ ] Is het apparaat verzonden, dan ziet de klant de track-and-trace-code van de vervoerder.
- [ ] Na het afronden vraagt de app de klant om een cijfer van 1 tot 10. Dat cijfer komt bij het ticket in Odoo.

---

### User story 8 – Chatbot die dag en nacht helpt

> **Als** klant **wil ik** dag en nacht vragen stellen aan een chatbot, **zodat** ik niet hoef te wachten tot de klantenservice open is.

| | |
|---|---|
| **Epic** | Hulp |
| **Prioriteit** | Must |
| **Inschatting** | L |

**Acceptatiecriteria**

- [ ] Bovenaan het gesprek staat duidelijk dat de klant met een chatbot praat.
- [ ] De chatbot gebruikt alleen onze handleidingen, veelgestelde vragen en de gegevens van de klant zelf. Hij noemt het apparaat van de klant bij naam.
- [ ] Weet de chatbot het antwoord niet, of vraagt de klant naar een medewerker, dan biedt hij een live chat (tijdens openingstijden) of een melding aan.
- [ ] De chatbot geeft geen medisch advies. Bij vragen over klachten of afwijkende waarden verwijst hij naar een huisarts.

---

### User story 9 – Weekplan van de AI-coach

> **Als** klant **wil ik** een weekplan van de AI-coach op basis van mijn doel en mijn gegevens, **zodat** ik gericht aan mijn doel kan werken.

| | |
|---|---|
| **Epic** | AI-coach |
| **Prioriteit** | Must |
| **Inschatting** | L |

**Acceptatiecriteria**

- [ ] De klant kiest een doel uit een lijst (bijvoorbeeld meer bewegen, beter slapen of een afstand lopen) en geeft aan hoeveel dagen per week hij kan trainen.
- [ ] De coach maakt een weekplan met per dag een activiteit, en toont elke ochtend een kort advies in gewone taal.
- [ ] Bij elk advies kan de klant op "waarom?" tikken. Dan ziet hij op welke gegevens het advies gebaseerd is.
- [ ] De coach gebruikt alleen gegevens waarvoor de klant toestemming gaf (zie story 2). Zonder toestemming voor hartslag en slaap maakt hij een plan op basis van het doel alleen.

---

### User story 10 – Toegankelijke app

> **Als** slechtziende klant **wil ik** de tekst groter maken en de app met een schermlezer gebruiken, **zodat** ik de app zelf kan gebruiken.

| | |
|---|---|
| **Epic** | Toegankelijkheid |
| **Prioriteit** | Must |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] De app volgt de lettergrootte die de klant op zijn telefoon heeft ingesteld, zonder dat tekst wegvalt.
- [ ] Alle knoppen en afbeeldingen hebben een omschrijving voor VoiceOver (iPhone) en TalkBack (Android).
- [ ] Het contrast tussen tekst en achtergrond voldoet aan WCAG 2.1 niveau AA.
- [ ] Alle video's in de handleidingen hebben ondertiteling.

---

### User story 11 – Live chat met een medewerker

> **Als** klant **wil ik** vanuit de chatbot een live chat met een medewerker starten, **zodat** ik geholpen word als de chatbot het antwoord niet weet.

| | |
|---|---|
| **Epic** | Hulp |
| **Prioriteit** | Should |
| **Inschatting** | M |

**Acceptatiecriteria**

- [ ] De medewerker ziet het hele gesprek met de chatbot en de gegevens van de klant. De klant hoeft niets te herhalen.
- [ ] Buiten openingstijden biedt de app een terugbelverzoek of een melding aan.
- [ ] De klant ziet hoe lang het ongeveer duurt voordat een medewerker reageert.

---

### User story 13 – Advies aangepast aan slaap en herstel

> **Als** klant **wil ik** dat de AI-coach zijn advies aanpast aan mijn slaap en herstel, **zodat** ik niet te zwaar train.

| | |
|---|---|
| **Epic** | AI-coach |
| **Prioriteit** | Should |
| **Inschatting** | L |

**Acceptatiecriteria**

- [ ] Heeft de klant duidelijk korter of slechter geslapen dan normaal, dan stelt de coach een lichtere activiteit voor die dag voor.
- [ ] De klant ziet in één zin waarom het plan is aangepast.
- [ ] De klant kan het oude plan toch kiezen.

---

### User story 16 – Accessoires bestellen voor mijn apparaat

> **Als** klant **wil ik** accessoires en onderdelen voor mijn eigen apparaat bestellen in de app, **zodat** ik zeker weet dat ze passen.

| | |
|---|---|
| **Epic** | Bestellen |
| **Prioriteit** | Should |
| **Inschatting** | L |

**Acceptatiecriteria**

- [ ] De winkel toont alleen producten die passen bij de geregistreerde apparaten van de klant.
- [ ] De voorraad komt uit Odoo. Is een product niet op voorraad, dan staat de verwachte levertijd erbij.
- [ ] Een bestelling wordt een verkooporder in Odoo, met de gegevens van de klant die al bekend zijn.

## 6.4 Minimum Viable Product (MVP)

Het MVP is de eerste werkende versie waarmee wij zo veel mogelijk leren van gebruikers, tegen zo weinig mogelijk kosten. Wij kiezen de stories die nodig zijn om twee vragen te beantwoorden: gebruiken klanten de app om hun problemen te melden en te volgen? En openen ze de app elke dag voor de AI-coach?

| Nr. | User story | Waarom in het MVP |
|---|---|---|
| 1 | Inloggen met tweefactorauthenticatie | Zonder veilig account kan niets anders. Wij werken met gezondheidsgegevens. |
| 2 | Toestemming per soort gegevens | Verplicht volgens de AVG, voordat wij gezondheidsgegevens gebruiken. |
| 3 | Apparaat registreren met een QR-code | De app moet weten welk apparaat de klant heeft. Alle andere functies bouwen hierop. |
| 4 | Dashboard met mijn apparaten | Het startscherm van de app. De klant ziet meteen wat de app hem oplevert. |
| 5 | Probleem melden met foto's | Lost het grootste knelpunt uit hoofdstuk 4 op. |
| 6 | Melding komt als ticket in Odoo | Zonder deze koppeling moet klantenservice alles nog met de hand overnemen. |
| 7 | Status van mijn melding volgen | Scheelt telefoontjes. Dit merkt de klant direct. |
| 8 | Chatbot die dag en nacht helpt | Nodig voor het doel dat klanten 30 procent van hun vragen zelf oplossen. |
| 9 | Weekplan van de AI-coach | Onze unieke functionaliteit en de reden om de app elke dag te openen. Wij willen zo vroeg mogelijk weten of klanten hem gebruiken. |
| 10 | Toegankelijke app | Wettelijk verplicht. Achteraf toevoegen kost veel meer dan het meteen goed doen. |
