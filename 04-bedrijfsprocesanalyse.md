[← Terug naar de inhoudsopgave](../README.md)

# 4. Bedrijfsprocesanalyse

## 4.1 Het proces dat de app ondersteunt

De app raakt veel processen, maar wij kiezen voor het proces **melding tot oplossing**: van de vraag of het probleem van een klant tot de oplossing of reparatie. Dat doen wij om drie redenen:

1. **Dit proces verandert het meest door de app.** Nu belt of mailt de klant. Straks meldt hij zijn probleem in de app, met foto's, en volgt hij zelf de status.
2. **Hier merkt de klant het meest van ons.** Een klant met een kapotte wearable wil snel geholpen worden. Als dat goed gaat, blijft hij klant. Dat is de kern van customer intimacy.
3. **Het sluit aan op ons eerdere werk.** In onze BPM Lifecycle hebben wij dit proces al geanalyseerd en verbeterd met Odoo Helpdesk en redencodes. De app is de volgende stap: nu ook aan de kant van de klant.

## 4.2 SIPOC

| Supplier (leverancier) | Input | Process (proces) | Output | Customer (klant) |
|---|---|---|---|---|
| Klant | Vraag of probleem, met foto's of een video | 1. Melding doen in de app | Melding gekoppeld aan het apparaat | Klantenservice |
| Wearable, Odoo | Batterij, softwareversie, aankoop en garantie | 2. Controle op het apparaat en de garantie | Oplossing of een ticket in Odoo | Klant, klantenservice |
| Klantenservice | Ticket met klant, aankoop en historie | 3. Melding beoordelen en beantwoorden | Antwoord of een reparatieopdracht | Klant, reparatie |
| Reparatie | Apparaat en reparatieopdracht | 4. Apparaat repareren en oorzaak vastleggen | Gerepareerd apparaat en een redencode | Klant, productie en logistiek |
| Odoo, app | Status van het ticket of de reparatie | 5. Klant op de hoogte houden en afsluiten | Statusupdates en een beoordeling van de klant | Klant, Power BI |

## 4.3 Huidige situatie (Ist)

![Huidig proces](../img/ist-proces.png)

*Figuur 4.1. Melding tot oplossing, huidige situatie. De rode stappen zijn knelpunten.*

De klant belt of mailt met een vraag of een klacht. Bij elke melding begint de medewerker opnieuw. Hij vraagt de klant om zijn gegevens en zijn aankoop, en zoekt de garantie op in losse bestanden. Daarna beantwoordt hij de vraag of stuurt hij het apparaat door naar reparatie. Bij een reparatie is de reparatiehistorie niet te zien. Aan het einde wordt de oorzaak niet centraal vastgelegd.

Wat goed gaat: de medewerkers lossen het probleem van de klant uiteindelijk op, en de reparatie zelf gaat goed. Wat niet goed gaat: het duurt lang en de klant moet veel zelf doen. In onze BPM Lifecycle schatten wij dat het opvragen van gegevens per melding tussen 8 en 12 minuten kost, en dat een melding nu gemiddeld 72 uur duurt.

## 4.4 Knelpunten

| Knelpunt | Waar in het proces | Gevolg |
|---|---|---|
| De klant moet bij elke melding opnieuw zijn gegevens en aankoop doorgeven | Stap 1 en 2 | Tussen 8 en 12 minuten extra werk per melding. De klant ergert zich. |
| De garantie staat in losse bestanden | Stap 2 | De medewerker moet zoeken. Soms wordt de garantie verkeerd beoordeeld. |
| De klant weet niet hoe ver zijn reparatie is | Stap 4 en 5 | De klant belt om de status te vragen. Dat geeft nog meer werk voor klantenservice. |
| Hulp is er alleen tijdens kantoortijden | Stap 1 | Een eenvoudige vraag 's avonds blijft tot de volgende werkdag liggen. |
| Veel vragen zijn eenvoudig en komen steeds terug, zoals over de batterij of de Bluetoothverbinding | Stap 3 | Medewerkers besteden tijd aan vragen die de klant met een goede uitleg zelf kan oplossen. |
| De oorzaak van een reparatie wordt niet vastgelegd | Stap 4 | Niemand ziet dat meerdere klanten hetzelfde probleem hebben. De klacht wordt opgelost, maar de oorzaak niet. |

Het eerste, tweede en laatste knelpunt lossen wij al deels op met Odoo Helpdesk en de redencodes uit onze BPM Lifecycle. Maar dan heeft alleen de medewerker de gegevens. De klant merkt er nog weinig van. De andere drie knelpunten liggen aan de kant van de klant. Die lost de app op.

## 4.5 Gewenste situatie (Soll)

![Gewenst proces](../img/soll-proces.png)

*Figuur 4.2. Melding tot oplossing, gewenste situatie met de app. De groene stappen zijn nieuw. Een taak met een tandwiel voert een systeem uit, een taak met een poppetje een medewerker.*

De klant meldt zijn probleem in de app. Hij kiest het apparaat waar het om gaat en kan foto's of een video toevoegen. De app weet al wie de klant is en koppelt de melding aan het apparaat en de garantie uit Odoo. Daarna doet de app een controle op het apparaat, bijvoorbeeld op de batterij en de softwareversie. Is het probleem bekend en eenvoudig, dan toont de app meteen de oplossing.

Lukt dat niet, dan maakt de app een ticket aan in Odoo Helpdesk. De medewerker ziet daarin de klant, de aankoop, de historie en de foto's. Hij hoeft niets meer op te vragen. Is er geen reparatie nodig, dan antwoordt hij via de app of de live chat. Is er wel een reparatie nodig, dan repareert reparatie het apparaat en legt de oorzaak vast met een redencode. Bij elke stap stuurt de app de klant een statusupdate, net als bij een pakketje.

## 4.6 Gap: van Ist naar Soll

| Knelpunt nu (Ist) | Wat de app verandert (Soll) | Wat er nodig is (Gap) |
|---|---|---|
| De klant geeft steeds opnieuw zijn gegevens | De klant is ingelogd en kiest zijn apparaat. De melding komt met alle gegevens in Odoo | Een koppeling tussen de app en Odoo Helpdesk. Apparaten moeten geregistreerd zijn met serienummer en aankoopdatum |
| De garantie staat in losse bestanden | De app en Odoo tonen meteen of er garantie is | Alle aankopen en garantietermijnen in Odoo. Dat gebeurt bij de invoering van Odoo |
| De klant weet niet hoe ver zijn reparatie is | De klant volgt de status in de app en krijgt een pushbericht bij elke stap | Vaste statussen in Odoo Reparaties, die de app kan uitlezen. Een pushdienst |
| Hulp alleen tijdens kantoortijden | De chatbot helpt dag en nacht. Tijdens openingstijden kan de klant een live chat starten | Een AI-chatbot die getraind is op onze handleidingen. Live chat in Odoo. Afspraken over wanneer de chatbot doorverwijst |
| Eenvoudige vragen komen steeds terug | De app doet een controle op het apparaat en toont de oplossing. Handleidingen zijn per apparaat te doorzoeken | Een lijst met veelvoorkomende problemen en oplossingen. Handleidingen per apparaat en per taal |
| De oorzaak wordt niet vastgelegd | Elke melding en reparatie krijgt een redencode. Power BI laat zien welke problemen het vaakst voorkomen | Dezelfde redencodes in de app, Odoo en Power BI |
