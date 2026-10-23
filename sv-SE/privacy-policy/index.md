---
layout: default
title: "Integritetspolicy"
permalink: /sv-SE/privacy-policy/
lang: sv-SE
---

*Detta är en översättning. Vid skillnader gäller den [engelska versionen](https://etcho.github.io/poopify-legal/privacy-policy/).*

# Poopify - Integritetspolicy

**Gäller från:** 21 oktober 2026
**Version:** 1.0

Den här integritetspolicyn förklarar vilka personuppgifter appen Poopify (”Appen”) behandlar, varför och vilka rättigheter du har. Den gäller Appen på alla enheter och den valfria tjänsten Molnsynkronisering.

## Sammanfattning

- **Som standard lämnar dina hälsodata aldrig din enhet.** I Lokalt läge sparas allt du loggar (tarmtömningar, menscykel, symtom, anteckningar, profiler) bara på din telefon. Vi tar inte emot det.
- **Molnsynkronisering är valfri.** Om du slår på den och ger ditt uttryckliga samtycke sparas en kopia av dina loggar i molnet (Google Firebase, i Europeiska unionen) så att de kan synkroniseras mellan dina enheter. Molnsynkronisering görs tillgänglig stegvis och **är kanske inte tillgänglig i alla regioner**.
- **Vi säljer aldrig dina data, använder aldrig dina hälsodata för annonser och delar dem aldrig med någon för deras egna syften.**
- Appen visar annonser och använder Googles verktyg för analys och kraschrapporter. Dessa tjänster tar emot enhetsidentifierare och information om hur Appen används, **men inte innehållet i dina hälsodata.**
- Du kan när som helst stänga av Molnsynkronisering, exportera dina data eller radera ditt molnkonto, direkt i Appen (Meny > Integritet).

---

## 1. Vem som ansvarar för dina uppgifter

Personuppgiftsansvarig för dina personuppgifter är:

Everton Carvalho Leite, oberoende utvecklare, Rio de Janeiro, Brasilien
E-post: **poopify.dev@gmail.com**

- **Kontakt för dataskydd / Encarregado (LGPD):** Everton Carvalho Leite, poopify.dev@gmail.com

## 2. Data som bara sparas på din enhet (Lokalt läge)

När du använder Appen utan Molnsynkronisering sparas följande data **bara på din enhet**, i Appens privata lagring:
- loggarna du anger: datum och tid, avföringens egenskaper, symtom, smärta, anteckningar om läkemedel och mat, hygienmetod, information om menscykeln, fria anteckningar;
- profilerna du skapar (namn, ikon, valfritt födelsedatum) och Appens inställningar.

Vi har inte tillgång till dessa data. De skickas inte till oss eller till tredje part, utom i följande fall som du själv styr:
- **Export och delning:** när du exporterar en säkerhetskopia, CSV, JSON eller PDF skapas filen på din enhet och skickas bara dit du väljer att dela den.
- **Säkerhetskopia av Android-enheten:** beroende på enhetens inställningar kan Android ta med Appens data i enhetens egen säkerhetskopia på ditt Google-konto. Den säkerhetskopian hanteras av Google och enhetens inställningar, inte av oss.

## 3. Molnsynkronisering (valfri)

Molnsynkronisering är en valfri funktion som görs tillgänglig stegvis. Den **är kanske inte tillgänglig i alla länder eller regioner**, och där den inte är tillgänglig visar Appen den inte.

### 3.1 Vad vi behandlar
Om du slår på Molnsynkronisering behandlar vi:
- **Kontouppgifter:** en unik kontoidentifierare och e-postadressen för kontot du loggar in med (till exempel ditt Google-konto), som hanteras av Firebase Authentication.
- **Dina hälsodata:** en kopia av loggarna och profilerna som beskrivs i avsnitt 2, **utom platsdata**.
- **Tekniska synkroniseringsdata:** en enhetsidentifierare som skapas av Appen, tidsstämplar för ändringar och synkroniseringsstatus.
- **Registrering av samtycke:** den version av denna integritetspolicy och av användarvillkoren som du godkände, och när.
- **Integritetssignaler för Appen:** information som bekräftar att förfrågningar kommer från en äkta kopia av Appen (Firebase App Check med Google Play Integrity).

### 3.2 Syfte och rättslig grund
- **Syfte:** endast att spara dina loggar, synkronisera dem mellan enheterna som är inloggade på ditt konto och låta dig återställa dem på en ny enhet.
- **Rättslig grund:** ditt **uttryckliga samtycke** (GDPR art. 6.1 a och art. 9.2 a; LGPD art. 7, I och art. 11, I; och motsvarande regler i andra jurisdiktioner). Konto- och tekniska uppgifter behandlas eftersom de krävs för att tillhandahålla tjänsten du begärt (GDPR art. 6.1 b; LGPD art. 7, V).
- Du kan **när som helst återkalla ditt samtycke** genom att radera dina data i molnet i Appen (avsnitt 9). Att bara stänga av Molnsynkronisering stoppar endast synkroniseringen: kopian som redan finns i molnet ligger kvar tills du raderar den, och Appen erbjuder dig att radera den när du stänger av synkroniseringen. Återkallelsen påverkar inte behandling som skett dessförinnan.
- Vi använder **inte** dina molndata för analys, annonser, profilering, forskning, träning av artificiell intelligens eller något annat syfte än att tillhandahålla Molnsynkronisering till dig.

### 3.3 Var dina data lagras
Data för Molnsynkronisering lagras på Google Clouds servrar i **Europeiska unionen** (Firestore-multiregionen ”eur3”). Google är vårt personuppgiftsbiträde enligt Firebases villkor för databehandling och säkerhet.

### 3.4 Vem som har åtkomst
- **Via Appen bara ditt konto.** Säkerhetsregler på servrarna hindrar alla andra konton från att läsa eller skriva dina data.
- **Utvecklaren, bara i undantagsfall.** Data är krypterade vid överföring och i lagring, men inte end-to-end: tekniskt sett kan de ses via tjänstens administrationskonsol. Den konsolen är begränsad till utvecklarens konto, skyddad med tvåstegsverifiering, och åtkomsten loggas. Vi tittar på dina molndata bara om du uttryckligen ber oss om hjälp med ditt konto, eller om lagen kräver det.
- **Google**, som vår infrastrukturleverantör, behandlar data bara för att lagra dem åt oss.

### 3.5 Tillgänglighet per region
Molnsynkronisering kan vara otillgänglig i vissa länder eller regioner av rättsliga eller tekniska skäl. Om den inte längre är tillgänglig där du befinner dig stoppas synkroniseringen, data på dina enheter påverkas inte, och du kan fortfarande när som helst radera ditt molnkonto och dina molndata under Meny > Integritet.

## 4. Annonser

- Appen visar annonser från **Google AdMob**. AdMob kan behandla din enhets annonsidentifierare, din IP-adress och information om visade och klickade annonser.
- I Europeiska ekonomiska samarbetsområdet, Storbritannien, Schweiz och där lagen annars kräver det ber vi om ditt samtycke innan annonser anpassas, med Googles samtyckesverktyg. Du kan när som helst ändra ditt val i Appens meny, under **Integritetsalternativ för annonser** (visas där valet gäller).
- På Android kan du också återställa eller radera din annonsidentifierare i enhetens inställningar.
- **Innehållet i dina hälsodata delas aldrig med AdMob och används aldrig för att välja annonser.**
- Om du köper ”Ta bort annonser” visas inga fler annonser.
- Mer information: https://policies.google.com/technologies/partner-sites

## 5. Analys och kraschrapporter

- Vi använder **Google Analytics för Firebase** för att förstå hur Appen används (till exempel vilka skärmar som öppnas och vilka funktioner som används) och **Firebase Crashlytics** för att ta emot rapporter om krascher och fel.
- Dessa tjänster behandlar en identifierare för Appens installation, information om enheten och operativsystemet, ungefärlig plats som härleds från IP-adressen (land och region) och användningshändelser.
- Användningshändelser registrerar **att** en funktion användes (till exempel ”en logg skapades”), **aldrig innehållet** i det du loggade.
- **Rättslig grund:** vårt berättigade intresse av att hålla Appen fungerande och förbättra den (GDPR art. 6.1 f; LGPD art. 7, IX), eller ditt samtycke där lagen kräver det.
- Analytics är kopplat till Google AdMob bara för att mäta prestanda och intäkter för annonserna som visas i Appen. **Analytics-data används inte för att anpassa annonser** (annonsanpassning och Google Signals är avstängda i våra Analytics-inställningar) och delas inte med andra annonspartner.
- **Lagringstid:** händelsedata i Analytics sparas i 2 månader och användarbaserade Analytics-data i upp till 14 månader. Kraschrapporter sparas i upp till 90 dagar.

## 6. Köp

Köp (som ”Ta bort annonser”) hanteras av **Google Play**. Vi tar bara emot den information som behövs för att bekräfta köpet (till exempel en köptoken och status). Vi tar inte emot dina betalningsuppgifter. Googles integritetspolicy gäller för betalningen.

## 7. Supportmejl

Om du mejlar oss behandlar vi din e-postadress och innehållet i ditt meddelande bara för att svara dig, och vi sparar konversationen som historik för vår support tills du ber oss radera den. Skicka helst inte hälsoinformation via e-post om det inte behövs.

## 8. Vilka vi delar data med

Vi säljer inte personuppgifter och ”delar” dem inte för beteendebaserad annonsering över olika sammanhang.

Vi använder följande tjänsteleverantörer (personuppgiftsbiträden), som behandlar data för vår räkning och enligt våra instruktioner, eller som självständigt personuppgiftsansvariga där det anges:

| Leverantör | Tjänst | Data | Roll |
|---|---|---|---|
| Google (Firebase Authentication, Cloud Firestore, App Check) | Molnsynkronisering | Konto, data för Molnsynkronisering | Personuppgiftsbiträde |
| Google (Analytics för Firebase, Crashlytics) | Analys och kraschrapporter | Användningshändelser, enhetsdata, identifierare | Personuppgiftsbiträde |
| Google (AdMob) | Annonser | Annonsidentifierare, IP, interaktioner med annonser | Självständigt ansvarig för annonserna, se avsnitt 4 |
| Google (Google Play) | Köp | Köpdata | Självständigt ansvarig |

Vi kan också lämna ut data när lagen kräver det, eller för att skydda användarnas eller Appens rättigheter, säkerhet eller integritet, men bara i den utsträckning som är absolut nödvändig, och vi meddelar dig när lagen tillåter det.

## 9. Dina val och rättigheter

### 9.1 Alltid tillgängligt i Appen
- **Stänga av Molnsynkronisering:** dina data finns kvar på din enhet och Appen fortsätter att fungera i Lokalt läge.
- **Radera ditt molnkonto och dina molndata:** i Appen (Meny > Integritet > Radera ett konto för molnsynkronisering, eller Meny > Molnsynkronisering > Radera molnkonto och data), eller på [https://etcho.github.io/poopify-legal/sv-SE/delete-account/](https://etcho.github.io/poopify-legal/sv-SE/delete-account/).
- **Exportera dina data** (SQL-säkerhetskopia, CSV, JSON, PDF), för åtkomst och dataportabilitet.
- **Rätta eller radera loggar** direkt i Appen.

### 9.2 Dina rättigheter
Beroende på var du bor kan du ha rätt till: tillgång till dina uppgifter; rättelse; radering; begränsning av eller invändning mot behandlingen; dataportabilitet; att återkalla samtycke; att inte bli föremål för beslut som enbart grundas på automatiserad behandling; och information om vilka uppgifterna delas med.
- **Europeiska unionen / EES / Storbritannien (GDPR / UK GDPR):** alla rättigheter ovan. Du kan också lämna klagomål till dataskyddsmyndigheten i ditt land.
- **Brasilien (LGPD, art. 18):** bekräftelse på behandling, tillgång, rättelse, anonymisering, blockering eller radering av onödiga uppgifter, dataportabilitet, radering av uppgifter som behandlats med samtycke, information om delning, information om möjligheten att neka samtycke och följderna av det, samt återkallelse av samtycke. Du kan också lämna klagomål till ANPD (den brasilianska dataskyddsmyndigheten).
- **USA:** se avsnitt 11 och 12.
- **Andra länder:** vi respekterar motsvarande rättigheter enligt din lokala lagstiftning.

För att utöva en rättighet som inte finns direkt i Appen, mejla **poopify.dev@gmail.com**. Vi svarar inom den tid som lagen kräver för varje typ av begäran (till exempel upp till 15 dagar för fullständig bekräftelse och tillgång till dina uppgifter enligt LGPD, och en månad enligt GDPR, som GDPR i vissa fall tillåter att förlänga). Vi kan behöva kontrollera att begäran kommer från kontoinnehavaren.

## 10. Hur länge vi sparar data

| Data | Lagringstid |
|---|---|
| Data i Lokalt läge | På din enhet, tills du raderar dem eller avinstallerar Appen |
| Data för Molnsynkronisering | Tills du raderar ditt molnkonto eller dina molndata; eller senast tills kontot inte har använts av någon enhet på 24 månader i följd; eller tills Molnsynkronisering upphör. I inget av dessa fall påverkas data på dina enheter |
| Raderade molndata | Tas bort från våra aktiva system omedelbart; kvarvarande kopior i Googles säkerhetskopieringssystem raderas inom de tider som anges i Google Clouds villkor för radering av data |
| Registreringar av samtycke (vilka versioner av dessa dokument du godkänt, och när) | Sparas med ditt konto för molnsynkronisering och raderas tillsammans med det, eller när du raderar dina molndata |
| Analys / kraschrapporter | Se avsnitt 5 |
| Supportmejl | Se avsnitt 7 |

## 11. Ytterligare information för invånare i USA

- **Insamlade kategorier:** identifierare (konto-ID, ID för Appens installation, annonsidentifierare, IP-adress); internet- eller elektronisk aktivitet (användningshändelser i Appen); ungefärlig geografisk plats (från IP, för analys); **känsliga personuppgifter / konsumenters hälsodata** (bara med Molnsynkronisering, se avsnitt 12); kommersiell information (köpstatus).
- Vi säljer inte personuppgifter och delar dem inte för beteendebaserad annonsering över olika sammanhang, och har inte gjort det de senaste 12 månaderna.
- Vi använder känsliga personuppgifter bara för att tillhandahålla tjänsten du begärt, så rätten att begränsa användningen tillämpas som standard.
- **Kalifornien, Colorado, Connecticut, Virginia, Oregon, Texas och andra delstater med konsumentintegritetslagar:** du har rätt att få veta om, få tillgång till, rätta och radera dina personuppgifter, och att inte diskrimineras för att du utövar dessa rättigheter. Du kan överklaga varje beslut om din begäran genom att svara på vårt svar.
- Vi samlar inte medvetet in personuppgifter från barn under 13 år via konton för molnsynkronisering (se avsnitt 13).

## 12. Integritetspolicy för konsumenters hälsodata (Washington, Nevada, Connecticut och liknande lagar)

{% include sv-SE/consumer-health-data.md %}

## 13. Barn

- Appen är en personlig hälsodagbok och riktar sig inte till barn.
- **Konton för molnsynkronisering är bara för vuxna** (18 år eller myndighetsåldern där du bor).
- Föräldrar och vårdnadshavare kan använda Appen för att föra loggar om sina barn, i separata profiler. I så fall ansvarar föräldern eller vårdnadshavaren för informationen och samtycker för barnets räkning.
- Om du tror att ett barn har skapat ett konto för molnsynkronisering, kontakta oss så raderar vi det.

## 14. Säkerhet

Vi skyddar dina data med tekniska och organisatoriska åtgärder som står i proportion till deras känslighet, bland annat:
- kryptering vid överföring (TLS) och i lagring;
- serverregler som bara ger varje konto åtkomst till sina egna data;
- kontroll av att förfrågningar kommer från den äkta Appen;
- begränsad administrativ åtkomst som skyddas med tvåstegsverifiering och loggas;
- dataminimering (till exempel synkroniseras platsdata aldrig);
- automatiska tester av våra säkerhetsregler.

Inget system är helt säkert. Om en säkerhetsincident påverkar dina personuppgifter meddelar vi behöriga myndigheter och dig, när och på det sätt som lagen kräver (till exempel inom 72 timmar till tillsynsmyndigheten enligt GDPR).

## 15. Internationella överföringar

Vi har vår bas i Brasilien, och våra leverantörer kan behandla data i andra länder. Data för Molnsynkronisering lagras i Europeiska unionen. När personuppgifter överförs till andra länder förlitar vi oss på lämpliga skyddsåtgärder, som Europeiska kommissionens standardavtalsklausuler, ramverket för dataskydd mellan EU och USA (Data Privacy Framework) där det är tillämpligt, och mekanismerna i art. 33 i LGPD, så som Google erbjuder dem i sina villkor för databehandling.

## 16. Ändringar i denna policy

Vi meddelar dig i Appen om väsentliga ändringar innan de börjar gälla. Om en ändring påverkar hur vi behandlar data för Molnsynkronisering ber vi om ditt samtycke igen. Tidigare versioner finns kvar på adressen till den engelska versionen följd av versionsnumret (till exempel https://etcho.github.io/poopify-legal/privacy-policy/1.0/).

Denna policy kan översättas till andra språk. Vid motstridigheter mellan en översättning och den engelska versionen gäller den engelska versionen, om inte lagen i ditt land föreskriver något annat.

## 17. Kontakt

E-post: **poopify.dev@gmail.com**

## Versionshistorik

| Version | Gäller från | Ändringar |
|---|---|---|
| 1.0 | 21 oktober 2026 | Första versionen |
