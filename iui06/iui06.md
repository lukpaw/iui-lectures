## Sieci semantyczne - Rozszerzenie koncepcji WWW

**Sieci semantyczne** to rozszerzenie tradycyjnego Internetu, które umożliwia maszynom rozumienie i wnioskowanie z danych online.

* **Możliwość wnioskowania:** Sieci semantyczne pozwalają na wyciąganie wniosków z danych i odkrywanie nowych informacji.
* **Jednolite traktowanie danych:** Dane są reprezentowane w formacie maszynowo czytelnym, co ułatwia ich integrację i analizę.
* **Oparte na standardach:** Sieci semantyczne wykorzystują wspólne standardy, takie jak RDF i OWL, zapewniając interoperacyjność.
* **Relacje pomiędzy danymi:** Sieci semantyczne tworzą relacje między danymi, ujawniając ukryte powiązania i kontekst.

## Dane w Internecie - Wyzwania

**Dane w Internecie** są często:

* **Nie czytelne dla maszyn:** Prezentowane w formacie HTML, który jest przeznaczony dla ludzi, a nie dla programów.
* **Powtarzalne:** Te same informacje są często rozproszone w wielu miejscach, co utrudnia ich agregację i analizę.
* **Zmienna rzetelność:** Poziom wiarygodności danych może się różnić, co wymaga weryfikacji.
* **Brak kontekstu:** Brakuje powiązań między danymi, co utrudnia ich zrozumienie w szerszym kontekście.

## Dane na potrzeby sieci semantycznych - Strukturyzacja

**Dane w sieciach semantycznych** są:

* **Identyfikowane za pomocą URI:** Każdy element ma unikalny identyfikator, ułatwiając jego odnajdywanie i adresowanie.
* **Nazwane za pomocą URI:** Nazwy elementów są oparte na standardach, zapewniając spójność i interpretowalność.
* **Lokalizowane za pomocą URI:** Możliwe jest określenie lokalizacji i źródła danych.
* **Informacje o sobie:** Dane zawierają informacje o własnej strukturze i znaczeniu.
* **Odnoszą się do innych danych:** Elementy są połączone ze sobą relacjami, tworząc sieć powiązań.

**Graf wiedzy:** Sieci semantyczne są często reprezentowane jako grafy wiedzy, gdzie:

* **Węzły** reprezentują obiekty lub pojęcia.
* **Krawędzie** reprezentują relacje między węzłami.
* **Etykiety** zawierają dodatkowe informacje o węzłach i krawędziach.

**Wnioskowanie:** Sieci semantyczne umożliwiają:

* **Wiedza:** Gromadzenie i reprezentowanie wiedzy w sposób uporządkowany i zrozumiały.
* **Rozumienie:** Interpretowanie i analizowanie danych w kontekście.
* **Wnioski:** Wyciąganie nowych wniosków i odkrywanie ukrytych zależności.

## Resource Description Framework (RDF)

**RDF - Opis metadanych:**

* **Standaryzowany sposób:** RDF zapewnia standardowy sposób opisu metadanych o zasobach w Internecie.
* **Składniki:** Wyrażenia RDF składają się z trzech komponentów:
    * **Podmiot:** Zasób, który jest opisywany.
    * **Orzeczenie:** Właściwość lub charakterystyka podmiotu.
    * **Przedmiot:** Wartość właściwości dla podmiotu.

## RDF w akcji - Opis kota Ali

**Przykład:** Ala ma kota.

* **Podmiot:** "Ala" - Osoba posiadająca kota.
* **Orzeczenie:** "ma", "posiada", "jest posiadaczem" - Relacja między Alą a kotem.
* **Przedmiot:** "kot" - Rodzaj zwierzaka, którego posiada Ala.

## Reprezentacja RDF w XML

**Przykład kodu XML:**

```xml
<?xml version="1.0"?>
<rdf:RDF
xmlns:rdf="http://www.w3.org/1999/02/22−rdf−syntax−ns#"
xmlns:descr="http://www.examle.com/descr">
<rdf:Description
rdf:about="http://www.example.com/descr/Ala">
<descr:ma>Kot</descr:ma>
</rdf:Description>
</rdf:RDF>
```

