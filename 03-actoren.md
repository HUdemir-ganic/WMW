[← Terug naar de inhoudsopgave](../README.md)

# 3. Actoren

Een actor is iets of iemand die een handeling uitvoert in de app. Dat hoeft geen mens te zijn: een chatbot of een gekoppeld systeem kan ook een actor zijn. Een functie gaat over het organiseren van mensen, een rol over het organiseren van werk. Eén functie kan dus meerdere rollen hebben. Hieronder staan eerst alle actoren, daarna de functies en daarna de rollen.

## 3.1 Overzicht

| Actor | Mens of systeem | Wat doet de actor in de app? |
|---|---|---|
| Particuliere klant | Mens | Registreert apparaten, krijgt advies van de AI-coach, meldt problemen, bestelt en doet mee in de community |
| Zakelijke beheerder | Mens | Beheert de apparaten van de medewerkers van een zakelijke klant |
| Klantenservicemedewerker | Mens | Behandelt meldingen uit de app en voert live chats |
| Reparatiemedewerker | Mens | Repareert apparaten en zet de status en de redencode in Odoo |
| Marketingmedewerker | Mens | Maakt aanbiedingen, uitdagingen en evenementen, en modereert de community |
| Functioneel beheerder | Mens | Beheert de inhoud van de app, de gebruikers en de koppelingen |
| Wearable | Systeem | Stuurt via Bluetooth gegevens naar de app, zoals batterij, softwareversie, hartslag en slaap |
| AI-chatbot | Systeem | Beantwoordt vragen van klanten, dag en nacht, en geeft een gesprek door aan een medewerker |
| AI-coach | Systeem | Maakt persoonlijke trainings- en leefstijladviezen op basis van de gegevens en de doelen van de klant |
| Odoo (ERP en CRM) | Systeem | Levert klant-, product-, garantie- en voorraadgegevens. Ontvangt meldingen en bestellingen |
| Power BI | Systeem | Ontvangt geanonimiseerde gebruiksgegevens voor dashboards |
| Gezondheidsplatforms | Systeem | Apple Gezondheid, Google Health Connect en Strava. Wisselen sport- en gezondheidsgegevens uit met de app, als de klant dat wil |

## 3.2 Functiebeschrijvingen

### Functie: Klantenservicemedewerker

| | |
|---|---|
| **Functie** | Klantenservicemedewerker |
| **Omschrijving** | Werkt op de afdeling klantenservice. Beantwoordt vragen van klanten via telefoon, mail en de app, en behandelt garantieaanvragen. Werkt in Odoo Helpdesk. |

### Functie: Reparatiemedewerker

| | |
|---|---|
| **Functie** | Reparatiemedewerker |
| **Omschrijving** | Werkt op de afdeling klantenservice, bij reparatie. Onderzoekt en repareert apparaten die klanten opsturen of brengen. Werkt in Odoo Reparaties. |

### Functie: Marketingmedewerker

| | |
|---|---|
| **Functie** | Marketingmedewerker |
| **Omschrijving** | Werkt op de afdeling verkoop en marketing. Maakt campagnes en aanbiedingen en onderhoudt het contact met de klant buiten de verkoop om. |

### Functie: Functioneel beheerder

| | |
|---|---|
| **Functie** | Functioneel beheerder |
| **Omschrijving** | Werkt op de IT-afdeling. Beheert Odoo en straks ook de app: gebruikers, rechten, inhoud en koppelingen. |

### Functie: Zakelijke beheerder

| | |
|---|---|
| **Functie** | Medewerker van een zakelijke klant, meestal van HR of facilitair |
| **Omschrijving** | Werkt niet bij Watch My Watch, maar bij een bedrijf dat wearables voor zijn medewerkers koopt. Is ons aanspreekpunt bij dat bedrijf. |

## 3.3 Rol- en actorbeschrijvingen

De frequenties zijn schattingen. Voor de meldingen gaan wij uit van 350 tot 450 per maand, zoals in onze BPM Lifecycle.

### Rol: Gebruiker van de app

| | |
|---|---|
| **Rol** | Gebruiker van de app |
| **Omschrijving** | Gebruikt de app voor zijn eigen apparaten: registreren, advies van de AI-coach, hulp, melden en bestellen |
| **Gekoppelde functies** | Geen functie bij Watch My Watch. Dit is de particuliere klant |
| **Wie vervult de rol?** | Elke klant met een wearable van Watch My Watch |
| **Frequentie** | Meerdere keren per week. De AI-coach geeft elke dag een advies |

### Rol: Melding beoordelen

| | |
|---|---|
| **Rol** | Melding beoordelen |
| **Omschrijving** | Bekijkt een ticket uit de app en kiest: de vraag beantwoorden of het apparaat laten repareren |
| **Gekoppelde functies** | Klantenservicemedewerker |
| **Wie vervult de rol?** | De afdeling klantenservice |
| **Frequentie** | Tussen 350 en 450 meldingen per maand. Wij verwachten dat dit daalt als klanten meer zelf oplossen |

