# **Task 1**
## **Subtask 1**
9 punktów 🤸
## **Subtask 3**
<p align="justify">Cześć! Nazywam się Kasia i biorę udział w challenge portfolio, bo zdecydowałam wywrócić swoje życie do góry nogami i się przebranżowić. Wiem, że to proces, w którym poza samozaparciem jest potrzebna duża dawka wsparcia. Dlatego, ogromnym atutem tego wyzwania jest dla mnie mentoring, a także możliwość poznania innych kursantek. Poza tym szukałam takiego kursu, który będzie umożliwiał mi nie tylko zdobycie niezbędnej wiedzy, ale zrobienie tego w przyjaznych warunkach. Po obejrzeniu webinaru byłam już pewna, że czeka tu na mnie ogromna fala siostrzeństwa i dobrej zabawy, a nie tylko uczenia się na pamięć pustych frazesów. Poza tym bardzo przekanało mnie to, że wyzwanie jest nastawione na praktykę, a ja uwielbiam uczyć się właśnie przez doświadczenie. Moim celem jest zrobienie wszystkich zadań w terminie (zobaczymy, czy się uda;)), zdobycie niezbędnej wiedzy oraz poznanie ludzi, z którymi będziemy mogli się wspierać nie tylko w trakcie kursu, ale przede wszystkim na naszej nowej zawodowej drodze życia! 🍾</p>

