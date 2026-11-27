# SPECER – system wewnętrzny

Wewnętrzny panel dla pracowników SPECER Centrum Rehabilitacji (Otwock, Wiązowna) wraz ze stroną główną.
Całość to jeden plik `index.html` (HTML + CSS + JavaScript), bez serwera i bez bazy danych.

## Uruchomienie
- Online: GitHub Pages (gałąź `main`, katalog główny).
- Lokalnie: otwórz `index.html` w przeglądarce.

## Pierwsze uruchomienie
1. Kliknij „Zaloguj się” i utwórz konto administratora.
2. W zakładce **Pracownicy** załóż konta pracownikom („Utwórz konto”).

## Funkcje
- Rezerwacja online dla pacjentów: placówka → usługa → specjalista → termin → dane, kod rezerwacji, sprawdzanie i odwoływanie (wersja demonstracyjna – bez serwera rezerwacje zostają w przeglądarce pacjenta).
- Grafik pracy i nieobecności specjalistów, lista oczekujących, plan terapii i skala bólu VAS, PESEL i zgody, raport miesięczny.
- Kalendarz z przeciąganiem wizyt, serie wizyt, blokada podwójnej rezerwacji, dwie placówki (Otwock, Wiązowna).
- Płatności (gotówka, karta, BLIK, telefon, przelew, pakiet, abonament) i pakiety wizyt ważne 3 miesiące.
- Przypomnienia przez WhatsApp, SMS i Gmail, dodawanie wizyt do Kalendarza Google i plik .ics.
- Strona główna: oferta, cennik, personel, integracja sensoryczna, partnerzy, regulamin, nawigacja Google Maps / Waze.

## Ważne
- Dane (pacjenci, wizyty, konta) są zapisywane tylko w przeglądarce (localStorage) na danym urządzeniu – nie są wspólne dla różnych komputerów.
- Przenoszenie danych: Ustawienia → Kopia zapasowa (pobierz / wczytaj JSON).
- Hasła są przechowywane jako skrót SHA-256 z solą, ale logowanie działa po stronie przeglądarki – to nie jest zabezpieczenie na poziomie serwera.
- Personel, cennik i dane kontaktowe pochodzą ze strony www.specer.pl.
- Ikony marek: [theSVG](https://thesvg.org) (licencja MIT), ikony interfejsu: [Lucide](https://lucide.dev) (licencja ISC). Nazwy i logotypy należą do ich właścicieli.
