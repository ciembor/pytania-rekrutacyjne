# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: API

## Tworzenie API
- [ ] **Zrozumienie RESTful API**: podstawy, zasady projektowania zasobów i tras
- [ ] **Definiowanie tras API**: `namespace`, `scope`, `resources` w `routes.rb`
- [ ] **Kontrolery API**: oddzielne kontrolery dla API (`Api::V1::ExampleController`)
- [ ] **Formatuj odpowiedzi JSON**: użycie `render json: data`
- [ ] **Serializacja danych**: użycie `Active Model Serializers` lub `JBuilder` do serializacji
- [ ] **Paginate**: wprowadzanie paginacji przy dużych zbiorach danych (np. `Kaminari`, `will_paginate`)

## Obsługa żądań i odpowiedzi
- [ ] **Obsługa parametrów**: korzystanie z `params` i `strong parameters`
- [ ] **Właściwe kody statusu HTTP**: `200 OK`, `201 Created`, `404 Not Found`, `422 Unprocessable Entity`, itp.
- [ ] **Obsługa błędów**: globalna obsługa błędów w API, użycie `rescue_from` w kontrolerach
- [ ] **CORS**: konfiguracja `rack-cors` do obsługi żądań między domenami
- [ ] **Headers**: ustawianie i czytanie nagłówków HTTP (np. `Authorization`, `Content-Type`)

## Autoryzacja i Uwierzytelnianie
- [ ] **Token-based Authentication**: implementacja autoryzacji za pomocą JWT (np. `Devise-JWT`, `Knock`)
- [ ] **OAuth**: integracja z dostawcami OAuth, np. Google, Facebook
- [ ] **API Keys**: zabezpieczenie endpointów za pomocą kluczy API
- [ ] **Rate Limiting**: ograniczanie liczby żądań z tej samej IP za pomocą `Rack::Attack`

## Wersjonowanie API
- [ ] **Wersjonowanie w ścieżce URL**: `/api/v1/resource`
- [ ] **Wersjonowanie w nagłówkach**: akceptowanie wersji API w nagłówkach (np. `Accept: application/vnd.myapp.v1+json`)

## Optymalizacja API
- [ ] **Cache’owanie odpowiedzi**: używanie `HTTP Cache`, `Redis`, `fragment caching`
- [ ] **Eager Loading**: zapobieganie N+1 zapytaniom przy użyciu `includes`
- [ ] **Kompresja odpowiedzi**: włączanie `gzip` dla zmniejszenia rozmiaru odpowiedzi

## Dokumentacja API
- [ ] **Generowanie dokumentacji**: użycie narzędzi takich jak `Swagger`, `rswag`, `Apipie`
- [ ] **Testowanie API**: pisanie testów integracyjnych dla endpointów API za pomocą `RSpec`, `Postman`

## Inne
- [ ] **Long Polling / WebSockets**: obsługa w czasie rzeczywistym, np. `ActionCable`
- [ ] **Webhooki**: tworzenie i odbieranie webhooków
- [ ] **JSON:API Standard**: przestrzeganie standardu JSON:API (opcjonalnie)
- [ ] **Streaming**: zwracanie danych w strumieniu (np. `send_data`)