* **rdf:RDF:** Element główny dokumentu RDF.
* **xmlns:rdf:** Deklaruje przestrzeń nazw RDF.
* **xmlns:descr:** Deklaruje niestandardową przestrzeń nazw dla właściwości "ma".
* **rdf:Description:** Element opisujący zasób "[http://www.example.com/descr/Ala](http://www.example.com/descr/Ala)".
* **descr:ma:** Niestandardowa właściwość "ma" o wartości "Kot" (po polsku "kot").

## Elementy składni RDF - Podstawy

**Podstawowe elementy składni RDF:**

* **rdf:Description:** Reprezentuje zasób i jego właściwości.
    * Identyfikowany przez URI RDF.
    * Zawiera pary właściwość-wartość opisujące zasób.
* **rdf:Property:** Reprezentuje właściwość lub charakterystykę zasobu.
    * Łączy podmiot i przedmiot.
    * Może mieć zakres (oczekiwany typ wartości) i domenę (oczekiwany typ podmiotu).
* **rdfs:Literal:** Reprezentuje wartość literaturową (łańcuch znaków, liczba, data itp.).
    * Może mieć znacznik języka dla tekstu wielojęzycznego.
* **rdf:Statement:** Reprezentuje pełny potrójny RDF (podmiot-orzeczenie-przedmiot).
    * Używany do deklarowania relacji między zasobami.

## Triplety RDF - szczegółowe omówienie

**Definicja:**

W kontekście danych RDF **triplet** to podstawowa jednostka informacji, składająca się z trzech elementów:

1. **Podmiot:** 
    - Reprezentuje obiekt, o którym mowa w triplecie.
    - Może to być URI (Uniform Resource Identifier), nazwa węzła lub literał (wartość tekstowa).

2. **Predykat:**
    - Opisuje relację między podmiotem a obiektem.
    - Jest to URI definiujący znaczenie relacji.

3. **Obiekt:**
    - Reprezentuje wartość związaną z podmiotem poprzez predykat.
    - Może to być URI, nazwa węzła, literał lub inny triplet.

**Przykład:**

```
<http://example.org/Jan>  <foaf:name>  "Jan Kowalski"
```

W tym przykładzie:

- Podmiot: `<http://example.org/Jan>` - URI reprezentujący osobę o imieniu Jan.
- Predykat: `<foaf:name>` - URI definiujący predykat "name" z ontologii FOAF (Friend of a Friend).
- Obiekt: `"Jan Kowalski"` - Literał reprezentujący imię i nazwisko osoby.

**Znaczenie tripletu:**

Ten triplet oznacza, że osoba o URI `<http://example.org/Jan>` posiada imię "Jan Kowalski" zgodnie z ontologią FOAF.

**Zastosowanie tripletu:**

Triplety są podstawą do tworzenia grafów RDF, które reprezentują złożone relacje między obiektami w sposób zrozumiały dla komputerów i ułatwiają wyszukiwanie i analizę informacji.

**Cechy tripletu:**

- **Kierunkowość:** 
    - Relacje w tripletach są kierunkowe, tzn. podmiot jest powiązany z obiektem poprzez predykat.
    - Na przykład, zdanie "Jan ma imię Jan Kowalski" jest reprezentowane jako `<http://example.org/Jan> <foaf:name> "Jan Kowalski"`.

- **Unikalność:**
    - W grafie RDF każdy triplet powinien być unikalny, tzn. nie może istnieć ten sam podmiot, predykat i obiekt w dwóch różnych tripletach.

- **Formalność:**
    - Triplety są zdefiniowane w formalnym języku RDF, co zapewnia spójność i dokładność reprezentacji informacji.


## SPARQL Protocol and RDF Query Language

**SPARQL - Potężne narzędzie do eksploracji danych RDF**

