# Project inleiding

*\[ Certificate management tool\
Nick Hellemans & Stijn Willemen\
Vervolgtraject Software\
2021 -2022 Project Analysis\
product owners: Jacques-Henri De Vos & Johan Kestens
proxy product owners: Jeroen De Vos \]*

# Opdrachtgever

> *\[De opdrachtgevers van het project en hun rol in het project. Benoem
> de product owner met bijhorende functie. Waarom heeft deze persoon
> nood aan dit project en vanwaar de betrokkenheid in dit project?\]*
> *\[ \]*



# Samenvatting

> *\[Korte samenvatting van het project en context, 1 of 2 alinea's.
> Best op het einde pas schrijven als de blueprint klaar is. Maak een
> inleiding met de aanleiding van het project, het doel en wat daarvoor
> ontwikkeld wordt.\]*

# Situatie As-Is

Huidig proces

> *\[De beschrijving van het **huidig proces** of de huidige werkwijze
> en probleemstelling. Het huidig werkproces kan een handmatig proces
> zijn, eventueel deels gedigitaliseerd, of volledig gedigitaliseerd.
> Als er nog geen project is, dan beschrijf je het werkproces dat nu
> gebruikt wordt. Ook dit dient volledig geanalyseerd te worden ahv
> procesflows (activity diagram bv met swimlanes of sequence diagrams).
> Begeleidend schrijven is noodzakelijk ter verduidelijking van de flow,
> het beschrijven van de plaatsen waar het op dit moment mis loopt of
> problemen vastgesteld worden.\]*
> *\[ \]*
>
> *\[TIP ! Dit kan m.b.v. diagrammen zoals activiteitsdiagrammen voor
> processen, BPMN, toestandsdiagrammen voor toestandsveranderingen,
> sequentiediagrammen...\]*

Probleemstelling

> *\[De **probleemstelling** beschrijven aan de hand van dit huidig
> proces is belangrijk. Je kan bv afleiden uit de huidige manier van
> werken dat het foutgevoelig is, beperkingen heeft, veel manueel werk
> vereist, omslachtig werken is, dat het innovatie in de weg staat,
> enzovoort. Luister hiervoor vooral naar jouw P(P)O over welke
> problemen zich allemaal voordoen op dit moment.\]*

# Situatie To-Be

## Doelstelling {#doelstelling .list-paragraph}

> *\[Beschrijf de **doelstelling** van het project. Dit is niet de
> ontwikkeling van de applicatie. De ontwikkeling van de
> I(o)T-applicatie is een middel om het doel te bereiken. Idealiter
> omvat de doelstelling een antwoord op de probleemstellingen uit de
> AS-IS situatie.\]*

*Nieuw proces*

> *\[Teken hier het **nieuwe proces** uit, de procesflow die gehanteerd
> wordt nadat de applicatie ontwikkeld is. Als er minder manueel werk
> moet verricht worden tov de as-is processflow en er meer
> geautomatiseerd wordt, dan zou dit duidelijk moeten worden in de
> nieuwe procestekening, de swimlane(s) die de rol omvat van de
> handmatige acties zou minder activiteiten moeten bevatten dan
> voorheen, de systeem swimlane zou er meer moeten omvatten. Belangrijk
> is om in begeleidend schrijven te duiden waar de meerwaarde ligt van
> het nieuwe proces, welke problemen er waar opgelost worden.\]*

## Projectdefinitie

> *\[Wat ga je juist maken? Indien je Agile werkt, kan je de Epics
> beschrijven, het Minimal Viable Product, \...\]*

## Scope {#scope .list-paragraph}

-   *\[Opsommen van de **functionaliteit** en onderdelen dit bij het
> uitvoeren van het project horen. Probeer dit zo sluitend mogelijk
> te doen, dit voorkomt discussies.\]*

-   *Wat zijn de must-haves, Zijn er nice-to-haves? Prioriteiten?*

-   *Maak **assumpties** indien nodig.*

