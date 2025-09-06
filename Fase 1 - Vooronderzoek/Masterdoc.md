## Opdracht
Ontwerp een aantrekkelijke en gebruiksvriendelijke [digital wallet](#digitalWallet) met de nadruk op het ondertekenen van documenten en houdt rekening met toegankelijkheid.
## Eindresultaat
Jullie eindproduct moet een gedetailleerd en onderbouwd ontwerp zijn van deze applicatie waarbij er verschillende prototypen worden opgeleverd.
## Doelgroep
Iedereen

## Aandachtspunten
- Toegankelijk voor zo veel mogelijk mensen en bedrijven, in overeenstemming met [Europese Accessibility Act7](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882)
- Mensgericht en [inclusief](#beperkingen) ontwerpproces
- [Privacy](#internetVeiligheid) moet goed gewaarborgd worden
- Gebruikers moeten volledige controle hebben over wat ze willen delen, en dit bij kunnen houden
- Gebruikers moeten hun identiteit kunnen bewijzen, hun documenten op kunne slaan en delen, en makkelijk dingen ondertekenen
- In overeenstemming met [Architecture and reference framework](https://eu-digital-identity-wallet.github.io/eudi-doc-architecture-and-reference-framework/1.6.0/)

## Opdrachtgever
- Lectoraat Media Design
- Innovatie op UX gebied
- https://www.han.nl/onderzoek/lectoraten/lectoraat-media-design/

## Vergelijkbare producten
### Yivi
- https://yivi.app
- [Onderzoek yivi](https://github.com/ehhermans/cursus5/blob/main/Fase%201%20-%20vooronderzoek/Onderzoek%20Yivi.md)
- Risicovol vanwege de gebruikte techbedrijven en toezicht.
- Open-source en gratis voor eindgebruikers, met een focus op privacy by design
- Ontwikkeld en beheerd door de Privacy by Design Foundation en partners
- Gebruikt cryptografische technieken om enkel noodzakelijke gegevens te delen, zonder volledige persoonsgegevens prijs te geven
- Visie: Zelf de baas over jouw gegevens Jouw digitale identiteit in één app
- Missie: Internetgebruikers wordt te pas en te onpas gevraagd om privacygevoelige gegevens te delen en vaak delen ze meer informatie dan nodig is. Dat kan en moet anders. Wij geloven dat de ontwikkeling van eenvoudige, privacyvriendelijke en veilig te gebruiken oplossingen voor online identificatie bijdraagt aan de bescherming van privacy en identiteit en een optimaal gebruik van het internet. En daarmee dus aan onze missie voor een kansrijk en zorgeloos digitaal bestaan voor iedereen.

### DigiD
- https://www.digid.nl
- [Onderzoek DigiD](https://github.com/ehhermans/cursus5/blob/main/Fase%201%20-%20vooronderzoek/Onderzoek%20naar%20DigiD.md)
- DigiD is een digitale app voor de mobiele telefoon
↪ Mensen die niet digitaal onderlegd zijn in het gebruik van een computer of smartphone — of daarbij, helemaal geen smartphone hebben — zullen moeite hebben met het gebruiken van de app.
- De app is ontworpen om door zoveel mogelijk Nederlandse burgers gebruikt te worden
- De app en website zullen ondersteuning bieden voor mensen met lichamelijke of mentale beperkingen
- Het verkrijgen van een DigiD-account is lastiger dan gemiddelde mobiele applicaties (bijv. social media)

### ID010-wallet. 
- Zijn nog bezig met het prototype en de wetgeving is nog incompleet.
### Ockto.
- Wetgeving incompleet
### eIDS 2.0. 
- Weg vanwege kritiek.

## Mogelijke gebruiksgevallen
### Identificatiebewijzen
-	ID-kaart
-	Paspoort

### Persoonsgegevens
-	Naam
-	Geboortedatum
-	BSN
-	Andere gegevens uit het basisregister personen (geboorteplaats, adres, geslacht, nationaliteit, huwelijk, kinderen, familie etc.)

### Bewijsstukken
-	Diploma’s
-	Vergunningen
-	Certificaten
-	Rijbewijs
-   Contracten

### Andere info
-	Financiële info
-	Gezondheidsgegevens
-   Zorg verzekering
-	Studiebewijs
-	Kamer van koophandel
-	Autogegevens
-	Toegangspassen / reisdocumenten
-   Simkaart in ander EU land kopen


## Stakeholders
-	Burgers (gebruikers)
    - Makkelijkere toegang tot data door heel de EU
    - Persoonlijke data wordt beschermt
    - Alleen benodigde data word gedeeld
-	Dienstverlening (bedrijven die de gegevens controleren zoals banken, gemeentes etc)
    - Goede cybersecurity
    - Betere toegang tot services
    - Betere bestendigheid tegen fraude
-   Commerciele bedrijven (bedrijven die gegevens nodig hebben voor bijv. aankopen)
    - Makkelijker en goedkoper om gegevens te controleren
    - Makkelijker om business 100% online to doen (bijv. verkoop van alchohol)
    - Neutrale manier van gegevens controleren (geen 3rd party bedrijven die dit moeten doen)
-	Overheid (regelgeving en uitgifte)
-	Zorginstellingen
-	EU Member States
-	Device manufactures
-	Cybersecurity experts
-	Makers 
-	Waarborgers (voor toezicht)
-	Ontwikkelaars (software ontwikkelen)
-	Uitgevers van documenten (diploma’s)

## Mogelijke functies (uit voorbeelden)
- Verschillende documenten per type geordend 
- Pin om in app te komen
- Lijst van informatie over gebruiker
- Kiezen wat voor informatie je wil delen (informatie voorgesteld, maar je kan het uitzetten > waarschuwing dat dit voor problemen kan zorgen)
- QR code/nfc om te laten scannen 
- Transactie geschiedenis
- Makkelijke manier om email te sturen naar service om te stoppen met het gebruik van data
- Transactie rapottern functie > makkelijke manier om email te sturen naar overheid

- eSignature: Manier om toestemming te geven
    - Voor burger: Makkelijk dingen ondertekenen zonder gebruik van papier
    - Voor bedrijven: Sneller en goedkoper door gestroomlijnd process
- eTimestamp: Bewijs dat data op een specifieke tijd bestond
    - Voor burger: Geeft bewijs dat je iets gekocht hebt
    - Voor bedrijven: Maakt het bijhouden van documenten makkelijker en zorgt voor grotere verantwoordelijkheid
- eID: Manier om identiteit digitaal te bewijzen
    - Voor burger: Maakt het makkelijker om officele processen te doorgaan zoals bankrekening openen in ander land
    - Voor bedrijven: Zorgt voor meer klanten, bespaard kosten en tijd, en bouwt beter vertrouwen in internationale transacties
- Qualified web authentication certificate: Zorgt ervoor dat websites betrouwbaar zijn
    - Voor burger: Zien dat een website veilig is
    - Voor bedrijven: Bouwt vertrouwen met de klant, en verkomt phishing in de naam van het bedrijf
- eSeal: Garandeerd waar het document vandaan komt en de echtheid ervan
    - Voor burger: Aankoop van tweedehands documenten (bijv. tickets) is betrouwbaarder
    - Voor bedrijven: Kosten en tijd word bespaart, en bouwt vertrouwen
- Electronic registered delivery service: Beschermt documenten van verloren, gestolen, beschadigd of veranderd worden
    - Voor burger: Zorgt ervoor dat documenten heel aankomen
    - Voor bedrijven: Tijd en kosten worden bespaard en bijhouden van documenten word makkelijker

## <a name="digitalWallet">Digital Wallet</a>
- Een digital wallet zorgt dat je je persoonlijke gegevens veilig kan opslaan en delen
- Met een digital wallet kan je bijvoorbeeld in alle EU-landen veilig inloggen en makkelijk iets over je zelf aantonen zonder dat je meer gegevens hoeft te delen dan nodig is
- De ID wallet moet aangeboden worden door de overheid ipv bedrijven om privacy beter te waarborgen, en zodat persoonlijke gegevens niet in de handen van bedrijven liggen
- Anders dan DigiD, er moet echt meer in dan alleen ID zoals bij een fysieke portemonnee
- Er kan vanuit gegaan worden door diensten dat de informatie in de wallet klopt, waardoor er minder gecontroleerd moet worden
- De ID wallet moet idealieter open source zijn zodat gebruikers makkelijk inzicht kunnen krijgen in hoe het werkt

### Mogelijke uitdagingen 
- Elk EU land gaat een eigen ID-wallet hebben
- Sommige data in EU landen is ongeveer hetzelfde maar met een andere naam, dat moet allemaal op 1 lijn getrokken worden
- De wallets gaan constant veel aanpassingen nodig hebben (manier van koppelen, gewenste data etc.)
- Verifieren of het device tot de vermeende persoon behoord

## <a name="internetVeiligheid">Internet veiligheid</a>
### Internetbankieren

Elke bank-app maakt gebruik van een verificatiecode. Er zijn hiervoor nog geen gevallen van fraude bekend. Het wordt aangeraden om apps alleen via de **officiële appstores** te downloaden. 

Gebruik geen openbare wifinetwerken, maar alleen het netwerk van je eigen provider. In Nederland zijn bank-apps extra beveiligd met maatregelen zoals:
- Een transactielimiet
- Het weigeren van betalingen naar onbekende rekeningen

### Wat is een datalek?
Een datalek betekent dat zonder toestemming of bedoeling toegang wordt verkregen tot persoonsgegevens. Dit omvat ook:
- Ongewenste vernietiging
- Verlies
- Wijziging
- Verstrekking van gegevens

### Wat zijn de gevaren?
- Identiteitsfraude  
- Oplichting  
- Phishing  
- Hacks  
- Diefstal / inbraak

### Persoonsgegevens op het internet
Mensen delen veel persoonsgegevens online, zoals foto's op Instagram. Deze gegevens kunnen jarenlang vindbaar blijven, wat negatieve gevolgen kan hebben.

### Locatiegegevens

Apps die toestemming krijgen om je locatie te volgen, verzamelen deze gegevens en sturen ze naar advertentienetwerken. Daar worden ze gekoppeld aan jouw unieke advertentie-ID.

Deze gegevens worden:
- Gebruikt om advertenties te personaliseren
- Doorverkocht, mogelijk zelfs aan stalkers of kwaadwillenden

Wat kun je doen?
- Tracking-toestemming intrekken
- Advertentie-ID regelmatig vernieuwen
- Bedrijven vragen je gegevens in te zien of te verwijderen

### Toegang vragen

Lees de voorwaarden wanneer je een app downloadt, vooral bij gratis apps. 

> Als je niet met geld betaalt, betaal je vaak met je gegevens.

Geef alleen toegang tot functies die echt nodig zijn. Voorbeeld: wel camera-toegang voor Snapchat, maar niet voor een simpele berichten-app.

### Kinderen en het internet

- Vanaf 16 jaar mag je zelfstandig social media accounts aanmaken
- Onder de 16 is ouderlijke toestemming nodig voor het verwerken van persoonsgegevens

### Appcategorieën en gegevensgebruik

| Appcategorie        | Gegevensgebruik |
|---------------------|-----------------|
| Social media        | Veel            |
| Eten bezorgen       | Veel            |
| Afbeelding editors  | Weinig          |
| Browsers            | Weinig          |

### Wat kun je zelf doen?

- Blijf alert: Herken trucs van oplichters (zoals valse berichten van je bank)
- Antivirussoftware: Gebruik een betrouwbare virusscanner
- Wachtwoordbeheer: Gebruik sterke en unieke wachtwoorden, eventueel met een wachtwoordmanager
- Twee-factor authenticatie (2FA): Zoals gebruikt bij HAN, een extra code via mail of telefoon
- Updates: Houd je apparaten up-to-date tegen beveiligingslekken
- Back-ups: Maak minstens twee back-ups, waarvan één op een andere locatie
- Cookies verwijderen: Regelmatig cookies wissen helpt je privacy te beschermen


Wat zijn cookies?
- Cookies zijn kleine tekstbestanden die websites opslaan op je computer wanneer je ze bezoekt. Ze worden gebruikt om gebruikers te herkennen, bijvoorbeeld zodat je ingelogd blijft.
- Je kunt meestal niet zien waar een cookie precies voor dient; de inhoud is vaak onleesbare code. 
- De echte gegevens over jou staan in de database van de website.
- Cookies helpen websites om je gedrag te volgen en hun aanbod aan te passen.

## <a name="beperkingen"> Belangrijke beperkingen om mee te nemen </a>
### Lichamelijke beperkingen
<ul>
  <li>Blind (aan één of beide ogen)</li>
  <li>Doof (aan één of beide oren) </li>
  <li>Kleurenblind</li>
  <li>Congenitale aplasie (ontbreken van ledematen)</li>
  <li>Amputatie</li>
</ul>

### Verstandelijke beperkingen
<ul>
  <li>Syndroom van Down</li>
  <li>Fragiele X-Syndroom</li>
  <li>Smith-Magnis Syndroom</li>
</ul>

### Cognitieve beperkingen
<ul>
  <li>Alzheimer</li>
  <li>Analfabeet/Laaggeletterdheid</li>
  <li>Autisme</li>
  <li>Problemen met lezen</li>
  <li>Problemen met schrijven</li>
  <li>Communicatie, voeren van gesprekken en taalgebruik</li>
</ul>

# Bronnen:
- Ondertekenen, A. O. D. (z.d.). Alles over Digitaal Ondertekenen. Digitaal Ondertekenen. https://digitaal-ondertekenen.nl/blog/wat-is-de-european-digital-identity-wallet-en-waarom-is-het-belangrijk
Digitale Overheid. (2025, 28 augustus).
- De EDI-wallet Identiteit digitale overheid. https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/identiteit/id-wallet/#:~:text=Wat%20is%20een%20EDI%2Dwallet,wallet%20ook%20documenten%20digitaal%20ondertekenen.
- Betaalvereniging Nederland. (2025, 17 juni). EU-digitale ‘identity-wallet’ voor betalingen: interpretatie en haalbaarheidsbeoordeling. https://www.betaalvereniging.nl/actueel/nieuws/eu-digitale-identity-wallet-interpretatie/
- European Digital Identity. (z.d.).
- European Commission. https://commission.europa.eu/strategy-and-policy/priorities-2019-2024/europe-fit-digital-age/european-digital-identity_en
- Europese Digitale Identiteit: alles wat je moet weten! (z.d.). https://ockto.eu/europese-digitale-identiteit-id-wallet#:~:text=Wat%20is%20de%20Europese%20ID,aangesloten%20partijen%20(Relying%20Parties).
- Madrigal, D. (2024, 28 oktober). GlobalPlatform Brings Together Key Stakeholders To Discuss EU Digital ID Wallet, Setting a Roadmap for Europe’s Digital Identity Future. GlobalPlatform. https://globalplatform.org/globalplatform-brings-together-key-stakeholders-to-discuss-eu-digital-id-wallet-setting-a-roadmap-for-europes-digital-identity-future/
- https://www.han.nl/onderzoek/lectoraten/lectoraat-media-design/
- https://www.yivi.app/
- [De Europese id-wallet: hoe, wat en waarom? - Digitale Overheid](https://www.digitaleoverheid.nl/achtergrondartikelen/de-europese-id-wallet-hoe-wat-en-waarom/)
- [ID-wallets: wat staat overheidsorganisaties te… - Signicat](https://www.signicat.com/nl/blog/id-wallets-wat-staat-overheidsorganisaties-te-wachten)
- https://www.vpro.nl/programmas/tegenlicht/lees/artikelen/2022/irma-identiteitsplatform0.html
- https://waag.org/nl/project/digitale-identiteitslab/
- [Video Serie | Digitale Identiteitslab](https://digitaleidentiteit.waag.org/artikel/video-serie/)
- https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/716146139/The+many+use+cases+of+the+EU+Digital+Identity+Wallet
- DigiD – Over DigiD 
- DigiD – Inlogmethodes
- DigiD – Toegankelijkheid
- Yivi – Officiële website
- Tweakers – Waar staat Nederland in de zoektocht naar een digitaal identiteitsbewijs?
- Signicat Developer Docs – About Yivi
- Zynyo – Yivi
- App Store – Yivi
- Radboud Universiteit – Yivi overview (B. Jacobs)
- Ver.id Docs – Yivi overview
- https://www.digid.nl/over-digid
- https://www.digid.nl/inlogmethodes/digid-app
- https://www.digid.nl/
- https://www.digid.nl/over-digid/toegankelijkheid-van-digid
- https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/694487738/EU+Digital+Identity+Wallet+Home
- https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/716146139/The+many+use+cases+of+the+EU+Digital+Identity+Wallet
- https://commission.europa.eu/strategy-and-policy/priorities-2019-2024/europe-fit-digital-age/european-digital-identity_en
- https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/identiteit/id-wallet/
- [Veilig Bankieren](https://www.veiligbankieren.nl/veiligheid-betaalproducten/mobiel-bankieren/)
- [Autoriteit Persoonsgegevens: Wat is een datalek?](https://www.autoriteitpersoonsgegevens.nl/themas/beveiliging/datalekken/wat-is-een-datalek)
- [Consumentenbond - Datalekken](https://www.consumentenbond.nl/veilig-internetten/datalekken-de-gevaren-en-wat-moet-je-doen)
- [AP - Persoonsgegevens op internet](https://www.autoriteitpersoonsgegevens.nl/themas/internet-slimme-apparaten/persoonsgegevens-op-internet)
- [Veilig Internetten - Locatiegegevens](https://veiliginternetten.nl/locatiegegevens-nederlanders-online-te-koop/)
- [Veilig Internetten - App toegang tot foto's](https://veiliginternetten.nl/wat-moet-ik-doen-als-een-app-toegang-wil-tot-mijn-fotos/)
- [Consumentenbond - Veilig Internetten](https://www.consumentenbond.nl/veilig-internetten)
- [Surfshark - Apps die je tracken](https://surfshark.com/apps-that-track-you#:~:text=These%20include%20navigation%20app%20InRoute,data%20app%20from%20their%20category)
- https://handicap.nl/wat-is-een-handicap-en-welke-zijn-er-dan-allemaal/
- https://www.prinsenstichting.nl/orienteren/niveaus-en-syndromen/
