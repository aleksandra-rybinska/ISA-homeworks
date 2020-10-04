# Prace domowe

To repozytorium zawiera zadania do zrealizowania w ramach pracy domowej.

## Zadanie 1

Celem tego zadania jest zbudowanie aplikacji, która będzie wyświetlała w 3 zakładkach 3 różne zbiory danych, pobierane asynchronicznie z serwera.

- Wykonaj fork tego repozytorium
- Na forku załóż gałąź `feature/homework-1` (na niej wykonasz commity poszczególnych części zadania)
- Część pierwsza:
  - załóż katalog `homework-1` i utwórz z w nim pliki `index.html`, `main.css` oraz `app.js`
  - wygeneruj szkielet w pliku HTML z użyciem Emmeta, a następnie podlinkuj w nim pliki CSS i JS
  - wykonaj commit zmian
- Część druga:
  - skorzystaj z https://www.mockaroo.com/ i wygeneruj 3 dowolne zbiory danych w formacie JSON - niech każdy z nich zawiera 20 elementów
  - zapisz te zbiory w katalogu `homework-1` w formie plików `.json`
  - w pliku `app.js` napisz skrypt, który pobierze pierwszy zbiór, korzystając z funkcji `fetch` i wyświetli go na ekranie w formie listy (wybierz samodzielnie atrybuty obiektów ze zbioru, które chcesz na liście wyświetlić)
  - wykonaj commit zmian
- Część trzecia:
  - do dokumentu dodaj nawigację, która składać się będzie z 3 zakładek, niech pierwsza zakładka będzie wyróżniona (w związku z tym, że jest aktywna); niech lista z poprzedniego zadania stanowi zawartość tej zakładki
  - wykonaj commit zmian
- Część czwarta:
  - spraw, żeby kliknięcia w zakładki aktywowały je (wyróżnienie ma znikać z aktualnie aktywnej zakładki i przenosić się na tę klikniętą)
  - wykonaj commit zmian
- Część piąta:
  - spraw, żeby w momencie kliknięcia zakładki rozpoczynąło się pobieranie pliku `.json` z kolekcją z nią związaną, a następnie niech kolekcja wyświetli się w formie listy jako zawartość zakładki
  - wykonaj commit zmian
- Część szósta:
  - spraw, żeby szybkie przełączanie się między zakładkami zatrzymywało pobieranie kolekcji, która jest w trakcie pobierania (unikniemy irytującego "mignięcia" zawartości z poprzednio aktywnej zakładki)
  - wykonaj commit zmian
- Część siódma:
  - wyświetl informację o tym, że trwa ładowanie kolekcji
  - wykonaj commit zmian
- Część dziewiąta:
  - opublikuj rozwiązanie w formie strony na Github Pages
  - upewnij się, że działa
  - dodaj link prowadzący do strony do sekcji "about" w Twoim repozytorium

Czas na realizację tego zadania: **2 tygodnie** (19 października 2020, godz. 9:00)

Powodzenia! :)