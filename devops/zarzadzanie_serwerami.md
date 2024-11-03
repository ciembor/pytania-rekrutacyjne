# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Zarządzanie Serwerami

## Podstawy zarządzania serwerami
- [ ] **Systemy operacyjne**: znajomość systemu Linux (np. Ubuntu, CentOS) oraz podstawowe komendy terminalowe
- [ ] **SSH**: konfiguracja i użycie SSH do bezpiecznego łączenia się z serwerami zdalnymi
- [ ] **Konta użytkowników i uprawnienia**: zarządzanie użytkownikami i grupami oraz przyznawanie odpowiednich uprawnień

## Konfiguracja serwera
- [ ] **Konfiguracja firewalla**: użycie `ufw` (Uncomplicated Firewall) lub `iptables` do zabezpieczenia serwera
- [ ] **Zarządzanie pakietami**: instalowanie, aktualizowanie i usuwanie pakietów za pomocą `apt`, `yum` lub innych menedżerów pakietów
- [ ] **Automatyzacja konfiguracji**: używanie narzędzi takich jak Ansible, Chef, czy Puppet do automatyzacji konfiguracji serwerów

## Serwery aplikacji
- [ ] **Puma**: konfiguracja serwera Puma do uruchamiania aplikacji Rails
- [ ] **Passenger**: konfiguracja Phusion Passenger jako serwera aplikacji, w szczególności dla wdrożeń produkcyjnych
- [ ] **Unicorn**: podstawy konfiguracji serwera Unicorn i kiedy warto go używać

## Reverse Proxy
- [ ] **Nginx**: konfiguracja Nginx jako reverse proxy dla aplikacji Rails, w tym obsługa SSL i przekierowania
- [ ] **Apache**: podstawy konfiguracji Apache jako reverse proxy, w tym różnice w stosunku do Nginx
- [ ] **Load Balancing**: użycie Nginx lub Apache do rozkładania obciążenia między wieloma instancjami aplikacji

## Monitorowanie i logowanie
- [ ] **Logi serwera**: lokalizacja i analiza logów systemowych oraz logów aplikacji (np. `/var/log`)
- [ ] **Monitorowanie zasobów**: użycie narzędzi takich jak `htop`, `top`, `iostat` do monitorowania użycia CPU, pamięci i dysku
- [ ] **Automatyczne powiadomienia**: konfiguracja powiadomień (np. e-mailowych) w przypadku wykrycia problemów z serwerem

## Backup i odzyskiwanie danych
- [ ] **Kopie zapasowe**: strategie tworzenia kopii zapasowych, narzędzia do backupu (np. `rsync`, `tar`) oraz przywracanie danych
- [ ] **Snapshoty**: tworzenie snapshotów serwera w celu szybkiego przywrócenia systemu w przypadku awarii
- [ ] **Szyfrowanie danych**: jak zabezpieczać kopie zapasowe, aby były bezpieczne

## Zarządzanie bazami danych
- [ ] **Instalacja i konfiguracja**: instalowanie i konfigurowanie Postgres, MySQL, lub innych silników baz danych
- [ ] **Optymalizacja**: monitorowanie wydajności bazy danych i optymalizacja ustawień serwera bazy danych
- [ ] **Replikacja**: wprowadzenie do replikacji bazy danych w celu zwiększenia niezawodności

## Skalowanie serwerów
- [ ] **Pionowe vs. poziome skalowanie**: zrozumienie różnic i kiedy stosować każdą strategię
- [ ] **Autoskalowanie**: jak skonfigurować serwery do automatycznego skalowania w zależności od obciążenia
- [ ] **Load Balancing**: konfiguracja i zarządzanie load balancerami w celu rozkładania ruchu

## Bezpieczeństwo serwera
- [ ] **Hardening serwera**: zabezpieczanie serwera poprzez ograniczenie dostępu, zamykanie niepotrzebnych portów, itp.
- [ ] **Certyfikaty SSL/TLS**: instalacja i konfiguracja certyfikatów SSL dla bezpiecznej komunikacji
- [ ] **Regularne aktualizacje**: utrzymywanie serwera w aktualnej wersji, aby zabezpieczyć go przed znanymi lukami

## Zarządzanie procesami
- [ ] **Systemd**: jak zarządzać usługami i procesami za pomocą `systemd` (np. uruchamianie aplikacji Rails jako usługi)
- [ ] **Cron Jobs**: tworzenie zadań cron do automatyzacji działań, takich jak backupy lub czyszczenie logów
- [ ] **Supervisor**: użycie Supervisora do monitorowania i restartowania procesów w przypadku awarii

## Narzędzia do zarządzania serwerami
- [ ] **Docker**: uruchamianie aplikacji w kontenerach Docker na serwerach produkcyjnych
- [ ] **Kubernetes**: wprowadzenie do orkiestracji kontenerów i zarządzania klastrami
- [ ] **Terraform**: podstawy użycia Terraform do automatycznego zarządzania infrastrukturą
