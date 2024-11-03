# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Testowanie

## Testowanie jednostkowe
- [ ] **Podstawy RSpec**: składnia i struktura testów RSpec, konfiguracja `spec_helper` i `rails_helper`
- [ ] **Testowanie modeli**: pisanie testów dla walidacji, metod instancji i metod klasowych w modelach
- [ ] **Testowanie metod**: używanie `describe`, `context` i `it` do organizowania testów
- [ ] **Testowanie walidacji**: sprawdzanie, czy atrybuty są poprawnie walidowane w modelach
- [ ] **Mockowanie i stubowanie**: użycie `double`, `mock` i `stub` do testowania w izolacji

## Testowanie kontrolerów
- [ ] **Testowanie akcji kontrolerów**: sprawdzanie odpowiedzi HTTP, przekierowań, renderowanych widoków
- [ ] **Testowanie parametrów**: użycie `params` do symulowania danych wejściowych w akcjach kontrolera
- [ ] **Sprawdzanie uprawnień**: testowanie logiki autoryzacji w kontrolerach
- [ ] **Testowanie JSON API**: testowanie odpowiedzi JSON w akcjach API

## Testowanie integracyjne
- [ ] **Capybara**: użycie Capybara do testowania zachowania aplikacji na poziomie użytkownika
- [ ] **Testowanie przepływów użytkownika**: symulowanie wizyt użytkowników i interakcji z aplikacją
- [ ] **Sprawdzanie renderowania widoków**: weryfikacja, czy odpowiednie widoki są renderowane w odpowiedzi na żądania

## FactoryBot
- [ ] **Definiowanie fabryk**: tworzenie fabryk do generowania obiektów testowych
- [ ] **Użycie fabryk w testach**: korzystanie z `build`, `create`, `build_stubbed` w testach
- [ ] **Konfiguracja FactoryBot**: ustawienie FactoryBot jako domyślnego generatora obiektów w `rails_helper`

## Testowanie widoków
- [ ] **Sprawdzanie renderowania**: testowanie, czy odpowiednie elementy HTML są renderowane
- [ ] **Testowanie helperów**: pisanie testów dla metod pomocniczych używanych w widokach

## Testowanie z użyciem bazy danych
- [ ] **Database Cleaner**: konfiguracja i użycie `Database Cleaner` do zarządzania stanem bazy danych w testach
- [ ] **Fixtures vs. Factories**: różnice między `fixtures` a `factories` i kiedy które stosować
- [ ] **Transakcje w testach**: jak Rails obsługuje transakcje w testach, aby izolować przypadki testowe

## Mockowanie i Stubowanie
- [ ] **WebMock**: blokowanie żądań HTTP i symulowanie odpowiedzi w testach
- [ ] **VCR**: nagrywanie i odtwarzanie żądań HTTP w testach integracyjnych
- [ ] **Stubowanie metod**: kiedy i jak stubować metody w testach, aby testować w izolacji

## Testowanie bezpieczeństwa
- [ ] **Sprawdzanie CSRF**: testowanie, czy aplikacja jest chroniona przed atakami CSRF
- [ ] **Testowanie uprawnień**: weryfikowanie, czy użytkownicy nie mają dostępu do zasobów, do których nie powinni mieć dostępu
- [ ] **Testowanie SQL Injection**: sprawdzanie, czy aplikacja jest odporna na wstrzyknięcia SQL

## Testowanie wydajności
- [ ] **Profilowanie testów**: użycie narzędzi do profilowania testów, aby zidentyfikować wąskie gardła
- [ ] **Testowanie obciążeniowe**: symulowanie dużej liczby równoczesnych żądań w celu oceny wydajności aplikacji
- [ ] **Testowanie czasu odpowiedzi**: sprawdzanie, czy aplikacja odpowiada w odpowiednim czasie

## Narzędzia wspomagające
- [ ] **SimpleCov**: użycie SimpleCov do mierzenia pokrycia kodu testami
- [ ] **Shoulda Matchers**: użycie Shoulda Matchers do pisania zwięzłych testów walidacji i relacji modeli
- [ ] **Parallel Tests**: uruchamianie testów równolegle w celu skrócenia czasu testowania
