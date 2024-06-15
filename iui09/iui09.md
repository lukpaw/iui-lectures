## Mobilne roboty jako dostawcy usług

Mobilne roboty stają się coraz bardziej powszechne w różnych dziedzinach, nie tylko w usługach informacyjnych. 
Wykorzystywane są one w szerokim zakresie zastosowań, od domowych urządzeń sprzątających po złożone systemy autonomiczne w przemyśle.

**Przykładowe zastosowania mobilnych robotów:**

* **Domowe roboty sprzątające:** Roboty odkurzające, roboty mopujące, roboty czyszczące okna
* **Roboty ogrodowe:** Autonomiczne kosiarki do trawy
* **Roboty przemysłowe:** Roboty spawalnicze, roboty montażowe, roboty transportowe
* **Roboty medyczne:** Roboty chirurgiczne, roboty rehabilitacyjne, roboty asystujące
* **Roboty wojskowe:** Roboty rozpoznawcze, roboty saperskie, roboty bojowe
* **Roboty ratunkowe:** Roboty poszukiwawczo-ratownicze, roboty gaśnicze, roboty do usuwania gruzu
* **Roboty edukacyjne:** Roboty edukacyjne do nauki programowania, robotyki i inżynierii
* **Roboty usługowe:** Roboty do obsługi klienta, roboty do dostarczania towarów, roboty do transportu pasażerów

**Korzyści z wykorzystywania mobilnych robotów:**

* **Zwiększona wydajność i produktywność**
* **Poprawa bezpieczeństwa i zmniejszenie ryzyka wypadków**
* **Obniżenie kosztów operacyjnych**
* **Zwiększona dokładność i precyzja**
* **Możliwość pracy w niebezpiecznych lub trudnych warunkach**
* **Zwiększona elastyczność i skalowalność**
* **Poprawa obsługi klienta i satysfakcji**

**Wyzwania związane z wykorzystywaniem mobilnych robotów:**

* **Wysokie koszty początkowe**
* **Złożoność integracji z istniejącymi systemami**
* **Kwestie bezpieczeństwa i etyczne**
* **Ograniczenia technologiczne**
* **Akceptacja społeczna**

**Przyszłość mobilnych robotów:**

Oczekuje się, że rynek mobilnych robotów będzie nadal szybko rosnąć w nadchodzących latach. 
Nowe technologie, takie jak sztuczna inteligencja, uczenie maszynowe i internet rzeczy, otwierają nowe możliwości dla mobilnych robotów. 
Możemy się spodziewać, że roboty staną się jeszcze bardziej autonomiczne, inteligentne i wszechstronne, co doprowadzi do jeszcze szerszego zakresu zastosowań.

## Wybór platformy dla mobilnych robotów

Wybór odpowiedniej platformy do tworzenia mobilnego robota jest kluczowy dla sukcesu projektu. Należy wziąć pod uwagę wiele czynników, takich jak:

* **Poziom umiejętności:** Doświadczonym programistom łatwiej będzie pracować z bardziej złożonymi platformami, podczas gdy początkujący użytkownicy mogą preferować bardziej przyjazne dla użytkownika platformy.
* **Budżet:** Niektóre platformy są droższe od innych, a do niektórych platform mogą być wymagane dodatkowe komponenty elektroniczne.
* **Funkcjonalność:** Należy określić, jakie funkcje ma mieć robot i wybrać platformę, która może je obsłużyć.
* **Dostępność zasobów:** Należy sprawdzić, czy dostępne są zasoby edukacyjne i społeczność użytkowników dla wybranej platformy.

**Trzy popularne platformy do tworzenia mobilnych robotów:**

* **Arduino:** Prosta i niedroga platforma, idealna dla początkujących użytkowników i projektów o niskiej mocy obliczeniowej.
* **Raspberry Pi:** Potężny komputer jednopłytkowy, idealny dla bardziej złożonych projektów wymagających przetwarzania obrazu, rozpoznawania mowy i uczenia maszynowego.
* **LEGO Mindstorms:** Intuicyjny system robotyki edukacyjnej, idealny dla dzieci i początkujących użytkowników.

