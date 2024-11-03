# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: ORM

## Podstawy ORM i Active Record
- [ ] **Zrozumienie ORM**: czym jest Object-Relational Mapping i jak działa Active Record w Rails
- [ ] **Modelowanie danych**: tworzenie modeli i ich odwzorowanie na tabele w bazie danych
- [ ] **CRUD z Active Record**: operacje `create`, `read`, `update`, `destroy` przy użyciu Active Record
- [ ] **Konwencje Active Record**: jak Rails automatycznie mapuje nazwy modeli na tabele i kolumny

## Relacje między modelami
- [ ] **Relacja `has_many` i `belongs_to`**: definiowanie relacji między modelami, np. `User has_many :posts`
- [ ] **Relacja `has_one`**: kiedy używać `has_one` i jak działa
- [ ] **Relacja `has_and_belongs_to_many`**: tworzenie relacji wiele do wielu przy użyciu łączącej tabeli
- [ ] **Relacja `has_many :through`**: bardziej zaawansowane relacje wiele do wielu z dodatkową logiką
- [ ] **Nested Attributes**: jak tworzyć i aktualizować powiązane rekordy za pomocą `accepts_nested_attributes_for`

## Walidacje
- [ ] **Podstawowe walidacje**: użycie `validates` do sprawdzania poprawności danych, np. `presence`, `uniqueness`, `length`
- [ ] **Walidacje niestandardowe**: tworzenie własnych walidatorów dla bardziej złożonych reguł
- [ ] **Conditional Validations**: walidacje warunkowe przy użyciu `if` i `unless`

## Callbacks
- [ ] **Podstawowe callbacki**: `before_save`, `after_create`, `around_update`, itd.
- [ ] **Zrozumienie cyklu życia obiektu**: jak i kiedy są wywoływane poszczególne callbacki
- [ ] **Unikanie callbacków**: kiedy lepiej unikać callbacków i gdzie przenieść logikę (np. do service objects)

## Zapytania Active Record
- [ ] **Podstawowe zapytania**: `where`, `order`, `limit`, `select`, `pluck`
- [ ] **Łączenie zapytań**: używanie `joins`, `includes`, `eager_load`, `preload` do optymalizacji zapytań
- [ ] **Scope**: definiowanie złożonych zapytań przy użyciu scope’ów
- [ ] **Lazy Loading vs Eager Loading**: zrozumienie różnicy między leniwym a natychmiastowym ładowaniem danych
- [ ] **Named Scopes**: użycie `scope` do definiowania wielokrotnego użytku zapytań

## Migracje bazy danych
- [ ] **Tworzenie migracji**: użycie `rails generate migration` do tworzenia i zmiany tabel
- [ ] **Zmiana struktury bazy danych**: dodawanie, usuwanie i zmiana kolumn oraz indeksów
- [ ] **Reversibility**: pisanie migracji, które mogą być odwrócone (`reversible do`)

## Transakcje
- [ ] **Obsługa transakcji**: używanie `ActiveRecord::Base.transaction` do grupowania operacji w jedną transakcję
- [ ] **Rollback**: automatyczne wycofywanie zmian w przypadku błędów

## Indexing i optymalizacja
- [ ] **Tworzenie indeksów**: kiedy i jak dodawać indeksy, aby poprawić wydajność zapytań
- [ ] **Composite Indexes**: zrozumienie, jak tworzyć i używać indeksów wielokolumnowych
- [ ] **Monitoring wydajności zapytań**: korzystanie z `EXPLAIN` do analizy zapytań SQL generowanych przez Active Record

## Praca z niestandardowymi zapytaniami SQL
- [ ] **Wykonywanie niestandardowych zapytań**: użycie `find_by_sql` i `ActiveRecord::Base.connection.execute`
- [ ] **Sanitizing Inputs**: ochrona przed SQL Injection poprzez stosowanie bezpiecznych placeholderów

## Optymalizacja Active Record
- [ ] **Batch Processing**: użycie `find_each` do przetwarzania dużych zestawów danych
- [ ] **Counter Cache**: optymalizacja liczenia rekordów za pomocą `counter_cache`
- [ ] **Cache’owanie wyników**: cache'owanie zapytań często używanych do poprawy wydajności
