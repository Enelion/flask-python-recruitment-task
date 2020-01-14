# Zadanie rekrutacyjne, Backend Developer
## Treść zadania
Przygotować backend, który gromadzi i serwuje punkty ładowania (funkcjonalność analogiczna do Open Charge Map API).
Przykładowo, zapytanie GET na url do pobrania wszystkich punktów ładowania powinno zwrócić:
```json
[<ChargeNetwork1>, ...]
```
, gdzie *ChargeNetwork* posiada atrybuty:
- lokalizacja (lat, lng)
- identyfikator zasobu
- tablicę punktów ładowania *<ChargePoint>*
- timestampy utworzenia, modyfikacji
- kwota jednostkowa za 1kWh
- właściciel *<User>*
- średnia moc punktów ładowania

, a *ChargePoint*:
- oferowana moc ładowania
- identyfikator zasobu
- timestampy utworzenia, modyfikacji


## Wymagania:
- pełny CRUD dla sieci i punktów ładowania
- wykorzystanie Flask, SQLAlchemy
- zaprojektowanie odpowiednich ścieżek dla zasobów
- krótka instrukcja instalacji i uruchomienia
- konteneryzacja projektu
- gromadzenie danych w PostgreSQL

## Źródła:
- Dokumentacja OpenChargeMap - https://openchargemap.org/site/develop/api