**Każda z tych platform ma swoje wady i zalety, a wybór odpowiedniej platformy zależy od konkretnych potrzeb i wymagań projektu.**

## Platforma Arduino

![arduino.png](https://github.com/lukpaw/iui-lectures/blob/main/iui08/img/arduino.png "Arduino Uno")

Source: https://store-usa.arduino.cc/products/arduino-uno-rev3

**Arduino to wszechstronna i łatwa w użyciu platforma mikrosterownikowa typu open-source, idealna dla osób w każdym wieku i z różnym poziomem doświadczenia.** Swoją popularność zawdzięcza prostocie obsługi, niskim kosztom i szerokiej gamie zastosowań. 

**Z Arduino możesz zbudować niemal każdy rodzaj robota mobilnego,** od prostych pojazdów sterowanych pilotem po inteligentne systemy autonomiczne. Platforma składa się z płytki mikrosterownikowej zawierającej procesor, pamięć i inne komponenty elektroniczne, a także z języka programowania opartego na C++. Język ten jest łatwy do nauczenia się nawet dla osób bez doświadczenia programistycznego.

* Arduino działa bez systemu operacyjnego, takiego jak Windows czy Linux, dzięki bootloaderowi i pamięci flash. 
* Bootloader jest to mały program zapisany w pamięci flash mikrokontrolera Arduino. Odpowiedzialny jest za uruchomienie procesora mikrokontrolera i załadowanie programu użytkownika z pamięci flash do pamięci RAM.

## Zalety i wady platformy Arduino

**Zalety:**

* **Przystępność:** Arduino jest niedrogą platformą, co czyni ją dostępną dla hobbystów, studentów i szkół. Dostępne są również tańsze klony Arduino.
* **Łatwość użytkowania:** Intuicyjny język programowania i bogate materiały edukacyjne ułatwiają rozpoczęcie pracy z Arduino nawet osobom początkującym.
* **Wszechstronność:** Platforma jest wysoce modułowa, co pozwala na łatwe rozbudowywanie i dostosowywanie projektów do indywidualnych potrzeb. Szeroki wybór płytek Arduino i modułów rozszerzeń umożliwia dodawanie nowych funkcji i rozszerzanie możliwości robota.
* **Otwartość:** Arduino jest platformą typu open-source, co oznacza, że oprogramowanie i schematy są dostępne bezpłatnie i mogą być dowolnie modyfikowane.
* **Społeczność:** Wokół Arduino istnieje duża i aktywna społeczność użytkowników, która chętnie dzieli się wiedzą i pomaga w rozwiązywaniu problemów.

**Wady:**

* **Ograniczona moc obliczeniowa:** W porównaniu do innych platform, moc obliczeniowa Arduino jest ograniczona, co może ograniczać jego zastosowanie w bardziej wymagających projektach, takich jak przetwarzanie obrazu czy uczenie maszynowe.
* **Brak systemu operacyjnego:** Brak wbudowanego systemu operacyjnego może utrudniać pracę z bardziej złożonymi funkcjami i ograniczać możliwości sieciowe.
* **Szybkość programowania:** Programowanie Arduino może być wolniejsze niż w przypadku innych platform, ze względu na konieczność kompilowania kodu przed jego uruchomieniem.
* **Wielkość:** Płytki Arduino mogą być stosunkowo duże i ciężkie w porównaniu z mikrokontrolerami o mniejszej mocy obliczeniowej.

**Podsumowując, Arduino to świetna platforma do tworzenia mobilnych robotów dla osób początkujących i hobbystów.** Należy jednak wziąć pod uwagę ograniczenia mocy obliczeniowej i brak systemu operacyjnego przy wyborze platformy do bardziej zaawansowanych projektów.

## Przykładowy kod w języku Arduino (C++)

```c++
// Definiujemy pin LED jako wyjście
const int ledPin = 13;

void setup() {
  // Inicjalizujemy pin LED jako wyjście
  pinMode(ledPin, OUTPUT);
}

void loop() {
  // Włączamy diodę LED
  digitalWrite(ledPin, HIGH);
  delay(1000); // Czekamy 1 sekundę

  // Wyłączamy diodę LED
  digitalWrite(ledPin, LOW);
  delay(1000); // Czekamy 1 sekundę
}
```

**Wyjaśnienie kodu:**

* **`const int ledPin = 13;`**: Ta linia definiuje stałą o nazwie `ledPin` i przypisuje jej wartość 13. Oznacza to, że pin 13 na płytce Arduino zostanie użyty do sterowania diodą LED.
* **`void setup()`**: Ta funkcja jest wykonywana tylko raz, podczas inicjalizacji programu. W tej funkcji ustawiamy pin LED jako wyjście.
* **`void loop()`**: Ta funkcja jest wykonywana w pętli, co oznacza, że ​​jej kod jest powtarzany ciągle. W tej funkcji włączamy i wyłączamy diodę LED z odstępem 1 sekundy.
* **`digitalWrite(ledPin, HIGH);`**: Ta linia włącza diodę LED podłączoną do pinu `ledPin`.
* **`delay(1000);`**: Ta funkcja powoduje zatrzymanie programu na 1000 milisekund (1 sekunda).
* **`digitalWrite(ledPin, LOW);`**: Ta linia wyłącza diodę LED podłączoną do pinu `ledPin`.

Powyższy kod jest prostym przykładem i może być modyfikowany w celu dodania bardziej złożonych funkcji, takich jak sterowanie silnikiem lub odczytywanie danych z czujników.

## Dodatkowe możliwości języka Arduino

Język programowania Arduino oferuje wiele dodatkowych funkcji, które można wykorzystać do tworzenia bardziej zaawansowanych robotów mobilnych. Niektóre z nich to:

* **Sterowanie silnikami:** Można używać funkcji języka Arduino do sterowania silnikami DC (prądu stałego) i serwomechanizmami (może precyzyjnie obracać wałem o określony kąt w dowolnym kierunku), co pozwala na ruch robota.
* **Odczytywanie danych z czujników:** Można podłączyć do Arduino różne czujniki, takie jak czujniki odległości, światła, temperatury lub dotyku, i odczytywać z nich dane, aby sterować zachowaniem robota.
* **Komunikacja:** Można używać Arduino do komunikacji z innymi urządzeniami za pomocą różnych interfejsów, takich jak Bluetooth, Wi-Fi lub RS232.
* **Obsługa wyświetlacza:** Można podłączyć do Arduino wyświetlacz LCD lub OLED i wyświetlać na nim informacje, takie jak stan robota lub odczyty z czujników.

## Platforma Raspberry Pi

![raspberry_pi.png](https://github.com/lukpaw/iui-lectures/blob/main/iui08/img/raspberry_pi.png "Raspberry Pi 4 Computer")

Source: https://www.amazon.com/Raspberry-Pi-Computer-Suitable-Workstation/dp/B0899VXM8F

**Raspberry Pi to niewielki komputer jednopłytkowy, idealny do tworzenia robotów mobilnych, systemów automatyki domowej i projektów multimedialnych.** 
Jest popularny wśród hobbystów, studentów i profesjonalistów ze względu na swoją moc obliczeniową, wszechstronność i przystępną cenę. 
Raspberry Pi może być używany do sterowania silnikami, odczytywania danych z czujników, przetwarzania obrazu i wykonywania wielu innych zadań.

## Zalety i wady platformy Raspberry Pi

**Zalety:**

* **Moc obliczeniowa:** Raspberry Pi posiada znacznie większą moc obliczeniową niż Arduino, co czyni je lepszym wyborem do bardziej wymagających projektów, takich jak przetwarzanie obrazu, uczenie maszynowe i sieci neuronowe.
* **Wszechstronność:** Raspberry Pi posiada szeroką gamę funkcji, w tym procesor graficzny, moduły Wi-Fi i Bluetooth, a także złącza GPIO, co czyni je idealnym do różnych projektów.
* **Łatwość użytkowania:** Raspberry Pi działa na systemie operacyjnym Linux, co ułatwia instalowanie oprogramowania i programowanie. Dostępnych jest wiele zasobów edukacyjnych i społeczność użytkowników jest bardzo pomocna.
* **Niska cena:** Raspberry Pi jest stosunkowo niedrogą platformą, co czyni ją dostępną dla hobbystów, studentów i szkół.

**Wady:**

* **Większy rozmiar i ciężar:** Raspberry Pi jest większe i cięższe niż Arduino, co może być wadą w przypadku niektórych projektów robotyki mobilnej.
* **Wyższy koszt akcesoriów:** Do uruchomienia Raspberry Pi potrzebne są dodatkowe akcesoria, takie jak karta microSD, zasilacz i kabel HDMI, co może zwiększyć całkowity koszt platformy.
* **Złożoność:** Raspberry Pi jest bardziej złożoną platformą niż Arduino, co może stanowić wyzwanie dla początkujących użytkowników.

**Informacje dodatkowe:**
* *Karta microSD:* Na karcie microSD zainstalowany jest system operacyjny i wszystkie aplikacje.
* *Zasilacz:* Raspberry Pi potrzebuje zasilania, aby działać. Zasilacz dostarcza niezbędną moc do płytki.
* *Kabel HDMI:* Raspberry Pi nie posiada wbudowanego wyświetlacza. Aby wyświetlać obraz na monitorze lub telewizorze, potrzebny jest kabel HDMI.

## Przykładowy kod w języku Python dla Raspberry Pi

```python
import time
import RPi.GPIO as GPIO

# Ustaw pin GPIO 18 jako wyjście
GPIO.setmode(GPIO.BCM)
GPIO.setup(18, GPIO.OUT)

while True:
  # Włącz diodę LED
  GPIO.output(18, GPIO.HIGH)
  time.sleep(1)

  # Wyłącz diodę LED
  GPIO.output(18, GPIO.LOW)
  time.sleep(1)
```

**Wyjaśnienie kodu:**

* `import time`: Importuje bibliotekę `time` do opóźniania wykonania kodu.
* `import RPi.GPIO as GPIO`: Importuje bibliotekę `RPi.GPIO` do sterowania pinami GPIO.
* `GPIO.setmode(GPIO.BCM)`: Ustawia tryb numerowania pinów GPIO na GPIO BCM.
* `GPIO.setup(18, GPIO.OUT)`: Ustawia pin GPIO 18 jako wyjście.
* `while True:`: Pętla `while` powoduje ciągłe wykonywanie kodu.
* `GPIO.output(18, GPIO.HIGH)`: Włącza diodę LED podłączoną do pinu GPIO 18.
* `time.sleep(1)`: Opóźnia wykonanie kodu o 1 sekundę.
* `GPIO.output(18, GPIO.LOW)`: Wyłącza diodę LED podłączoną do pinu GPIO 18.
* `time.sleep(1)`: Opóźnia wykonanie kodu o 1 sekundę.

## Dodatkowe możliwości Raspberry Pi

Raspberry Pi oferuje wiele dodatkowych funkcji, które można wykorzystać do tworzenia bardziej zaawansowanych robotów mobilnych. Niektóre z nich to:

* **Sterowanie silnikami:** Można używać bibliotek programowania do sterowania silnikami DC i serwomechanizmami, co pozwala na ruch robota.
* **Odczytywanie danych z czujników:** Można podłączyć do Raspberry Pi różne czujniki i odczytywać z nich dane, aby sterować zachowaniem robota.
* **Komunikacja:** Można używać Raspberry Pi do komunikacji z innymi urządzeniami za pomocą Wi-Fi, Bluetooth lub sieci

## Platforma LEGO Mindstorms

![lego_mindstorm.png.png](https://github.com/lukpaw/iui-lectures/blob/main/iui08/img/lego_mindstorm.png "Raspberry Pi 4 Computer")

Source: https://www.amazon.com/LEGO-MINDSTORMS-31313-Educational-Programming/dp/B00CWER3XY?th=1

*Platforma LEGO Mindstorms to system konstrukcyjny i programistyczny przeznaczony do tworzenia robotów i innych interaktywnych modeli.* 
Użytkownicy w każdym wieku mogą tworzyć z klocków LEGO roboty, które poruszają się, reagują na otoczenie i wykonują złożone zadania. 
Platforma Mindstorms jest łatwa w użyciu i oferuje szeroką gamę funkcji, które pozwalają użytkownikom na tworzenie kreatywnych i edukacyjnych projektów.

## Zalety i wady platformy LEGO Mindstorms

**Zalety:**

* **Łatwość użytkowania:** Platforma Mindstorms jest łatwa w użyciu nawet dla osób bez doświadczenia w programowaniu. Dostępne są intuicyjne oprogramowanie i instrukcje, które pomagają użytkownikom w szybkim rozpoczęciu pracy.
* **Wszechstronność:** Z klocków LEGO można zbudować szeroką gamę robotów i modeli, co pozwala użytkownikom na realizację swoich pomysłów. Platforma Mindstorms oferuje również szeroką gamę czujników i siłowników, które można wykorzystać do rozszerzenia możliwości robotów.
* **Kreatywność:** Platforma Mindstorms zachęca do kreatywności i rozwiązywania problemów. Użytkownicy mogą wymyślać własne projekty i wykorzystywać roboty do nauki o różnych tematach, takich jak fizyka, matematyka i inżynieria.
* **Edukacja:** Platforma Mindstorms jest doskonałym narzędziem edukacyjnym, które może być używane do nauczania dzieci i dorosłych o programowaniu, robotyce i technologii. Dostępnych jest wiele zasobów edukacyjnych, które wspierają nauczanie z wykorzystaniem platformy Mindstorms.

**Wady:**

* **Koszt:** Platforma Mindstorms może być droga, zwłaszcza jeśli chcesz zbudować bardziej złożone roboty. Dostępne są jednak tańsze zestawy, które są dobrym punktem wyjścia dla początkujących.
* **Ograniczenia programistyczne:** Język programowania Mindstorms jest stosunkowo prosty, co może ograniczać możliwości bardziej doświadczonych użytkowników. Istnieją jednak sposoby na rozszerzenie możliwości języka programowania za pomocą dodatkowych narzędzi i bibliotek.
* **Wytrzymałość:** Roboty zbudowane z klocków LEGO mogą nie być tak wytrzymałe jak roboty zbudowane z innych materiałów. Należy je ostrożnie obsługiwać, aby uniknąć uszkodzeń.

## Przykładowy program w języku programowania Mindstorms

```
// Program powoduje, że robot porusza się naprzód przez 2 sekundy, a następnie zatrzymuje się.

start(
  moveForward(power: 50) for 2 seconds,
  stop()
);
```

**Wyjaśnienie programu:**

* `start()`: Rozpoczyna wykonywanie programu.
* `moveForward(power: 50)`: Każe robotowi poruszać się naprzód z mocą 50%.
* `for 2 seconds`: Określa czas trwania ruchu robota na 2 sekundy.
* `stop()`: Każe robotowi się zatrzymać.

## Dodatkowe możliwości LEGO Mindstorms

Platforma LEGO Mindstorms oferuje wiele dodatkowych funkcji, które można wykorzystać do tworzenia bardziej zaawansowanych robotów. Niektóre z nich to:

* **Sterowanie silnikami:** Można używać języka programowania Mindstorms do sterowania silnikami DC i serwomechanizmami, co pozwala na ruch robota w różnych kierunkach.
* **Odczytywanie danych z czujników:** Można podłączyć do robota różne czujniki, takie jak czujniki odległości, światła i dotyku, i odczytywać z nich dane, aby sterować zachowaniem robota.
* **Komunikacja:** Można używać platformy Mindstorms do komunikacji z innymi urządzeniami za pomocą Bluetooth lub Wi-Fi.
* **Interfejs użytkownika:** Można stworzyć interfejs użytkownika na ekranie robota, który pozwala użytkownikowi sterować robotem lub wyświetlać informacje.

## Podsumowanie

* Platformy Arduino, Raspberry Pi i LEGO Mindstorms oferują szeroki zakres możliwości tworzenia mobilnych robotów.
* Wybór platformy zależy od konkretnych potrzeb i wymagań projektu.
* Mobilne roboty mogą świadczyć szeroki zakres usług w dziedzinie usług informacyjnych, co czyni je cennym narzędziem dla wielu aplikacji.