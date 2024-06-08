## Naruszenie bezpieczeństwa danych

**Wzrost skali incydentów:**

* **Przykład 1:** W 2023 roku firma Capital One padła ofiarą cyberataku, w wyniku którego wykradziono dane 106 milionów klientów. Atakujący wykorzystali lukę w zabezpieczeniach firewalla firmy.
* **Przykład 2:** W 2021 roku firma Marriott International zgłosiła wyciek danych dotyczących 500 milionów gości hotelowych. Dane zostały wykradzione z systemu rezerwacyjnego firmy.

**Odpowiedzialność: dostawca i użytkownik usług:**

* **Dostawca:**
    * Zapewnienie bezpiecznej infrastruktury i platformy chmurowej.
    * Wdrożenie odpowiednich zabezpieczeń technicznych i organizacyjnych.
    * Szybkie reagowanie na incydenty bezpieczeństwa.
    * Informowanie użytkowników o naruszeniach bezpieczeństwa.
* **Użytkownik:**
    * Stosowanie silnych haseł i innych środków uwierzytelniania.
    * Regularne aktualizowanie oprogramowania.
    * Edukacja pracowników w zakresie bezpieczeństwa cybernetycznego.
    * Stosowanie szyfrowania danych.
    * Monitorowanie aktywności w chmurze i zgłaszanie podejrzanych zdarzeń.

**Dodatkowe przykłady naruszeń bezpieczeństwa danych w chmurze:**

* Wyciek danych osobowych z platformy mediów społecznościowych
* Kradzież danych finansowych z systemów bankowości internetowej
* Przejęcie kontroli nad kontami w chmurze w celu przeprowadzania ataków DDoS
* Wykorzystanie danych z chmury do celów niezgodnych z prawem, np. do spamu lub phishingu

## Błędna konfiguracja usług

**Pozostawienie domyślnej konfiguracji:**

* **Przykład 1:** Użytkownik nie zmienia domyślnego hasła do konta administratora w chmurze, co ułatwia cyberprzestępcom włamanie się na konto.
* **Przykład 2:** Usługa chmurowa jest skonfigurowana tak, że zezwala na dostęp z dowolnego adresu IP, co naraża ją na ataki z zewnątrz.

**Nadmiarowe uprawnienia:**

* **Przykład 1:** Pracownikowi firmy przyznano uprawnienia administratora do wszystkich zasobów chmurowych, mimo że do wykonywania swojej pracy potrzebuje tylko dostępu do kilku z nich.
* **Przykład 2:** Konto użytkownika jest skonfigurowane tak, że może ono modyfikować krytyczne pliki konfiguracyjne systemu, co może doprowadzić do awarii.

**Brak mechanizmów bezpieczeństwa:**

* **Przykład 1:** Usługa chmurowa nie ma włączonego szyfrowania danych, co oznacza, że dane są przesyłane i przechowywane w postaci nieszyfrowanej.
* **Przykład 2:** Usługa chmurowa nie ma włączonego firewalla, co naraża ją na ataki z zewnątrz.

**Odpowiedzialność: użytkownik usług**

Użytkownik usług chmurowych jest odpowiedzialny za prawidłową konfigurację tych usług. Oznacza to, że użytkownik musi:

* Zmieniać domyślne hasła.
* Nadawać użytkownikom tylko te uprawnienia, których potrzebują do wykonywania swojej pracy.
* Włączać mechanizmy bezpieczeństwa, takie jak szyfrowanie danych i firewall.
* Regularnie monitorować konfigurację usług chmurowych i wprowadzać niezbędne zmiany.

## Brak architektury i strategii bezpieczeństwa w chmurze

**Brak jednoznacznej architektury:**

* **Przykład 1:** Firma korzysta z różnych platform chmurowych (np. Amazon Web Services, Microsoft Azure, Google Cloud Platform) bez żadnego planu i koordynacji, co utrudnia zarządzanie bezpieczeństwem i kontrolę nad danymi.
* **Przykład 2:** Usługi chmurowe są wdrażane bez uwzględnienia istniejącej infrastruktury IT firmy, co może prowadzić do problemów z integracją i kompatybilnością.

