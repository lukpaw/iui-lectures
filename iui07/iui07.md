## Praktyczne zastosowanie usług w Chmurze (cz. 1)
Praktyczne zastosowanie usług w Chmurze na przykładzie Azure AI Health Bot
Źródło: https://learn.microsoft.com/en-us/azure/health-bot/overview

## Microsoft Azure Health Bot - rewolucja w opiece zdrowotnej

* Innowacyjna platforma oparta na sztucznej inteligencji
    * Wykorzystuje najnowocześniejsze technologie AI do ułatwiania komunikacji i opieki nad pacjentami.
    * Pomaga w diagnozowaniu chorób, udzielaniu porad i kierowaniu do odpowiednich specjalistów.
* Zwiększona satysfakcja pacjentów
    * Ułatwia dostęp do informacji i wsparcia 24/7.
    * Pozwala na spersonalizowane podejście do każdego pacjenta.
    * Zmniejsza czas oczekiwania na wizyty lekarskie i badania.
* Poprawa efektywności pracowników służby zdrowia
    * Automatyzuje powtarzalne zadania, takie jak odpowiadanie na pytania i umawianie wizyt.
    * Zapewnia dostęp do aktualnych informacji i danych medycznych pacjentów.
    * Pozwala lekarzom skupić się na bardziej skomplikowanych przypadkach.

## Jak działa Health Bot?

* Przetwarzanie języka naturalnego (NLP)
    * Rozumie naturalny język ludzki i odpowiada w sposób naturalny.
    * Potrafi rozpoznawać intencje pacjentów i udzielać odpowiednich informacji.
    * Umożliwia pacjentom łatwą i intuicyjną interakcję z botem.
* Spersonalizowane informacje i zalecenia
    * Dostarcza pacjentom informacji dostosowanych do ich indywidualnych potrzeb i stanu zdrowia.
    * Wykorzystuje dane medyczne pacjentów do tworzenia spersonalizowanych planów opieki.
    * Pomaga pacjentom podejmować świadome decyzje dotyczące swojego zdrowia.
* Integracja z systemami EHR
    * Łączy się z istniejącymi systemami EHR, aby uzyskać dostęp do danych medycznych pacjentów.
    * Pozwala na całościowy obraz stanu zdrowia pacjenta.
    * Ułatwia pracownikom służby zdrowia świadczenie kompleksowej opieki.

## Korzyści ze stosowania Health Bot

* Poprawa satysfakcji pacjentów
    * Ułatwia dostęp do informacji i wsparcia 24/7.
    * Pozwala na spersonalizowane podejście do każdego pacjenta.
    * Zmniejsza czas oczekiwania na wizyty lekarskie i badania.
    * Zwiększa zaufanie pacjentów do opieki medycznej.
* Zwiększenie efektywności pracowników służby zdrowia
    * Automatyzuje powtarzalne zadania, takie jak odpowiadanie na pytania i umawianie wizyt.
    * Zapewnia dostęp do aktualnych informacji i danych medycznych pacjentów.
    * Pozwala lekarzom skupić się na bardziej skomplikowanych przypadkach.
    * Prowadzi do obniżenia kosztów opieki zdrowotnej.
* Obniżenie kosztów opieki zdrowotnej
    * Zmniejsza liczbę niepotrzebnych wizyt u lekarza i badań.
    * Pomaga pacjentom lepiej zarządzać swoim zdrowiem, co może prowadzić do zmniejszenia liczby chorób przewlekłych.
    * Umożliwia bardziej wydajne wykorzystanie zasobów opieki zdrowotnej.

## Przypadki użycia Health Bot

* Odpowiadanie na pytania dotyczące zdrowia
    * Health Bot może odpowiadać na szeroki zakres pytań dotyczących zdrowia, od objawów chorób po sposoby leczenia.
    * Może również udzielać informacji o zdrowym stylu życia i zapobieganiu chorobom.
* Planowanie wizyt lekarskich
    * Health Bot może pomóc pacjentom w planowaniu wizyt lekarskich, w tym w wyszukiwaniu lekarzy, ustalaniu terminów i przypominaniu o wizytach.
    * Może również udzielać informacji o tym, czego można się spodziewać podczas wizyty.
* Uzupełnianie recept
    * Health Bot może pomóc pacjentom w uzupełnianiu recept, w tym w wyszukiwaniu aptek, sprawdzaniu cen leków i składaniu zamówień online.
    * Może również przypominać pacjentom o przyjmowaniu leków.
