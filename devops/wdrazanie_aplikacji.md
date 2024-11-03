# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Wdrażanie Aplikacji

## Podstawy wdrażania aplikacji
- [ ] **Różnice między środowiskami**: zrozumienie różnic między środowiskami deweloperskim, testowym i produkcyjnym
- [ ] **Konfiguracja środowisk**: jak ustawić zmienne środowiskowe i konfigurację dla różnych środowisk
- [ ] **Wdrażanie ręczne vs automatyczne**: kiedy i jak wdrażać aplikację ręcznie oraz jak skonfigurować automatyzację

## Narzędzia do wdrażania
- [ ] **Capistrano**: konfiguracja Capistrano do wdrażania aplikacji Rails
- [ ] **Docker**: tworzenie i użycie kontenerów Docker do wdrażania aplikacji
- [ ] **Heroku**: jak wdrażać aplikacje Rails na Heroku, korzystając z Heroku CLI
- [ ] **AWS (Amazon Web Services)**: podstawy wdrażania aplikacji na AWS, konfiguracja instancji EC2
- [ ] **Ansible, Chef, Puppet**: wprowadzenie do narzędzi do zarządzania konfiguracją i ich rola w automatyzacji wdrażania

## CI/CD (Continuous Integration/Continuous Deployment)
- [ ] **Podstawy CI/CD**: czym jest CI/CD i dlaczego jest istotne dla wdrażania aplikacji
- [ ] **Konfiguracja CI/CD**: jak skonfigurować CI/CD w GitHub Actions, GitLab CI lub Jenkins
- [ ] **Testy automatyczne przed wdrożeniem**: uruchamianie testów jednostkowych i integracyjnych w pipeline CI/CD
- [ ] **Wdrażanie automatyczne**: jak skonfigurować automatyczne wdrażanie po zatwierdzeniu zmian w repozytorium

## Konfiguracja serwera produkcyjnego
- [ ] **Serwery aplikacji**: konfiguracja serwerów takich jak Puma, Passenger, czy Unicorn dla aplikacji Rails
- [ ] **Reverse Proxy**: konfiguracja Nginx lub Apache jako reverse proxy dla aplikacji Rails
- [ ] **SSL/TLS**: instalacja i konfiguracja certyfikatów SSL/TLS dla zabezpieczenia komunikacji
- [ ] **Migracje bazy danych**: jak uruchamiać migracje bazy danych na serwerze produkcyjnym

## Zarządzanie zależnościami
- [ ] **Bundler**: użycie Bundlera do zarządzania gemami i zależnościami w środowisku produkcyjnym
- [ ] **Node.js i Yarn**: instalacja i zarządzanie zależnościami JavaScript dla Vue.js
- [ ] **Prekompilacja assetów**: jak prekompilować assety za pomocą `rails assets:precompile`

## Skalowalność i wydajność
- [ ] **Load Balancing**: jak skonfigurować load balancer dla aplikacji Rails, aby rozkładać ruch
- [ ] **Horizontal Scaling**: skalowanie aplikacji przez dodawanie nowych instancji serwerów
- [ ] **Monitoring aplikacji**: użycie narzędzi takich jak New Relic, Datadog do monitorowania wydajności i stanu aplikacji

## Zarządzanie błędami i logowanie
- [ ] **Logi aplikacji**: jak przechwytywać i analizować logi produkcyjne
- [ ] **Obsługa błędów**: konfiguracja narzędzi do zgłaszania błędów, takich jak Sentry lub Rollbar
- [ ] **Health Checks**: konfiguracja endpointów do sprawdzania, czy aplikacja działa poprawnie

## Zarządzanie bazą danych
- [ ] **Backupy bazy danych**: jak tworzyć i przywracać kopie zapasowe bazy danych w produkcji
- [ ] **Replikacja bazy danych**: wprowadzenie do replikacji danych w celu zwiększenia niezawodności i skalowalności
- [ ] **Optymalizacja zapytań**: jak monitorować i optymalizować zapytania SQL w środowisku produkcyjnym

## Bezpieczeństwo
- [ ] **Ochrona danych**: jak zabezpieczyć dane wrażliwe i skonfigurować odpowiednie uprawnienia
- [ ] **Zmienne środowiskowe**: bezpieczne przechowywanie kluczy API i danych konfiguracyjnych przy użyciu `dotenv` lub usług chmurowych
- [ ] **Firewall i zabezpieczenia sieci**: podstawy konfiguracji firewalla oraz zabezpieczeń serwera

## Najlepsze praktyki
- [ ] **Blue-Green Deployment**: czym jest wdrażanie blue-green i jak może pomóc w minimalizacji przestojów
- [ ] **Rollback wdrożenia**: jak szybko wycofać nieudane wdrożenie
- [ ] **Zero Downtime Deployment**: jak wdrażać aplikacje bez przestojów
