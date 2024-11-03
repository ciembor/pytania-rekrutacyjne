# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Wydajność

## Optymalizacja zapytań do bazy danych
- [ ] **Unikanie N+1 zapytań**: użycie `includes` lub `joins` do ładowania powiązanych danych
- [ ] **Eager Loading**: stosowanie eager loadingu, aby zmniejszyć liczbę zapytań do bazy danych
- [ ] **Lazy Loading**: rozumienie, kiedy korzystać z lazy loadingu, aby zoptymalizować wydajność
- [ ] **Indeksy bazy danych**: dodawanie indeksów na kolumnach często używanych w zapytaniach
- [ ] **Optymalizacja zapytań Active Record**: unikanie nadmiernych zapytań i korzystanie z `select`, `pluck`, `exists?`, itp.

## Cache’owanie
- [ ] **Fragment Cache**: cache'owanie fragmentów widoków, aby zmniejszyć czas renderowania
- [ ] **Russian Doll Caching**: strategia cache'owania z zachowaniem hierarchii zależności
- [ ] **Cache na poziomie kontrolera**: używanie `before_action` do cache'owania odpowiedzi API
- [ ] **Cache na poziomie modelu**: wykorzystanie `Rails.cache` do cache'owania drogich operacji
- [ ] **External Cache Stores**: używanie Redis lub Memcached do cache'owania danych aplikacji

## Redukcja zużycia pamięci
- [ ] **Praca z dużymi kolekcjami danych**: użycie `find_each` zamiast `all` do iteracji po dużych zbiorach danych
- [ ] **Ograniczanie wielkości odpowiedzi JSON**: selektywne wybieranie danych do serializacji w API
- [ ] **Analiza zużycia pamięci**: korzystanie z narzędzi takich jak `memory_profiler` i `derailed_benchmarks`

## Optymalizacja kodu Ruby
- [ ] **Profilowanie aplikacji**: używanie narzędzi takich jak `rack-mini-profiler` i `RubyProf` do identyfikowania wąskich gardeł
- [ ] **Unikanie nadmiarowej alokacji obiektów**: optymalizacja pętli i tworzenia obiektów
- [ ] **Optymalizacja metod**: refaktoryzacja drogich metod i korzystanie z memoizacji

## Wydajność serwera
- [ ] **Konfiguracja serwera aplikacji**: tuning serwerów takich jak Puma, aby zmniejszyć czas odpowiedzi
- [ ] **Asynchroniczne przetwarzanie**: delegowanie ciężkich zadań do background jobs przy użyciu Sidekiq, Delayed Job, itp.
- [ ] **Preloading**: ładowanie aplikacji przed pierwszym żądaniem w środowiskach produkcyjnych (np. `preload_app!` w Puma)

## Zarządzanie zasobami
- [ ] **Ustalanie limitów pamięci**: konfiguracja limitów pamięci w serwerach aplikacji i dbanie o ich monitoring
- [ ] **Monitoring i logowanie**: ustawianie narzędzi monitorujących, np. New Relic, Skylight, dla bieżącej analizy wydajności
- [ ] **Optymalizacja logowania**: zmniejszenie liczby zapisów do logów i unikanie nadmiarowego logowania

## Użycie Content Delivery Network (CDN)
- [ ] **Konfiguracja CDN**: używanie CDN do przyspieszenia ładowania zasobów statycznych
- [ ] **Cache’owanie odpowiedzi HTTP**: ustawianie nagłówków `Cache-Control` dla statycznych plików

## Zmniejszenie rozmiaru aplikacji
- [ ] **Usuwanie nieużywanych gemów**: regularne przeglądanie zależności i usuwanie nieużywanych gemów
- [ ] **Kompresja odpowiedzi**: konfiguracja `gzip` lub `brotli` do kompresji odpowiedzi HTTP