* **Język zapytań i protokół:** SPARQL umożliwia formułowanie zapytań i pobieranie danych z grafoów wiedzy RDF.
* **Wyraźne zapytania:** SPARQL oferuje precyzyjny i deklaratywny sposób formułowania zapytań do danych RDF.
* **Wszechstronne możliwości:** Możliwe jest wyszukiwanie, filtrowanie, sortowanie i agregowanie danych RDF.
* **Interoperacyjność:** SPARQL działa na różnych implementacjach RDF, zapewniając interoperacyjność.

## Podstawowa składnia SPARQL

**Struktura zapytania SPARQL:**

```
SELECT ?variable
FROM <named graph>
WHERE {
  ?subject ?predicate ?object .
  # Optional filters and patterns
}
```

* **SELECT:** Określa zmienne, których wartości mają zostać zwrócone.
* **FROM:** Określa grafy wiedzy lub zestawy danych RDF, w których wyszukiwane są dane.
* **WHERE:** Zawiera wzorce określające żądane dane.
* **?subject, ?predicate, ?object:** Zmiennne reprezentujące elementy trójki RDF.
* **. (kropka):** Separator między wzorcami.

## Standard manipulacji plikami RDF

* **Formaty reprezentacji danych RDF:** Istnieją różne formaty do zapisu i przechowywania danych RDF (np. XML, JSON, Turtle).
* **Standardy:** Ważne jest stosowanie standardowych formatów, aby zapewnić interoperacyjność i łatwość wymiany danych.
* **Przykład:** Format Turtle jest popularnym wyborem ze względu na czytelność i zwięzłość.

## SPARQL - Tworzenie zapytań do danych

**Przykład zapytania SPARQL:**

```
SELECT ?name
WHERE {
  ?person rdf:type foaf:Person .
  ?person foaf:name ?name .
}
```

* **Zapytanie pobiera:** Nazwy osób z grafu wiedzy.
* **FROM:** Domyślnie cały graf wiedzy jest przeszukiwany.
* **WHERE:**
    * Pierwszy wzór określa, że osoby są instancjami klasy "foaf:Person".
    * Drugi wzór wybiera nazwy osób ("foaf:name").

## Więcej przykładów zapytań SPARQL

**Złożone zapytania:**

* Filtrowanie: Filtruj wyniki na podstawie określonych kryteriów.
* Sortowanie: Sortuj wyniki według określonych wartości.
* Agregacja: Oblicz sumy, średnie i inne statystyki na danych.
* Dołączanie: Dołączaj dane z różnych źródeł RDF.

**SPARQL oferuje potężne możliwości eksploracji i analizy danych RDF, umożliwiając odkrywanie ukrytych zależności i czerpanie cennych wniosków.**

## Punkt dostępu DBpedia SPARQL — dostęp do ogromnej bazy wiedzy

**DBpedia SPARQL:**
https://dbpedia.org/sparql

* **Publiczny punkt dostępu do wiedzy:** DBpedia udostępnia ogromny zbiór danych opartych na Wikipedii w formacie RDF, dostępny poprzez punkt końcowy SPARQL.
* **Bogactwo informacji:** DBpedia zawiera informacje o milionach obiektów i wydarzeń, obejmując różne domeny wiedzy.
* **Potężne narzędzie badawcze:** SPARQL umożliwia formułowanie złożonych zapytań do danych DBpedia, ułatwiając analizę i odkrywanie wiedzy.

**Przykład zapytania:**

```
SELECT ?city ?populationTotal
WHERE {
  ?city rdf:type dbo:City .
  ?city dbo:populationTotal ?populationTotal .
  FILTER(?populationTotal > 20000000)
}
```

* **Zapytanie pobiera:** Nazwy i populacje miast z populacją powyżej 20 milionów.
* **FROM:** Domyślnie cały zbiór danych DBpedia jest przeszukiwany.
* **WHERE:**
    * Pierwszy wzór określa, że miasta są instancjami klasy "dbo:City".
    * Drugi wzór wybiera populacje miast ("dbo:populationTotal").
    * Trzeci filtr ogranicza wyniki do miast o populacji powyżej 20 milionów.

