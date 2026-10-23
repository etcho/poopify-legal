---
layout: default
title: "Zásady ochrany osobních údajů"
permalink: /cs/privacy-policy/
lang: cs
---

*Toto je překlad. V případě rozporu má přednost [anglická verze](https://etcho.github.io/poopify-legal/privacy-policy/).*

# Poopify - Zásady ochrany osobních údajů

**Datum účinnosti:** 21. října 2026
**Verze:** 1.0

Tyto Zásady ochrany osobních údajů vysvětlují, jaké osobní údaje aplikace Poopify („Aplikace“) zpracovává, proč a jaká máte práva. Vztahují se na Aplikaci na všech zařízeních a na volitelnou službu Synchronizace s cloudem.

## Shrnutí

- **Ve výchozím nastavení vaše zdravotní záznamy nikdy neopustí vaše zařízení.** V Místním režimu je vše, co zaznamenáte (stolice, menstruační cyklus, příznaky, poznámky, profily), uloženo jen ve vašem telefonu. My to nedostáváme.
- **Synchronizace s cloudem je volitelná.** Pokud ji zapnete a udělíte výslovný souhlas, uloží se kopie vašich záznamů do cloudu (Google Firebase, v Evropské unii), aby je bylo možné synchronizovat mezi vašimi zařízeními. Synchronizace s cloudem se zpřístupňuje postupně a **nemusí být dostupná ve všech regionech**.
- **Vaše data nikdy neprodáváme, vaše zdravotní záznamy nikdy nepoužíváme pro reklamy a nikdy je s nikým nesdílíme pro jeho vlastní účely.**
- Aplikace zobrazuje reklamy a používá nástroje Google pro analýzu a hlášení pádů. Tyto služby dostávají identifikátory zařízení a informace o používání Aplikace, **ale ne obsah vašich zdravotních záznamů.**
- Synchronizaci s cloudem můžete kdykoli vypnout, svá data exportovat nebo smazat svůj cloudový účet, přímo v Aplikaci (Menu > Soukromí).

---

## 1. Kdo odpovídá za vaše údaje

Správcem vašich osobních údajů je:

Everton Carvalho Leite, nezávislý vývojář, Rio de Janeiro, Brazílie
E-mail: **poopify.dev@gmail.com**

- **Kontakt pro ochranu osobních údajů / Encarregado (LGPD):** Everton Carvalho Leite, poopify.dev@gmail.com

## 2. Údaje uložené jen ve vašem zařízení (Místní režim)

Když Aplikaci používáte bez Synchronizace s cloudem, jsou následující údaje uloženy **jen ve vašem zařízení**, v soukromém úložišti Aplikace:
- záznamy, které zadáte: datum a čas, vlastnosti stolice, příznaky, bolest, poznámky o lécích a jídle, způsob hygieny, informace o menstruačním cyklu, volné poznámky;
- profily, které vytvoříte (jméno, ikona, volitelné datum narození), a nastavení Aplikace.

K těmto údajům nemáme přístup. Nejsou zasílány nám ani třetím stranám, s výjimkou následujících případů, které máte pod kontrolou:
- **Export a sdílení:** když exportujete zálohu, soubor CSV, JSON nebo PDF, soubor se vytvoří ve vašem zařízení a odešle se jen tam, kam se ho rozhodnete sdílet.
- **Záloha zařízení s Androidem:** podle nastavení vašeho zařízení může Android zahrnout data Aplikace do zálohy zařízení ve vašem účtu Google. Tuto zálohu spravuje Google a nastavení vašeho zařízení, ne my.

## 3. Synchronizace s cloudem (volitelná)

Synchronizace s cloudem je volitelná funkce, která se zpřístupňuje postupně. **Nemusí být dostupná ve všech zemích nebo regionech**, a kde dostupná není, Aplikace ji nezobrazuje.

### 3.1 Co zpracováváme
Pokud zapnete Synchronizaci s cloudem, zpracováváme:
- **Údaje o účtu:** jedinečný identifikátor účtu a e-mailovou adresu účtu, kterým se přihlašujete (například účtu Google), spravované službou Firebase Authentication.
- **Vaše zdravotní záznamy:** kopii záznamů a profilů popsaných v oddíle 2, **bez údajů o poloze**.
- **Technické údaje o synchronizaci:** identifikátor zařízení vytvořený Aplikací, časy změn a stav synchronizace.
- **Záznam o souhlasu:** verzi těchto Zásad ochrany osobních údajů a Podmínek používání, kterou jste přijali, a kdy.
- **Signály integrity Aplikace:** informace potvrzující, že požadavky pocházejí z pravé kopie Aplikace (Firebase App Check s Google Play Integrity).

### 3.2 Účel a právní základ
- **Účel:** pouze ukládat vaše záznamy, synchronizovat je mezi zařízeními přihlášenými k vašemu účtu a umožnit vám je obnovit v novém zařízení.
- **Právní základ:** váš **výslovný souhlas** (GDPR čl. 6 odst. 1 písm. a) a čl. 9 odst. 2 písm. a); LGPD čl. 7, I a čl. 11, I; a obdobná pravidla v jiných jurisdikcích). Údaje o účtu a technické údaje se zpracovávají, protože jsou nezbytné k poskytnutí služby, o kterou žádáte (GDPR čl. 6 odst. 1 písm. b); LGPD čl. 7, V).
- Svůj **souhlas můžete kdykoli odvolat** smazáním svých dat v cloudu v Aplikaci (oddíl 9). Samotné vypnutí Synchronizace s cloudem jen zastaví synchronizaci: kopie, která už v cloudu je, tam zůstane, dokud ji nesmažete, a Aplikace vám při vypnutí synchronizace nabídne její smazání. Odvolání nemá vliv na zpracování, k němuž došlo předtím.
- Vaše data v cloudu **nepoužíváme** pro analýzu, reklamu, profilování, výzkum, trénování umělé inteligence ani k žádnému jinému účelu než k poskytování Synchronizace s cloudem vám.