**Brak uporządkowanej strategii:**

* **Przykład 1:** Firma nie ma jasno określonych celów bezpieczeństwa w chmurze, co utrudnia podejmowanie właściwych decyzji dotyczących zabezpieczeń.
* **Przykład 2:** Firma nie ma planu reagowania na incydenty bezpieczeństwa w chmurze, co może prowadzić do chaosu i strat w przypadku ataku.

**Niewystarczający nadzór:**

* **Przykład 1:** Firma nie monitoruje aktywności w chmurze, co utrudnia wykrywanie podejrzanych zdarzeń i reagowanie na nie.
* **Przykład 2:** Firma nie przeprowadza regularnych audytów bezpieczeństwa w chmurze, co może prowadzić do zidentyfikowania luk w zabezpieczeniach dopiero po ich wykorzystaniu przez cyberprzestępców.

**Nieracjonalne decyzje:**

* **Przykład 1:** Firma wybiera dostawcę usług chmurowych wyłącznie na podstawie ceny, nie biorąc pod uwagę bezpieczeństwa i innych czynników.
* **Przykład 2:** Firma wdraża usługi chmurowe bez przeprowadzenia odpowiednich analiz i testów, co może prowadzić do problemów z wydajnością i bezpieczeństwem.

**Odpowiedzialność: użytkownik usług**

Użytkownik usług chmurowych jest odpowiedzialny za opracowanie i wdrożenie odpowiedniej architektury i strategii bezpieczeństwa w chmurze. Oznacza to, że użytkownik musi:

* Określić swoje cele bezpieczeństwa w chmurze.
* Opracować plan wdrażania usług chmurowych.
* Wybrać odpowiedniego dostawcę usług chmurowych.
* Wdrożyć odpowiednie zabezpieczenia techniczne i organizacyjne.
* Monitorować aktywność w chmurze i reagować na podejrzane zdarzenia.
* Przeprowadzać regularne audyty bezpieczeństwa w chmurze.

## Niewystarczające zarządzanie tożsamością, dostępem i danymi uwierzytelniającymi

**Konieczność zmiany w zarządzaniu:**

* Tradycyjne metody zarządzania tożsamością i dostępem (IAM) często nie są wystarczające w środowisku chmurowym, gdzie użytkownicy mogą mieć dostęp do zasobów z dowolnego miejsca i urządzenia.
* Nowe rozwiązania IAM oparte na chmurze mogą zapewnić większą skalowalność, elastyczność i bezpieczeństwo.

**Zapewnienie integralności danych uwierzytelniających:**

* Stosowanie silnych haseł i innych środków uwierzytelniania, takich jak uwierzytelnianie wieloskładnikowe (MFA).
* Regularne zmienianie haseł.
* Nieużywanie tych samych haseł w różnych serwisach.
* Przechowywanie haseł w bezpiecznym miejscu.

**Skalowalność narzędzi klasy IAM:**

* Wybór narzędzi IAM, które mogą skalować się wraz ze wzrostem liczby użytkowników i zasobów.
* Automatyzacja procesów zarządzania tożsamością i dostępem.
* Integracja narzędzi IAM z innymi systemami IT.

**Odpowiedzialność: użytkownik usług**

Użytkownik usług chmurowych jest odpowiedzialny za zapewnienie odpowiedniego zarządzania tożsamością, dostępem i danymi uwierzytelniającymi. Oznacza to, że użytkownik musi:

* Wdrożyć odpowiednie rozwiązania IAM.
* Zapewnić integralność danych uwierzytelniających.
* Stosować narzędzia IAM, które są skalowalne i łatwe w zarządzaniu.
* Edukować pracowników w zakresie bezpieczeństwa cybernetycznego.
* Monitorować aktywność użytkowników i reagować na podejrzane zdarzenia.

**Przykładowe rozwiązania IAM:**

