# Zakres Wiedzy dla Full Stack Developera Ruby on Rails + Vue.js: Vuex

## Podstawy Vuex
- [ ] **Co to jest Vuex**: zrozumienie, czym jest Vuex i jak działa jako wzorzec zarządzania stanem w Vue.js
- [ ] **Instalacja i konfiguracja**: jak zainstalować Vuex i skonfigurować go w projekcie Vue.js
- [ ] **Struktura Store**: podstawowa struktura store Vuex (`state`, `mutations`, `actions`, `getters`)

## State
- [ ] **Definiowanie stanu**: jak deklarować stan (state) w store Vuex
- [ ] **Dostęp do stanu**: jak uzyskiwać dostęp do stanu w komponentach za pomocą `this.$store.state`
- [ ] **Reaktywność stanu**: jak Vuex zapewnia reaktywność danych w stanie

## Getters
- [ ] **Tworzenie getterów**: jak definiować gettery do pobierania danych ze stanu
- [ ] **Dostęp do getterów**: jak uzyskiwać dostęp do getterów w komponentach za pomocą `this.$store.getters`
- [ ] **Gettery z parametrami**: jak tworzyć gettery, które mogą przyjmować parametry

## Mutations
- [ ] **Definiowanie mutacji**: jak tworzyć mutacje, aby zmieniać stan w Vuex
- [ ] **Commitowanie mutacji**: jak commitować mutacje w komponentach za pomocą `this.$store.commit`
- [ ] **Zasady mutacji**: dlaczego mutacje powinny być synchroniczne

## Actions
- [ ] **Tworzenie akcji**: jak definiować akcje do wykonywania operacji asynchronicznych, takich jak żądania API
- [ ] **Dispatchowanie akcji**: jak dispatchować akcje z komponentów za pomocą `this.$store.dispatch`
- [ ] **Łączenie akcji z mutacjami**: jak akcje mogą commitować mutacje po zakończeniu operacji asynchronicznych

## Moduły Vuex
- [ ] **Modularny Store**: jak podzielić store na moduły, aby lepiej zarządzać złożonymi aplikacjami
- [ ] **Namespace modułów**: jak używać `namespaced: true` do tworzenia modułów z przestrzenią nazw
- [ ] **Dostęp do stanu i getterów w modułach**: jak uzyskiwać dostęp do stanu i getterów w modułach

## Mapowanie helperów Vuex
- [ ] **mapState**: jak używać `mapState` do mapowania stanu do właściwości komponentu
- [ ] **mapGetters**: jak używać `mapGetters` do mapowania getterów do właściwości komponentu
- [ ] **mapMutations**: jak używać `mapMutations` do mapowania mutacji do metod komponentu
- [ ] **mapActions**: jak używać `mapActions` do mapowania akcji do metod komponentu

## Obsługa asynchroniczności
- [ ] **Asynchroniczne akcje**: jak zarządzać operacjami asynchronicznymi, np. żądaniami API, za pomocą akcji
- [ ] **Promise chaining**: jak łączyć promisy w akcjach, aby obsłużyć złożone przepływy danych
- [ ] **Obsługa błędów**: jak łapać i obsługiwać błędy w akcjach

## Najlepsze praktyki
- [ ] **Organizacja plików**: jak organizować pliki Vuex w dużych projektach
- [ ] **Czyszczenie stanu**: jak i kiedy czyścić stan Vuex, np. po wylogowaniu użytkownika
- [ ] **Unikanie wycieków pamięci**: jak unikać problemów z wydajnością i wycieków pamięci, gdy stan nie jest odpowiednio zarządzany

## Debugowanie Vuex
- [ ] **Vue Devtools**: jak używać Vue Devtools do debugowania stanu Vuex, mutacji i akcji
- [ ] **Logowanie mutacji i akcji**: jak logować mutacje i akcje do debugowania w środowisku deweloperskim
