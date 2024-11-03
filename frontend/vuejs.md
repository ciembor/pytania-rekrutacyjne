# Zakres Wiedzy dla Full Stack Developera Ruby on Rails + Vue.js: Vue.js

## Podstawy Vue.js
- [ ] **Instalacja i konfiguracja**: jak rozpocząć projekt Vue.js, używając Vue CLI lub osadzenia Vue.js w istniejącym projekcie
- [ ] **Vue Instance**: co to jest instancja Vue, jak działa i jakie są jej podstawowe opcje (`el`, `data`, `methods`, `computed`, itd.)
- [ ] **Renderowanie danych**: jak wyświetlać dane w szablonach przy użyciu `{{ }}` (interpolacja)

## Komponenty
- [ ] **Tworzenie komponentów**: jak definiować i rejestrować komponenty lokalnie i globalnie
- [ ] **Props**: jak przekazywać dane z komponentu nadrzędnego do komponentu podrzędnego
- [ ] **Emitowanie zdarzeń**: jak komponenty podrzędne mogą komunikować się z komponentami nadrzędnymi przy użyciu `$emit`
- [ ] **Sloty**: jak tworzyć elastyczne komponenty przy użyciu slotów (`<slot>`), w tym slotów nazwanych i zagnieżdżonych
- [ ] **Komponenty zagnieżdżone**: jak organizować komponenty i zarządzać ich hierarchią

## Reaktywność
- [ ] **Reaktywne właściwości**: jak Vue.js śledzi zmiany w danych i aktualizuje widoki
- [ ] **Computed properties**: czym są obliczone właściwości i kiedy ich używać zamiast metod
- [ ] **Watchers**: jak i kiedy używać watcherów do śledzenia zmian w danych
- [ ] **Metody**: różnice między metodami, computed properties i watcherami

## Zarządzanie danymi
- [ ] **Data binding**: zrozumienie jednokierunkowego i dwukierunkowego wiązania danych (`v-bind`, `v-model`)
- [ ] **Praca z formularzami**: jak obsługiwać dane wejściowe użytkownika za pomocą `v-model` i walidować dane
- [ ] **Obsługa zdarzeń**: jak używać `v-on` do obsługi zdarzeń, takich jak kliknięcia, wprowadzanie danych i inne

## Dyrektywy
- [ ] **Podstawowe dyrektywy**: `v-if`, `v-else`, `v-for`, `v-bind`, `v-on`, `v-show`
- [ ] **V-for**: jak iterować po tablicach i obiektach oraz korzystać z indeksów
- [ ] **V-if vs V-show**: kiedy używać `v-if` w porównaniu do `v-show` w celu optymalizacji renderowania
- [ ] **V-model**: jak działa `v-model` w różnych elementach formularza (input, textarea, select)

## Lifecycle hooks
- [ ] **Zrozumienie cyklu życia komponentu**: `created`, `mounted`, `updated`, `destroyed` i kiedy je wykorzystywać
- [ ] **Hooki przed i po renderowaniu**: różnice między `beforeMount` i `mounted`, `beforeUpdate` i `updated`

## Style i klasy CSS
- [ ] **Dynamiczne klasy i style**: jak używać `v-bind:class` i `v-bind:style` do dynamicznego stosowania klas i stylów
- [ ] **Scoped CSS**: jak ograniczać style CSS tylko do komponentu, w którym są zdefiniowane
- [ ] **Praca z bibliotekami CSS**: integracja Vue.js z bibliotekami stylów, takimi jak Bootstrap czy Tailwind

## Obsługa zdarzeń i formularzy
- [ ] **Obsługa zdarzeń**: jak zatrzymywać propagację zdarzeń (`.stop`), zapobiegać domyślnym działaniom (`.prevent`) i inne modyfikatory zdarzeń
- [ ] **Walidacja formularzy**: jak walidować dane formularza przed ich przesłaniem

## Praca z asynchronicznością
- [ ] **Ładowanie danych**: jak używać `axios` lub `fetch` do pobierania danych z API
- [ ] **Obsługa błędów**: jak obsługiwać błędy asynchroniczne w aplikacjach Vue.js
- [ ] **Asynchroniczne metody**: jak deklarować i używać metod asynchronicznych w komponentach

## Optymalizacja
- [ ] **Renderowanie warunkowe**: jak unikać niepotrzebnych renderów i optymalizować działanie aplikacji
- [ ] **V-once**: kiedy używać `v-once` do renderowania elementów, które nie muszą się aktualizować
- [ ] **V-pre**: jak używać `v-pre` do ignorowania renderowania i oszczędzania zasobów

## Integracja z innymi narzędziami
- [ ] **Praca z pluginami Vue**: jak instalować i używać pluginów, np. `vue-toastification`, `vue-i18n`
- [ ] **Integracja z bibliotekami trzecimi**: jak integrować Vue.js z bibliotekami JavaScript, np. Chart.js, D3.js