* Amazon Web Services Identity and Access Management (IAM)
* Microsoft Azure Active Directory (Azure AD)
* Google Cloud Identity and Access Management (IAM)

## Przejęcie konta uprzywilejowanego

**Szczególne zainteresowanie cyberprzestępców:**

* Konta uprzywilejowane, takie jak konta administratorów, dają cyberprzestępcom szerokie możliwości dostępu do danych i systemów.
* Atakujący mogą wykorzystać przejęte konto do kradzieży danych, instalowania złośliwego oprogramowania lub nawet wyłączania systemów.

**Skutki:**

* **Straty finansowe:** Atakujący mogą wykorzystać przejęte konto do kradzieży pieniędzy lub innych aktywów.
* **Szkody wizerunkowe:** Wyciek danych lub awaria systemu mogą zaszkodzić reputacji firmy.
* **Kradzież danych:** Atakujący mogą ukraść dane osobowe, poufne dane biznesowe lub inne wartościowe dane.
* **Zatrzymanie krytycznych procesów biznesowych:** Atakujący mogą wyłączyć systemy, co może prowadzić do przerwy w działalności firmy.

**Odpowiedzialność: użytkownik usług**

Użytkownik usług chmurowych jest odpowiedzialny za ochronę kont uprzywilejowanych. Oznacza to, że użytkownik musi:

* Stosować silne hasła i inne środki uwierzytelniania, takie jak MFA.
* Regularnie zmieniać hasła.
* Nie używać tych samych haseł w różnych serwisach.
* Przechowywać hasła w bezpiecznym miejscu.
* Ograniczać liczbę kont uprzywilejowanych.
* Monitorować aktywność kont uprzywilejowanych i reagować na podejrzane zdarzenia.
* Przeprowadzać regularne szkolenia dla pracowników w zakresie bezpieczeństwa cybernetycznego.

**Przykładowe metody przejęcia konta uprzywilejowanego:**

* Phishing: Atakujący wysyła e-mail lub wiadomość SMS z linkiem do fałszywej strony logowania. Gdy użytkownik kliknie link i wprowadzi swoje dane logowania, atakujący kradnie je.
* Inżynieria społeczna: Atakujący manipuluje użytkownikiem, aby skłonił go do ujawnienia danych logowania lub wykonania innych czynności, które ułatwią przejęcie konta.
* Atak typu brute force: Atakujący używa oprogramowania do odgadnięcia hasła użytkownika.
* Złośliwe oprogramowanie: Atakujący instaluje złośliwe oprogramowanie na komputerze użytkownika, które może przechwycić jego dane logowania.

## Zagrożenia wewnętrzne

**Działania zagrażające organizacji:**

* **Kradzież danych:** Pracownik może ukraść dane osobowe, poufne dane biznesowe lub inne wartościowe dane.
* **Sabotaż:** Pracownik może celowo uszkodzić systemy lub dane firmy.
* **Niewłaściwe korzystanie z zasobów:** Pracownik może wykorzystywać zasoby firmy do celów prywatnych, co może prowadzić do strat finansowych lub innych szkód.
* **Niestosowanie się do procedur bezpieczeństwa:** Pracownik może nie stosować się do procedur bezpieczeństwa, co może ułatwić cyberprzestępcom włamanie się do systemów firmy.

**Skala strat:**

* Według raportu Cloud Security Alliance z 2017 roku średnia wysokość strat związanych z zagrożeniami typu insider threat wynosiła ponad 8,7 mld USD.
* Zagrożenia wewnętrzne są często trudne do wykrycia i zapobiegania, ponieważ pracownicy mają już dostęp do systemów i danych firmy.

**Odpowiedzialność: użytkownik usług**

Użytkownik usług chmurowych jest odpowiedzialny za zminimalizowanie ryzyka zagrożeń wewnętrznych. Oznacza to, że użytkownik musi:

