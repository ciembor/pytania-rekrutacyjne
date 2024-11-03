# Zakres Wiedzy dla Full Stack Developera Ruby on Rails + Vue.js: Testowanie Frontendu

## Podstawy testowania frontendu
- [ ] **Dlaczego testujemy frontend**: zrozumienie znaczenia testów w utrzymaniu stabilności aplikacji
- [ ] **Rodzaje testów**: testy jednostkowe, integracyjne, e2e (end-to-end), snapshoty
- [ ] **Pyramid of Testing**: co to jest piramida testów i jakie testy są najważniejsze

## Narzędzia do testowania
- [ ] **Jest**: podstawy konfiguracji i używania frameworka testowego Jest
- [ ] **Vue Test Utils**: jak używać Vue Test Utils do testowania komponentów Vue.js
- [ ] **Cypress**: użycie Cypress do testów e2e i integracyjnych
- [ ] **Mockowanie i stubowanie**: kiedy i jak używać mocków i stubów w testach

## Testy jednostkowe
- [ ] **Testowanie komponentów**: jak pisać testy jednostkowe dla komponentów Vue.js
- [ ] **Props i emitery**: testowanie, czy komponenty poprawnie otrzymują propsy i emitują zdarzenia
- [ ] **Computed properties i watchery**: jak testować obliczone właściwości i obserwatorów
- [ ] **Testowanie metod**: pisanie testów dla metod komponentów

## Snapshot Testing
- [ ] **Snapshoty**: co to są snapshoty i jak używać ich do sprawdzania wyglądu komponentów
- [ ] **Aktualizowanie snapshotów**: kiedy i jak aktualizować snapshoty, gdy zmienia się wygląd komponentu
- [ ] **Testowanie regresji**: jak snapshoty pomagają w wykrywaniu niezamierzonych zmian

## Testowanie interakcji
- [ ] **Simulowanie zdarzeń**: użycie `trigger` do symulowania kliknięć, wprowadzania danych i innych interakcji
- [ ] **Testowanie formularzy**: sprawdzanie, czy formularze reagują poprawnie na dane wejściowe użytkownika
- [ ] **Obsługa zdarzeń asynchronicznych**: jak testować operacje asynchroniczne, np. żądania API w komponentach

## Mockowanie zależności
- [ ] **Mockowanie API**: jak mockować żądania HTTP, aby testować komponenty w izolacji
- [ ] **Mockowanie modułów**: jak zastępować zależności, takie jak Vuex, za pomocą mocków
- [ ] **Sprawdzanie wywołań API**: jak testować, czy komponenty poprawnie wywołują API

## Testowanie Vuex
- [ ] **Testowanie akcji Vuex**: jak pisać testy dla akcji Vuex, zarówno synchronicznych, jak i asynchronicznych
- [ ] **Testowanie mutacji**: sprawdzanie, czy mutacje Vuex poprawnie modyfikują stan
- [ ] **Testowanie getterów**: pisanie testów dla getterów Vuex

## Testowanie routingu
- [ ] **Vue Router**: jak testować komponenty w kontekście routingu
- [ ] **Mockowanie nawigacji**: testowanie, czy nawigacja działa poprawnie i przekierowuje użytkowników na odpowiednie trasy
- [ ] **Sprawdzanie routingu warunkowego**: jak testować warunkowe przekierowania i guardy routingu

## Testowanie integracyjne
- [ ] **Łączenie komponentów**: jak pisać testy, które sprawdzają współdziałanie wielu komponentów
- [ ] **Testowanie pełnych przepływów użytkownika**: symulowanie pełnych interakcji, np. logowania, wysyłania formularzy
- [ ] **Sprawdzanie interfejsu użytkownika**: jak testować, czy interfejs jest zgodny z oczekiwaniami, np. za pomocą Cypress

## Testowanie e2e (end-to-end)
- [ ] **Pisanie testów e2e**: jak używać Cypress do pisania testów, które sprawdzają pełne działanie aplikacji w przeglądarce
- [ ] **Konfiguracja Cypress**: ustawienia i konfiguracja Cypress dla testów w różnych środowiskach
- [ ] **Debugowanie testów e2e**: jak debugować testy e2e, gdy coś pójdzie nie tak

## Optymalizacja testów
- [ ] **Równoległe uruchamianie testów**: jak przyspieszyć testowanie przez uruchamianie testów równolegle
- [ ] **Strategie mockowania**: kiedy mockować, a kiedy testować rzeczywiste zależności
- [ ] **Flaky tests**: jak radzić sobie z niestabilnymi testami, które czasami przechodzą, a czasami nie
