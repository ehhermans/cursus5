# EU Digital Identity Wallet

## Doel  
Kort, praktisch en begrijpelijk overzicht van wat een EU Digital Identity Wallet is, welke kernbegrippen belangrijk zijn, wat het doel en de belangrijkste use-cases zijn, welke voordelen er zijn en welke technische en organisatorische aandachtspunten je moet meenemen bij ontwerp en implementatie.

---

## 1. Korte inleiding  
Een EU Digital Identity Wallet is een app (meestal aangeboden door lidstaten) waarmee mensen digitale documenten veilig bewaren en gecontroleerd delen. Deze wallets maken identificatie, bewijslevering en elektronische handtekeningen makkelijker, veiliger en meer privacy-vriendelijk dan papieren documenten of centrale datastores.

---

## 2. Belangrijke begrippen (in eenvoudige bewoordingen)

- **Digital documents / verifiable credentials**  
  Digitale bewijzen zoals een rijbewijs, diploma of ticket. Ze zijn cryptografisch ondertekend zodat ontvangers zeker weten dat ze echt en ongewijzigd zijn.

- **Issuer (uitgever)**  
  De organisatie die het digitale bewijs uitgeeft (bijvoorbeeld gemeente, universiteit of werkgever).

- **Holder (houder / gebruiker)**  
  De persoon die het bewijs in zijn/haar wallet bewaart en zelf beslist met wie het gedeeld wordt.

- **Verifier / Service provider**  
  De partij die om een bewijs vraagt en controleert of het geldig is (bijvoorbeeld een verhuurder, winkel of overheidsdienst).

- **Selective disclosure / minimale gegevensdeling**  
  Mogelijkheid om alleen die gegevens te delen die echt nodig zijn (bijv. “ouder dan 18” in plaats van volledige geboortedatum).

- **Revocation / intrekking**  
  Mechanisme waarmee een uitgegeven bewijs ongeldig kan worden gemaakt (bijv. bij verlopen documenten).

---

## 3. Wat is het doel van de wallet?

- Gebruiker heeft controle over zijn data en deelt alleen wat nodig is.  
- Biedt veilige en betrouwbare identificatie en verificatie.  
- Zorgt voor interoperabiliteit tussen diensten en lidstaten, zodat één standaard overal werkt.  
- Maakt rechtsgeldige digitale handelingen mogelijk (bijv. elektronische handtekening).

---

## 4. Typische use-cases

- Inloggen en identificeren bij overheidsdiensten en banken.  
- Leeftijdscontrole (online en in winkels).  
- Tonen van diploma’s en certificaten aan werkgevers of onderwijsinstellingen.  
- Reis- en gezondheidsdocumenten (boarding passes, vaccinatiebewijzen).  
- Ondertekenen van contracten en KYC-processen (know-your-customer).

---

## 5. Voordelen

- **Voor gebruikers:** minder gedoe met formulieren, betere privacy en meer controle.  
- **Voor bedrijven:** snellere onboarding, lagere fraude en minder opslagverplichtingen.  
- **Voor overheden:** efficiëntere dienstverlening en veilige, interoperabele identiteiten.

---

## 6. Security & privacy — kernpunten

- Gebruik sterke cryptografie om documenten te ondertekenen en te verifiëren.  
- Ontwerp privacy-first: vraag alleen noodzakelijke data en toon duidelijk wat wordt gedeeld.  
- Voorzie in revocation checks zodat ingetrokken of verlopen documenten geweigerd worden.  
- Bied een privacy-dashboard waarin gebruikers transacties en toestemmingen kunnen beheren.

---

## 7. Pilots en regelgeving (kort)

Lidstaten en consortia voeren grootschalige pilots uit om flows en interoperabiliteit te testen. Er is een Europees regelgevend kader dat technische vereisten, certificatie en governance vastlegt. Ontwerpen moet dus rekening houden met toekomstige certificatieverplichtingen en standaarden.

---

## 8. Praktische implementatie-checklist (voor ontwerpers & ontwikkelaars)

### Architectuur & standaarden
- Bouw op de Europese referentiekaders en standaarden voor verifiable credentials.

### Verificatie
- Accepteer cryptografisch ondertekende credentials en voer revocation-checks uit.

### Data-minimalisatie
- Vraag alleen noodzakelijke attributen en toon altijd waarom iets gevraagd wordt.

### UX / Onboarding
- Heldere flow: downloaden → wallet beveiligen (PIN/biometrie) → koppelen eID → ontvangen credentials.  
- Duidelijke toestemming: wie vraagt wat en waarom, met een eenvoudige bevestigingsstap.

### Transacties
- Ondersteun QR-presentatie en scanning; toon welke attributen gedeeld worden voordat de gebruiker bevestigt.

### Logging & compliance
- Log op privacyvriendelijke wijze (geen onnodige persoonsgegevens).  
- Bied gebruikers inzage in hun transactielog.

### Voorbereiding op certificatie
- Zorg dat je systeem audit-klaar is: security-audits, conformance tests en governance-documentatie.

---

## 9. Knelpunten en mitigaties

- **Adoptie:** begin met één concreet, hoog-impact use-case.  
- **Vertrouwen & governance:** werk samen met erkende issuers en volg certificatiepaden.  
- **Technische integratie:** implementeer fallback-flows voor legacy systemen en plan middleware voor verificatie en revocation.

---

## Conclusie  
Een EU Digital Identity Wallet biedt een praktische, privacy-bewuste manier om digitale bewijzen te beheren en te delen. Voor succes heb je naast goede technologie ook aandacht voor adoptie, governance en heldere gebruikersflows nodig. Ontwerp daarom privacy-first, steun standaarden en ontwikkel in fases met een concrete eerste use-case.
