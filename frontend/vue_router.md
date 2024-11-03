# Zakres Wiedzy dla Full Stack Developera Ruby on Rails + Vue.js: Vue Router

## Podstawy Vue Router
- [ ] **Instalacja i konfiguracja**: jak zainstalować Vue Router i skonfigurować go w projekcie Vue.js
- [ ] **Definiowanie tras**: jak tworzyć podstawowe trasy za pomocą `routes` w pliku konfiguracyjnym
- [ ] **Komponenty routingu**: jak ładować komponenty za pomocą Vue Router, np. `Home`, `About`
- [ ] **Router View i Router Link**: użycie `<router-view>` i `<router-link>` do nawigacji w aplikacji

## Dynamiczne trasy i parametry
- [ ] **Trasy dynamiczne**: jak definiować dynamiczne trasy z parametrami, np. `/user/:id`
- [ ] **Odczytywanie parametrów**: jak uzyskać dostęp do parametrów trasy za pomocą `this.$route.params`
- [ ] **Zachowanie tras**: zrozumienie, jak Vue Router obsługuje zmiany parametrów i aktualizacje komponentów

## Nawigacja programowa
- [ ] **Programowa nawigacja**: jak nawigować za pomocą `this.$router.push()`, `this.$router.replace()`
- [ ] **Przechodzenie wstecz i do przodu**: użycie `this.$router.go()` do przechodzenia w historii przeglądarki
- [ ] **Obsługa nawigacji asynchronicznej**: jak obsługiwać asynchroniczne operacje przed nawigacją

## Guardy tras
- [ ] **Globalne guardy tras**: jak używać `beforeEach` i `afterEach` do obsługi zdarzeń globalnych
- [ ] **Guardy na trasach**: definiowanie guardów na poziomie trasy, aby ograniczać dostęp do stron
- [ ] **Guardy komponentów**: użycie `beforeRouteEnter`, `beforeRouteUpdate`, `beforeRouteLeave` w komponentach
- [ ] **Autoryzacja i uwierzytelnianie**: jak zabezpieczyć trasy przed nieautoryzowanym dostępem

## Trasy zagnieżdżone
- [ ] **Definiowanie tras zagnieżdżonych**: jak tworzyć trasy zagnieżdżone dla hierarchicznych komponentów
- [ ] **Routowanie zagnieżdżone**: jak używać `<router-view>` w komponentach zagnieżdżonych
- [ ] **Przekazywanie parametrów tras zagnieżdżonych**: jak obsługiwać parametry w trasach zagnieżdżonych

## Trasy nazwane
- [ ] **Tworzenie tras nazwanych**: jak definiować trasy z `name` i nawigować przy użyciu `this.$router.push({ name: 'routeName' })`
- [ ] **Przekazywanie parametrów do tras nazwanych**: jak nawigować do tras nazwanych z parametrami i query

## Obsługa błędów i przekierowania
- [ ] **Przekierowania**: jak konfigurować przekierowania za pomocą `redirect` w definicji tras
- [ ] **Strony 404**: jak obsługiwać nieistniejące trasy i definiować stronę błędu 404
- [ ] **Obsługa błędów nawigacji**: jak obsługiwać błędy nawigacji i używać `next()` w guardach tras

## Tryby historii
- [ ] **Mode "hash"**: jak działa domyślny tryb hash i dlaczego używa `#` w URL
- [ ] **Mode "history"**: jak skonfigurować tryb historii HTML5 i jakie są jego zalety
- [ ] **Fallback dla trybu historii**: jak obsługiwać fallback dla trybu historii w przypadku braku wsparcia

## Lazy Loading komponentów
- [ ] **Ładowanie komponentów asynchronicznych**: jak konfigurować lazy loading dla dużych komponentów, aby zoptymalizować wydajność
- [ ] **Code splitting**: jak Vue Router automatycznie dzieli kod, aby skrócić czas ładowania

## Praca z Vuex i Vue Router
- [ ] **Integracja Vuex z Vue Router**: jak zarządzać nawigacją i stanem aplikacji przy użyciu Vuex
- [ ] **Nawigacja w zależności od stanu**: jak zmieniać trasy w oparciu o stan Vuex, np. nawigowanie po zalogowaniu użytkownika
