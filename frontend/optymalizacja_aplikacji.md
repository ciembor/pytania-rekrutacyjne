# Zakres Wiedzy dla Full Stack Developera Ruby on Rails + Vue.js: Optymalizacja Aplikacji Frontendowej

## Optymalizacja wydajności
- [ ] **Lazy Loading komponentów**: jak używać `dynamic import()` i `Vue Router` do ładowania komponentów tylko wtedy, gdy są potrzebne
- [ ] **Code Splitting**: podział kodu na mniejsze fragmenty, aby skrócić czas ładowania strony
- [ ] **Tree Shaking**: zrozumienie, jak Webpack usuwa nieużywany kod, aby zmniejszyć rozmiar pakietu
- [ ] **Preloading i Prefetching**: konfiguracja, aby zasoby były ładowane z wyprzedzeniem w odpowiednich sytuacjach

## Optymalizacja renderowania
- [ ] **Virtual DOM**: zrozumienie, jak działa Virtual DOM w Vue.js i jak minimalizować re-renderowanie komponentów
- [ ] **Debounce i Throttle**: użycie technik `debounce` i `throttle` do optymalizacji często wykonywanych operacji, takich jak przewijanie
- [ ] **Watchers i Computed Properties**: kiedy używać `computed` zamiast `watch`, aby poprawić wydajność
- [ ] **V-if vs V-show**: wybór między `v-if` i `v-show` w zależności od potrzeb renderowania

## Optymalizacja zasobów
- [ ] **Kompresja i minifikacja**: użycie narzędzi do minifikacji plików CSS i JavaScript, np. `Terser` dla JS
- [ ] **Kompresja obrazów**: optymalizacja obrazów przed ich użyciem w aplikacji, np. użycie `ImageOptim` lub `TinyPNG`
- [ ] **WebP**: korzystanie z formatu WebP, aby zmniejszyć rozmiar obrazów bez utraty jakości
- [ ] **Lazy Loading obrazów**: ładowanie obrazów tylko wtedy, gdy są widoczne w oknie przeglądarki (użycie `Intersection Observer`)

## Optymalizacja CSS
- [ ] **Scoping stylów**: jak używać scoped CSS w komponentach, aby ograniczyć wpływ stylów
- [ ] **PurgeCSS**: usuwanie nieużywanych klas CSS w produkcji, aby zmniejszyć rozmiar CSS
- [ ] **Critical CSS**: generowanie i ładowanie krytycznych stylów, aby przyspieszyć renderowanie strony

## Zarządzanie stanem
- [ ] **Optymalizacja Vuex**: jak unikać niepotrzebnych re-renderów, kiedy dane w Vuex się zmieniają
- [ ] **Modular Vuex**: podział stanu Vuex na moduły, aby poprawić wydajność i organizację kodu
- [ ] **Shallow Copy i Deep Copy**: kiedy unikać głębokich kopii danych, aby zmniejszyć obciążenie aplikacji

## Obsługa zdarzeń
- [ ] **Unsubskrybowanie zdarzeń**: pamiętanie o usuwaniu nasłuchiwaczy zdarzeń, aby uniknąć wycieków pamięci
- [ ] **Delegacja zdarzeń**: optymalizacja dużych list elementów poprzez delegowanie zdarzeń
- [ ] **Przemyślane użycie `v-once`**: renderowanie komponentu tylko raz, jeśli jego dane nie będą się zmieniać

## Webpack i Build Tools
- [ ] **Optymalizacja Webpack**: konfiguracja Webpack, aby zmniejszyć rozmiar pakietu i przyspieszyć build
- [ ] **Bundle Analyzer**: jak używać narzędzia `webpack-bundle-analyzer`, aby zidentyfikować największe zależności w aplikacji
- [ ] **Source Maps**: kiedy i jak używać map źródłowych w środowisku produkcyjnym, aby zachować równowagę między debugowaniem a wydajnością

## Optymalizacja czasu ładowania
- [ ] **Critical Rendering Path**: zrozumienie, jak przeglądarka ładuje i renderuje stronę, aby zoptymalizować ten proces
- [ ] **Asynchroniczne ładowanie skryptów**: użycie atrybutów `async` i `defer` w skryptach, aby przyspieszyć ładowanie strony
- [ ] **Preloading czcionek**: ładowanie czcionek z wyprzedzeniem, aby zmniejszyć opóźnienia renderowania tekstu

## Optymalizacja interfejsu użytkownika
- [ ] **Animacje i przejścia**: unikanie kosztownych animacji, które wpływają na wydajność, i używanie `requestAnimationFrame`
- [ ] **Smooth Scrolling**: optymalizacja płynnego przewijania za pomocą CSS i JavaScript
- [ ] **Feedback dla użytkownika**: zapewnienie odpowiedniego feedbacku (np. wskaźników ładowania) podczas ładowania danych
