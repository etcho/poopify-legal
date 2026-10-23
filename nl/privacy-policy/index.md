---
layout: default
title: "Privacybeleid"
permalink: /nl/privacy-policy/
lang: nl
---

*Dit is een vertaling. Bij verschillen geldt de [Engelse versie](https://etcho.github.io/poopify-legal/privacy-policy/).*

# Poopify - Privacybeleid

**Ingangsdatum:** 21 oktober 2026
**Versie:** 1.0

Dit Privacybeleid legt uit welke persoonsgegevens de app Poopify (de "App") verwerkt, waarom, en welke rechten je hebt. Het geldt voor de App op alle apparaten en voor de optionele dienst Cloudsynchronisatie.

## Samenvatting

- **Standaard verlaten je gezondheidsgegevens je apparaat nooit.** In de Lokale modus wordt alles wat je vastlegt (ontlasting, menstruatiecyclus, symptomen, notities, profielen) alleen op je telefoon opgeslagen. Wij ontvangen het niet.
- **Cloudsynchronisatie is optioneel.** Als je het aanzet en uitdrukkelijk toestemming geeft, wordt een kopie van je gegevens in de cloud opgeslagen (Google Firebase, in de Europese Unie), zodat die tussen je apparaten kan worden gesynchroniseerd. Cloudsynchronisatie wordt geleidelijk beschikbaar gemaakt en is **mogelijk niet in alle regio's beschikbaar**.
- **We verkopen je gegevens nooit, gebruiken je gezondheidsgegevens nooit voor advertenties en delen ze nooit met anderen voor hun eigen doeleinden.**
- De App toont advertenties en gebruikt analyse- en crashrapportagediensten van Google. Deze diensten ontvangen apparaat-ID's en informatie over het gebruik van de App, **maar niet de inhoud van je gezondheidsgegevens.**
- Je kunt Cloudsynchronisatie op elk moment uitzetten, je gegevens exporteren of je cloudaccount verwijderen, rechtstreeks in de App (Menu > Privacy).

---

## 1. Wie verantwoordelijk is voor je gegevens

De verwerkingsverantwoordelijke voor je persoonsgegevens is:

Everton Carvalho Leite, onafhankelijke ontwikkelaar, Rio de Janeiro, Brazilië
E-mail: **poopify.dev@gmail.com**

- **Contactpersoon gegevensbescherming / Encarregado (LGPD):** Everton Carvalho Leite, poopify.dev@gmail.com

## 2. Gegevens die alleen op je apparaat worden opgeslagen (Lokale modus)

Als je de App zonder Cloudsynchronisatie gebruikt, worden de volgende gegevens **alleen op je apparaat** opgeslagen, in de privéopslag van de App:
- de gegevens die je invoert: datum en tijd, kenmerken van de ontlasting, symptomen, pijn, notities over medicijnen en eten, hygiënemethode, informatie over de menstruatiecyclus, vrije notities;
- de profielen die je aanmaakt (naam, pictogram, optionele geboortedatum) en de instellingen van de App.

Wij hebben geen toegang tot deze gegevens. Ze worden niet naar ons of naar derden gestuurd, behalve in de volgende gevallen, die jij zelf bepaalt:
- **Exporteren en delen:** als je een back-up, CSV, JSON of PDF exporteert, wordt het bestand op je apparaat gemaakt en alleen gestuurd naar waar jij het deelt.
- **Back-up van je Android-apparaat:** afhankelijk van je apparaatinstellingen kan Android de gegevens van de App opnemen in de back-up van het apparaat in je Google-account. Die back-up wordt beheerd door Google en je apparaatinstellingen, niet door ons.

## 3. Cloudsynchronisatie (optioneel)

Cloudsynchronisatie is een optionele functie die geleidelijk beschikbaar wordt gemaakt. Ze is **mogelijk niet in alle landen of regio's beschikbaar**, en waar ze niet beschikbaar is, toont de App haar niet.

### 3.1 Wat we verwerken
Als je Cloudsynchronisatie aanzet, verwerken we:
- **Accountgegevens:** een unieke account-ID en het e-mailadres van het account waarmee je inlogt (bijvoorbeeld je Google-account), beheerd door Firebase Authentication.
- **Je gezondheidsgegevens:** een kopie van de gegevens en profielen beschreven in Sectie 2, **zonder locatiegegevens**.
- **Technische synchronisatiegegevens:** een door de App gegenereerde apparaat-ID, tijdstippen van wijzigingen en de synchronisatiestatus.
- **Registratie van toestemming:** de versie van dit Privacybeleid en van de Gebruiksvoorwaarden die je hebt geaccepteerd, en wanneer.
- **Integriteitssignalen van de App:** informatie die bevestigt dat verzoeken afkomstig zijn van een echte kopie van de App (Firebase App Check met Google Play Integrity).

### 3.2 Waarvoor en op welke rechtsgrond
- **Doel:** alleen je gegevens opslaan, ze synchroniseren tussen de apparaten die met je account zijn ingelogd en je in staat stellen ze op een nieuw apparaat terug te zetten.
- **Rechtsgrond:** je **uitdrukkelijke toestemming** (AVG art. 6, lid 1, sub a en art. 9, lid 2, sub a; LGPD art. 7, I en art. 11, I; en gelijkwaardige regels in andere rechtsgebieden). Account- en technische gegevens worden verwerkt omdat ze nodig zijn om de dienst te leveren waarom je hebt gevraagd (AVG art. 6, lid 1, sub b; LGPD art. 7, V).
- Je kunt je **toestemming op elk moment intrekken** door je gegevens in de cloud te verwijderen in de App (Sectie 9). Alleen Cloudsynchronisatie uitzetten stopt de synchronisatie: de kopie die al in de cloud staat, blijft daar tot je die verwijdert, en de App biedt aan die te verwijderen als je de synchronisatie uitzet. Intrekking heeft geen invloed op verwerking die daarvoor plaatsvond.
- We gebruiken je cloudgegevens **niet** voor analyse, advertenties, profilering, onderzoek, het trainen van kunstmatige intelligentie of enig ander doel dan het leveren van Cloudsynchronisatie aan jou.

### 3.3 Waar je gegevens worden opgeslagen
Gegevens van Cloudsynchronisatie worden opgeslagen op servers van Google Cloud in de **Europese Unie** (Firestore-multiregio "eur3"). Google treedt op als onze verwerker onder de voorwaarden voor gegevensverwerking en beveiliging van Firebase.

### 3.4 Wie er toegang toe heeft
- **Via de App alleen jouw account.** Beveiligingsregels op de servers voorkomen dat een ander account je gegevens leest of schrijft.
- **De ontwikkelaar, alleen in uitzonderlijke gevallen.** De gegevens zijn versleuteld tijdens verzending en in opslag, maar niet end-to-end: technisch kunnen ze worden bekeken via de beheerconsole van de dienst. Die console is beperkt tot het account van de ontwikkelaar, beveiligd met verificatie in twee stappen, en de toegang wordt vastgelegd. We bekijken je cloudgegevens alleen als je ons uitdrukkelijk om hulp met je account vraagt, of als de wet ons daartoe verplicht.
- **Google** verwerkt de gegevens als onze infrastructuurleverancier alleen om ze namens ons te hosten.

### 3.5 Beschikbaarheid per regio
Cloudsynchronisatie kan in sommige landen of regio's om juridische of technische redenen niet beschikbaar zijn. Als ze niet meer beschikbaar is waar jij bent, stopt de synchronisatie, blijven de gegevens op je apparaten ongewijzigd en kun je je cloudaccount en cloudgegevens nog steeds op elk moment verwijderen via Menu > Privacy.

## 4. Advertenties

- De App toont advertenties van **Google AdMob**. AdMob kan de advertentie-ID van je apparaat, je IP-adres en informatie over getoonde en aangeklikte advertenties verwerken.
- In de Europese Economische Ruimte, het Verenigd Koninkrijk, Zwitserland en waar de wet het verder vereist, vragen we je toestemming voordat advertenties worden gepersonaliseerd, met de toestemmingstool van Google. Je kunt je keuze op elk moment wijzigen in het menu van de App, onder **Privacyopties voor advertenties** (getoond waar deze keuze van toepassing is).
- Op Android kun je je advertentie-ID ook resetten of verwijderen in de instellingen van je apparaat.
- **De inhoud van je gezondheidsgegevens wordt nooit met AdMob gedeeld of gebruikt om advertenties te kiezen.**
- Als je "Advertenties verwijderen" koopt, worden er geen advertenties meer getoond.
- Meer informatie: https://policies.google.com/technologies/partner-sites

## 5. Analyse en crashrapporten

- We gebruiken **Google Analytics voor Firebase** om te begrijpen hoe de App wordt gebruikt (bijvoorbeeld welke schermen worden geopend en welke functies worden gebruikt) en **Firebase Crashlytics** om rapporten over crashes en fouten te ontvangen.
- Deze diensten verwerken een installatie-ID van de App, informatie over het apparaat en het besturingssysteem, de bij benadering bepaalde locatie op basis van het IP-adres (land en regio) en gebruiksgebeurtenissen.
- Gebruiksgebeurtenissen leggen vast **dat** een functie is gebruikt (bijvoorbeeld "er is een gegeven aangemaakt"), **nooit de inhoud** van wat je hebt vastgelegd.
- **Rechtsgrond:** ons gerechtvaardigd belang om de App werkend te houden en te verbeteren (AVG art. 6, lid 1, sub f; LGPD art. 7, IX), of je toestemming waar de wet dat vereist.
- Analytics is alleen aan Google AdMob gekoppeld om de prestaties en opbrengsten van de advertenties in de App te meten. **Analytics-gegevens worden niet gebruikt om advertenties te personaliseren** (advertentiepersonalisatie en Google Signals staan uit in onze Analytics-instellingen) en worden niet gedeeld met andere advertentiepartners.
- **Bewaartermijn:** gebeurtenisgegevens van Analytics worden 2 maanden bewaard en Analytics-gegevens op gebruikersniveau tot 14 maanden. Crashrapporten worden tot 90 dagen bewaard.

## 6. Aankopen

Aankopen (zoals "Advertenties verwijderen") worden verwerkt door **Google Play**. We ontvangen alleen de informatie die nodig is om de aankoop te bevestigen (zoals een aankooptoken en de status). We ontvangen je betaalgegevens niet. Op de betaling is het privacybeleid van Google van toepassing.

## 7. Supportmails

Als je ons mailt, verwerken we je e-mailadres en de inhoud van je bericht alleen om je te antwoorden, en bewaren we het gesprek als geschiedenis van onze support, tot je ons vraagt het te verwijderen. Stuur alsjeblieft geen gezondheidsinformatie per e-mail, tenzij dat nodig is.

## 8. Met wie we gegevens delen

We verkopen geen persoonsgegevens en "delen" ze niet voor contextoverschrijdende gedragsgerichte advertenties.

We gebruiken de volgende dienstverleners (verwerkers), die gegevens namens ons en volgens onze instructies verwerken, of als zelfstandige verwerkingsverantwoordelijken waar aangegeven:

| Aanbieder | Dienst | Gegevens | Rol |
|---|---|---|---|
| Google (Firebase Authentication, Cloud Firestore, App Check) | Cloudsynchronisatie | Account, gegevens van Cloudsynchronisatie | Verwerker |
| Google (Analytics voor Firebase, Crashlytics) | Analyse en crashrapporten | Gebruiksgebeurtenissen, apparaatgegevens, ID's | Verwerker |
| Google (AdMob) | Advertenties | Advertentie-ID, IP, interacties met advertenties | Zelfstandige verwerkingsverantwoordelijke voor advertenties, zie Sectie 4 |
| Google (Google Play) | Aankopen | Aankoopgegevens | Zelfstandige verwerkingsverantwoordelijke |

We kunnen gegevens ook verstrekken als de wet dat vereist, of om de rechten, veiligheid of integriteit van gebruikers of van de App te beschermen, maar alleen voor zover strikt noodzakelijk, en we laten het je weten als de wet dat toestaat.

## 9. Je keuzes en rechten

### 9.1 Altijd beschikbaar in de App
- **Cloudsynchronisatie uitzetten:** je gegevens blijven op je apparaat en de App blijft werken in de Lokale modus.
- **Je cloudaccount en cloudgegevens verwijderen:** in de App (Menu > Privacy > Een account voor cloudsynchronisatie verwijderen, of Menu > Cloudsynchronisatie > Cloudaccount en gegevens verwijderen), of via [https://etcho.github.io/poopify-legal/nl/delete-account/](https://etcho.github.io/poopify-legal/nl/delete-account/).
- **Je gegevens exporteren** (SQL-back-up, CSV, JSON, PDF), voor inzage en overdraagbaarheid.
- **Gegevens corrigeren of verwijderen**, rechtstreeks in de App.

### 9.2 Je rechten
Afhankelijk van waar je woont, heb je mogelijk het recht op: inzage in je gegevens; rectificatie; verwijdering; beperking van of bezwaar tegen de verwerking; overdraagbaarheid van gegevens; intrekking van toestemming; het niet onderworpen worden aan uitsluitend geautomatiseerde besluiten; en informatie over met wie gegevens worden gedeeld.
- **Europese Unie / EER / Verenigd Koninkrijk (AVG / UK GDPR):** alle bovenstaande rechten. Je kunt ook een klacht indienen bij de gegevensbeschermingsautoriteit van je land.
- **Brazilië (LGPD, art. 18):** bevestiging van de verwerking, inzage, correctie, anonimisering, blokkering of verwijdering van onnodige gegevens, overdraagbaarheid, verwijdering van gegevens die met toestemming zijn verwerkt, informatie over het delen, informatie over de mogelijkheid om toestemming te weigeren en de gevolgen daarvan, en intrekking van toestemming. Je kunt ook een klacht indienen bij de ANPD (de Braziliaanse gegevensbeschermingsautoriteit).
- **Verenigde Staten:** zie Secties 11 en 12.
- **Andere landen:** we respecteren gelijkwaardige rechten volgens je lokale wetgeving.

Om een recht uit te oefenen dat niet rechtstreeks in de App beschikbaar is, mail je naar **poopify.dev@gmail.com**. We antwoorden binnen de wettelijke termijn voor elk type verzoek (bijvoorbeeld tot 15 dagen voor een volledige bevestiging en inzage in je gegevens volgens de LGPD, en één maand volgens de AVG, die de AVG in sommige gevallen laat verlengen). Mogelijk moeten we controleren of het verzoek van de accounthouder komt.

## 10. Hoe lang we gegevens bewaren

| Gegevens | Bewaartermijn |
|---|---|
| Gegevens van de Lokale modus | Op je apparaat, tot je ze verwijdert of de App verwijdert |
| Gegevens van Cloudsynchronisatie | Tot je je cloudaccount of cloudgegevens verwijdert; of uiterlijk tot het account 24 maanden achter elkaar door geen enkel apparaat is gebruikt; of tot Cloudsynchronisatie wordt beëindigd. In geen van deze gevallen worden de gegevens op je apparaten geraakt |
| Verwijderde cloudgegevens | Direct uit onze actieve systemen verwijderd; restkopieën in de back-upsystemen van Google worden verwijderd binnen de termijnen van de voorwaarden voor gegevensverwijdering van Google Cloud |
| Registraties van toestemming (welke versies van deze documenten je hebt geaccepteerd, en wanneer) | Bewaard bij je account voor cloudsynchronisatie en samen daarmee verwijderd, of wanneer je je cloudgegevens verwijdert |
| Analyse / crashrapporten | Zie Sectie 5 |
| Supportmails | Zie Sectie 7 |

## 11. Aanvullende informatie voor inwoners van de Verenigde Staten

- **Verzamelde categorieën:** identificatoren (account-ID, installatie-ID van de App, advertentie-ID, IP-adres); internet- of elektronische activiteit (gebruiksgebeurtenissen van de App); geschatte geolocatie (op basis van het IP, voor analyse); **gevoelige persoonsgegevens / gezondheidsgegevens van consumenten** (alleen met Cloudsynchronisatie, zie Sectie 12); commerciële informatie (aankoopstatus).
- We verkopen geen persoonsgegevens en delen ze niet voor contextoverschrijdende gedragsgerichte advertenties, en hebben dat de afgelopen 12 maanden ook niet gedaan.
- We gebruiken gevoelige persoonsgegevens alleen om de dienst te leveren waarom je hebt gevraagd, dus het recht om het gebruik ervan te beperken wordt standaard toegepast.
- **Californië, Colorado, Connecticut, Virginia, Oregon, Texas en andere staten met wetten op de privacy van consumenten:** je hebt het recht om je persoonsgegevens te kennen, in te zien, te corrigeren en te verwijderen, en om niet te worden gediscrimineerd omdat je deze rechten uitoefent. Je kunt tegen elk besluit over je verzoek in beroep gaan door op ons antwoord te reageren.
- We verzamelen niet bewust persoonsgegevens van kinderen jonger dan 13 jaar via accounts voor cloudsynchronisatie (zie Sectie 13).

## 12. Privacybeleid voor gezondheidsgegevens van consumenten (Washington, Nevada, Connecticut en vergelijkbare wetten)

{% include nl/consumer-health-data.md %}

## 13. Kinderen

- De App is een persoonlijk gezondheidsdagboek en is niet gericht op kinderen.
- **Accounts voor cloudsynchronisatie zijn alleen voor volwassenen** (18 jaar of de meerderjarigheidsleeftijd waar je woont).
- Ouders en voogden kunnen de App gebruiken om gegevens over hun kinderen bij te houden, in aparte profielen. In dat geval is de ouder of voogd verantwoordelijk voor die informatie en geeft die toestemming namens het kind.
- Als je denkt dat een kind een account voor cloudsynchronisatie heeft aangemaakt, neem dan contact met ons op en we verwijderen het.

## 14. Beveiliging

We beschermen je gegevens met technische en organisatorische maatregelen die passen bij hun gevoeligheid, waaronder:
- versleuteling tijdens verzending (TLS) en in opslag;
- serverregels die elk account alleen toegang geven tot zijn eigen gegevens;
- controle of verzoeken afkomstig zijn van de echte App;
- beperkte beheertoegang, beveiligd met verificatie in twee stappen en vastgelegd;
- dataminimalisatie (locatiegegevens worden bijvoorbeeld nooit gesynchroniseerd);
- geautomatiseerde tests van onze beveiligingsregels.

Geen enkel systeem is volledig veilig. Als een beveiligingsincident je persoonsgegevens treft, informeren we de bevoegde autoriteiten en jou, wanneer en zoals de wet vereist (bijvoorbeeld binnen 72 uur de toezichthoudende autoriteit volgens de AVG).

## 15. Internationale doorgifte

We zijn gevestigd in Brazilië, en onze dienstverleners kunnen gegevens in andere landen verwerken. Gegevens van Cloudsynchronisatie worden opgeslagen in de Europese Unie. Als persoonsgegevens naar andere landen worden doorgegeven, baseren we ons op passende waarborgen, zoals de modelcontractbepalingen van de Europese Commissie, het EU-VS-kader voor gegevensbescherming (Data Privacy Framework) waar van toepassing, en de mechanismen van art. 33 van de LGPD, zoals Google die aanbiedt in zijn voorwaarden voor gegevensverwerking.

## 16. Wijzigingen in dit beleid

We laten je in de App weten wanneer er belangrijke wijzigingen zijn, voordat ze ingaan. Als een wijziging invloed heeft op hoe we gegevens van Cloudsynchronisatie verwerken, vragen we je opnieuw om toestemming. Eerdere versies blijven beschikbaar op het adres van de Engelse versie, gevolgd door het versienummer (bijvoorbeeld https://etcho.github.io/poopify-legal/privacy-policy/1.0/).

Dit beleid kan in andere talen worden vertaald. Bij strijdigheid tussen een vertaling en de Engelse versie geldt de Engelse versie, tenzij de wet van je land anders bepaalt.

## 17. Contact

E-mail: **poopify.dev@gmail.com**

## Versiegeschiedenis

| Versie | Ingangsdatum | Wijzigingen |
|---|---|---|
| 1.0 | 21 oktober 2026 | Eerste versie |
