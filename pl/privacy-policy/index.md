---
layout: default
title: "Polityka prywatności"
permalink: /pl/privacy-policy/
lang: pl
---

*To jest tłumaczenie. W razie rozbieżności rozstrzyga [wersja angielska](https://etcho.github.io/poopify-legal/privacy-policy/).*

# Poopify - Polityka prywatności

**Data wejścia w życie:** 21 października 2026 r.
**Wersja:** 1.0

Niniejsza Polityka prywatności wyjaśnia, jakie dane osobowe przetwarza aplikacja Poopify („Aplikacja”), w jakim celu i jakie prawa Ci przysługują. Dotyczy Aplikacji na wszystkich urządzeniach oraz opcjonalnej usługi Synchronizacji w chmurze.

## Podsumowanie

- **Domyślnie Twoje dane o zdrowiu nigdy nie opuszczają Twojego urządzenia.** W Trybie lokalnym wszystko, co zapisujesz (wypróżnienia, cykl menstruacyjny, objawy, notatki, profile), jest przechowywane tylko na Twoim telefonie. My tego nie otrzymujemy.
- **Synchronizacja w chmurze jest opcjonalna.** Jeśli ją włączysz i wyrazisz wyraźną zgodę, kopia Twoich wpisów jest przechowywana w chmurze (Google Firebase, w Unii Europejskiej), aby można ją było synchronizować między Twoimi urządzeniami. Synchronizacja w chmurze jest udostępniana stopniowo i **może nie być dostępna we wszystkich regionach**.
- **Nigdy nie sprzedajemy Twoich danych, nigdy nie używamy Twoich danych o zdrowiu do reklam i nigdy nie udostępniamy ich nikomu do jego własnych celów.**
- Aplikacja wyświetla reklamy i korzysta z narzędzi Google do analityki i raportowania awarii. Te usługi otrzymują identyfikatory urządzenia i informacje o korzystaniu z Aplikacji, **ale nie treść Twoich danych o zdrowiu.**
- W każdej chwili możesz wyłączyć Synchronizację w chmurze, wyeksportować swoje dane lub usunąć konto w chmurze, bezpośrednio w Aplikacji (Menu > Prywatność).

---

## 1. Kto odpowiada za Twoje dane

Administratorem Twoich danych osobowych jest:

Everton Carvalho Leite, niezależny deweloper, Rio de Janeiro, Brazylia
E-mail: **poopify.dev@gmail.com**

- **Kontakt w sprawie ochrony danych / Encarregado (LGPD):** Everton Carvalho Leite, poopify.dev@gmail.com

## 2. Dane przechowywane tylko na Twoim urządzeniu (Tryb lokalny)

Gdy korzystasz z Aplikacji bez Synchronizacji w chmurze, poniższe dane są przechowywane **tylko na Twoim urządzeniu**, w prywatnej pamięci Aplikacji:
- wpisy, które wprowadzasz: data i godzina, cechy stolca, objawy, ból, notatki o lekach i jedzeniu, metoda higieny, informacje o cyklu menstruacyjnym, notatki tekstowe;
- profile, które tworzysz (nazwa, ikona, opcjonalna data urodzenia), oraz ustawienia Aplikacji.

Nie mamy dostępu do tych danych. Nie są one wysyłane do nas ani do osób trzecich, z wyjątkiem następujących sytuacji, które kontrolujesz:
- **Eksport i udostępnianie:** gdy eksportujesz kopię zapasową, plik CSV, JSON lub PDF, plik jest tworzony na Twoim urządzeniu i wysyłany tylko tam, gdzie zdecydujesz się go udostępnić.
- **Kopia zapasowa urządzenia z Androidem:** w zależności od ustawień urządzenia Android może uwzględnić dane Aplikacji w kopii zapasowej urządzenia na Twoim koncie Google. Tą kopią zarządza Google i ustawienia Twojego urządzenia, a nie my.

## 3. Synchronizacja w chmurze (opcjonalna)

Synchronizacja w chmurze to opcjonalna funkcja udostępniana stopniowo. **Może nie być dostępna we wszystkich krajach lub regionach**, a tam, gdzie nie jest dostępna, Aplikacja jej nie pokazuje.

### 3.1 Co przetwarzamy
Jeśli włączysz Synchronizację w chmurze, przetwarzamy:
- **Dane konta:** unikalny identyfikator konta i adres e-mail konta, na które się logujesz (na przykład konta Google), zarządzane przez Firebase Authentication.
- **Twoje dane o zdrowiu:** kopię wpisów i profili opisanych w Sekcji 2, **bez danych o lokalizacji**.
- **Techniczne dane synchronizacji:** identyfikator urządzenia wygenerowany przez Aplikację, znaczniki czasu zmian i stan synchronizacji.
- **Zapis zgody:** wersję niniejszej Polityki prywatności i Warunków korzystania, którą zaakceptowałeś(-aś), oraz datę.
- **Sygnały integralności Aplikacji:** informacje potwierdzające, że żądania pochodzą z oryginalnej kopii Aplikacji (Firebase App Check z Google Play Integrity).

### 3.2 Cel i podstawa prawna
- **Cel:** wyłącznie przechowywanie Twoich wpisów, synchronizowanie ich między urządzeniami zalogowanymi na Twoje konto i umożliwienie ich przywrócenia na nowym urządzeniu.
- **Podstawa prawna:** Twoja **wyraźna zgoda** (RODO art. 6 ust. 1 lit. a i art. 9 ust. 2 lit. a; LGPD art. 7, I i art. 11, I; oraz równoważne przepisy w innych jurysdykcjach). Dane konta i dane techniczne są przetwarzane, ponieważ są niezbędne do świadczenia usługi, o którą prosisz (RODO art. 6 ust. 1 lit. b; LGPD art. 7, V).
- Możesz **w każdej chwili wycofać zgodę**, usuwając swoje dane z chmury w Aplikacji (Sekcja 9). Samo wyłączenie Synchronizacji w chmurze tylko zatrzymuje synchronizację: kopia, która już jest w chmurze, pozostaje tam, dopóki jej nie usuniesz, a Aplikacja proponuje jej usunięcie przy wyłączaniu synchronizacji. Wycofanie zgody nie wpływa na przetwarzanie dokonane przed nim.
- **Nie** używamy Twoich danych z chmury do analityki, reklam, profilowania, badań, trenowania sztucznej inteligencji ani w żadnym innym celu niż świadczenie Ci Synchronizacji w chmurze.

### 3.3 Gdzie przechowywane są Twoje dane
Dane Synchronizacji w chmurze są przechowywane na serwerach Google Cloud znajdujących się w **Unii Europejskiej** (multiregion Firestore „eur3”). Google działa jako nasz podmiot przetwarzający na podstawie Warunków przetwarzania i bezpieczeństwa danych Firebase.

### 3.4 Kto ma do nich dostęp
- **Przez Aplikację tylko Twoje konto.** Reguły bezpieczeństwa na serwerach uniemożliwiają każdemu innemu kontu odczyt lub zapis Twoich danych.
- **Deweloper tylko w wyjątkowych przypadkach.** Dane są szyfrowane podczas przesyłania i w spoczynku, ale nie w sposób end-to-end: technicznie można je zobaczyć w konsoli administracyjnej usługi. Ta konsola jest dostępna tylko dla konta dewelopera, chroniona weryfikacją dwuetapową, a dostęp do niej jest rejestrowany. Zaglądamy do Twoich danych z chmury tylko wtedy, gdy wyraźnie poprosisz nas o pomoc z kontem albo gdy wymaga tego prawo.
- **Google**, jako nasz dostawca infrastruktury, przetwarza dane wyłącznie po to, by hostować je w naszym imieniu.

### 3.5 Dostępność w regionach
Synchronizacja w chmurze może być niedostępna w niektórych krajach lub regionach z przyczyn prawnych lub technicznych. Jeśli przestanie być dostępna tam, gdzie jesteś, synchronizacja zostanie zatrzymana, dane na Twoich urządzeniach pozostaną bez zmian, a Ty nadal będziesz mógł(-a) w każdej chwili usunąć swoje konto i dane z chmury w Menu > Prywatność.

## 4. Reklamy

- Aplikacja wyświetla reklamy dostarczane przez **Google AdMob**. AdMob może przetwarzać identyfikator reklamowy Twojego urządzenia, Twój adres IP oraz informacje o wyświetlonych i klikniętych reklamach.
- W Europejskim Obszarze Gospodarczym, Wielkiej Brytanii, Szwajcarii i wszędzie tam, gdzie wymaga tego prawo, prosimy o Twoją zgodę przed personalizacją reklam, korzystając z narzędzia do zgód Google. Możesz w każdej chwili zmienić swój wybór w menu Aplikacji, w **Opcjach prywatności reklam** (wyświetlane tam, gdzie ten wybór ma zastosowanie).
- Na Androidzie możesz też zresetować lub usunąć swój identyfikator reklamowy w ustawieniach urządzenia.
- **Treść Twoich danych o zdrowiu nigdy nie jest udostępniana AdMob ani używana do wyboru reklam.**
- Jeśli kupisz „Usuń reklamy”, reklamy przestaną się wyświetlać.
- Więcej informacji: https://policies.google.com/technologies/partner-sites

## 5. Analityka i raporty o awariach

- Używamy **Google Analytics dla Firebase**, aby zrozumieć, jak korzysta się z Aplikacji (na przykład, które ekrany są otwierane i które funkcje są używane), oraz **Firebase Crashlytics**, aby otrzymywać raporty o awariach i błędach.
- Te usługi przetwarzają identyfikator instalacji Aplikacji, informacje o urządzeniu i systemie operacyjnym, przybliżoną lokalizację ustaloną na podstawie adresu IP (kraj i region) oraz zdarzenia użytkowania.
- Zdarzenia użytkowania rejestrują, **że** użyto danej funkcji (na przykład „utworzono wpis”), **nigdy treść** tego, co zapisałeś(-aś).
- **Podstawa prawna:** nasz prawnie uzasadniony interes w utrzymaniu działania i ulepszaniu Aplikacji (RODO art. 6 ust. 1 lit. f; LGPD art. 7, IX) lub Twoja zgoda, tam gdzie wymaga jej prawo.
- Analytics jest połączony z Google AdMob wyłącznie w celu mierzenia skuteczności i przychodów z reklam wyświetlanych w Aplikacji. **Dane Analytics nie są używane do personalizacji reklam** (personalizacja reklam i Google Signals są wyłączone w naszych ustawieniach Analytics) i nie są udostępniane innym partnerom reklamowym.
- **Okres przechowywania:** dane o zdarzeniach w Analytics są przechowywane przez 2 miesiące, a dane Analytics na poziomie użytkownika do 14 miesięcy. Raporty o awariach są przechowywane do 90 dni.

## 6. Zakupy

Zakupy (takie jak „Usuń reklamy”) są obsługiwane przez **Google Play**. Otrzymujemy tylko informacje potrzebne do potwierdzenia zakupu (takie jak token i status zakupu). Nie otrzymujemy Twoich danych płatniczych. Do płatności ma zastosowanie polityka prywatności Google.

## 7. Wiadomości do pomocy technicznej

Jeśli do nas napiszesz, przetwarzamy Twój adres e-mail i treść wiadomości wyłącznie po to, by Ci odpowiedzieć, a rozmowę przechowujemy jako historię naszej pomocy technicznej, dopóki nie poprosisz o jej usunięcie. Prosimy nie wysyłać informacji o zdrowiu e-mailem, jeśli nie jest to konieczne.

## 8. Komu udostępniamy dane

Nie sprzedajemy danych osobowych i nie „udostępniamy” ich do reklamy behawioralnej między kontekstami.

Korzystamy z następujących usługodawców (podmiotów przetwarzających), którzy przetwarzają dane w naszym imieniu i zgodnie z naszymi instrukcjami, lub jako niezależni administratorzy, gdy tak wskazano:

| Dostawca | Usługa | Dane | Rola |
|---|---|---|---|
| Google (Firebase Authentication, Cloud Firestore, App Check) | Synchronizacja w chmurze | Konto, dane Synchronizacji w chmurze | Podmiot przetwarzający |
| Google (Analytics dla Firebase, Crashlytics) | Analityka i raporty o awariach | Zdarzenia użytkowania, dane urządzenia, identyfikatory | Podmiot przetwarzający |
| Google (AdMob) | Reklamy | Identyfikator reklamowy, IP, interakcje z reklamami | Niezależny administrator w zakresie reklam, patrz Sekcja 4 |
| Google (Google Play) | Zakupy | Dane zakupu | Niezależny administrator |

Możemy też ujawnić dane, gdy wymaga tego prawo, albo w celu ochrony praw, bezpieczeństwa lub integralności użytkowników lub Aplikacji, ale tylko w ściśle niezbędnym zakresie, i poinformujemy Cię o tym, gdy prawo na to pozwala.

## 9. Twoje wybory i prawa

### 9.1 Dostępne w Aplikacji w każdej chwili
- **Wyłączenie Synchronizacji w chmurze:** Twoje dane pozostają na urządzeniu, a Aplikacja dalej działa w Trybie lokalnym.
- **Usunięcie konta i danych z chmury:** w Aplikacji (Menu > Prywatność > Usuń konto Synchronizacji w chmurze, albo Menu > Synchronizacja w chmurze > Usuń konto i dane z chmury) lub na stronie [https://etcho.github.io/poopify-legal/pl/delete-account/](https://etcho.github.io/poopify-legal/pl/delete-account/).
- **Eksport danych** (kopia zapasowa SQL, CSV, JSON, PDF), w celu dostępu i przenoszenia.
- **Poprawianie lub usuwanie wpisów** bezpośrednio w Aplikacji.

### 9.2 Twoje prawa
W zależności od miejsca zamieszkania możesz mieć prawo do: dostępu do swoich danych; ich sprostowania; usunięcia; ograniczenia przetwarzania lub sprzeciwu wobec niego; przenoszenia danych; wycofania zgody; niepodlegania decyzjom opartym wyłącznie na zautomatyzowanym przetwarzaniu; oraz informacji o tym, komu dane są udostępniane.
- **Unia Europejska / EOG / Wielka Brytania (RODO / UK GDPR):** wszystkie powyższe prawa. Możesz też złożyć skargę do organu ochrony danych w swoim kraju.
- **Brazylia (LGPD, art. 18):** potwierdzenie przetwarzania, dostęp, poprawienie, anonimizacja, blokowanie lub usunięcie zbędnych danych, przenoszenie, usunięcie danych przetwarzanych na podstawie zgody, informacja o udostępnianiu, informacja o możliwości odmowy zgody i jej skutkach oraz cofnięcie zgody. Możesz też złożyć skargę do ANPD (brazylijskiego organu ochrony danych).
- **Stany Zjednoczone:** patrz Sekcje 11 i 12.
- **Inne kraje:** respektujemy równoważne prawa wynikające z Twojego prawa lokalnego.

Aby skorzystać z prawa, które nie jest dostępne bezpośrednio w Aplikacji, napisz na **poopify.dev@gmail.com**. Odpowiemy w terminie wymaganym przez prawo dla danego rodzaju żądania (na przykład do 15 dni na pełne potwierdzenie i dostęp do danych zgodnie z LGPD oraz miesiąc zgodnie z RODO, które w niektórych przypadkach pozwala ten termin przedłużyć). Możemy potrzebować potwierdzenia, że żądanie pochodzi od właściciela konta.

## 10. Jak długo przechowujemy dane

| Dane | Okres przechowywania |
|---|---|
| Dane Trybu lokalnego | Na Twoim urządzeniu, dopóki ich nie usuniesz lub nie odinstalujesz Aplikacji |
| Dane Synchronizacji w chmurze | Dopóki nie usuniesz konta lub danych z chmury; albo najpóźniej do czasu, gdy konto przez 24 kolejne miesiące nie będzie używane przez żadne urządzenie; albo do zakończenia Synchronizacji w chmurze. W żadnym z tych przypadków dane na Twoich urządzeniach nie są naruszane |
| Usunięte dane z chmury | Usuwane natychmiast z naszych aktywnych systemów; pozostałe kopie w systemach kopii zapasowych Google są usuwane w terminach określonych w warunkach usuwania danych Google Cloud |
| Zapisy zgody (które wersje tych dokumentów zaakceptowałeś(-aś) i kiedy) | Przechowywane razem z kontem Synchronizacji w chmurze i usuwane wraz z nim albo wtedy, gdy usuniesz dane z chmury |
| Analityka / raporty o awariach | Patrz Sekcja 5 |
| Wiadomości do pomocy technicznej | Patrz Sekcja 7 |

## 11. Dodatkowe informacje dla mieszkańców Stanów Zjednoczonych

- **Zbierane kategorie:** identyfikatory (ID konta, ID instalacji Aplikacji, identyfikator reklamowy, adres IP); aktywność w internecie lub elektroniczna (zdarzenia użytkowania Aplikacji); przybliżona geolokalizacja (na podstawie IP, do analityki); **wrażliwe dane osobowe / dane o zdrowiu konsumentów** (tylko z Synchronizacją w chmurze, patrz Sekcja 12); informacje handlowe (status zakupu).
- Nie sprzedajemy danych osobowych ani nie udostępniamy ich do reklamy behawioralnej między kontekstami i nie robiliśmy tego w ciągu ostatnich 12 miesięcy.
- Wrażliwych danych osobowych używamy wyłącznie do świadczenia usługi, o którą prosisz, więc prawo do ograniczenia ich wykorzystania jest stosowane domyślnie.
- **Kalifornia, Kolorado, Connecticut, Wirginia, Oregon, Teksas i inne stany z przepisami o prywatności konsumentów:** masz prawo do informacji o swoich danych osobowych, dostępu do nich, ich poprawienia i usunięcia oraz do tego, by nie być dyskryminowanym za korzystanie z tych praw. Możesz odwołać się od każdej decyzji w sprawie swojego żądania, odpowiadając na naszą odpowiedź.
- Nie zbieramy świadomie danych osobowych dzieci poniżej 13 roku życia za pośrednictwem kont Synchronizacji w chmurze (patrz Sekcja 13).

## 12. Polityka prywatności danych o zdrowiu konsumentów (Waszyngton, Nevada, Connecticut i podobne przepisy)

{% include pl/consumer-health-data.md %}

## 13. Dzieci

- Aplikacja jest osobistym dziennikiem zdrowia i nie jest skierowana do dzieci.
- **Konta Synchronizacji w chmurze są tylko dla dorosłych** (18 lat lub wiek pełnoletności w miejscu Twojego zamieszkania).
- Rodzice i opiekunowie mogą używać Aplikacji do prowadzenia wpisów o swoich dzieciach w osobnych profilach. W takim przypadku rodzic lub opiekun odpowiada za te informacje i wyraża zgodę w imieniu dziecka.
- Jeśli uważasz, że dziecko założyło konto Synchronizacji w chmurze, skontaktuj się z nami, a je usuniemy.

## 14. Bezpieczeństwo

Chronimy Twoje dane za pomocą środków technicznych i organizacyjnych odpowiednich do ich wrażliwości, w tym:
- szyfrowania podczas przesyłania (TLS) i w spoczynku;
- reguł na serwerach, które pozwalają każdemu kontu na dostęp tylko do własnych danych;
- weryfikacji, że żądania pochodzą z oryginalnej Aplikacji;
- ograniczonego, chronionego weryfikacją dwuetapową i rejestrowanego dostępu administracyjnego;
- minimalizacji danych (na przykład dane o lokalizacji nigdy nie są synchronizowane);
- automatycznych testów naszych reguł bezpieczeństwa.

Żaden system nie jest całkowicie bezpieczny. Jeśli incydent bezpieczeństwa dotknie Twoich danych osobowych, powiadomimy właściwe organy i Ciebie, kiedy i w sposób, jakiego wymaga prawo (na przykład w ciągu 72 godzin organ nadzorczy zgodnie z RODO).

## 15. Przekazywanie danych za granicę

Mamy siedzibę w Brazylii, a nasi usługodawcy mogą przetwarzać dane w innych krajach. Dane Synchronizacji w chmurze są przechowywane w Unii Europejskiej. Gdy dane osobowe są przekazywane do innych krajów, opieramy się na odpowiednich zabezpieczeniach, takich jak standardowe klauzule umowne Komisji Europejskiej, ramy ochrony danych UE-USA (Data Privacy Framework), jeśli mają zastosowanie, oraz mechanizmy przewidziane w art. 33 LGPD, oferowane przez Google w jego warunkach przetwarzania danych.

## 16. Zmiany niniejszej polityki

O istotnych zmianach poinformujemy Cię w Aplikacji, zanim wejdą w życie. Jeśli zmiana będzie dotyczyć sposobu przetwarzania danych Synchronizacji w chmurze, ponownie poprosimy o Twoją zgodę. Wcześniejsze wersje pozostają dostępne pod adresem wersji angielskiej z dodanym numerem wersji (na przykład https://etcho.github.io/poopify-legal/privacy-policy/1.0/).

Niniejsza polityka może zostać przetłumaczona na inne języki. W razie sprzeczności między tłumaczeniem a wersją angielską rozstrzyga wersja angielska, chyba że prawo Twojego kraju stanowi inaczej.

## 17. Kontakt

E-mail: **poopify.dev@gmail.com**

## Historia wersji

| Wersja | Data wejścia w życie | Zmiany |
|---|---|---|
| 1.0 | 21 października 2026 r. | Pierwsza wersja |
