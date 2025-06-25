Sortownik Dwustronnych PDF
Proste narzędzie do automatycznego porządkowania stron skanów dwustronnych
Opis
Aplikacja Sortownik Dwustronnych PDF to proste, webowe narzędzie zaprojektowane, aby ułatwić porządkowanie stron zeskanowanych dokumentów dwustronnych, zwłaszcza gdy korzystasz ze skanera bez funkcji automatycznego dupleksu. Eliminuje potrzebę ręcznego sortowania stron po zeskanowaniu ich w dwóch oddzielnych przebiegach (np. najpierw wszystkie strony nieparzyste, a następnie wszystkie parzyste, często w odwróconej kolejności).

Funkcje
Aplikacja oferuje dwie intuicyjne metody sortowania, dostosowane do różnych scenariuszy skanowania:

Metoda A: Sortowanie z dwóch plików PDF
Działanie: Wgrywasz dwa oddzielne pliki PDF.

Plik 1: Powinien zawierać wszystkie strony nieparzyste zeskanowane w kolejności rosnącej (np. strona 1, 3, 5...).

Plik 2: Powinien zawierać wszystkie strony parzyste zeskanowane w kolejności malejącej (np. strona 26, 24, 22...).

Przetwarzanie: Aplikacja inteligentnie przeplata strony z obu plików, automatycznie tworząc jeden, prawidłowo posortowany dokument PDF (strona 1, 2, 3, 4...).

Wymagania: Liczba stron w obu plikach musi być taka sama (np. jeśli dokument ma 26 stron, oba pliki powinny mieć po 13 stron).

Metoda B: Sortowanie z jednego scalonego pliku PDF
Działanie: Wgrywasz jeden scalony plik PDF. Zakłada się, że ten plik został utworzony poprzez połączenie najpierw wszystkich stron nieparzystych (w kolejności rosnącej), a następnie wszystkich stron parzystych (w kolejności malejącej) w jeden dokument.

Przetwarzanie: Aplikacja dzieli plik na dwie równe części i dynamicznie przeplata strony, aby uzyskać prawidłową kolejność wszystkich stron.

Wymagania: Całkowita liczba stron w pliku musi być parzysta (ponieważ każda strona nieparzysta ma odpowiadającą jej stronę parzystą).

Jak używać
Aby skorzystać z aplikacji, wykonaj poniższe kroki:

Otwórz aplikację w przeglądarce internetowej (np. poprzez link do GitHub Pages).

Wybierz preferowaną metodę sortowania (Metoda A lub Metoda B), klikając w odpowiednią sekcję.

Wgraj swoje pliki PDF:

Dla Metody A: Przeciągnij i upuść plik na wyznaczone strefy "Przeciągnij i upuść plik PDF tutaj" lub użyj przycisków "Wybierz plik" dla "Pliku PDF 1" i "Pliku PDF 2".

Dla Metody B: Przeciągnij i upuść plik na wyznaczoną strefę lub użyj przycisku "Wybierz plik" dla "Jeden plik PDF".

Po wgraniu plików, kliknij przycisk "Sortuj dwa pliki PDF" (dla Metody A) lub "Sortuj jeden plik PDF" (dla Metody B).

Po zakończeniu przetwarzania (które odbywa się lokalnie w przeglądarce), pojawi się przycisk "Pobierz posortowany PDF". Kliknij go, aby zapisać uporządkowany dokument na swoim komputerze.

Technologia
Projekt został zbudowany przy użyciu standardowych technologii webowych, z naciskiem na wydajność i prywatność użytkownika:

HTML, CSS (Tailwind CSS), JavaScript: Podstawowe technologie front-endowe do struktury, stylizacji i logiki aplikacji.

pdf-lib: Kluczowa biblioteka JavaScript, która umożliwia manipulację plikami PDF bezpośrednio po stronie klienta (w przeglądarce). Oznacza to, że Twoje pliki PDF są przetwarzane lokalnie i nie są przesyłane na żaden serwer, co zapewnia pełną prywatność i bezpieczeństwo danych.

Autor
Stworzone przez RS PROJECTS.