### 3.3 Kde jsou vaše data uložena
Data Synchronizace s cloudem jsou uložena na serverech Google Cloud v **Evropské unii** (multiregion Firestore „eur3“). Google vystupuje jako náš zpracovatel podle Podmínek zpracování a zabezpečení dat služby Firebase.

### 3.4 Kdo k nim má přístup
- **Přes Aplikaci jen váš účet.** Bezpečnostní pravidla na serverech brání jakémukoli jinému účtu číst nebo zapisovat vaše data.
- **Vývojář jen ve výjimečných případech.** Data jsou šifrována při přenosu i v úložišti, ale ne koncově: technicky je lze zobrazit v administrační konzoli služby. Tato konzole je vyhrazena účtu vývojáře, chráněna dvoufázovým ověřením a přístupy do ní se zaznamenávají. Do vašich dat v cloudu se díváme jen tehdy, když nás výslovně požádáte o pomoc s účtem, nebo když nám to ukládá zákon.
- **Google** jako náš poskytovatel infrastruktury zpracovává data jen proto, aby je za nás hostoval.

### 3.5 Dostupnost podle regionu
Synchronizace s cloudem může být v některých zemích nebo regionech z právních nebo technických důvodů nedostupná. Pokud přestane být dostupná tam, kde jste, synchronizace se zastaví, data ve vašich zařízeních zůstanou beze změny a svůj cloudový účet i data v cloudu můžete stále kdykoli smazat v Menu > Soukromí.

## 4. Reklama

