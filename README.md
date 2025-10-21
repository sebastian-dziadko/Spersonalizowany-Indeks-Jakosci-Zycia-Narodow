# Spersonalizowany Indeks Jakości Życia Narodów
Aplikacja w Pythonie, która pozwala użytkownikowi na spersonalizowane obliczanie Indeksu Jakości Życia dla krajów OECD. Użytkownik decyduje o znaczeniu (wadze) każdego z kilkunastu wskaźników, a aplikacja dynamicznie przelicza ranking.

Tradycyjne indeksy jakości życia (np. Human Development Index - HDI) wykorzystują z góry ustalone wagi. Ta aplikacja daje pełną kontrolę użytkownikowi. Pozwala ona odpowiedzieć na pytanie: "Jak wyglądałby ranking krajów, gdyby to moje priorytety (np. długość życia i niskie nierówności) były najważniejsze?".

Kluczowe Funkcje ✨
Personalizacja Wag: Użytkownik może ustawiać wagi (od 0 do 100) dla każdego z 20 wskaźników za pomocą interaktywnych suwaków.

Dynamiczne Przeliczanie: Ranking krajów aktualizuje się natychmiast po zmianie wagi dowolnego czynnika.

Wizualizacja: Prezentacja rankingu na czytelnym wykresie słupkowym oraz w tabeli dla TOP 10.

Szeroki Zakres Wskaźników: Analiza opiera się na danych z 20 różnych kategorii, obejmujących aspekty ekonomiczne, społeczne, zdrowotne i środowiskowe (patrz lista poniżej).

Lista wskaźników:
Wskaźnik (w aplikacji),Pełna Nazwa / Definicja,Jednostka / Miernik,Kategoria
Pkb per capita,Produkt Krajowy Brutto na mieszkańca.,"Miernik bogactwa i wielkości gospodarki, skorygowany o liczbę ludności.",Ekonomia
Konsumpcja,Wydatki konsumpcyjne gospodarstw domowych.,Mierzy siłę nabywczą i ogólny dobrobyt materialny w kraju.,Ekonomia
Długość życia kobiet,Oczekiwana długość życia w chwili urodzenia dla kobiet.,Miernik jakości systemu opieki zdrowotnej i warunków życia.,Zdrowie
Długość życia mężczyzn,Oczekiwana długość życia w chwili urodzenia dla mężczyzn.,"Analogicznie jak wyżej, ale dla populacji mężczyzn.",Zdrowie
Stopa bezrobocia,"Procent siły roboczej, która aktywnie szuka pracy, ale jej nie ma.",Wskaźnik stabilności i efektywności rynku pracy.,Rynek Pracy
Średnia roczna płaca,Średnia wynagrodzeń w kraju w skali roku.,"Miernik dochodów z pracy, odzwierciedlający standard życia.",Ekonomia
Decyl 9/1 zarobki,Stosunek zarobków 10% najlepiej zarabiających do 10% najmniej zarabiających.,Miernik nierówności w zarobkach. Wyższa wartość = większa nierówność.,Nierówności
Decyl 9/1 dochód,Stosunek dochodów 10% najbogatszych do 10% najbiedniejszych.,Szerszy miernik nierówności (uwzględnia transfery socjalne).,Nierówności
Liczba godzin przepracowanych/pracownika,Średnia liczba godzin przepracowanych rocznie przez pracownika.,Wskaźnik równowagi między życiem zawodowym a prywatnym (Work-Life Balance).,Rynek Pracy
Liczba samobójstw na 100 tys. mieszkańców,Wskaźnik umieralności z powodu samobójstw.,Wskaźnik zdrowia psychicznego i społecznego.,Zdrowie / Bezpieczeństwo
Wydatki publiczne jako % PKB,Łączne wydatki rządu centralnego i lokalnych w stosunku do PKB.,"Miernik roli państwa w gospodarce (np. na edukację, opiekę zdrowotną).",Finanse Publ.
Gin dochód,"Wskaźnik nierówności Giniego, mierzony na dochodach.",Klasyczny miernik nierówności. Wartość bliższa 0 = większa równość.,Nierówności
Odsetek ubogich (dochód <50% mediany),"Procent osób, których dochód jest niższy niż 50% mediany dochodu.",Wskaźnik ubóstwa relatywnego (zagrożenie ubóstwem).,Nierówności
PKB na godzinę pracy ceny stałe ppp,Wskaźnik efektywności wykorzystania pracy w gospodarce.,Miernik wydajności pracy (produktywności).,Ekonomia
Śmierci drogowe na 100 k,Liczba śmiertelnych wypadków drogowych na 100 000 mieszkańców.,Wskaźnik bezpieczeństwa publicznego i jakości infrastruktury.,Bezpieczeństwo
Realne ceny mieszkań (2015=100),Zmiana cen nieruchomości mieszkalnych skorygowana o inflację (indeks).,Wskaźnik stabilności rynku nieruchomości i dostępności mieszkań.,Ekonomia
