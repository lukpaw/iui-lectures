## Rodzaje aplikacji komputerowych

### Aplikacje desktopowe

* Instalowane na komputerze użytkownika
* Działają niezależnie od przeglądarki internetowej
* Oferują szeroki zakres funkcji i możliwości
* Przykładowe nazwy: Microsoft Word, Adobe Acrobat Reader

**Zalety:**

* Wysoka wydajność i moc obliczeniowa
* Dostęp do większej liczby funkcji
* Możliwość pracy offline
* Szybsze działanie w przypadku złożonych zadań

**Wady:**

* Wymagają instalacji na każdym komputerze
* Zajmują miejsce na dysku twardym
* Mogą być aktualizowane ręcznie
* Niektóre funkcje mogą być niedostępne online

### Aplikacje webowe

* Dostępne przez przeglądarkę internetową
* Nie wymagają instalacji na komputerze
* Łatwe w dostępie z dowolnego miejsca
* Przykłady nazwy: Gmail, Facebook

**Zalety:**

* Łatwość dostępu i użytkowania
* Nie wymagają instalacji
* Automatyczne aktualizacje
* Możliwość pracy na różnych urządzeniach

**Wady:**

* Mniejsza wydajność i moc obliczeniowa
* Ograniczony zakres funkcji
* Wymagane połączenie internetowe
* Mogą być wolniejsze w przypadku złożonych zadań

### Aplikacje mobilne

* Przeznaczone na urządzenia mobilne (smartfony, tablety)
* Dostępne w sklepach z aplikacjami (App Store, Google Play)
* Zaprojektowane do użytku na urządzeniach dotykowych
* Przykłady nazwy: Instagram, Spotify

**Zalety:**

* Wygodne i łatwe w użyciu na urządzeniach mobilnych
* Dostosowane do mniejszych ekranów
* Możliwość korzystania z funkcji GPS i aparatu
* Dostępność offline (w niektórych przypadkach)

**Wady:**

* Mniejszy ekran i ograniczona moc obliczeniowa
* Ograniczony zakres funkcji
* Mogą być droższe niż aplikacje webowe
* Wymagają regularnego ładowania

### Podsumowanie

Każdy rodzaj aplikacji ma swoje zalety i wady. Wybór odpowiedniej aplikacji zależy od potrzeb użytkownika, dostępnego sprzętu i rodzaju wykonywanych zadań.


## Aplikacje webowe

### Monolityczna aplikacja webowa (np. Spring Boot z JavaServer Pages)

**Opis:**

* Pojedyncza jednostka programistyczna łącząca frontend i backend
* Technologia: Spring Boot (backend), JavaServer Pages (JSP) (frontend)

**Zalety:**

* Prosta struktura i łatwość implementacji
* Szybki czas rozwoju na wczesnym etapie
* Niskie koszty początkowe
* Łatwe zarządzanie konfiguracją

**Wady:**

* Trudność w skalowaniu i dodawaniu nowych funkcji
* Słabe wykrywanie i izolowanie błędów
* Ryzyko rozrostu kodu i spadku wydajności
* Utrudniona automatyzacja testowania i wdrażania

### Aplikacja z oddzielonym frontem i backendem (np. Spring Boot z Angular)

**Opis:**

* Dwie niezależne jednostki programistyczne: frontend i backend
* Technologia: Spring Boot (backend), Angular (frontend)

**Zalety:**

* Łatwość skalowania i dodawania nowych funkcji
* Szybsze tempo rozwoju i wdrażania
* Lepsze wykrywanie i izolowanie błędów
* Zwiększona odporność na awarie
* Ułatwiona automatyzacja testowania i wdrażania

**Wady:**

* Bardziej złożona architektura i zarządzanie
* Wyższe koszty początkowe i czas rozwoju
* Wymagane umiejętności DevOps i zarządzania mikroserwisami
* Potencjalne problemy z wydajnością i bezpieczeństwem

### Podsumowanie

**Monolityczna aplikacja webowa:**

* Dobra dla prostych aplikacji o niskich wymaganiach skalowalności.
* Łatwa do nauczenia i zaimplementowania.
* Może być trudna do skalowania i rozbudowy w przyszłości.

