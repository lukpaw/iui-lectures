## Tradycyjna komunikacja, a orkiestracja usług sieciowych

**Problem:**

Tradycyjna komunikacja synchroniczna między mikroserwisami może prowadzić do sztywnego powiązania usług, 
Single Point of Failure i problemów z utrzymaniem spójności danych.

**Rozwiązanie:**

Przejście na komunikację asynchroniczną z wykorzystaniem zdarzeń i kolejek.

**Wdrażanie:**

1. Wprowadzenie kolejki do wymiany zdarzeń.
2. Usługi komunikują się za pomocą zdarzeń, nie bezpośrednio.
3. Zwiększona elastyczność i skalowalność.
4. Wprowadzenie Single Point of Failure (SPOF) w postaci kolejki.
5. Potencjalne problemy ze spójnością (Consistency) i zdarzeniami (Events).

## Wprowadzenie orkiestratora

Wprowadzenie orkiestratora do nadzorowania procesu:

1. Orkiestrator wysyła komendy do usług.
2. Usługi realizują zadania po otrzymaniu zdarzenia.
3. Zwiększona kontrola i spójność procesu.
4. Wprowadzenie kolejnego SPOF w postaci orkiestratora.
5. Mniejsza elastyczność i utrudnione wdrażanie nowych wersji procesu.

## Silniki Workflow

Zastosowanie silnika workflow do wsparcia orkiestratora:

1. Wysoka niezawodność i monitorowanie procesu.
2. Łatwe wdrażanie nowych wersji procesu bez usuwania starych.
3. Wykorzystanie wizualnych narzędzi do definiowania procesu (np. BPMN 2.0).
4. Zapanowanie nad chaosem w złożonych procesach biznesowych.

## Silniki workflow dla orkiestratorów mikroserwisów

**Activiti**

* Lekki i wydajny silnik workflow dla platform Java
* Prosta konfiguracja i łatwość użytkowania
* Integracja z Spring Framework i innymi popularnymi technologiami Java
* Aktywna społeczność i wsparcie komercyjne

**Camunda BPMN**

* Popularny silnik workflow dla platform Java
* Szeroka gama funkcji, w tym zarządzanie procesami biznesowymi, reguły biznesowe i Case Management
* Integracja z różnymi systemami i frameworkami
* Duża społeczność i bogate zasoby dokumentacyjne

**Zeebe**

* Darmowy i open-source'owy silnik workflow
* Wysoka skalowalność i odporność na awarie
* Architektura oparta na zdarzeniach
* Integracja z różnymi językami programowania
* Wizualne modelowanie procesu w standardzie BPMN 2.0

**Apache Airflow**

* Platforma do zarządzania zadaniami open-source
* Stosowana do orkiestracji złożonych przepływów danych
* Możliwość integracji z różnymi systemami i narzędziami
* Duża społeczność i bogate zasoby dokumentacyjne

## Dodatkowe narzędzia ##

Oprócz silników workflow, dostępne są również inne narzędzia, które mogą ułatwić orkiestrację mikroserwisów, takie jak:

* Kolejki komunikatów (np. Kafka, RabbitMQ)
* Systemy koordynacji rozproszonej (np. ZooKeeper)
* Narzędzia do monitorowania i debugowania (np. Grafana, Prometheus)

## Wybór odpowiedniego silnika workflow zależy od wielu czynników, takich jak:

Wybór odpowiedniego silnika workflow:

* Wymagane funkcje
* Platforma technologiczna
* Poziom skalowalności
* Budżet
* Doświadczenie zespołu

Orkiestracja mikroserwisów może znacząco poprawić kontrolę nad procesami biznesowymi, zwiększyć ich elastyczność i skalowalność. 
Dostępnych jest wiele różnych silników workflow i narzędzi, które mogą ułatwić wdrożenie orkiestracji.

## Orkiestracja mikroserwisów w BPMN

**BPMN (Business Process Model and Notation)** to standardowy język modelowania procesów biznesowych, 
który pozwala na wizualne przedstawianie przepływów procesów, definiowanie zadań, ról i reguł biznesowych. 
Orkiestracja mikroserwisów może być realizowana przy użyciu BPMN, co ułatwia zrozumienie i komunikowanie złożonych procesów.