- Aplikace zobrazuje reklamy od **Google AdMob**. AdMob může zpracovávat reklamní identifikátor vašeho zařízení, vaši IP adresu a informace o zobrazených a kliknutých reklamách.
- V Evropském hospodářském prostoru, ve Spojeném království, ve Švýcarsku a všude, kde to vyžaduje zákon, vás před personalizací reklam žádáme o souhlas pomocí nástroje pro souhlas od Googlu. Svou volbu můžete kdykoli změnit v menu Aplikace, v položce **Možnosti ochrany soukromí u reklam** (zobrazuje se tam, kde tato volba platí).
- V Androidu můžete svůj reklamní identifikátor také resetovat nebo smazat v nastavení zařízení.
- **Obsah vašich zdravotních záznamů se nikdy nesdílí s AdMob ani se nepoužívá k výběru reklam.**
- Pokud si koupíte „Odebrat reklamy“, reklamy se přestanou zobrazovat.
- Více informací: https://policies.google.com/technologies/partner-sites

## 5. Analýza a hlášení pádů

- Používáme **Google Analytics pro Firebase**, abychom pochopili, jak se Aplikace používá (například které obrazovky se otevírají a které funkce se používají), a **Firebase Crashlytics** k přijímání hlášení o pádech a chybách.
- Tyto služby zpracovávají identifikátor instalace Aplikace, informace o zařízení a operačním systému, přibližnou polohu odvozenou z IP adresy (země a region) a události používání.
- Události používání zaznamenávají, **že** byla použita nějaká funkce (například „byl vytvořen záznam“), **nikdy obsah** toho, co jste zaznamenali.
- **Právní základ:** náš oprávněný zájem na udržení funkčnosti a zlepšování Aplikace (GDPR čl. 6 odst. 1 písm. f); LGPD čl. 7, IX), nebo váš souhlas tam, kde to zákon vyžaduje.
- Analytics je propojen s Google AdMob jen kvůli měření výkonu a příjmů z reklam zobrazených v Aplikaci. **Data z Analytics se nepoužívají k personalizaci reklam** (personalizace reklam a Google Signals jsou v našem nastavení Analytics vypnuté) a nesdílejí se s dalšími reklamními partnery.
- **Doba uchování:** data o událostech v Analytics se uchovávají 2 měsíce a data Analytics na úrovni uživatele až 14 měsíců. Hlášení o pádech se uchovávají až 90 dní.

## 6. Nákupy

Nákupy (například „Odebrat reklamy“) zpracovává **Google Play**. Dostáváme jen informace potřebné k potvrzení nákupu (například token a stav nákupu). Vaše platební údaje nedostáváme. Na platbu se vztahují zásady ochrany soukromí Googlu.

## 7. E-maily podpoře

Pokud nám napíšete, zpracováváme vaši e-mailovou adresu a obsah zprávy jen proto, abychom vám odpověděli, a konverzaci uchováváme jako historii naší podpory, dokud nás nepožádáte o její smazání. Zdravotní informace prosím e-mailem neposílejte, pokud to není nutné.

## 8. S kým údaje sdílíme

Osobní údaje neprodáváme a „nesdílíme“ je pro behaviorální reklamu napříč kontexty.

Využíváme následující poskytovatele služeb (zpracovatele), kteří zpracovávají údaje naším jménem a podle našich pokynů, nebo jako samostatní správci, pokud je to uvedeno:

| Poskytovatel | Služba | Údaje | Role |
|---|---|---|---|
| Google (Firebase Authentication, Cloud Firestore, App Check) | Synchronizace s cloudem | Účet, data Synchronizace s cloudem | Zpracovatel |
| Google (Analytics pro Firebase, Crashlytics) | Analýza a hlášení pádů | Události používání, údaje o zařízení, identifikátory | Zpracovatel |
| Google (AdMob) | Reklama | Reklamní identifikátor, IP, interakce s reklamami | Samostatný správce pro reklamy, viz oddíl 4 |
| Google (Google Play) | Nákupy | Údaje o nákupu | Samostatný správce |

Údaje můžeme také zpřístupnit, pokud to vyžaduje zákon, nebo k ochraně práv, bezpečnosti či integrity uživatelů nebo Aplikace, ale jen v nezbytně nutném rozsahu, a dáme vám vědět, pokud to zákon dovolí.

## 9. Vaše volby a práva

