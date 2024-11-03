# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: NoSQL

## Podstawy NoSQL
- [ ] **Zrozumienie NoSQL**: różnice między bazami danych NoSQL a relacyjnymi bazami danych (SQL)
- [ ] **Rodzaje baz NoSQL**: klucz-wartość, dokumentowe, grafowe, kolumnowe
- [ ] **Kiedy używać NoSQL**: scenariusze, w których NoSQL jest bardziej odpowiedni niż SQL (np. przechowywanie dużych ilości danych nieustrukturyzowanych)

## Popularne bazy danych NoSQL
- [ ] **MongoDB**: podstawy, jak działa, instalacja i konfiguracja
- [ ] **Redis**: użycie jako pamięć cache lub przechowywanie klucz-wartość
- [ ] **Elasticsearch**: wyszukiwanie pełnotekstowe i analiza danych w dużych zbiorach

## Integracja NoSQL z Ruby on Rails
- [ ] **Korzystanie z gemów**: np. `mongoid` dla MongoDB, `redis-rb` dla Redis
- [ ] **Konfiguracja**: jak skonfigurować NoSQL w aplikacji Rails, np. ustawienia dla MongoDB w `mongoid.yml`
- [ ] **Migracja danych**: jak migrować dane z SQL do NoSQL, strategie i najlepsze praktyki

## Praca z dokumentami
- [ ] **Struktura dokumentu**: zrozumienie struktury JSON w bazach dokumentowych, takich jak MongoDB
- [ ] **Wstawianie i aktualizacja dokumentów**: jak tworzyć, odczytywać, aktualizować i usuwać dokumenty (CRUD)
- [ ] **Querying**: jak wykonywać zapytania, filtrować dane i korzystać z operatorów wyszukiwania

## Indexing i optymalizacja zapytań
- [ ] **Tworzenie indeksów**: kiedy i jak tworzyć indeksy, aby przyspieszyć wyszukiwanie
- [ ] **Sharding i replikacja**: podział danych i replikacja dla zwiększenia wydajności i niezawodności
- [ ] **Optymalizacja zapytań**: jak analizować i optymalizować zapytania NoSQL

## Użycie Redis
- [ ] **Podstawy Redis**: instalacja, konfiguracja i podstawowe operacje klucz-wartość
- [ ] **Cache’owanie w Rails**: jak wykorzystać Redis do cache'owania danych, np. w `Rails.cache`
- [ ] **Sesje i kolejki**: używanie Redis do przechowywania sesji użytkowników i jako backend dla Sidekiq

## Bezpieczeństwo i zarządzanie danymi
- [ ] **Zarządzanie dostępem**: jak kontrolować dostęp do danych w bazach NoSQL, np. konfiguracja użytkowników i uprawnień w MongoDB
- [ ] **Szyfrowanie danych**: zasady szyfrowania danych przechowywanych i przesyłanych
- [ ] **Kopie zapasowe**: strategie tworzenia kopii zapasowych i przywracania danych w przypadku awarii

## Najlepsze praktyki
- [ ] **Normalizacja vs Denormalizacja**: kiedy denormalizować dane w NoSQL i jakie są tego zalety oraz wady
- [ ] **Obsługa dużych zbiorów danych**: techniki zarządzania dużymi kolekcjami dokumentów, aby uniknąć spadków wydajności
- [ ] **Monitorowanie i debugowanie**: narzędzia do monitorowania wydajności bazy danych NoSQL i identyfikowania problemów