**Zalety orkiestracji BPMN:**

* **Czytelność:** Diagramy BPMN są łatwe do zrozumienia dla osób technicznych i nietechnicznych.
* **Komunikacja:** Modele BPMN ułatwiają komunikację między zespołami biznesowymi i technicznymi.
* **Standaryzacja:** BPMN to standardowy język, co ułatwia wymianę modeli między różnymi narzędziami.
* **Automatyzacja:** Modele BPMN mogą być automatyzowane za pomocą silników workflow.

**Modelowanie orkiestr mikroserwisów w BPMN:**

1. Zdefiniuj proces biznesowy za pomocą diagramu BPMN.
2. Zidentyfikuj mikroserwisy, które będą zaangażowane w proces.
3. Dla każdej mikrousługi utwórz zadanie BPMN.
4. Zdefiniuj przepływy sekwencji i równoległe między zadaniami.
5. Dodaj zdarzenia BPMN do wyzwalania i kończenia zadań.
6. Zdefiniuj reguły biznesowe BPMN do sterowania przepływem procesu.

## Przykład orkiestracji w BPMN:

Wyobraźmy sobie proces składania zamówienia w sklepie internetowym. Proces ten może być zmodelowany w BPMN przy użyciu następujących kroków:

1. Klient składa zamówienie na stronie internetowej.
2. System sklepu internetowego wysyła zdarzenie BPMN do mikrousługi zarządzania zamówieniami.
3. Mikrousługa zarządzania zamówieniami tworzy zamówienie w systemie i wysyła zdarzenie BPMN do mikrousługi zarządzania magazynem.
4. Mikrousługa zarządzania magazynem sprawdza dostępność produktów i rezerwuje je.
5. W przypadku braku produktów mikrousługa zarządzania magazynem wysyła zdarzenie BPMN do mikrousługi obsługi klienta.
6. Mikrousługa obsługi klienta informuje klienta o braku produktów i oferuje alternatywy.
7. Jeśli produkty są dostępne, mikrousługa zarządzania magazynem przygotowuje je do wysyłki i wysyła zdarzenie BPMN do mikrousługi wysyłkowej.
8. Mikrousługa wysyłkowa wysyła zamówienie do klienta i wysyła zdarzenie BPMN do mikrousługi zarządzania zamówieniami.
9. Mikrousługa zarządzania zamówieniami aktualizuje status zamówienia na "wysłane".

