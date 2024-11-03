# Zakres Wiedzy dla Full Stack Developera Ruby on Rails

## Struktura Projektu
- [ ] **Zrozumienie struktury katalogów Rails**: `app`, `config`, `db`, `lib`, `public`, itd.
- [ ] **Autoloading**: jak Rails ładuje pliki i klasy
- [ ] **Konfiguracja aplikacji**: użycie `config/application.rb`, `config/environments`

## Routing
- [ ] **Definiowanie tras**: użycie `routes.rb`, `resources`, `get`, `post`, `put`, `delete`
- [ ] **Nested routes**: zagnieżdżone trasy i ich zastosowanie
- [ ] **Named routes**: korzystanie z nazwanych tras

## Kontrolery
- [ ] **Tworzenie kontrolerów**: podstawowe akcje `index`, `show`, `new`, `create`, `edit`, `update`, `destroy`
- [ ] **Filtrowanie danych**: `before_action`, `skip_before_action`
- [ ] **Obsługa błędów**: renderowanie odpowiednich odpowiedzi błędów

## Widoki
- [ ] **ERB**: składnia szablonów ERB, interpolacja Ruby
- [ ] **Layouts**: struktura layoutów i `yield`
- [ ] **Partials**: tworzenie i korzystanie z partials do ponownego użycia kodu
- [ ] **Form Helpers**: używanie helperów do tworzenia formularzy
- [ ] **Asset Pipeline**: zarządzanie plikami CSS, JS, obrazami

## Modele i Active Record
- [ ] **ORM Active Record**: podstawowe operacje CRUD
- [ ] **Walidacje**: dodawanie walidacji do modeli
- [ ] **Relacje między modelami**: `has_many`, `belongs_to`, `has_one`, `has_and_belongs_to_many`
- [ ] **Scope**: definiowanie i używanie scope’ów
- [ ] **Migracje bazy danych**: tworzenie i modyfikowanie tabel w bazie danych
- [ ] **Callbacki**: `before_save`, `after_create`, `around_update`, itd.

## Bezpieczeństwo
- [ ] **CSRF ochrona**: jak Rails chroni przed atakami CSRF
- [ ] **Autoryzacja i uwierzytelnianie**: korzystanie z Devise, Pundit, CanCanCan
- [ ] **SQL Injection**: ochrona przed wstrzyknięciami SQL, użycie zapytań Active Record
- [ ] **Bezpieczne parametry**: użycie `strong parameters` w kontrolerach

## Taski i Background Jobs
- [ ] **Taski Rake**: tworzenie i uruchamianie tasków Rake
- [ ] **Background Jobs**: używanie Active Job, Sidekiq, Delayed Job
- [ ] **Scheduling**: planowanie zadań za pomocą `cron`, Whenever

## Testowanie
- [ ] **Testy jednostkowe i integracyjne**: użycie RSpec, MiniTest
- [ ] **Testowanie kontrolerów i modeli**
- [ ] **FactoryBot**: tworzenie obiektów testowych
- [ ] **Testowanie widoków i helperów**

## Wydajność
- [ ] **Cache’owanie**: fragment cache, Russian doll caching, cache na poziomie modelu
- [ ] **Optymalizacja zapytań SQL**: `includes`, `joins`, `pluck`
- [ ] **Lazy Loading vs Eager Loading**: zrozumienie różnic i zastosowania

## API
- [ ] **Tworzenie API**: renderowanie JSON, użycie `Active Model Serializers`
- [ ] **RESTful API**: zasady i tworzenie RESTful API
- [ ] **Obsługa błędów w API**: odpowiednie statusy HTTP, formaty błędów

## Inne
- [ ] **Active Storage**: przechowywanie i zarządzanie plikami
- [ ] **Action Mailer**: konfiguracja i wysyłanie e-maili
- [ ] **Internacjonalizacja (I18n)**: dodawanie wielojęzyczności do aplikacji
- [ ] **Console**: korzystanie z konsoli Rails do debugowania i zarządzania danymi
- [ ] **Uprawnienia i Role**: implementacja logiki ról użytkowników