**DBpedia SPARQL Endpoint oferuje potężny sposób na dostęp i analizę ogromnej ilości wiedzy o świecie, umożliwiając badaczom, 
naukowcom i entuzjastom danych odkrywanie nowych informacji i tworzenie cennych spostrzeżeń.**

## Przykład
https://github.com/lukpaw/iui-semantic-networks

## Funkcje `build_graph1` i `lookup_ewa_in_graph1` - szczegółowe omówienie

**Kod funkcji:**

```python
def build_graph1():
    """Tworzy graf RDF z danych N3."""
    print("Stwórz graf używając składni N3")
    g = Graph()
    n3data = """\
    @prefix : <http://example.org/ns/graph1#> .
    :Ola  :hasParent :Jan ;
          :gender    :female .
    :Ewa  :hasParent :Jan ;
          :gender    :female .
    :Jan  :gender    :male .
    :Olek :hasParent :Ewa ;
          :gender    :male ."""
    g.parse(data=n3data, format="n3")
    return g


def lookup_ewa_in_graph1(g):
    """Wyszukuje informacje o Ewie w grafie RDF."""
    print("Wyszukaj Ewę po globalnym identyfikatorze")
    ewa = URIRef('http://example.org/ns/graph1#Ewa')
    print([o for o in g.predicate_objects(subject=ewa)])
```

**Omówienie funkcji:**

**Funkcja `build_graph1()`**

1. **Wyświetla komunikat:**
   - Informuje o rozpoczęciu tworzenia grafu.

2. **Inicjuje obiekt grafu:**
   - Tworzy pusty obiekt `Graph` do przechowywania tripes RDF.

3. **Definiuje dane N3:**
   - Przechowuje triplety N3 reprezentujące relacje między jednostkami.

4. **Parsuje dane N3:**
   - Interpretuje łańcuch danych N3 i dodaje triplety do grafu.

5. **Zwrócenie grafu:**
   - Udostępnia skonstruowany graf RDF do dalszego przetwarzania.

**Funkcja `lookup_ewa_in_graph1(g)`**

1. **Wyświetla komunikat:**
   - Informuje o rozpoczęciu wyszukiwania.

2. **Tworzy obiekt URIRef:**
   - Konstruuje obiekt `URIRef` reprezentujący globalny identyfikator URI Ewy.

3. **Pobiera obiekty predykatu:**
   - Przechodzi przez graf, szukając obiektów predykatu powiązanych z podmiotem `ewa`.

4. **Zwrócenie wyników:**
   - Zwraca listę znalezionych obiektów predykatu, umożliwiając dostęp do informacji o Ewie.

**Przykład działania:**

- Załóżmy, że `g` to graf utworzony przez `build_graph1()`.
- Wywołanie `lookup_ewa_in_graph1(g)` zwróci listę:

```
[('hasParent', URIRef('http://example.org/ns/graph1#Jan')),
 ('gender', Literal('female')),
 ('hasChild', URIRef('http://example.org/ns/graph1#Olek'))]
```

Lista zawiera predykaty i odpowiadające im obiekty, ujawniając informacje o Ewie i jej relacjach.

## Funkcje `build_graph2` i `simple_sparql_query`, `who_knows_each_other` - szczegółowe omówienie

**Kod funkcji:**