**Aplikacja z oddzielonym frontem i backendem:**

* Dobra dla skalowalnych i elastycznych aplikacji.
* Oferuje wiele funkcji i ułatwień.
* Bardziej złożona i wymagająca większych umiejętności developerskich.

## Architektury backendu

### Monolityczna architektura backendu

* Pojedyncza jednostka programistyczna zawierająca wszystkie funkcje
* Łatwa do zrozumienia i rozwijania na początku
* Przykłady: starsze wersje systemów CRM, ERP

**Zalety:**

* Prosta struktura i łatwość implementacji
* Szybszy czas rozwoju na wczesnym etapie
* Niskie koszty początkowe
* Łatwe zarządzanie konfiguracją

**Wady:**

* Trudność w skalowaniu i dodawaniu nowych funkcji
* Słabe wykrywanie i izolowanie błędów
* Ryzyko rozrostu kodu i spadku wydajności
* Utrudniona automatyzacja testowania i wdrażania

### Architektura backendu typu Mikroserwisy

* Zdecentralizowana architektura składająca się z wielu niezależnych usług
* Każda usługa odpowiada za określoną funkcjonalność
* Komunikacja między usługami odbywa się za pomocą interfejsów API
* Przykłady: Netflix, Amazon, Spotify

**Zalety:**

* Łatwość skalowania i dodawania nowych funkcji
* Szybsze tempo rozwoju i wdrażania
* Lepsze wykrywanie i izolowanie błędów
* Zwiększona odporność na awarie
* Ułatwiona automatyzacja testowania i wdrażania

**Wady:**

* Bardziej złożona architektura i zarządzanie
* Wyższe koszty początkowe i czas rozwoju
* Wymagane umiejętności DevOps i zarządzania mikroserwisami
* Potencjalne problemy z wydajnością i bezpieczeństwem

### Podsumowanie

**Monolityczna architektura backendu:**

* Dobra dla prostych aplikacji o niskich wymaganiach skalowalności.
* Łatwa do nauczenia i zaimplementowania.
* Może być trudna do skalowania i rozbudowy w przyszłości.

**Architektura backendu typu Mikroserwisy:**

* Dobra dla skalowalnych i elastycznych aplikacji.
* Oferuje wiele funkcji i ułatwień.
* Bardziej złożona i wymagająca większych umiejętności developerskich.

## Protokoły komunikacji

### Protokół UDP (User Datagram Protocol)

* Protokół warstwy transportowej modelu OSI
* Służy do przesyłania datagramów (jednostek danych)
* Nie gwarantuje dostarczenia datagramów
* Nie ma kontroli przepływu ani retransmisji
* Jest szybki i lekki
* Przydatny do:
    * Strumieniowania mediów
    * Gier online
    * RTP (transmisja multimediów w czasie rzeczywistym)
    * DNS (rozwiązywanie nazw domenowych)
    * DHCP (przydzielanie adresów IP)

### Protokół TCP/IP (Transmission Control Protocol/Internet Protocol)

* Zestaw protokołów warstwy transportowej i sieciowej modelu OSI
* Gwarantuje dostarczenie danych
* Posiada kontrolę przepływu i retransmisję
* Jest bardziej złożony i obciążający niż UDP
* Przydatny do:
    * Komunikacji z bazą danych
    * Komunikacji SIP
    * SMTP (poczta e-mail)
    * SSH (zdalny dostęp)
    * Telnet (zdalne sterowanie)
### Protokół HTTP (Hypertext Transfer Protocol)

* Protokół warstwy aplikacji
* Służy do przesyłania hipertekstu (stron internetowych) i danych
* Opiera się na protokole TCP/IP
* Definiuje metody żądań i odpowiedzi
* Jest używany do:
    * Pobierania stron internetowych, obrazów, filmów i innych zasobów
    * Komunikacji typu REST
    * Komunikacji typu SOAP

### Podsumowanie

**Protokół UDP:**

* Szybki i bezpołączeniowy
* Nie gwarantuje dostarczenia datagramów
* Przydatny do strumieniowania mediów, gier online, RTP

