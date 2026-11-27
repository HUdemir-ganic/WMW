[← Terug naar de inhoudsopgave](../README.md)

# 7. Definition of Ready en Definition of Done

| | Definition of Ready (DoR) | Definition of Done (DoD) |
|---|---|---|
| **Vraag** | Is de user story goed genoeg beschreven om in een sprint op te pakken? | Is de user story volgens onze kwaliteitseisen gebouwd? |
| **Wanneer** | Voor de sprint, bij refinement | Na de bouw, voordat de story op Done gaat |
| **Wie** | Het scrumteam, met de product owner | Het scrumteam, met de product owner |
| **Geldt voor** | Alle user stories | Alle user stories |

## 7.1 Definition of Ready

Wij gebruiken INVEST als basis (Wake, 2003) en vullen dat aan met eigen afspraken. Een user story is klaar om op te pakken als:

- [ ] **Onafhankelijk** – De story kan los van andere stories worden gebouwd. Hangt hij toch af van een andere story, dan staat dat erbij en is die andere story al af of zit hij in dezelfde sprint.
- [ ] **Onderhandelbaar** – De story beschrijft wat de gebruiker wil en waarom, maar niet precies hoe het gebouwd moet worden. Het team kan met de product owner over de invulling praten.
- [ ] **Waardevol** – De story levert de gebruiker of Watch My Watch iets op. De zin "zodat …" is ingevuld.
- [ ] **Inschatbaar** – Het team weet genoeg om een T-shirtmaat te geven.
- [ ] **Klein** – De story past binnen één sprint. Een story met maat XL wordt eerst opgesplitst.
- [ ] **Testbaar** – Er zijn minstens drie acceptatiecriteria die je kunt controleren.
- [ ] **Wireframe** – Heeft de story een scherm, dan is er een wireframe dat de product owner heeft gezien.
- [ ] **Koppelingen** – Heeft de story gegevens uit Odoo of een ander systeem nodig, dan heeft het hoofd IT bevestigd welke gegevens de app mag gebruiken.
- [ ] **Privacy** – Gebruikt de story persoonsgegevens of gezondheidsgegevens, dan is gecontroleerd dat dit in de DPIA staat.

## 7.2 Definition of Done

Een user story is af als:

- [ ] Alle acceptatiecriteria zijn getest en werken.
- [ ] De code is door een tweede ontwikkelaar nagekeken.
- [ ] Er zijn automatische tests voor de belangrijkste stappen, en alle tests slagen.
- [ ] De story werkt op iPhone en Android, op een klein en een groot scherm.
- [ ] De story voldoet aan WCAG 2.1 niveau AA (zie story 10).
- [ ] Koppelingen met Odoo zijn getest in de testomgeving van Odoo, niet in de echte omgeving.
- [ ] Een key user van de afdeling die ermee werkt, heeft de story getest en goedgekeurd. Bij meldingen is dat een key user van klantenservice.
- [ ] De code en de koppelingen zijn kort gedocumenteerd, zodat de functioneel beheerder ze kan beheren.
- [ ] De product owner heeft de story bij de sprintreview geaccepteerd.