**Przykładowy kod BPMN w XML dla procesu składania zamówienia w sklepie internetowym**
[Example](https://github.com/lukpaw/iui-lectures/blob/main/iui05/bpmn.xml)
```xml
<?xml version="1.0" encoding="UTF-8"?>
<bpmn2:definitions xmlns:bpmn2="http://www.omg.org/bpmn/20" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                   xsi:schemaLocation="http://www.omg.org/bpmn/20 http://www.omg.org/bpmn/20/BPMN20.xsd">

    <bpmn2:process id="process_skladanieZamowienia" name="Proces składania zamówienia">

        <bpmn2:startEvent id="event_zlozenieZamowienia" name="Złożenie zamówienia przez klienta"/>

        <bpmn2:userTask id="task_weryfikacjaZamowienia" name="Weryfikacja zamówienia przez system">
            <bpmn2:extensionElements>
                <bpmn2:assignedUser>
                    <bpmn2:humanTaskResource id="resource_systemSklepu" name="System sklepu internetowego"/>
                </bpmn2:assignedUser>
            </bpmn2:extensionElements>
        </bpmn2:userTask>

        <bpmn2:sequenceFlow id="flow_weryfikacjaDoUtworzenia" from="event_zlozenieZamowienia"
                            to="task_weryfikacjaZamowienia"/>

        <bpmn2:serviceTask id="task_utworzZamowienie" name="Utworzenie zamówienia w mikrousłudze">
            <bpmn2:ioOperation id="io_utworzZamowienie" name="Utwórz zamówienie">
                <bpmn2:inMessage id="message_zamowienie" itemRef="item_zamowienie"/>
            </bpmn2:ioOperation>
            <bpmn2:extensionElements>
                <bpmn2:implementation>
                    <bpmn2:serviceImplementation class="com.example.microservice.ZamowieniaService"
                                                 method="utworzZamowienie"/>
                </bpmn2:implementation>
            </bpmn2:extensionElements>
        </bpmn2:serviceTask>
...      
        <bpmn2:complexType id="tns:DanePłatnicze">
            <bpmn2:sequence>
                <bpmn2:element name="metodaPłatności" type="xsd:string"/>
                <bpmn2:element name="numerKarty" type="xsd:string"/>
                <bpmn2:element name="dataWażności" type="xsd:date"/>
                <bpmn2:element name="cvv" type="xsd:int"/>
            </bpmn2:sequence>
        </bpmn2:complexType>

        <bpmn2:complexType id="tns:Dostepnosc">
            <bpmn2:sequence>
                <bpmn2:element name="produktyDostepne" type="xsd:boolean"/>
            </bpmn2:sequence>
        </bpmn2:complexType>

    </bpmn2:schema>

</bpmn2:definitions>
```

## Orkiestracja w Azure

Przepływy pracy orkiestracji to funkcja Azure umożliwiająca łączenie różnych projektów Azure w jeden przepływ pracy. 
Umożliwia to tworzenie złożonych scenariuszy z wykorzystaniem różnych usług Azure, takich jak LUIS, interpretowanie 
języka konwersacyjnego i niestandardowe odpowiadanie na pytania.

Korzyści z orkiestracji:

* Łączenie różnych projektów Azure w jeden przepływ pracy
* Automatyzacja złożonych scenariuszy
* Usprawnienie przepływu danych i logiki
* Skalowanie przepływów pracy w miarę wzrostu potrzeb

### Przykład orkiestracji

Wyobraźmy sobie bota czatowego, który może odpowiadać na pytania klientów, kierować ich do odpowiednich działów 
i wykonywać proste akcje w skrzynce pocztowej. Możemy zbudować takiego bota przy użyciu orkiestracji w następujący sposób:

1. Utwórz projekt LUIS do interpretowania języka konwersacyjnego użytkownika.
2. Utwórz projekt QnA do odpowiadania na pytania klientów z bazy wiedzy.
3. Utwórz projekt Cognitive Services do wykonywania prostych akcji w skrzynce pocztowej.
4. Utwórz przepływ pracy orkiestracji, który łączy te trzy projekty.

Przepływ pracy orkiestracji będzie działał w następujący sposób:

1. Użytkownik wysyła wiadomość do bota czatowego.
2. Projekt LUIS interpretuje wiadomość i identyfikuje intencję użytkownika.
3. Na podstawie intencji przepływ pracy orkiestracji kieruje żądanie do odpowiedniego projektu:
    * Jeśli użytkownik zada pytanie, żądanie zostanie wysłane do projektu QnA.
    * Jeśli użytkownik chce wykonać akcję w skrzynce pocztowej, żądanie zostanie wysłane do projektu Cognitive Services.
4. Odpowiedni projekt przetwarza żądanie i zwraca odpowiedź.
5. Przepływ pracy orkiestracji zwraca odpowiedź użytkownikowi.

## Wywoływanie przepływów pracy orkiestracji Azure

Przepływy pracy orkiestracji Azure można wywoływać za pomocą różnych metod, takich jak:

* HTTP
* Azure Functions
* Azure Logic Apps
* Można również używać zestawu SDK platformy Azure do wywoływania przepływów pracy orkiestracji z kodu aplikacji.

### Przykład orkiestracji przy użyciu plarformy Azur i języka Python

https://learn.microsoft.com/pl-pl/azure/ai-services/language-service/orchestration-workflow/tutorials/connect-services

Ten przykład pokazuje, jak połączyć odpowiedzi na pytania z projektem interpretacji języka konwersacyjnego.

Przykład obejmuje tworzenie:
* Poleceń e-mail
* Chitchat (z bazy wiedzy)

Polecenia e-mail będą przewidywać spośród kilku prostych akcji dotyczących asystenta wiadomości e-mail.
Rozmowa Chitchat zajmie się typowymi uprzejmościami i pozdrowieniami ze statycznymi odpowiedziami. 

Wywoływanie Orchestratora przy użyciu zestawu Azure SDK w środowisku Python:

https://github.com/lukpaw/mslearn-ai-language/tree/main/Labfiles/09-orchestration/Python