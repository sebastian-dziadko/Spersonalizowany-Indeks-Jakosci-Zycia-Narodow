# Spersonalizowany Indeks Jakości Życia Narodów
Aplikacja w Pythonie, która pozwala użytkownikowi na spersonalizowane obliczanie Indeksu Jakości Życia dla krajów OECD. Użytkownik decyduje o znaczeniu (wadze) każdego z kilkunastu wskaźników, a aplikacja dynamicznie przelicza ranking.

Tradycyjne indeksy jakości życia (np. Human Development Index - HDI) wykorzystują z góry ustalone wagi. Ta aplikacja daje pełną kontrolę użytkownikowi. Pozwala ona odpowiedzieć na pytanie: "Jak wyglądałby ranking krajów, gdyby to moje priorytety (np. długość życia i niskie nierówności) były najważniejsze?".

Kluczowe Funkcje:
  Personalizacja Wag: Użytkownik może ustawiać wagi (od 0 do 100) dla każdego z 20 wskaźników za pomocą interaktywnych suwaków.

  Dynamiczne Przeliczanie: Ranking krajów aktualizuje się natychmiast po zmianie wagi dowolnego czynnika.

  Wizualizacja: Prezentacja rankingu na czytelnym wykresie słupkowym oraz w tabeli dla TOP 10.

  Szeroki Zakres Wskaźników: Analiza opiera się na danych z 20 różnych kategorii, obejmujących aspekty ekonomiczne, społeczne, zdrowotne i środowiskowe (patrz lista poniżej).

Lista wskaźników:
## Szczegółowy Opis Wskaźników 📊

Aplikacja wykorzystuje 16 wskaźników, z których każdy może być spersonalizowany przez użytkownika. Dane bazują głównie na statystykach krajów **OECD**.

| Wskaźnik (w aplikacji) | Pełna Nazwa / Definicja | Kategoria |
| :--- | :--- | :--- |
| **Pkb per capita** | Produkt Krajowy Brutto na mieszkańca. Miernik bogactwa i wielkości gospodarki. | Ekonomia |
| **Konsumpcja** | Wydatki konsumpcyjne gospodarstw domowych, mierzące siłę nabywczą. | Ekonomia |
| **Długość życia kobiet/mężczyzn** | Oczekiwana długość życia w chwili urodzenia. | Zdrowie |
| **Stopa bezrobocia** | Procent siły roboczej bez pracy. Wskaźnik stabilności rynku pracy. | Rynek Pracy |
| **Średnia roczna płaca** | Średnia wynagrodzeń w kraju w skali roku. | Ekonomia |
| **Decyl 9/1 zarobki/dochód** | Stosunek dochodów (lub zarobków) 10% najbogatszych do 10% najbiedniejszych. | Nierówności |
| **Liczba godzin przepracowanych/pracownika** | Średnia liczba godzin przepracowanych rocznie. Wskaźnik Work-Life Balance. | Rynek Pracy |
| **Liczba samobójstw na 100 tys.** | Wskaźnik zdrowia psychicznego i bezpieczeństwa społecznego. | Zdrowie / Bezpieczeństwo |
| **Wydatki publiczne jako \% PKB** | Łączne wydatki rządowe w stosunku do PKB. Miernik roli państwa w gospodarce. | Finanse Publ. |
| **Gin dochód** | Wskaźnik nierówności Giniego, mierzony na dochodach (0 = idealna równość). | Nierówności |
| **Odsetek ubogich (dochód <50% mediany)** | Procent osób zagrożonych ubóstwem relatywnym. | Nierówności |
| **PKB na godzinę pracy** | Wskaźnik efektywności i **wydajności pracy** w gospodarce. | Ekonomia |
| **Śmierci drogowe na 100 k** | Liczba śmiertelnych wypadków drogowych. | Bezpieczeństwo |
| **Realne ceny mieszkań** | Zmiana cen nieruchomości skorygowana o inflację (indeks). | Ekonomia |
| **Wiek emerytalny** | Wiek emerytalny dla kobiet oraz mężczyzn. | Rynek Pracy |
*W aplikacji dane są normalizowane i skalowane, aby nadać im równe znaczenie przed zastosowaniem wag użytkownika.*
