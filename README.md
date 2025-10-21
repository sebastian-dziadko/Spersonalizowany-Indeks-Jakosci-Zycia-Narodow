# Spersonalizowany Indeks Jakości Życia Narodów
Aplikacja w Pythonie, która pozwala użytkownikowi na spersonalizowane obliczanie Indeksu Jakości Życia dla krajów OECD. Użytkownik decyduje o znaczeniu (wadze) każdego z kilkunastu wskaźników, a aplikacja dynamicznie przelicza ranking.

Tradycyjne indeksy jakości życia (np. Human Development Index - HDI) wykorzystują z góry ustalone wagi. Ta aplikacja daje pełną kontrolę użytkownikowi. Pozwala ona odpowiedzieć na pytanie: "Jak wyglądałby ranking krajów, gdyby to moje priorytety (np. długość życia i niskie nierówności) były najważniejsze?".
### Kluczowe Funkcje

* **Personalizacja Wag:** Użytkownik może ustawiać wagi  dla każdego z 20 wskaźników za pomocą interaktywnych suwaków.
* **Dynamiczne Przeliczanie:** Ranking krajów aktualizuje się natychmiast po zmianie wagi dowolnego czynnika.
* **Wizualizacja:** Prezentacja rankingu na czytelnym wykresie słupkowym oraz w tabeli.
* **Szeroki Zakres Wskaźników:** Analiza opiera się na danych z 20 różnych kategorii, obejmujących aspekty ekonomiczne, społeczne, zdrowotne i środowiskowe (patrz lista poniżej).
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
| **Decyl 9/1 i 9/5 zarobki/dochód** | Stosunek dochodów (lub zarobków) 10% najbogatszych do 10% najbiedniejszych. | Nierówności |
| **Liczba godzin przepracowanych/pracownika** | Średnia liczba godzin przepracowanych rocznie. Wskaźnik Work-Life Balance. | Rynek Pracy |
| **Liczba samobójstw na 100 tys.** | Wskaźnik zdrowia psychicznego i bezpieczeństwa społecznego. | Zdrowie / Bezpieczeństwo |
| **Wydatki publiczne jako \% PKB** | Łączne wydatki rządowe w stosunku do PKB. Miernik roli państwa w gospodarce. | Finanse Publ. |
| **Gin dochód** | Wskaźnik nierówności Giniego, mierzony na dochodach (0 = idealna równość). | Nierówności |
| **Odsetek ubogich (dochód <50% mediany)** | Procent osób zagrożonych ubóstwem relatywnym. | Nierówności |
| **PKB na godzinę pracy** | Wskaźnik efektywności i **wydajności pracy** w gospodarce. | Ekonomia |
| **Śmierci drogowe na 100 k** | Liczba śmiertelnych wypadków drogowych. | Bezpieczeństwo |
| **Realne ceny mieszkań** | Zmiana cen nieruchomości skorygowana o inflację (indeks). | Ekonomia |
| **Wiek emerytalny** | Wiek emerytalny dla kobiet oraz mężczyzn. | Rynek Pracy |

# Uruchamianie Aplikacji   
Aplikacja jest w pełni przenośna, ponieważ plik danych OECD.xlsx jest dołączony do projektu. Wystarczy zainstalować biblioteki.

**1. Przygotowanie Plików i Instalacja**  
Wykonaj te kroki, zanim zaczniesz uruchamiać kod w terminalu.

Pobierz Projekt: Pobierz całe repozytorium (np. jako plik ZIP) i rozpakuj je w łatwo dostępnym miejscu.

Napraw Nazwę Pliku: Znajdź plik Kod i zmień jego nazwę na Kod.py. Jest to konieczne, aby Python rozpoznał go jako skrypt.

**2. Instalacja Wymaganych Bibliotek**  
Otwórz terminal (Wiersz Poleceń/PowerShell), aby zainstalować pakiety potrzebne do działania aplikacji.

Przejdź do Folderu: Użyj komendy cd (Change Directory), aby wejść do rozpakowanego folderu projektu (tam, gdzie znajduje się plik Kod.py):


PRZYKŁAD: Zastąp ścieżkę swoją własną  
cd /sciezka/do/folderu/z/projektem  
**Zainstaluj pakiety:**  
pip install pandas numpy matplotlib openpyxl  

**3. Uruchomienie Aplikacji**   
Będąc w terminalu w folderze projektu, wpisz:
python Kod.py  
Aplikacja z interfejsem graficznym (GUI) powinna się uruchomić. Możesz teraz dostosowywać wagi wskaźników jakości życia.

## Licencja##

Licencja MIT (MIT License)

Copyright (c) 2025 Sebastian Dziadko

Niniejszym udziela się nieodpłatnie każdej osobie, która uzyska kopię tego oprogramowania i związanej z nim dokumentacji (dalej "Oprogramowanie"), prawo do korzystania z Oprogramowania bez żadnych ograniczeń, w tym między innymi prawo do używania, kopiowania, modyfikowania, łączenia, publikowania, rozpowszechniania, udzielania sublicencji i/lub sprzedaży kopii Oprogramowania, z zastrzeżeniem następujących warunków:

Powyższa informacja o prawach autorskich i niniejsze zezwolenie muszą być zawarte we wszystkich kopiach lub istotnych częściach Oprogramowania.

OPROGRAMOWANIE JEST DOSTARCZANE "TAKIE, JAKIE JEST", BEZ JAKIEJKOLWIEK GWARANCJI, WYRAŹNEJ LUB DOROZUMIANEJ, W TYM MIĘDZY INNYMI GWARANCJI PRZYDATNOŚCI HANDLOWEJ, PRZYDATNOŚCI DO OKREŚLONEGO CELU I NIENARUSZALNOŚCI. W ŻADNYM WYPADKU AUTORZY LUB WŁAŚCICIELE PRAW AUTORSKICH NIE PONOSZĄ ODPOWIEDZIALNOŚCI ZA ŻADNE ROSZCZENIA, SZKODY LUB INNE ZOBOWIĄZANIA WYNIKAJĄCE Z UMOWY, CZYNÓW NIEDOZWOLONYCH LUB INNYCH DZIAŁAŃ, ZWIĄZANE Z OPROGRAMOWANIEM LUB KORZYSTANIEM Z OPROGRAMOWANIA LUB INNYMI TRANSAKCJAMI Z OPROGRAMOWANIEM.
