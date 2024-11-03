# Zakres Wiedzy dla Full Stack Developera Ruby on Rails: Bezpieczeństwo Aplikacji

## Ochrona przed atakami
- [ ] **Cross-Site Request Forgery (CSRF)**: jak Rails domyślnie chroni przed atakami CSRF i kiedy używać `skip_before_action :verify_authenticity_token`
- [ ] **Cross-Site Scripting (XSS)**: zabezpieczenie aplikacji poprzez automatyczne escape'owanie HTML i stosowanie `sanitize` lub `strip_tags`
- [ ] **SQL Injection**: ochrona przed wstrzyknięciami SQL poprzez korzystanie z zapytań Active Record i placeholderów (`where("name = ?", name)`)
- [ ] **Mass Assignment**: używanie `strong parameters` w kontrolerach, aby chronić przed nieautoryzowaną modyfikacją atrybutów

## Uwierzytelnianie i Autoryzacja
- [ ] **Uwierzytelnianie użytkowników**: korzystanie z gemów, takich jak `Devise`, do zarządzania logowaniem i hasłami
- [ ] **Haszowanie haseł**: zrozumienie, jak Rails haszuje hasła za pomocą `bcrypt` i przechowywanie bezpiecznych haseł
- [ ] **Autoryzacja dostępu**: implementacja polityk dostępu użytkowników za pomocą `Pundit`, `CanCanCan` lub własnych rozwiązań
- [ ] **Token-based Authentication**: wdrażanie bezpiecznych tokenów API (np. JWT) do autoryzacji

## Ochrona danych
- [ ] **Bezpieczne przechowywanie danych wrażliwych**: szyfrowanie danych za pomocą `ActiveSupport::MessageEncryptor`
- [ ] **Bezpieczna konfiguracja**: korzystanie z `Rails.credentials` lub gemów takich jak `dotenv-rails` do przechowywania kluczy API i tajnych danych
- [ ] **Bezpieczne logowanie**: unikanie wycieku danych wrażliwych w logach aplikacji

## Nagłówki bezpieczeństwa
- [ ] **HTTP Security Headers**: konfiguracja nagłówków takich jak `X-Content-Type-Options`, `X-Frame-Options`, `X-XSS-Protection`, `Strict-Transport-Security`
- [ ] **Content Security Policy (CSP)**: ograniczanie typów zasobów, które mogą być załadowane przez aplikację

## Obsługa błędów i wyjątków
- [ ] **Bezpieczna obsługa błędów**: renderowanie przyjaznych komunikatów błędów bez ujawniania szczegółów dotyczących aplikacji
- [ ] **Zapobieganie atakom typu enumeration**: minimalizowanie ilości informacji zwracanych w odpowiedziach błędów (np. nie ujawnianie, czy dany e-mail istnieje w bazie)

## Ochrona przed atakami typu DoS
- [ ] **Rate Limiting**: ograniczanie liczby żądań za pomocą `Rack::Attack`
- [ ] **Throttle Requests**: implementacja mechanizmów blokujących zbyt częste żądania od tego samego IP

## Inne środki bezpieczeństwa
- [ ] **Regularne aktualizacje gemów**: monitorowanie zależności za pomocą narzędzi, takich jak `Bundler Audit` i aktualizowanie ich, aby uniknąć luk w zabezpieczeniach
- [ ] **Zarządzanie sesjami**: zabezpieczanie sesji, ustawianie limitów czasowych, unikanie przechowywania wrażliwych danych w sesji
- [ ] **Szyfrowanie transmisji danych**: wymuszanie HTTPS i konfiguracja `force_ssl` w Rails
- [ ] **Używanie `Secure` i `HttpOnly` dla ciasteczek**: zapobieganie kradzieży ciasteczek przez skrypty JavaScript
