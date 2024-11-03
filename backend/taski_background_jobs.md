# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Taski i Background Jobs

## Taski Rake
- [ ] **Tworzenie tasków Rake**: zrozumienie struktury tasków Rake, tworzenie nowych tasków w `lib/tasks`
- [ ] **Uruchamianie tasków Rake**: znajomość komend `rake task_name` oraz jak wykonywać taski w środowiskach produkcyjnych
- [ ] **Zależności tasków**: jak definiować zależności między taskami Rake
- [ ] **Zarządzanie taskami cyklicznymi**: tworzenie tasków, które mogą być uruchamiane na żądanie

## Background Jobs
- [ ] **Podstawy Active Job**: zrozumienie jak działa Active Job jako warstwa abstrakcji dla różnych backendów
- [ ] **Tworzenie background jobs**: generowanie jobów (`rails generate job ExampleJob`) i definiowanie logiki w `perform`
- [ ] **Konfiguracja backendu**: konfiguracja Active Job z backendami jak Sidekiq, Delayed Job, Resque
- [ ] **Przetwarzanie asynchroniczne**: kiedy i dlaczego używać background jobs zamiast wykonywania zadań w request-response cycle
- [ ] **Retry Mechanisms**: konfiguracja ponownego uruchamiania jobów w przypadku błędów

## Sidekiq
- [ ] **Instalacja i konfiguracja Sidekiq**: instalacja gema Sidekiq, konfiguracja w `config/sidekiq.yml`
- [ ] **Tworzenie workerów Sidekiq**: zrozumienie jak tworzyć i uruchamiać workery
- [ ] **Queue Prioritization**: zarządzanie priorytetami kolejek i konfiguracja kolejek o różnym poziomie ważności
- [ ] **Monitoring i debugowanie**: używanie panelu administracyjnego Sidekiq do monitorowania i zarządzania jobami
- [ ] **Zarządzanie pamięcią i zasobami**: optymalizacja pracy workerów, konfiguracja ograniczeń pamięci i użycia zasobów

## Inne Backendy
- [ ] **Delayed Job**: konfiguracja i użycie Delayed Job jako backendu dla Active Job
- [ ] **Resque**: podstawy użycia Resque, kiedy warto go rozważyć zamiast Sidekiq
- [ ] **Custom backends**: jak tworzyć i integrować niestandardowe backendy dla Active Job

## Scheduling Zadań
- [ ] **Planowanie zadań cyklicznych**: użycie gemów takich jak `whenever` do tworzenia harmonogramów
- [ ] **Konfiguracja cron jobs**: pisanie cron jobs do automatycznego uruchamiania tasków w regularnych odstępach czasu
- [ ] **Retry Logic**: jak implementować logikę ponawiania zadań przy użyciu schedulerów

## Obsługa błędów i logowanie
- [ ] **Logowanie błędów**: przechwytywanie i logowanie błędów występujących w background jobs
- [ ] **Powiadamianie o błędach**: konfiguracja powiadomień o błędach (np. integracja z systemami takimi jak Rollbar, Sentry)
- [ ] **Testowanie background jobs**: pisanie testów jednostkowych i integracyjnych dla jobów asynchronicznych

## Optymalizacja i najlepsze praktyki
- [ ] **Idempotency**: zapewnienie, że joby są bezpieczne do ponownego wykonania
- [ ] **Ograniczenie pracy na bazie danych**: minimalizowanie liczby zapytań do bazy w background jobs
- [ ] **Batch Processing**: efektywne przetwarzanie dużych zbiorów danych w partiach