### Rol: Live chat voeren

| | |
|---|---|
| **Rol** | Live chat voeren |
| **Omschrijving** | Neemt een gesprek over van de chatbot en ziet daarbij het hele gesprek en de gegevens van de klant |
| **Gekoppelde functies** | Klantenservicemedewerker |
| **Wie vervult de rol?** | De afdeling klantenservice, tijdens openingstijden |
| **Frequentie** | Dagelijks, naar verwachting tussen 10 en 30 gesprekken per dag |

### Rol: Reparatie uitvoeren en status bijwerken

| | |
|---|---|
| **Rol** | Reparatie uitvoeren en status bijwerken |
| **Omschrijving** | Repareert het apparaat, werkt de status bij in Odoo en legt de oorzaak vast met een redencode. De app laat de nieuwe status meteen aan de klant zien |
| **Gekoppelde functies** | Reparatiemedewerker |
| **Wie vervult de rol?** | Reparatie, binnen klantenservice |
| **Frequentie** | Dagelijks |

### Rol: Inhoud en aanbiedingen beheren

| | |
|---|---|
| **Rol** | Inhoud en aanbiedingen beheren |
| **Omschrijving** | Zet aanbiedingen, uitdagingen, badges en evenementen in de app en stuurt pushberichten naar klanten die daar toestemming voor gaven |
| **Gekoppelde functies** | Marketingmedewerker |
| **Wie vervult de rol?** | Verkoop en marketing |
| **Frequentie** | Wekelijks |

### Rol: Community modereren

| | |
|---|---|
| **Rol** | Community modereren |
| **Omschrijving** | Controleert berichten in de community en haalt berichten weg die niet passen bij de regels |
| **Gekoppelde functies** | Marketingmedewerker |
| **Wie vervult de rol?** | Verkoop en marketing |
| **Frequentie** | Dagelijks, een korte controle |

### Rol: Handleidingen en antwoorden beheren

| | |
|---|---|
| **Rol** | Handleidingen en antwoorden beheren |
| **Omschrijving** | Zet handleidingen, video's en veelgestelde vragen in de app, per apparaat en per taal. De chatbot gebruikt deze inhoud voor zijn antwoorden |
| **Gekoppelde functies** | Functioneel beheerder, met input van klantenservice |
| **Wie vervult de rol?** | IT-afdeling |
| **Frequentie** | Bij elk nieuw product of elke nieuwe software-update, ongeveer maandelijks |

### Rol: Zakelijke apparaten beheren

| | |
|---|---|
| **Rol** | Zakelijke apparaten beheren |
| **Omschrijving** | Ziet alle apparaten van zijn bedrijf, met garantie en batterijstatus, en vraagt vervanging aan |
| **Gekoppelde functies** | Zakelijke beheerder |
| **Wie vervult de rol?** | Een medewerker van de zakelijke klant |
| **Frequentie** | Maandelijks |

### Rol: Vragen beantwoorden (AI-chatbot)

| | |
|---|---|
| **Rol** | Vragen beantwoorden |
| **Omschrijving** | Beantwoordt vragen met de handleidingen en de klantgegevens uit Odoo. Zegt erbij dat hij een chatbot is. Geeft het gesprek door als hij het antwoord niet weet |
| **Gekoppelde functies** | Systeem |
| **Wie vervult de rol?** | AI-chatbot |
| **Frequentie** | Dag en nacht |

### Rol: Persoonlijk advies geven (AI-coach)

| | |
|---|---|
| **Rol** | Persoonlijk advies geven |
| **Omschrijving** | Maakt een weekplan en een dagadvies op basis van het doel, de activiteit, de slaap en het herstel van de klant. Stelt geen diagnoses |
| **Gekoppelde functies** | Systeem |
| **Wie vervult de rol?** | AI-coach |
| **Frequentie** | Elke dag een advies, elke week een nieuw plan |

### Rol: Gegevens leveren en ontvangen (Odoo)

| | |
|---|---|
| **Rol** | Gegevens leveren en ontvangen |
| **Omschrijving** | Levert klant-, aankoop-, garantie- en voorraadgegevens aan de app. Maakt van een melding een ticket en van een bestelling een order |
| **Gekoppelde functies** | Systeem |
| **Wie vervult de rol?** | Odoo |
| **Frequentie** | Bij elke actie in de app |

### Rol: Gegevens meten en tonen (wearable)

| | |
|---|---|
| **Rol** | Gegevens meten en tonen |
| **Omschrijving** | Meet activiteit, hartslag en slaap, en stuurt die samen met de batterijstatus en de softwareversie naar de app |
| **Gekoppelde functies** | Systeem |
| **Wie vervult de rol?** | De wearable van de klant |
| **Frequentie** | Steeds als de wearable met de telefoon verbonden is |