**Protokół TCP/IP:**

* Niezawodny i zorientowany na połączenie
* Gwarantuje dostarczenie danych
* Przydatny do komunikacji z bazą danych, komunikacji SIP, SMTP

**Protokół HTTP:**

* Służy do przesyłania hipertekstu (stron internetowych) i danych
* Opiera się na protokole TCP/IP
* Jest używany do pobierania stron internetowych, obrazów, filmów i innych zasobów, a także do komunikacji REST i WebService'ów

## Protokół HTTP

### Metody HTTP

* Najczęstsze metody:
    * GET - pobieranie danych (np. strony internetowej)
    * POST - wysyłanie danych (np. formularza)
    * PUT - aktualizacja danych
    * DELETE - usuwanie danych
    * HEAD - pobieranie nagłówków
    * OPTIONS - sprawdzanie dostępnych opcji

**Przykład GET:**

```
GET /index.html HTTP/1.1
Host: www.example.com
```

**Przykład POST:**

```
POST /login HTTP/1.1
Host: www.example.com
Content-Type: application/x-www-form-urlencoded
Content-Length: 32

username=johndoe&password=secret
```

### Kody odpowiedzi HTTP

* Kody odpowiedzi informują o statusie żądania
* Przykładowe kody:
    * 200 OK - żądanie zostało pomyślnie wykonane
    * 404 Not Found - żądany zasób nie istnieje
    * 401 Unauthorized - brak autoryzacji
    * 500 Internal Server Error - błąd serwera

### Nagłówki HTTP

* Dodatkowe informacje o żądaniu lub odpowiedzi
* Przykłady nagłówków:
    * Accept-Charset - określa akceptowane kodowania znaków
    * Content-Type - określa typ MIME przesyłanych danych
    * Content-Length - określa długość danych
    * Location - określa adres URL przekierowania

### MIME

**Punkty:**

* Multipurpose Internet Mail Extensions
* Standard definiujący typy danych przesyłanych w Internecie
* Przykłady typów MIME:
    * text/html - strona internetowa
    * image/png - obraz PNG
    * application/json - dane JSON

### Cookie

**Punkty:**

* Małe pliki tekstowe przechowywane na komputerze użytkownika
* Używane do śledzenia stanu sesji
* Przykłady zastosowań:
    * Zapamiętanie preferencji użytkownika
    * Utrzymanie sesji użytkownika

### Sesje

**Punkty:**

* Mechanizm śledzenia stanu interakcji użytkownika z serwerem
* Przechowuje dane sesji na serwerze
* Przykłady zastosowań:
    * Koszyk w sklepie internetowym
    * Autoryzacja użytkownika

### Web Storage

* API do przechowywania danych w przeglądarce internetowej
* Dwa rodzaje:
    * Local Storage - dane dostępne tylko dla danej strony internetowej
    * Session Storage - dane usuwane po zamknięciu przeglądarki

**Przykład:**

```javascript
// Ustawienie wartości w Local Storage
localStorage.setItem("username", "johndoe");

// Pobranie wartości z Local Storage
const username = localStorage.getItem("username");
```

### Podsumowanie

**Protokół HTTP:**

* Podstawowy protokół Internetu
* Służy do przesyłania danych
* Definiuje metody żądań i odpowiedzi
* Używa kodów odpowiedzi, nagłówków, MIME, Cookie, sesji i Web Storage

## Strony internetowe

### HTML (HyperText Markup Language)

* Język znaczników do tworzenia stron internetowych
* Definiuje strukturę strony
* Przykłady znaczników:
    * `html` - definiuje początek strony
    * `head` - zawiera informacje o stronie
    * `body` - zawiera treść strony
    * `h1` - nagłówek pierwszego poziomu
    * `p` - akapit
    * `img` - obrazek

**Przykład:**

```html
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Przykładowy formularz</title>
</head>
<body>
    <h1>Przykładowy formularz</h1>
    <form action="/submit">
        <label for="name">Imię:</label>
        <input type="text" id="name" name="name">
        <br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <br>
        <input type="submit" value="Wyślij">
    </form>
</body>
</html>
```

