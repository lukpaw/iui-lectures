## Mikroserwisy na przykładzie Portalu turysty

![Portal turysty](https://github.com/lukpaw/iui-lectures/blob/main/iui03/img/1_portal_turysty.jpg "Portal turysty")

## Wymagania do uruchomienia SpringBoot

* Git
* Zainstaluj Java 17 (Windows 10 x64 Java Development Kit): https://jdk.java.net/java-se-ri/17
* IDE IDEA IntelliJ (lub inny IDE)
* Zapoznaj się z dokumentacją SpringBoot:
  * https://spring.io/guides/gs/rest-service

## Tworzenie mikroserwisów jako aplikacji SpringBoot
* Przy tworzeniu od początku projektu można skorzystać z: https://start.spring.io/

### Pierwszy mikroserwis: iui-translator
![Translator](https://github.com/lukpaw/iui-lectures/blob/main/iui03/img/2_springboot_starter_translator.jpg "Translator")

### Drugi mikroserwis: iui-tourist
![Tourist](https://github.com/lukpaw/iui-lectures/blob/main/iui03/img/3_springboot_starter_tourist.jpg "Tourist")

## Aplikacje internetowe typu SPA na przykładzie Angular

* Zainstaluj NodeJS: https://nodejs.org/en/download/
* Sprawdź w wierszu poleceń: `node --version`
* W wierszu poleceń uruchom komendę: npm install -g @angular/cli
* Zapoznaj się z dokumentacją Angulara: 
  * https://angular.io/tutorial/first-app#local-development-environment
  * https://angular.io/tutorial/tour-of-heroes/toh-pt0

### Aplikacja internetowa typu SPA: iui-tourist-portal

* W wierszu poleceń uruchom komendę: `C:\Users\lukpa\IdeaProjects>ng new --no-standalone iui-tourist-portal`
  * Na wszystkie pytania odpowiedzi są domyślne
  * Poza pytaniem: `Which stylesheet format would you like to use?` - wybierz `Sass (SCSS)`
* W wierszu poleceń uruchom komendy:
    ```
    cd iui-tourist-portal
    npm install
    ng serve
    ```
* Gdy chcesz dodać nowy komponent do Angulara uruchom: `ng generate component [nazwa_komponentu]`

## Uruchomienie i dokładne omówienie aplikacji

### Mikroserwis iui-translator

Ten Spring Boot odpowiada za tłumaczenie pytań z języków obcych na język polski.

https://github.com/lukpaw/iui-translator

### Mikroserwis iui-tourist

Ten Spring Boot odpowiada za dostarczanie informacji turyście na podstawie zadanego pytania w języku pl, en, de.

https://github.com/lukpaw/iui-tourist

### Aplikacja SPA iui-tourist-portal

Portal turysty posiadający funkcjonalności:
* Wyszukiwarka informacji turystycznych w językach polskim, angielskim, niemieckim.
* Tłumaczenia z języka angielskiego lub niemieckiego na język polski.

https://github.com/lukpaw/iui-tourist-portal