**Kasia**
## **Subtask 4**
- Scouts Panel to aplikacja do analizowania informacji na temat młodych talentów piłki nożnej oraz ich wyników w rozgrywkach.
- Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)
- Funkcjonalności w aplikacji to 
* logowanie, wylogowywanie, pokazywanie ostatnich aktywności w aplikacji, przeglądanie listy graczy, dodawanie nowych graczy, edycja danych dodanych graczy, 
- Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?
- Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).
- Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)
1. Na głównej stronie nie ma opcji dodawania nowego użytkownika. Istnieje tylko opcja zalogowania. Do weryfikacja czy to zamierzone.
2. Na stronie logowania w języku polskim, nie jest przetłumaczony nagłówek "Scouts Panel". 
3. Na głównej stronie w kafelku Scouts Panel - przycisk "Dev Team Contact" nie jest przetłumaczony na język polski.
4. Na głównej stronie w zakładce "Aktywnosć" jest literówka, kafelek powinien mieć nagłówek "Aktywność".
5. Bardziej intuicyjne byłoby umieszczenie funkcji dodawania nowego gracza w zakładce "Gracze".
6. W formularzu dodawania gracza w polu "Główna Pozycja" przydałoby się rozwijane pole z propozycjami pozycji.
7. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się spację a nie prawidłowe dane.
8. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się po jednym znaku, a nie dane w prawidłowym formacie.
9. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się znaki specjalne, np. "&", a nie prawidłowe dane.
10. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się cyfry, np. "1", a nie dane w prawidłowym formacie.
11. Formularz zapisuje do listy gracza, jeśli w polu "Główna pozycja" wpiszę się cyfry, np. "1", a nie dane w prawidłowym formacie.
12. Formularz zapisuje do listy gracza, jeśli w polu "Data Urodzenia" wpiszę niemożliwą datę, czyli datę z przyszłości, np. 20.02.2023 lub z bardzo dalekiej przeszłości, np. 02.02.0001, brak ogranicznika daty.
13. Formularz zapisuje do listy gracza, nawet jeśli wpiszemy identyczne dane, jak poprzedniego gracza.
14. Formularz zapisuje niemożliwe dane w polu "Waga" i "Wiek", istnieje możliwość dodania minusowych wartości.
15. Formularz zapisuje niemożliwe dane w polu "Telefon", istnieje możliwość dodania znaków specjalnych, np. &, liter, np. a i spacji.
16. Po wpisaniu do formularza w polu "E-mail" maila w nieprawidłowym formacie (bez "@") wyskakuje komunikat "Nie udało się dodać gracza.", ale pole e-mail nie podkreśla się na czerwono, więc nie wiadomo czego dokładnie dotyczy błąd.
17. 16. Po wpisaniu do formularza w polu "DODAJ LINK Z YOUTUBE" danych bez formatu strony internetowej formularz zapisuje błędne dane.
18. Przycisk "CLEAR" pod formularzem edycji gracza nie działa zgodnie z logicznym opisem, po naciśnięciu dane wracają do wersji przed edycją.
19. Przyciski "SUBMIT" i "CLEAR" pod formularzem dodawania gracza powinny być przetłumaczone na język polski.
20. Brak możliwości usunięcia gracza z listy graczy.
21. Pod formularzem dodawania gracza brak przycisku "NIE ZAPISUJ ZMIAN".
22. Po zapisaniu danych gracza strona nie odsyła do zakładki "Gracze" tylko przekierowuje do strony edycji.
23. Dodawanie informacji o meczach i raportów doyczących zawodnika jest nieintuicyjne.
24. Funkcjonalność "Rozpocznij mecz" jest dla mnie nieintuicyjna. Nie ma opisu i nie wiem, jak działa to rozgrywanie meczu. Czy tu się zapisuje rozegrane mecze w formie graficznej czy hipotetyczne? Do tego nie ma opisów nad przyciskami, więc nei wiem czego dotyczą. Nie rozumiem jak działają te funkcjonalności po wciśnięciu przycisku "Play" , nie umiem rozgryść tego bez opisu.
25. Nie mogę wygenerować raportu z meczu bez wpisania danych gracza w polu "Województwo" chociaż w formularzu dodawania gracza nie ma tam gwiazdki. Komunikat: "Brakujące dane gracza. Pole "Województwo" jest wymagane do stworzenia raportu."
26. Przy otwarciu strony z edycją raportu meczowego przycisk "SAVE" rusza się po ekranie razem z przewijaniem strony w dół, często zasłaniając tekst.
27. Przycisk "SAVE" na stronie edycji raportu meczowego nie ejst przetłumaczony na język polski.
28. Strona raport meczowy nie wyświetla się na całym ekranie, żeby zobaczyć pełny raport trzeba przewinąć stronę w prawy bok.
29. w opisach pomocniczych pod nagłówkami w raportach meczowych licznie braki znaków inteprpunkcyjnych.
30. Układ strony głównej jest nielogiczny, dłuższą chwilę zajmuje znalezienie poszczególnych fuunkcjonalności.
31. Wywołanie edycji gracza już istniejącego na liście Gracze nie jest intuicyjna. Po najechaniu na konkretnego gracza nie pojawia się informacja o edycji ani wybrany gracz się nie podświetla. Dopiero naciśnięcie (bez żadnej podpowiedzi) przekierowuje nas do edycji danych gracza.
32. Po wejściu w Devtoolsy pojawia się komunikat - błąd 404 - GEThttps://scouts-test.futbolkolektyw.pl/pl/favicon.ico
33. Strona "Mecze" nie jest responsywna.
34. Strona "Raporty" nie jest responsywna.
35. Strona z edycją raportów nie jest responsywna.
36. Strona z funkcją "Rozpocznij mecz" nie jest responsywna.
37. Na stronie z fucnkją "Rozpocznij mecz" istnieje możliwość dodania nieskończonej ilości połówek, a w meczu mogą być maksymlanie 4 połowy (w przypadku dogrywki).
38. Opisy funkcji na stronie "Gracze" nie zostały przetłumaczone na język polski, tj. Download CSV, Print, View Columns, Filter Table.
39. Na stronie "Gracze" napis w wyszukiwarce nie został przetłumaczony na język polski, tj. Search.
40. Jeśli nie zapiszemy meczu tylko opuścimy stronę, na głównej stronie pojawi się kafelek z tytułem "Niezapisany mecz" z przyciskiem "Wróc do raportu". Po kliknięciu w przycisk nic się nie dzieje, a w Devtools wyskakuje komunikat: Uncaught (in promise) Error: The provided `as` value (/pl/players/6026b48956c79737b3f3c624/reports/start) is incompatible with the `href` value (/players/[id]/reports/start). Read more: https://err.sh/vercel/next.js/incompatible-href-as

PS. Podczas testowania nie zapomnij z korzystania z poznanych dzisiaj DEVTOOLSÓW