```python
def build_graph2():
    """Tworzy graf RDF konstruując węzły."""
    print("Stwórz graf konstruując węzły")
    g = Graph()

    zygmunt = URIRef("http://example.org/ludzie/Zygmunt")
    aniela = BNode()

    name = Literal('Zygmunt')
    age = Literal(24)

    g.add((zygmunt, RDF.type, FOAF.Person))
    g.add((zygmunt, FOAF.name, name))
    g.add((zygmunt, FOAF.age, age))
    g.add((zygmunt, FOAF.knows, aniela))

    g.add((aniela, RDF.type, FOAF.Person))
    g.add((aniela, FOAF.name, Literal('Aniela')))
    return g


def simple_sparql_query(g):
    """Proste zapytanie SPARQL do grafu."""
    print("Proste zapytanie SPARQL")
    result = g.query("SELECT * WHERE {?s ?p ?o}")
    for row in result:
        print(row)


def who_knows_each_other(g):
    """Wyszukuje znajomości w grafie."""
    print("Proste zapytanie SPARQL - znajomości")
    result = g.query(
        """SELECT DISTINCT ?aname ?bname
           WHERE {
              ?a foaf:knows ?b .
              ?a foaf:name ?aname .
              ?b foaf:name ?bname .
           }""", initNs={'foaf': FOAF})

    for row in result:
        print("%s knows %s" % row)
```

**Omówienie funkcji:**

**Funkcja `build_graph2()`**

1. **Wyświetla komunikat:**
   - Informuje o rozpoczęciu tworzenia grafu.

2. **Inicjuje obiekt grafu:**
   - Tworzy pusty obiekt `Graph` do przechowywania tripes RDF.

3. **Tworzy węzły:**
   - Definiuje węzły dla Zygmunta (`zygmunt`) i anonimowej osoby (`aniela`).

4. **Dodaje literały:**
   - Tworzy literały dla imienia (`name`) i wieku (`age`) Zygmunta.

5. **Dodaje triplety:**
   - Używa funkcji `g.add` aby dodać potrójne zawierające informacje o Zygmuncie i jego relacji z anonimową osobą (`aniela`).

**Funkcja `simple_sparql_query(g)`**

1. **Wyświetla komunikat:**
   - Informuje o uruchomieniu prostego zapytania SPARQL.

2. **Tworzy zapytanie:**
   - `SELECT * WHERE {?s ?p ?o}` pobiera wszystkie triplety z grafu `g`.

3. **Wykonuje zapytanie:**
   - Metoda `g.query` uruchamia zapytanie na grafie.

4. **Przetwarza wyniki:**
   - Iteruje po wynikach i drukuje każdy wiersz zawierający tripletę.

**Funkcja `who_knows_each_other(g)`**

1. **Wyświetla komunikat:**
   - Informuje o uruchomieniu zapytania SPARQL wyszukującego znajomości.

2. **Tworzy zapytanie:**
   - Zapytanie SPARQL wyszukuje osoby powiązane relacją `foaf:knows` i pobiera ich imiona (`aname`, `bname`).

3. **Wykonuje zapytanie:**
   - `g.query` uruchamia zapytanie na grafie `g`.

4. **Przetwarza wyniki:**
   - Iteruje po wynikach i drukuje relacje znajomości.

## Funkcje `build_graph3` i `which_is_zwierze` - szczegółowe omówienie

**Kod funkcji:**

```python
def build_graph3():
    """Tworzy graf RDF definiujący klasy zwierząt i roślin."""
    g = Graph()
    n3data = """
    @prefix ex: <http://example.org/schemas/vehicles#> .
    @prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
    @prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .    
    ex:Zwierze            rdf:type          rdfs:Class .
    ex:Ssak               rdf:type          rdfs:Class .
    ex:Roslina            rdf:type          rdfs:Class .
    ex:Pies               rdf:type          rdfs:Class .
    ex:Karp               rdf:type          rdfs:Class .
    ex:Drzewo             rdf:type          rdfs:Class .

    ex:Ssak               rdfs:subClassOf   ex:Zwierze .
    ex:Pies               rdfs:subClassOf   ex:Ssak .
    ex:Karp               rdfs:subClassOf   ex:Zwierze .
    ex:Drzewo             rdfs:subClassOf   ex:Roslina .
    """

    g.parse(data=n3data, format="n3")
    return g


def which_is_zwierze(g):
    """Wyszukuje instancje klasy Zwierzę w grafie."""
    print("Zwraca zwierzeta")
    result = g.query(
        """SELECT DISTINCT ?s WHERE {
        ?s ?p ?o .
        ?s rdfs:subClassOf+ ex:Zwierze . }""",
        initNs={'rdfs': RDFS, 'rdf': RDF, 'ex': 'http://example.org/organizmy#'})

    for row in result:
        print(row)
```

