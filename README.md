# SPECER – system wewnętrzny

Wewnętrzny panel dla pracowników SPECER Centrum Rehabilitacji (Otwock, Wiązowna) wraz ze stroną główną.
Całość to jeden plik `index.html` (HTML + CSS + JavaScript), bez serwera i bez bazy danych.

## Uruchomienie
- Online: GitHub Pages (gałąź `main`, katalog główny).
- Lokalnie: otwórz `index.html` w przeglądarce.

## Pierwsze uruchomienie
1. Kliknij „Zaloguj się” i utwórz konto administratora.
2. W zakładce **Pracownicy** załóż konta pracownikom („Utwórz konto”).

## Ważne
- Dane (pacjenci, wizyty, konta) są zapisywane tylko w przeglądarce (localStorage) na danym urządzeniu – nie są wspólne dla różnych komputerów.
- Przenoszenie danych: Ustawienia → Kopia zapasowa (pobierz / wczytaj JSON).
- Hasła są przechowywane jako skrót SHA-256 z solą, ale logowanie działa po stronie przeglądarki – to nie jest zabezpieczenie na poziomie serwera.
- Personel, cennik i dane kontaktowe pochodzą ze strony www.specer.pl.