### CSS (Cascading Style Sheets)

* Język do stylizacji stron internetowych
* Definiuje wygląd strony
* Przykłady właściwości CSS:
    * `color` - kolor tekstu
    * `font-size` - rozmiar czcionki
    * `background-color` - kolor tła
    * `border` - ramka
    * `margin` - margines

**Przykład kodu:**

```css
h1 {
    color: red;
    font-size: 24px;
}

label {
    font-weight: bold;
}

.required::after {
    content: "*";
    color: red;
}

input[type="submit"] {
    background-color: blue;
    color: white;
}
```

### JavaScript

* Język programowania do interaktywnych stron internetowych
* Umożliwia dodanie dynamiki do strony
* Przykłady zastosowań JavaScript:
    * Walidacja formularzy
    * Animacje
    * Gry
    * Mapy interaktywne

**Przykład:**

```javascript
const form = document.querySelector("form");

form.addEventListener("submit", (event) => {
    event.preventDefault();

    const name = document.querySelector("#name").value;
    const email = document.querySelector("#email").value;

    if (!name || !email) {
        alert("Wypełnij wszystkie pola!");
        return;
    }

    // ...

    // Wysyłanie formularza
});
```

## Frameworki webowe

### Spring MVC z Thymeleaf

* Framework Spring MVC do tworzenia aplikacji webowych z Javą
* Umożliwia tworzenie interaktywnych i spersonalizowanych stron
* Łączy się z szablonami Thymeleaf do generowania dynamicznych stron HTML
* Przykładowe zastosowania:
    * Formularze logowania
    * Koszyki w sklepach internetowych
    * Systemy zarządzania treścią

**Przykład kodu:**

**Kontroler Spring MVC:**

```java
@Controller
public class MyController {

    @RequestMapping("/")
    public String index(Model model) {
        model.addAttribute("message", "Witaj w Spring MVC z Thymeleaf!");
        return "index";
    }
}
```

**Szablon Thymeleaf:**

```html
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Przykładowy szablon Thymeleaf</title>
</head>
<body>
    <h1>Przykładowy szablon</h1>
    <p>
        {{ message }}
    </p>
</body>
</html>
```

### Angular

* Framework JavaScript do tworzenia jednostronicowych aplikacji (SPA)
* Umożliwia tworzenie bogatych i interaktywnych interfejsów użytkownika
* Opiera się na komponentach i modułach
* Przykładowe zastosowania:
    * Aplikacje biznesowe
    * Strony internetowe z dużą ilością interakcji
    * Aplikacje mobilne hybrydowe

**Przykład kodu:**

```html
<h1>Przykładowy komponent Angular</h1>

<p>
    Ten komponent wyświetla wiadomość powitalną.
</p>

<button (click)="onButtonClick()">Kliknij mnie!</button>

<p>
    {{ message }}
</p>
```

```typescript
import { Component } from '@angular/core';

@Component({
    selector: 'my-app',
    templateUrl: './app.component.html'
})
export class AppComponent {
    message = 'Witaj w Angular!';

    onButtonClick() {
        this.message = 'Kliknięto przycisk!';
    }
}
```

### Podsumowanie

**Spring MVC z Thymeleaf i Angular to dwa różne frameworki do tworzenia stron internetowych:**

* Spring MVC z Thymeleaf to rozwiązanie po stronie serwera, które łączy Javę z szablonami Thymeleaf do generowania dynamicznych stron HTML.
* Angular to framework JavaScript po stronie klienta, który umożliwia tworzenie jednostronicowych aplikacji (SPA).

**Wybór frameworka zależy od specyficznych potrzeb projektu:**

* Spring MVC z Thymeleaf jest dobrym wyborem dla stron internetowych, które wymagają dużej dynamiki i integracji z Javą.
* Angular jest dobrym wyborem dla nowoczesnych aplikacji webowych o bogatym interfejsie użytkownika.

## Frameworki backendowe

### Spring Boot

* Framework do tworzenia aplikacji webowych z Javą
* Ułatwia tworzenie REST API
* Opiera się na starterach, które automatyzują konfigurację
* Przykładowe zastosowania:
    * Mikrousługi
    * Aplikacje webowe z interfejsem REST
    * Monolityczne aplikacje webowe