* Przeprowadzać odpowiednie kontrole bezpieczeństwa przed zatrudnieniem pracowników.
* Edukować pracowników w zakresie bezpieczeństwa cybernetycznego.
* Wdrażać zasady kontroli dostępu, które ograniczają dostęp pracowników do danych i systemów.
* Monitorować aktywność pracowników i reagować na podejrzane zdarzenia.
* Stworzyć kulturę bezpieczeństwa, w której pracownicy czują się komfortowo zgłaszając potencjalne zagrożenia.

**Przykładowe procedury bezpieczeństwa:**

* Polityka haseł
* Polityka dostępu do danych
* Polityka korzystania z urządzeń mobilnych
* Polityka zgłaszania incydentów bezpieczeństwa

## Brak planu reagowania na incydenty bezpieczeństwa

**Znaczenie planu reagowania:**

* Incydenty bezpieczeństwa mogą się zdarzyć w każdej chwili, dlatego ważne jest, aby mieć plan, jak na nie reagować.
* Plan reagowania na incydenty może pomóc zminimalizować szkody i przywrócić normalną działalność firmy.

**Elementy planu reagowania:**

* Identyfikacja i ocena ryzyka
* Procedury zgłaszania incydentów
* Zespół reagowania na incydenty
* Procesy dochodzenia i naprawy
* Komunikacja z interesariuszami
* Testowanie i aktualizacja planu

**Skutki braku planu reagowania:**

* Chaos i zamieszanie podczas incydentu
* Opóźnienia w przywróceniu normalnej działalności
* Zwiększone ryzyko utraty danych i innych szkód
* Straty finansowe
* Szkody wizerunkowe

**Odpowiedzialność: użytkownik usług**

Użytkownik usług chmurowych jest odpowiedzialny za opracowanie i wdrożenie planu reagowania na incydenty bezpieczeństwa. Oznacza to, że użytkownik musi:

* Określić potencjalne zagrożenia dla bezpieczeństwa.
* Opracować procedury zgłaszania incydentów.
* Powołać zespół reagowania na incydenty.
* Opracować procesy dochodzenia i naprawy.
* Opracować plan komunikacji z interesariuszami.
* Regularnie testować i aktualizować plan.

**Przykładowe procedury reagowania na incydenty:**

* Izolowanie zainfekowanych systemów
* Przywracanie danych z kopii zapasowych
* Wymiana skompromitowanych haseł
* Zgłaszanie incydentu organom ścigania

## Podsumowanie i wnioski

**Podsumowanie:**

* Usługi chmurowe mogą stwarzać nowe zagrożenia bezpieczeństwa, których nie ma w tradycyjnych środowiskach IT.
* Ważne jest, aby użytkownicy usług chmurowych byli świadomi tych zagrożeń i podjęli odpowiednie kroki w celu ich zminimalizowania.
* Istnieje wiele sposobów na poprawę bezpieczeństwa usług chmurowych, w tym:
    * Wdrożenie odpowiedniej konfiguracji
    * Opracowanie architektury i strategii bezpieczeństwa w chmurze
    * Zapewnienie odpowiedniego zarządzania tożsamością, dostępem i danymi uwierzytelniającymi
    * Ochrona przed przejęciem kont uprzywilejowanych
    * Zminimalizowanie ryzyka zagrożeń wewnętrznych
    * Opracowanie planu reagowania na incydenty bezpieczeństwa

**Wnioski:**

* Bezpieczeństwo usług chmurowych to wspólna odpowiedzialność użytkownika usług i dostawcy usług.
* Użytkownicy usług muszą podjąć kroki, aby chronić swoje dane i systemy.
* Dostawcy usług muszą zapewnić bezpieczne i niezawodne środowisko chmurowe.

**Dodatkowe zalecenia:**

* Regularna aktualizacja oprogramowania i systemów operacyjnych.
* Stosowanie najnowsze poprawek bezpieczeństwa.
* Korzystanie z szyfrowania danych.
* Przeprowadzanie regularnych audytów bezpieczeństwa.
* Śledzenie na bieżąco najnowszych zagrożeń bezpieczeństwa.
