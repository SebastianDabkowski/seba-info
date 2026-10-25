# Seba Info

Osobiste repozytorium raportów, analiz i hipotez biznesowych. Strony HTML są publikowane przez GitHub Pages w formie zaszyfrowanej przez StatiCrypt i wymagają wspólnego hasła.

**Strona główna:** https://sebastiandabkowski.github.io/seba-info/

## Status zabezpieczenia

**Aktualne pliki HTML są zaszyfrowane przez StatiCrypt (24.10.2026).** Dostęp do raportów wymaga hasła, które nie jest przechowywane w repozytorium. **UWAGA:** w dotychczasowej publicznej historii Git pozostają wcześniejsze, niezaszyfrowane wersje raportów. Zabezpieczenie nie jest kompletne, dopóki nie zostanie utworzone nowe repozytorium z czystą historią. Nawet to nie gwarantuje usunięcia wcześniej pobranych kopii.

## Raporty

<!-- SEBA-INFO-REPORTS-START -->
| Data publikacji | Raport | Opis | Strona |
| --- | --- | --- | --- |
| 2026-10-25 | Financial Decision Intelligence / Wizualna koncepcja produktu 🔒 | Interaktywny opis produktu: dashboard CFO, diagnoza odchyleń, analiza otoczenia, symulator scenariuszy, architektura, moduły, MVP i roadmapa. | [Otwórz](https://sebastiandabkowski.github.io/seba-info/2026-10-25-opis-produktu-financial-decision-intelligence.html) |
| 2026-10-24 | Test publikacji 🔒 | Strona demonstracyjna sprawdzająca automatyczne szyfrowanie i publikację HTML. | [Otwórz](https://sebastiandabkowski.github.io/seba-info/test-publikacji.html) |
| 2026-10-24 | Financial Forecasting & Decision Intelligence / Hipoteza H1 🔒 | Pomysł produktowy: od Exceli przez forecast i diagnozę odchyleń po analizę otoczenia, rekomendacje AI, ICP, MVP, monetyzację i walidację. | [Otwórz](https://sebastiandabkowski.github.io/seba-info/hipoteza-financial-decision-intelligence-2026-10-24.html) |
| 2026-10-24 | TOP 100 spółek notowanych wyłącznie na GPW 🔒 | Ranking kapitalizacji i ceny na 23.10.2026. Tylko Główny Rynek GPW, bez GlobalConnect, NewConnect i dual-listingu zagranicznego. | [Otwórz](https://sebastiandabkowski.github.io/seba-info/gpw-rynek-glowny-top100-2026-10-23.html) |
| 2026-10-24 | Finance Performance Cockpit 🔒 | Hipoteza biznesowa: prognozowanie finansowe z Power BI i AI, ICP, oferta i strategia sprzedaży. | [Otwórz](https://sebastiandabkowski.github.io/seba-info/finance-performance-cockpit.html) |
| 2026-10-24 | Arpeggia Studio / Strategia dedykowanych warsztatów doradczych 🔒 | Prezentacja dla zarządu: 6 etapów współpracy od diagnozy problemu przez 3-dniowy warsztat do planu działania i opcjonalnego mentoringu. | [Otwórz](https://sebastiandabkowski.github.io/seba-info/arpeggia-strategia-warsztatow-doradczych-2026-10-24.html) |
<!-- SEBA-INFO-REPORTS-END -->

## Zasady publikowania kolejnych raportów HTML

1. **Przed wysłaniem raportu do publicznego repozytorium zaszyfruj lokalnie kompletny HTML przez StatiCrypt.** Nigdy nie wrzucaj tam tekstu źródłowego ani hasła. Weryfikuj, że HTML zawiera formularz StatiCrypt, a tekst raportu nie występuje jawnie.
2. **Każdy nowy raport otrzymuje własną, czytelną nazwę pliku HTML**, złożoną z krótkich słów opisujących temat, np. `analiza-rynku-ai-2026.html`. Nazwy stosują małe litery, cyfry i myślniki (kebab-case). Nie publikujemy kolejnych raportów pod nazwą `index.html`.
3. **Każda publikacja lub istotna aktualizacja raportu wymaga aktualizacji `README.md`**. Dodaj lub zmodyfikuj wpis w tabeli: data publikacji, tytuł, krótki opis i publiczny link.
4. Nowe raporty umieszczamy w tabeli **od najnowszych**. Gdy aktualizowany jest istniejący materiał, aktualizujemy jego dotychczasowy wpis zamiast tworzyć duplikat.
5. Publiczny adres raportu ma format `https://sebastiandabkowski.github.io/seba-info/<nazwa-pliku>.html`.
6. `index.html` pozostaje punktem wejścia do serwisu. Nowe raporty zapisujemy pod osobnymi nazwami, nie nadpisując przypadkowo strony głównej.
7. Przed publikacją w publicznym repozytorium sprawdzamy, czy raport nie zawiera poufnych danych, danych osobowych ani informacji objętych NDA.

### Dla asystenta publikującego przez GitHub

Przy każdej prośbie o dodanie strony HTML do repozytorium `SebastianDabkowski/seba-info`: sprawdź istniejące pliki, nadaj nazwę opisową, dodaj lub zaktualizuj HTML, uaktualnij `README.md` oraz zwróć link do opublikowanej strony. Nigdy nie zakładaj, że wystarczy samo zapisanie pliku HTML.

> Historycznie pierwszy raport jest także dostępny pod adresem strony głównej (`index.html`). Jego nazwany plik to `finance-performance-cockpit.html`.