-   *\[TIP ! Gebruik use case diagram en use case scenario's\]*

## Niet in Scope {#niet-in-scope .list-paragraph}

-   *\[Expliciet vernoemen wat niet tot de draagwijdte (scope) van het
> project hoort, bv. het aanleveren van onderdelen, opleiding,
> maintenance, onderhoud van servers, ...\]*

# Planning

*\[Agile of Waterfall? Scrum of Kanban? Wekelijkse sprints of per maand?
Hoe omgaan met stories die niet goedgekeurd zijn op demo? Welke tools om
alles op te volgen?\]*

## Hoofdlijnen {#hoofdlijnen .list-paragraph}

*\[Korte beschrijving van de planning met de grootste deadlines binnen
het project.\]*

## Toelichting fases {#toelichting-fases .list-paragraph}

*\[Indien de planning in fases of iteraties verloopt, bespreek dan kort
hoe deze opgebouwd zijn. Wanneer ga je analyseren, testen, wat doe je
met feedback uit de demo's en sprintreviews, \...\]*

# Functioneel design

-   \[*Beschrijf hier wat er qua ontwerp opgenomen moet worden m.b.t.
functionaliteit, bv. alle GUI-schermen moeten volgens de huisstijl
opgebouwd zijn, maak dan ook ontwerpen voor de GUI en verduidelijk
de schermen hier ook. Het is op die manier duidelijk voor de P(P)O
wat hij/zij na het project kan verwachten. Bij review van deze
mockups komt ook heel wat nuttige feedback van de P(P)O. Wat is de
algemene lay-out, welke automatische acties moeten er achter je
knoppen/processen zitten?\]*

-   \[*Verduidelijk ook business rules en beslissingen die het systeem
neemt, achterliggende berekeningen die functioneel van belang zijn,
logische keuzes die het systeem maakt op basis van ingevoerde
info.\]*

-   *\[TIP ! Denk aan wireframes,mock-ups, toestandsdiagrammen,
beslissingstabellen, activitydiagrammen.\]*

#  Technisch design

-   *\[Geen code maar algemene software/hardware **architectuur.** Welke
technologie of stacks zou je gebruiken voor dit project? Overloop
per technologie waarom de keuze voor deze technologie de beste is
voor dit project. \]*

-   *\[Beschrijf de technische opbouw, bv database, gebruikte
hardwarecomponenten. Maak hiervoor technische schema's die passen
bij jouw technische keuzes.\]*

-   *\[TIP ! Denk aan klassediagrammen, sequentiediagrammen,
beslissingstabellen, toestandsdiagrammen.\]*

# Beschrijving van de mogelijke interfaces

-   *\[Beschrijf de mogelijke systeem interfaces van je project en hoe
de gegevensstromen gebeuren aan de hand van een context DFD en DD.
Welke gegevens bereiken het systeem en welke zijn de gegevens die
uit het systeem komen? Naar wie gaan ze? Wat zijn deze gegevens
juist?\]*

-   *\[TIP ! Gebruik een context DFD + DD om te verduidelijken en zoek
nog eens op wat een context DFD ook al weer is.\]*

# Beschrijving van eventuele datamigratie

-   *\[Beschrijf de aanpak van de datamigratie en hoe de scripts
opgebouwd zijn. Indien geen datamigratie, gelieve dit te
vermelden.\]*

-   *\[TIP ! Je kan hiervoor ERD gebruiken, activiteitsdiagrammen.\]*

# Beschrijving van eventuele impact op de huidige infrastructuur

-   *\[Beschrijf de impact op de infrastructuur. Dienen er servers
aangekocht te worden, geherinstalleerd, of gewijzigd te worden?
Worden er andere systemen in het landschap voorzien of verwijderd?
Wordt er een cloud service gebruikt? Wat zijn de vereisten daarvan?
Zijn er specifieke licentiekosten waar rekening mee gehouden moet
worden? Wat met schaling?\]*

-   *\[TIP ! Gebruik component- of deploymentdiagram.\]*

# Analyse van security en eventuele autorisatierollen

-   *\[Beschrijf de methode en aanpak van de security. Als het om een
extern systeem gaat, leg dan uit hoe zij het aanpakken. Kan het
gehackt worden? Wat zijn de security breaches en hoe ga je daarmee
om in dit project?\]*

-   *\[Beschrijf hoe omgegaan wordt met privacy. Hoe worden gegevens
verdeeld, wie heeft er toegang op welke gegevens, welke mechanismes
stel je in het werk om te voorkomen dat gegevens te grijpen
liggen?\]*

-   *\[CSC : Beschrijf het Business continuity plan\]*

-   *\[Beschrijf de verschillende autorisatierollen en wat ze net kunnen
in het systeem\]*

# Documentatie

-   *\[Hoe wordt documentatie in de code voorzien?\]*

-   *\[Zal er documentatie voorzien worden als het project opgeleverd
wordt, bv. Handleidingen, release plan, technische documentatie?\]*

# Bronvermelding

\[Vermeld hier al je bronnen volgens de APA stijlgids
(<https://apastyle.apa.org/>). Denk eraan dat elk brontype
(website/rapport/wetenschappelijk artikel/hoofdstuk uit boek/...) zijn
eigen stijl heeft. \]

--------------------------------------------------------------------------
\[1\]   Jan, A. (2015-04-12). De titel van deze pagina. Opgehaald van
<http://xxxxxxxxx>.
------- ------------------------------------------------------------------


--------------------------------------------------------------------------
