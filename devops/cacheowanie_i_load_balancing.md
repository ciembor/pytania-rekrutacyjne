# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Cache'owanie i Load Balancing

## Cache'owanie
- [ ] **Podstawy cache'owania**: zrozumienie, czym jest cache'owanie i dlaczego jest ważne dla wydajności aplikacji
- [ ] **Rodzaje cache'owania**: cache'owanie na poziomie aplikacji, cache'owanie obiektów, cache'owanie stron
- [ ] **Cache'owanie fragmentów**: użycie `fragment_cache` do przechowywania części widoków, które nie zmieniają się często
- [ ] **Cache'owanie w kontrolerach**: jak stosować `before_action` do cache'owania całych odpowiedzi API
- [ ] **ActiveSupport::Cache**: konfiguracja cache'owania w Rails, korzystanie z backendów takich jak Redis, Memcached
- [ ] **HTTP Cache**: jak konfigurować nagłówki HTTP dla cache'owania po stronie klienta, np. `Cache-Control`, `ETag`
- [ ] **Russian Doll Caching**: strategia cache'owania, która wykorzystuje zagnieżdżone fragmenty, aby zoptymalizować wydajność
- [ ] **Wygaszanie cache'u**: kiedy i jak wygaszać (inwalidować) cache, aby dane były aktualne
- [ ] **Configuring Redis**: podstawy konfiguracji Redis jako backendu cache'owania w aplikacjach Rails

## Load Balancing
- [ ] **Podstawy load balancingu**: czym jest load balancing i dlaczego jest kluczowy dla skalowalności aplikacji
- [ ] **Rodzaje load balancerów**: load balancery sprzętowe vs. programowe, np. Nginx, HAProxy, AWS ELB
- [ ] **Round Robin vs. Least Connections**: zrozumienie różnych algorytmów load balancingu i ich zastosowań
- [ ] **Sticky Sessions**: co to są sesje lepkie i kiedy warto je stosować
- [ ] **SSL Termination**: konfiguracja load balancera do rozpoznawania i obsługi SSL
- [ ] **Health Checks**: jak konfigurować health checks dla instancji aplikacji, aby load balancer mógł odciążyć niedziałające serwery
- [ ] **Scaling aplikacji**: jak load balancer wspomaga skalowanie aplikacji w poziomie
- [ ] **Konfiguracja Nginx jako load balancera**: jak skonfigurować Nginx do dystrybucji ruchu między instancje aplikacji

## Optymalizacja cache'owania i load balancingu
- [ ] **Profilowanie cache'u**: jak mierzyć wydajność cache'owania i identyfikować wąskie gardła
- [ ] **Monitorowanie load balancingu**: narzędzia do monitorowania obciążenia serwerów i ruchu sieciowego
- [ ] **Failover i wysokodostępność**: jak skonfigurować load balancer do automatycznego failovera
- [ ] **Testing load balancing**: jak testować konfigurację load balancingu i symulować wysokie obciążenie

## Najlepsze praktyki
- [ ] **Cache tylko to, co konieczne**: unikanie cache'owania danych, które zmieniają się często
- [ ] **Obsługa cache stampede**: strategie radzenia sobie z nagłym obciążeniem, gdy wiele żądań odświeża cache w tym samym czasie
- [ ] **Planowanie wygaszenia cache'u**: harmonogramy inwalidacji cache'u, aby uniknąć spadków wydajności
- [ ] **Bezpieczeństwo w load balancingu**: jak zabezpieczyć load balancer przed atakami DDoS i innymi zagrożeniami