* Monitorowanie stanu zdrowia pacjentów
    * Health Bot może monitorować stan zdrowia pacjentów, śledząc ich objawy, znaki życiowe i inne dane.
    * Może również ostrzegać pracowników służ

## Azure AI Health Bot
https://learn.microsoft.com/en-us/azure/health-bot/quickstart-createyourfirstscenario

## Enable communication using the Direct Line channel
https://learn.microsoft.com/en-us/azure/health-bot/channels/directline

## Authentication in Direct Line API 3.0
https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-authentication?view=azure-bot-service-4.0

### Stwórz Azure Health Bot (krok 1) 
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/1_hbot_create.jpg "Obraz")

### Stwórz Azure Health Bot (krok 2)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/2_hbot_create2.jpg "Obraz")

### Azure Health Bot uruchomiony
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/3_hbot_deployed.jpg "Obraz")

### Health Bot Portal - zarządzanie scenariuszami
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/4_hbot_portal.jpg "Obraz")

### Dodaj nowy scenariusz
* Name: Hello world
* Scenario ID: hello
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/5_hbot_new_scenario.jpg "Obraz")

### Scenariusz "hello" stworzony
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/6_hbot_new_scenario2.jpg "Obraz")

### Dodaj element "Statement" do scenariusza (krok 1)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/7_hbot_new_scenario3.jpg "Obraz")

### Dodaj element "Statement" do scenariusza (krok 2)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/8_hbot_scenario_statement.jpg "Obraz")

### Wprowadź dane do elementu "Statement"
* Title: Greeting
* Display text: Hello, World!
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/9_hbot_statement_greetings.jpg "Obraz")

### Gotowy pierwszy element scenariusza
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/10_hbot_statement_greetings2.jpg "Obraz")

### Dodaj drugi element "Yes/No" do scenariusza (krok 1)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/11_hbot_statement_yes_no.jpg "Obraz")

### Dodaj drugi element "Yes/No" do scenariusza (krok 2)
* Display text: Would you like to see a doctor?
* Input variable: ShouldScheduleDoctor
* Maximum number of retries: 1
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/12_hbot_statement_schedule_prompt.jpg "Obraz")

### Połącz elementy w scenariuszu
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/13_hbot_statement_schedule_prompt2.jpg "Obraz")

### Dodaj kolejne dwa elementy "Statement": "Good bye", "Start Scehdule"
* Połącz z poprzednimi elementami
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/14_hbot_statement_schedule_prompt3.jpg "Obraz")

### Przetestuj Health Bot w Web Chat
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/15_hbot_statement_scenario_run.jpg "Obraz")

### Przypisz scenariusz "hello" jako "Automatic welcome scenario"
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/16_hbot_automatic_scenario.jpg "Obraz")

### Skopiuj "DirectLine secret"
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/17_hbot_direct_line_secret.jpg "Obraz")

## Praktyczne zastosowanie Health Bot w programie Python
https://github.com/lukpaw/mslearn-ai-language/blob/main/Labfiles/10-health-bot/Python/health-bot/health-bot.py

### Program do komunikacji z botem

* Program umożliwia komunikację z botem za pomocą interfejsu DirectLine.
* DirectLine to usługa firmy Microsoft do tworzenia botów konwersacyjnych.
* Program wykorzystuje bibliotekę aiohttp do obsługi asynchronicznych żądań HTTP.

### Klasy

* Program definiuje trzy klasy: DirectLineToken, ChatConfig i test_bot.
* Klasa DirectLineToken przechowuje informacje o tokenie DirectLine.
* Klasa ChatConfig przechowuje informacje o konfiguracji czatu.
* Klasa test_bot demonstruje komunikację z botem.

### Funkcje asynchroniczne

* Program definiuje funkcje asynchroniczne:
    * get_direct_line_token: pobiera token DirectLine.
    * new_conversation: tworzy nową konwersację z botem.
    * send_activity: wysyła wiadomość do bota.
    * get_activities: pobiera wiadomości od bota.
    * interaction: wysyła i odbiera wiadomości.

### Test bota

* Funkcja test_bot demonstruje komunikację z botem:
    1. Pobiera token DirectLine.
    2. Tworzy nową konwersację z botem.
    3. Wysyła wiadomość do bota.
    4. Pobiera odpowiedzi od bota i drukuje je na konsoli.
