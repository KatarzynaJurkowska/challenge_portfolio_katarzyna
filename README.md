# challenge_portfolio_katarzyna
**TASK 1**


**_Subtask 1_**


Ilość punktów: 9/10


**_Subtask 3_**


Dlaczego zdecydowałam się na udział w challenge portfolio? 


* zdobycie pierwszego, niekomercyjnego doświadczenia - uczestniczyłam w licznych webinarach, najwyższy czas na praktykę ;)
* stworzenie własnego portfolio
* przebranżowienie się i znalezienie pracy w IT
* atrakcyjna cena kursu


**_Subtask 4_**


_1 - Na czym polega ta aplikacja? Do czego służy?_


Aplikacja pozwala zarządzać graczami, meczami oraz umożliwia tworzenie raportów.


_2 - Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmieniła?_


Aplikacja pozwala na dodawanie i edycję graczy, meczy i raportów (jest opcja "clear", ale nie działa więc nie wiem czy można usunąć cokolwiek). Jest również możliwość zapisywania danych do pliku csv oraz drukowania zestawień. Opcja rozpoczynania meczy, słabo jak dla mnie zrozumiała.


_3 - Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?_


Interfejs bardzo skromny. Strona główna niestandardowa pod kątem umieszczenia elementów: statyczna informacja w samym centrum (ilość graczy/meczy/raportów/akcji) - chce się od razu kliknąć a tu nic. Dziwne, że logo umieszczone gdzieś na boku, zamiast centralnie, a linki pomocnicze umieszczone w centrum, zamiast gdzieś na boku... Opcja dodawania gracza pod linkiem pomocniczym zamiast w "graczu". Nie widać też z poziomu strony głównej, znajdujących się po lewej stronie, meczy i raportów - pojawiają się dopiero po wybraniu gracza. Trochę dziwna koncepcja. Za to same formularze są ok - proste i czytelne. Raporty wręcz przeciwnie - dość rozbudowane (ale może po to, żeby nikomu nie chciało się ich czytać ;)).


_4 - Czy aplikacja jest intuicyjna?_


Jeśli chodzi o tworzenie i edycję to jest ok, pojawiają się małe obszary, nad którymi można się jeszcze zastanowić:


* Lupka w wyszukiwarce nie jest aktywna, wyłącznie enter powoduje zatwierdzenie wyszukiwanej frazy. Fajnie by było, gdyby można było wykorzystać ją do wyszukiwania i, gdyby wyniki wyszukiwania były wyświetlane już w trakcie wpisywania tekstu w wyszukiwarkę.
* Brak widocznej opcji sortowania rosnąco/malejąco - dopiero jak się kliknie w nagłówek pojawia się strzałka (mecze i raporty nie mają w ogóle opcji sortowania).
* Klikając w Mecze i Raporty po lewej stronie mamy opcję "dodaj", natomiast dla Graczy mamy tę funkcjonalność w innym miejscu.
* Fajnie by było, gdyby była opcja eksportu zestawień z graczami do innego formatu niż csv.
* Niewygodne jest przewijanie stron z graczami jeśli nie ma możliwości szybkiego przejścia do strony pierwszej, ostatniej lub wybrania samemu zakresu.
* Podobnie jest z wydrukiem/zapisywaniem do pliku - brak funkcji "zaznacz wszystko" lub "wskaż zakres".
* Nie do końca rozumiem cel stosowania pola "języki", jeśli już istnieje, to może powinno być to pole zasłownikowane?
* Nie do końca wiem na czym ma polegać mecz - ikonki nie są podpisane i są nieaktywne - jedynie można wysłać raport, reszta nie reaguje.


_5 - Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem?_


Kilka małych niedoskonałości poniżej:

1. Gdy mamy 1 filtr w wyszukiwarce głównej (np. „kat”) i poprawnie wyfiltrowane wyniki, to dodanie kolejnego filtra (np. „Age”) powoduje, że poprzedni filtr nie jest już brany pod uwagę tzn. widzimy znacznie więcej wyników niż powinniśmy.
2. Gdy mamy 1 filtr w wyszukiwarce głównej (np. „lo”) i poprawnie wyfiltrowane wyniki (1-10 of 14), to przejście do kolejnej strony (11-20 of 713) powoduje, że poprzedni filtr nie jest już brany pod uwagę tzn. widzimy znacznie więcej wyników niż powinniśmy.
3. Dodano gracza, który się jeszcze nie urodził: 11.11.2022 (dzisiaj jest 31.10.2022)
4. Będąc w "raportach" klikam "dodaj raport" i przeskakuje mi na "dodaj mecz", a więc nie mam możliwości dodania raportu.
5. W opcji dodawania meczu dla gracza, system pozwala wpisać warość ujemną dla pola "zdobyte gole" oraz nierealną datę (05-05-0005)
6. W edycji gracza "waga" i "wzrost" mogą mieć wartość ujemną oraz dużą ilość znaków np 88888888888888888888888888888888888888.
7. Przy próbie zapisania błędnego e-maila w edycji gracza, wystepuje informacja: "Nie udało się zaktualizować gracza". Mógłby się pojawić powód, dla którego nie dało się zapisać zmiany lub przynajmniej mogłoby się podświetlić to pole, które nie dało się zmienić.
8. Województwo nie jest oznaczone jako pole obowiązkowe a system "krzyczy", że pole to jest wymagane do stworzenia raportu (i trzeba jeszcze raz zaktualizować dane gracza).
9. Zapisano niepoprawny link do youtube (kkkkkkkkkkkkkkkkkkkkkkkkkkkkkkk)
10. Na liście raportów brak informacji o numerze/nazwie raportu. Również nie można zmienić numeru/nazwy raportu podczas edycji raportu - efekt: dwa raporty o tym samym numerze a z innymi danymi "w środku".
11. Literówki na stronie głównej: 
>Aktywnosć


oraz


>zaaktualizowany


12. Nieistniejąca ikona:

![obraz](https://user-images.githubusercontent.com/116674154/199107790-e5e3dc8c-2e1f-421d-961c-e4d5762b84f7.png)


To chyba tyle na dziś :)

Pozdrawiam

Kaśka