**Omówienie funkcji:**

**Funkcja `build_graph3()`**

1. **Tworzy obiekt grafu:**
   - Inicjuje pusty obiekt `Graph` do przechowywania tripes RDF.

2. **Definiuje prefiksy:**
   - Ustawia prefiksy dla często używanych ontologii RDF i schematu RDF.

3. **Definiuje klasy:**
   - Definiuje klasy dla Zwierząt (`ex:Zwierze`), Ssaków (`ex:Ssak`), Roślin (`ex:Roslina`), Psów (`ex:Pies`), Karpi (`ex:Karp`), i Drzew (`ex:Drzewo`) za pomocą `rdf:type rdfs:Class`.

4. **Definiuje relacje dziedziczenia:**
   - Używa `rdfs:subClassOf` aby wskazać relacje dziedziczenia między klasami. Na przykład, `ex:Pies` jest podklasą (`rdfs:subClassOf`) `ex:Ssak`, a `ex:Ssak` jest podklasą `ex:Zwierze`.

5. **Parsuje dane N3:**
   - Interpretuje łańcuch danych N3 i dodaje triplety do grafu `g`.

6. **Zwrócenie grafu:**
   - Zwraca skonstruowany graf RDF.

**Funkcja `which_is_zwierze(g)`**

1. **Wyświetla komunikat:**
   - Informuje o uruchomieniu zapytania wyszukującego zwierzęta.

2. **Tworzy zapytanie SPARQL:**
   - `SELECT DISTINCT ?s WHERE {...}` pobiera wszystkie unikalne instancje (`?s`) powiązane z klasą `ex:Zwierze` poprzez łańcuch relacji `rdfs:subClassOf`.

3. **Wykonuje zapytanie:**
   - `g.query` uruchamia zapytanie na grafie `g`.

4. **Przetwarza wyniki:**
   - Iteruje po wynikach i drukuje każdą instancję (`?s`) będącą zwierzęciem.

## Funkcja `explore_dbpedia` - szczegółowe omówienie

**Kod funkcji:**

```python
def explore_dbpedia():
    """Pobiera i drukuje informacje o miastach z dużą populacją z DBPedia."""
    sparql = SPARQLWrapper("http://dbpedia.org/sparql")

    sparql.setQuery("""
    SELECT ?city ?populationTotal
    WHERE {
      ?city rdf:type dbo:City .
      ?city dbo:populationTotal ?populationTotal .
      FILTER(?populationTotal > 20000000)
    }
    """)

    sparql.setReturnFormat(JSON)
    results = sparql.query().convert()
    json_string = json.dumps(results)
    print(json_string)
```

**Omówienie funkcji:**

1. **Inicjuje obiekt SPARQLWrapper:**
   - Tworzy obiekt `SPARQLWrapper` wskazujący na punkt końcowy SPARQL serwisu DBPedia (`http://dbpedia.org/sparql`).

2. **Tworzy zapytanie SPARQL:**
   - Definiuje zapytanie SPARQL, które:
     - Wybiera nazwy miast (`?city`) i ich całkowitą populację (`?populationTotal`).
     - Filtruje wyniki, aby uwzględnić tylko miasta z populacją powyżej 20 milionów.

3. **Ustawia format zwrotny:**
   - Ustawia format zwrotny wyników zapytania na JSON (`sparql.setReturnFormat(JSON)`) dla łatwiejszej obsługi.

4. **Wykonuje zapytanie i pobiera wyniki:**
   - `sparql.query().convert()` wykonuje zapytanie na serwerze DBPedia i zwraca wyniki w postaci słownika.

5. **Konwertuje i drukuje wyniki:**
   - `json.dumps` konwertuje słownik wyników na łańcuch JSON.
   - `print(json_string)` drukuje łańcuch JSON zawierający informacje o miastach z dużą populacją.
