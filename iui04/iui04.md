## Usługa tożsamości na przykładzie Microsoft Entra
https://learn.microsoft.com/pl-pl/entra/identity-platform/

## Centrum administracyjne Microsoft Entra
https://entra.microsoft.com/

Najważniejsze elementy:
* Dzierżawy
* Użytkownicy 
* Aplikacje

## Rejestracja aplikacji
![Rejestruj](https://github.com/lukpaw/iui-lectures/blob/main/iui04/img/1_entra_rejestruj.jpg "Rejestruj")

## Utwórz nowego użytkownika
![Nowy użytkownik](https://github.com/lukpaw/iui-lectures/blob/main/iui04/img/2_entra_utworz_uzytkownika.jpg "Nowy użytkownik")

## Zabezpieczenie aplikacji Angular z użyciem Microsoft Entra
Aplikacja działająca w przeglądarce
![Szybki start](https://github.com/lukpaw/iui-lectures/blob/main/iui04/img/3_entra_szybki_start.jpg "Szybki start")

## Nowy branch entra-auth aplikacji iui-tourist-portal 
https://github.com/lukpaw/iui-tourist-portal/tree/entra-auth

## Zmień clientId
Pobierz z zarejestrowanej aplikacji clientId.
Klient w kontekście client-id i client-secret to aplikacja frontend lub backend. 
![Zmień clientId](https://github.com/lukpaw/iui-lectures/blob/main/iui04/img/4_entra_zmien_client_id.jpg "Zmień clientId")

## Dodaj klucz tajny klienta
Klucz tajny klienta jest potrzebny dla aplikacji backend.
![odaj klucz tajny klienta](https://github.com/lukpaw/iui-lectures/blob/main/iui04/img/5_entra_zmien_client_secret.jpg "Dodaj klucz tajny klienta")

```yaml
spring:
  cloud:
    azure:
      active-directory:
        enabled: true
        profile:
          tenant-id: <tenant>
        credential:
          client-id: ${AZURE_CLIENT_ID}
          client-secret: ${AZURE_CLIENT_SECRET}
```
## Obsługa Spring Cloud Azure dla Spring Security
https://learn.microsoft.com/en-us/azure/developer/java/spring-framework/spring-security-support

## Inne rozwiązania Identity and Access Management
https://www.keycloak.org/

## Zabezpieczenie aplikacji Angular / Spring boot z użyciem Keycloak
https://hamdi-bouallague.medium.com/secure-your-angular-spring-boot-application-using-keycloak-891efab50db8

## Materiały OAuth 2.0 i OpenID Connect
"Wprowadzenie do OAuth 2.0 i OpenID Connect", Aleksander Żelazny https://youtu.be/9LRZXg0NK5k?si=qgApHsB8QygHGoZK