**Przykład kodu:**

```java
@SpringBootApplication
public class App {

    public static void main(String[] args) {
        SpringApplication.run(App.class, args);
    }
}

@RestController
@RequestMapping("/api")
public class ApiController {

    @GetMapping("/")
    public String index() {
        return "Witaj w Spring Boot!";
    }
}
```

### Flask Python

* Mikroframework do tworzenia aplikacji webowych z Pythonem
* Ułatwia tworzenie REST API
* Lekki i elastyczny
* Przykładowe zastosowania:
    * Mikrousługi
    * Aplikacje webowe z interfejsem REST
    * Prototypowanie

**Przykład kodu:**

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def index():
    return "Witaj w Flask!"

@app.route("/api")
def api():
    return {"message": "Witaj w API Flask!"}

if __name__ == "__main__":
    app.run()
```

## Podsumowanie

**Spring Boot i Flask to dwa różne frameworki do tworzenia aplikacji webowych:**

* Spring Boot to framework Java, który oferuje wiele funkcji ułatwiających tworzenie aplikacji webowych.
* Flask to framework Python, który jest lekki i elastyczny, idealny do prototypowania i tworzenia mikrousług.

**Wybór frameworka zależy od specyficznych potrzeb projektu:**

* Spring Boot jest dobrym wyborem dla dużych i złożonych aplikacji webowych.
* Flask jest dobrym wyborem dla małych i prostych aplikacji webowych.

## Przykład inteligentnego systemu informacyjnego

Architektura inteligentnego systemu informacyjnego typu ChatBot i VoiceBot. System składa się z następujących elementów:
* **Aplikacja frontend Angular:** Aplikacja webowa, która zapewnia interfejs użytkownika dla ChatBota.
* **Aplikacja backend (kilka Springbootów - mikroserwisy):** Aplikacja backendowa, która odpowiada na zapytania użytkowników i integruje się z systemami dziedzinowymi.
* **Baza danych PostgreSQL:** Baza danych do przechowywania danych systemowych.
* **In-memory data store Redis:** Szybki magazyn danych do przechowywania danych w pamięci podręcznej.
* **Serwer kolejek RabbitMQ:** Serwer kolejek do komunikacji asynchronicznej między komponentami systemu.
* **Azure Speech-service:** Usługa rozpoznawania mowy i syntezy mowy firmy Microsoft.
* **Serwer telekomunikacyjny Freeswitch:** Serwer telekomunikacyjny do obsługi połączeń głosowych.
* **Azure AI Bot Service:** Usługa firmy Microsoft do tworzenia i wdrażania chatbotów.
* **Serwer autoryzacji Keycloak:** Serwer do zarządzania autoryzacją i uwierzytelnianiem użytkowników.
* **Systemy dziedzinowe (CRM, ERP często legacy):** Systemy biznesowe, z których ChatBot i VoiceBot pobierają dane.

## SOA – budowanie systemów informatycznych jako usługi

### Architektura zorientowana na usługi (SOA)

* Koncepcja budowania systemów informatycznych jako niezależnych, współpracujących ze sobą usług
* Umożliwia tworzenie elastycznych i skalowalnych systemów
* Ułatwia integrację różnych systemów
* Przykłady zastosowań:
    * Integracja systemów biznesowych
    * Tworzenie portali internetowych
    * Budowanie systemów e-commerce

### Integracja w SOA
 
* Szyny danych ESB (Enterprise Service Bus): służą do przesyłania danych między różnymi komponentami SOA.
* Interfejsy API: REST i SOAP to popularne standardy interfejsów API do przesyłania danych między systemami.
* Serwery kolejek MQ (Message Queuing): służą do asynchronicznej komunikacji między komponentami SOA.

### Podsumowanie

* SOA to potężny paradygmat projektowania oprogramowania, który może być używany do tworzenia elastycznych, skalowalnych i zintegrowanych systemów informatycznych.
* Wybór odpowiednich technologii integracji w SOA zależy od specyficznych potrzeb projektu.

## Modele wdrażania systemów informatycznych: On-Premise i Cloud

**On-Premise:**

* Infrastruktura IT jest własnością i zarządzana przez firmę
* Większa kontrola i bezpieczeństwo
* Wyższe początkowe koszty
* Mniejsza elastyczność
* Wymaga większego zaangażowania IT

**Cloud:**

* Infrastruktura IT jest dostarczana i zarządzana przez zewnętrznego dostawcę
* Niższe początkowe koszty
* Większa elastyczność
* Mniejsza kontrola i bezpieczeństwo
* Wymaga mniejszego zaangażowania IT

## Przykładowe usługi inteligentne

* **Zamiana mowy na tekst:** Usługi takie jak Azure Speech-service transkrybują mowę na tekst w czasie rzeczywistym.
* **Zamiana tekstu na mowę:** Usługi takie jak Azure Speech-service generują mowę z tekstu, umożliwiając tworzenie realistycznych chatbotów i systemów nawigacyjnych.
* **Rozpoznawanie intencji:** Usługi takie jak Azure AI Bot Service rozpoznają intencje użytkownika na podstawie tekstu, umożliwiając tworzenie inteligentnych chatbotów, które rozumieją kontekst rozmowy.
* **Klasyfikacja treści:** Usługi takie jak Azure AI Language klasyfikują treści tekstowe według kategorii, np. tematu, emocji lub języka.
* **Rozpoznawanie emocji:** Sieci neuronowe mogą analizować obrazy i tekst, aby rozpoznawać emocje użytkownika.
* **Odpowiedzi na pytania:** Usługi takie jak ChatGPT odpowiadają na pytania użytkownika w sposób wyczerpujący i logiczny, nawet jeśli są one otwarte lub trudne.
* **Rozpoznawanie obrazów:** Usługi takie jak Google Cloud Vision API rozpoznają obiekty, sceny i tekst na obrazach.

## Systemy inteligentne: kluczowe filary

* **Usługi:** Samodzielne moduły funkcjonalne, dostępne za pomocą interfejsów API.
* **Usługi inteligentne:** Usługi wykorzystujące sztuczną inteligencję do realizacji zadań, np. rozpoznawanie obrazu, analiza tekstu, tłumaczenie języków.
* **Integracja:** Bezproblemowe łączenie różnych usług w celu tworzenia kompleksowych systemów.
* **Otwarte standardy:** Używanie uniwersalnych formatów danych i protokołów komunikacyjnych zapewniających interoperacyjność.
* **Skalowalna architektura:** Możliwość łatwego rozszerzania i dostosowywania systemu do zmieniających się potrzeb.
* **Bezpieczeństwo:** Ochrona danych i systemów przed nieautoryzowanym dostępem, wykorzystaniem i modyfikacją.

## Systemy inteligentne: Przykładowe zastosowania

* **Systemy rekomendacyjne:** Prezentują użytkownikowi produkty, które mogą go zainteresować.
* **Systemy rozpoznawania obrazu:** Rozpoznają obiekty, sceny i tekst na obrazach.
* **Systemy tłumaczenia maszynowego:** Tłumaczą tekst z jednego języka na drugi.
* **Systemy wnioskujące o wydanie kredytów:** Analizują dane o wnioskodawcy, aby ocenić jego zdolność kredytową.
* **Systemy zarządzania ruchem drogowym:** Optymalizują ruch drogowy i zmniejszają korki.
* **Systemy inteligentnego domu:** Sterują urządzeniami domowymi i zapewniają komfort użytkownika.
* **Systemy monitorowania infrastruktury:** Monitorują stan infrastruktury i ostrzegają o zagrożeniach.
* **Systemy wspomagania diagnostyki medycznej:** Wspomagają lekarzy w diagnozowaniu chorób.
* **Systemy personalizacji treści:** Dostosowują treści do preferencji użytkownika.
* **Systemy automatycznego generowania tekstu:** Generują tekst na podstawie określonych parametrów.
* **Systemy chatbotów wielojęzycznych:** Prowadzą konwersację z użytkownikiem w różnych językach.