### 9.1 Kdykoli dostupné v Aplikaci
- **Vypnout Synchronizaci s cloudem:** vaše data zůstanou ve vašem zařízení a Aplikace dál funguje v Místním režimu.
- **Smazat svůj cloudový účet a data v cloudu:** v Aplikaci (Menu > Soukromí > Smazat účet synchronizace s cloudem, nebo Menu > Synchronizace s cloudem > Smazat účet a data v cloudu), nebo na stránce [https://etcho.github.io/poopify-legal/cs/delete-account/](https://etcho.github.io/poopify-legal/cs/delete-account/).
- **Exportovat svá data** (záloha SQL, CSV, JSON, PDF), pro přístup a přenositelnost.
- **Opravit nebo smazat záznamy** přímo v Aplikaci.

### 9.2 Vaše práva
Podle místa, kde žijete, můžete mít právo: na přístup ke svým údajům; na jejich opravu; na výmaz; na omezení zpracování nebo vznesení námitky proti němu; na přenositelnost údajů; odvolat souhlas; nebýt předmětem rozhodnutí založeného výhradně na automatizovaném zpracování; a být informováni o tom, s kým se údaje sdílejí.
- **Evropská unie / EHP / Spojené království (GDPR / UK GDPR):** všechna výše uvedená práva. Můžete také podat stížnost u úřadu pro ochranu osobních údajů ve své zemi.
- **Brazílie (LGPD, čl. 18):** potvrzení o zpracování, přístup, oprava, anonymizace, blokace nebo výmaz nepotřebných údajů, přenositelnost, výmaz údajů zpracovávaných se souhlasem, informace o sdílení, informace o možnosti souhlas neudělit a o jejích důsledcích a odvolání souhlasu. Můžete také podat stížnost u ANPD (brazilský úřad pro ochranu osobních údajů).
- **Spojené státy:** viz oddíly 11 a 12.
- **Ostatní země:** respektujeme obdobná práva podle vašeho místního práva.

Chcete-li uplatnit právo, které není přímo dostupné v Aplikaci, napište na **poopify.dev@gmail.com**. Odpovíme ve lhůtě stanovené zákonem pro daný typ žádosti (například do 15 dnů pro úplné potvrzení a přístup k vašim údajům podle LGPD a do jednoho měsíce podle GDPR, které v některých případech umožňuje lhůtu prodloužit). Možná budeme muset ověřit, že žádost pochází od majitele účtu.

## 10. Jak dlouho údaje uchováváme

| Údaje | Doba uchování |
|---|---|
| Data Místního režimu | Ve vašem zařízení, dokud je nesmažete nebo neodinstalujete Aplikaci |
| Data Synchronizace s cloudem | Dokud nesmažete svůj cloudový účet nebo data v cloudu; nebo nejpozději do doby, kdy účet 24 měsíců po sobě nepoužije žádné zařízení; nebo do ukončení Synchronizace s cloudem. V žádném z těchto případů nejsou dotčena data ve vašich zařízeních |
| Smazaná data v cloudu | Okamžitě odstraněna z našich aktivních systémů; zbytkové kopie v zálohovacích systémech Googlu se mažou ve lhůtách stanovených podmínkami mazání dat Google Cloud |
| Záznamy o souhlasu (které verze těchto dokumentů jste přijali, a kdy) | Uchovávány s vaším účtem synchronizace s cloudem a smazány spolu s ním, nebo když smažete svá data v cloudu |
| Analýza / hlášení pádů | Viz oddíl 5 |
| E-maily podpoře | Viz oddíl 7 |

## 11. Další informace pro obyvatele Spojených států

- **Shromažďované kategorie:** identifikátory (ID účtu, ID instalace Aplikace, reklamní identifikátor, IP adresa); činnost na internetu nebo elektronická činnost (události používání Aplikace); přibližná geolokace (z IP adresy, pro analýzu); **citlivé osobní údaje / spotřebitelské zdravotní údaje** (jen se Synchronizací s cloudem, viz oddíl 12); obchodní informace (stav nákupu).
- Osobní údaje neprodáváme ani je nesdílíme pro behaviorální reklamu napříč kontexty a v posledních 12 měsících jsme to nedělali.
- Citlivé osobní údaje používáme jen k poskytování služby, o kterou žádáte, proto se právo omezit jejich použití uplatňuje automaticky.
- **Kalifornie, Colorado, Connecticut, Virginie, Oregon, Texas a další státy se zákony o ochraně soukromí spotřebitelů:** máte právo znát své osobní údaje, mít k nim přístup, opravit je a smazat a nebýt diskriminováni za uplatnění těchto práv. Proti jakémukoli rozhodnutí o vaší žádosti se můžete odvolat odpovědí na naši odpověď.
- Prostřednictvím účtů synchronizace s cloudem vědomě neshromažďujeme osobní údaje dětí mladších 13 let (viz oddíl 13).

## 12. Zásady ochrany spotřebitelských zdravotních údajů (Washington, Nevada, Connecticut a obdobné zákony)

{% include cs/consumer-health-data.md %}

## 13. Děti

- Aplikace je osobní zdravotní deník a není určena dětem.
- **Účty synchronizace s cloudem jsou jen pro dospělé** (18 let nebo věk zletilosti tam, kde žijete).
- Rodiče a zákonní zástupci mohou Aplikaci používat k vedení záznamů o svých dětech v samostatných profilech. V takovém případě za tyto informace odpovídá rodič nebo zákonný zástupce a uděluje souhlas jménem dítěte.
- Pokud se domníváte, že účet synchronizace s cloudem vytvořilo dítě, kontaktujte nás a účet smažeme.

## 14. Zabezpečení

Vaše data chráníme technickými a organizačními opatřeními přiměřenými jejich citlivosti, mimo jiné:
- šifrováním při přenosu (TLS) i v úložišti;
- pravidly na serverech, která každému účtu umožňují přístup jen k vlastním datům;
- ověřováním, že požadavky pocházejí z pravé Aplikace;
- omezeným administrativním přístupem chráněným dvoufázovým ověřením a zaznamenávaným;
- minimalizací údajů (například údaje o poloze se nikdy nesynchronizují);
- automatizovanými testy našich bezpečnostních pravidel.

Žádný systém není zcela bezpečný. Pokud bezpečnostní incident zasáhne vaše osobní údaje, oznámíme to příslušným úřadům i vám, kdy a jak to vyžaduje zákon (například do 72 hodin dozorovému úřadu podle GDPR).

## 15. Mezinárodní předávání

Sídlíme v Brazílii a naši poskytovatelé mohou zpracovávat údaje v jiných zemích. Data Synchronizace s cloudem jsou uložena v Evropské unii. Při předávání osobních údajů do jiných zemí se opíráme o vhodné záruky, jako jsou standardní smluvní doložky Evropské komise, rámec EU–USA pro ochranu osobních údajů (Data Privacy Framework), pokud se uplatní, a mechanismy podle čl. 33 LGPD, jak je nabízí Google ve svých podmínkách zpracování dat.

## 16. Změny těchto zásad

O podstatných změnách vás v Aplikaci informujeme dříve, než nabudou účinnosti. Pokud změna ovlivní způsob, jakým zpracováváme data Synchronizace s cloudem, znovu vás požádáme o souhlas. Předchozí verze zůstávají dostupné na adrese anglické verze, za kterou následuje číslo verze (například https://etcho.github.io/poopify-legal/privacy-policy/1.0/).

Tyto zásady mohou být přeloženy do jiných jazyků. V případě rozporu mezi překladem a anglickou verzí má přednost anglická verze, pokud právo vaší země nestanoví jinak.

## 17. Kontakt

E-mail: **poopify.dev@gmail.com**

## Historie verzí

| Verze | Datum účinnosti | Změny |
|---|---|---|
| 1.0 | 21. října 2026 | První verze |
