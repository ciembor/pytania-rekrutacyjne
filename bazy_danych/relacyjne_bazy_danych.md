# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Relacyjne Bazy Danych

## Podstawy relacyjnych baz danych
- [ ] **Zrozumienie relacyjnych baz danych**: czym są tabele, wiersze, kolumny oraz podstawowe pojęcia, takie jak klucze główne i obce
- [ ] **Podstawy SQL**: znajomość składni SQL dla operacji `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- [ ] **Normalizacja danych**: zasady normalizacji i kiedy denormalizacja jest uzasadniona
- [ ] **Relacje między tabelami**: rozumienie relacji jeden-do-jednego, jeden-do-wielu, wiele-do-wielu

## Projektowanie bazy danych
- [ ] **Tworzenie schematów baz danych**: jak zaprojektować schematy bazy danych dla aplikacji Rails
- [ ] **Migracje w Rails**: generowanie i zarządzanie migracjami przy użyciu `rails generate migration`
- [ ] **Indeksy**: kiedy i jak dodawać indeksy do kolumn, aby poprawić wydajność zapytań
- [ ] **Klucze obce**: używanie kluczy obcych do utrzymywania spójności danych

## Złożone zapytania SQL
- [ ] **Łączenie tabel**: używanie `JOIN` do łączenia danych z wielu tabel
- [ ] **Agregacje**: użycie funkcji `COUNT`, `SUM`, `AVG`, `MIN`, `MAX` oraz grupowanie danych za pomocą `GROUP BY`
- [ ] **Podzapytania**: jak pisać i optymalizować podzapytania
- [ ] **Filtrowanie i sortowanie**: jak używać `WHERE`, `ORDER BY`, `LIMIT`

## Transakcje i spójność danych
- [ ] **Obsługa transakcji**: używanie transakcji do zapewnienia spójności danych, np. `ActiveRecord::Base.transaction`
- [ ] **ACID**: zrozumienie właściwości transakcji (Atomicity, Consistency, Isolation, Durability)
- [ ] **Blokowanie**: jak unikać deadlocków i zarządzać blokowaniem rekordów

## Optymalizacja bazy danych
- [ ] **Indeksy**: kiedy stosować indeksy wielokolumnowe i jak je optymalizować
- [ ] **Denormalizacja**: kiedy denormalizacja może poprawić wydajność
- [ ] **Profilowanie zapytań**: używanie narzędzi takich jak `EXPLAIN` do analizy wydajności zapytań SQL
- [ ] **Cache'owanie wyników**: cache'owanie wyników zapytań często używanych do poprawy wydajności

## Zarządzanie danymi
- [ ] **Seedy**: jak używać `db/seeds.rb` do wstawiania danych początkowych
- [ ] **Obsługa migracji**: jak wykonywać, cofać i zarządzać migracjami w środowisku produkcyjnym
- [ ] **Zmiany struktury bazy danych**: jak bezpiecznie zmieniać schemat bazy danych w aplikacjach produkcyjnych

## Bezpieczeństwo bazy danych
- [ ] **SQL Injection**: jak zabezpieczyć się przed atakami SQL Injection, korzystając z zapytań Active Record
- [ ] **Uprawnienia**: zasady zarządzania uprawnieniami do baz danych, aby ograniczyć dostęp
- [ ] **Szyfrowanie danych**: kiedy i jak szyfrować wrażliwe dane w bazie

## Backup i przywracanie danych
- [ ] **Tworzenie kopii zapasowych**: strategie tworzenia kopii zapasowych bazy danych
- [ ] **Przywracanie danych**: jak przywracać dane z kopii zapasowych w przypadku awarii
- [ ] **Migracja danych**: jak migrować dane między różnymi środowiskami

## Praca z narzędziami
- [ ] **Konsola bazy danych**: używanie konsoli Rails do wykonywania zapytań bezpośrednio w bazie
- [ ] **Narzędzia do zarządzania bazami danych**: użycie narzędzi, takich jak `pgAdmin`, `TablePlus`, do zarządzania bazami danych
- [ ] **Monitoring bazy danych**: jak monitorować wydajność bazy danych i wykrywać problemy
