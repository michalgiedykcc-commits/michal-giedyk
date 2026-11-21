# michal-giedyk
allegro-app-docs-TopKoszykPL
# wystawianie ofert 
## 1. Opis i cel
Wewnętrzne narzędzie firmy Michał Giedyk do wystawiania ofert na Allegro. Obsługuje wyłącznie własne konto Allegro firmy.

## 2. Zakres funkcjonalny
- wystawianie ofert,
- edycja ceny i liczby sztuk,
- odczyt cenników dostaw, warunków zwrotów i reklamacji.

## 3. Sposób połączenia z Allegro
OAuth 2.0 Device flow. Właściciel konta jednorazowo zatwierdza dostęp w przeglądarce, token jest odświeżany refresh tokenem.

## 4. Wykorzystanie Allegro API i uprawnienia
| Scope | Funkcja aplikacji | Wykorzystanie |
|---|---|---|
| `allegro:api:sale:offers:write` | Wystawianie ofert | Tworzenie i edycja własnych ofert |
| `allegro:api:sale:offers:read` | Podgląd ofert | Pobieranie danych własnych ofert |
| `allegro:api:sale:settings:read` | Ustawienia sprzedaży | Odczyt cenników dostaw, warunków zwrotów i reklamacji |

## 5. Dostęp i bezpieczeństwo danych
Aplikacja działa na komputerze firmowym, dostęp ma tylko właściciel konta. Client Secret i tokeny są przechowywane lokalnie i nie są nikomu przekazywane. Dane z Allegro nie są udostępniane osobom trzecim.

## 6. Dane kontaktowe
MICHAŁ GEIDYK, MICHAŁ GEIDYK – michal.giedyk.lfw@gmail.com
