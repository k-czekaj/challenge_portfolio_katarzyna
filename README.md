# **Task 1**
## **Subtask 1**
9 punktów 🤸
## **Subtask 3**
<p align="justify">Cześć! Nazywam się Kasia i biorę udział w challenge portfolio, bo zdecydowałam wywrócić swoje życie do góry nogami i się przebranżowić. Wiem, że to proces, w którym poza samozaparciem jest potrzebna duża dawka wsparcia. Dlatego, ogromnym atutem tego wyzwania jest dla mnie mentoring, a także możliwość poznania innych kursantek. Poza tym szukałam takiego kursu, który będzie umożliwiał mi nie tylko zdobycie niezbędnej wiedzy, ale zrobienie tego w przyjaznych warunkach. Po obejrzeniu webinaru byłam już pewna, że czeka tu na mnie ogromna fala siostrzeństwa i dobrej zabawy, a nie tylko uczenia się na pamięć pustych frazesów. Poza tym bardzo przekanało mnie to, że wyzwanie jest nastawione na praktykę, a ja uwielbiam uczyć się właśnie przez doświadczenie. Moim celem jest zrobienie wszystkich zadań w terminie (zobaczymy, czy się uda;)), zdobycie niezbędnej wiedzy oraz poznanie ludzi, z którymi będziemy mogli się wspierać nie tylko w trakcie kursu, ale przede wszystkim na naszej nowej zawodowej drodze życia! 🍾</p>

**Kasia**
## **Subtask 4**
- Scouts Panel to aplikacja do analizowania informacji na temat młodych talentów piłki nożnej oraz ich wyników w rozgrywkach.
- Funkcjonalności w aplikacji to:
  * logowanie - służy do logowania się w aplikacji,
  * wylogowywanie - służy do wylogowywania się z aplikacji,
  * pokazywanie ostatnich aktywności w aplikacji - służy do pokazywania ostatnich dodanych graczy, raportów, meczy oraz ostatnich aktualizacji graczy, raportów, meczy. Umożliwia przeniesienie się za pomocą przycisków do tych aktywności.
  * pokazywanie ilości wszystkich graczy - licznik pokazujący sumę wszystkich graczy w aplikacji,
  * pokazywanie ilości wszystkich meczy - licznik pokazujący sumę wszystkich meczy w aplikacji,
  * pokazywanie ilości wszystkich raportów - licznik pokazujący sumę wszystkich raportów w aplikacji,
  * pokazywanie ilości wszystkich akcji - licznik pokazujący sumę wszystkich akcji w aplikacji,
  * przeglądanie listy graczy - pokazywanie tabeli ze wszystkimi graczami oraz ich dane,
  * dodawanie nowych graczy - umożliwia użytkownikowi dodanie nowego gracza do listy,
    * lokalizacja przycisku "DODAJ GRACZA" nie jest intuicyjna, przycisk przekierowujący na stronę z dodawaniem nowego gracza znajduje się na głównej stronie w kafelku z nagłówkiem "Linki pomocnicze", moja pierwsza myśl była taka, że dodawanie nowego gracza powinno znajdować się na liście graczy i tam najpierw szukałam;
  * wyszukiwanie graczy - pole do wpisywania danych szukanego gracza, w celu szybszego znalezienie go na liście graczy,
  * sortowanie danych graczy w poszczególnych kolumnach - sortowanie wartości w kolumnach alfabetycznie lub liczbowo,
    * napis SORT pojawia się dopiero po najechaniu na nagłówek którejś z kolumn; bardziej intuicyjne byłoby dodanie strzałki od razu przy każdym nagłówku, aktualnie strzałka pojawia się dopiero po kliknięciu na nagłówek kolumny;
  * filtrowanie tabeli z listą graczy - umożliwia filtrowanie danych w tabeli potakich danych jak: Imię, Nazwisko, Age, Pozycja, Klub, Rate;
  * wybór kolumn wyświetlanych w tabeli z listą graczy - umożliwia wybór tego, z których kolumn chcemy oglądać dane graczy;
  * drukowanie listy graczy - umożliwia wydrukowanie listy graczy,
  * ściaganie pliku CSV z listą graczy - umożliwia pobranie pliku z listą graczy w formacie CSV na swój komputer,
  * edycja danych dodanych graczy - umożliwia edytowanie danych znajdujących się na liście graczy,
    * sposób przeniesienia na stronę edycji zawodnika jest nieintuicyjny, po najechaniu na dane zawodnika nic się nie podświetla, nie pojawia się żaden napis sugerujący, że musimy kliknąć na gracza; bardziej intuicyjne byłoby dodanie ikony ołówka na końcu wiersza, tj. w przypadku listy meczy i raportów;
  * zmiana języka aplikacji na angielski - umożliwia zmianę języka aplikacji z polskiego na angielski,
  * przekierowywanie do wspólnego kanału komunikacji na Slacku - umożliwia znalezienie kanału komunikacji na Slacku,
    * lokalizacja przycisku kontaktowego oraz jego opis nie jest intuicyjny; pierwszą myślą było to, że po jego kliknięciu zostanę przekierowana do strony kontaktowej, formularza kontaktowego albo e-maila, bezpośrednie przekierowanie do Slacka trochę mnie zaskoczyło; wydaje mi się, że lepszym pomysłem byłoby stworzenie podstrony z tytułem "KONTAKT", gdzie byłyby opisane formy kontaktu;
  * przeglądanie listy meczy danego zawodnika - pokazywanie tabeli ze wszystkimi meczami rozegranymi przez danego gracza oraz dane o nich,
    * ścieżka dojścia do zakładki "MECZE" jest nieintuicyjna, musimy najpierw wejść w listę graczy -> kliknąć na konkretnego gracza -> zostajemy przekierowani do edycji danych -> na panelu po lewej stronie pokazuje się opcja kliknięcia na zakładkę "MECZE"; bardziej intuicyjne byłoby zlokalizowanie przycisku przekierowaującego do zakładki mecze pod danymi gracza;
  * dodawanie meczy rozegranych przez danego zawodnika - umożliwia użytkownikowi dodanie nowego meczu rozegranego przez danego zawodnika do listy meczy,
  * edycja meczy danego zawodnika - umożliwia edytowanie danych znajdujących się w meczu danego zawodnika,
  * przeglądanie listy raportów z meczy danego zawodnika - pokazywanie tabeli ze wszystkimi raportami z meczy danego gracza oraz dane o nich,
    * ścieżka dojścia do zakładki "RAPORTY" jest nieintuicyjna, musimy najpierw wejść w listę graczy -> kliknąć na konkretnego gracza -> zostajemy przekierowani do edycji danych -> na panelu po lewej stronie pokazuje się opcja kliknięcia na zakładkę "RAPORTY"; bardziej intuicyjne byłoby zlokalizowanie przycisku przekierowaującego do zakładki raporty pod danymi gracza;
  * dodawanie raportów - umożliwia użytkownikowi dodanie nowego raportu z rozegranego przez danego zawodnika meczu,
  * edycja raportów - umożliwia edytowanie danych znajdujących się w raportach,
  * rozgrywanie meczy w formie interaktywnej grafiki - umożliwia rozegranie meczu poprzez klikanie na grafikę boiska, pozwala na dodawanie zdarzeń meczowych, np. faul, strzały, podanie długie; pozwala na granie, pauzowanie, zmianę połówek, cofanie zdarzenia, eksport raportu z meczu i kasowanie meczu;
    * próbowałam analizować tę funkcjonalność kilka razy i dalej jej nie rozumiem, nie mam najmniejszego pojęcia jak poprawnie rozegrać mecz i po co; zdecydowanie brakuje jakieś krótkiej instrukcji dotyczącej obsługi tego narzędzia;
  * pokazywanie informacji o niezapisanym meczu - pokazywanie na głównej stronie kafelka z informacją o niezapisanym meczu,
    * nie rozumiem dlaczego ta funkcjonalność pojawia się na głównej stronie, bardziej intuicyjny byłby komunikat pokazujący się na ekranie przy próbie opuszczenia strony z rozgrywanym meczem.
- Interfejs aplikacji jest mało atrakcyjny, a przede wszystkim nie sugeruje na czym użytkownik ma skupić wzrok. Żaden wizualny element nie pomaga znaleźć funckjonalności, której w danym momencie szukamy. Strona główna powinna być wizytówką aplikacji, zachęcać użytkownika do dalszego korzystania, niestety tutaj strona główna wita nas chaosem wizualnym i nudą. Logo Platformy Skautingowej powinno być zlokalizowane w bardziej reprezentatywnym miejscu, a kafelek "Linki pomocnicze" lepiej, żeby znajdował się na dole strony niż w jej centralnej części. Strona wygląda bardziej jak strona w budowie niż finalny produkt.
- Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).
- Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)
26. Na głównej stronie nie ma opcji dodawania nowego użytkownika. Istnieje tylko opcja zalogowania. Do weryfikacja czy to zamierzone.
27. Na stronie logowania w języku polskim, nie jest przetłumaczony nagłówek "Scouts Panel". 
28. Na głównej stronie w kafelku Scouts Panel - przycisk "Dev Team Contact" nie jest przetłumaczony na język polski.
29. Na głównej stronie w zakładce "Aktywnosć" jest literówka, kafelek powinien mieć nagłówek "Aktywność".
30. Bardziej intuicyjne byłoby umieszczenie funkcji dodawania nowego gracza w zakładce "Gracze".
31. W formularzu dodawania gracza w polu "Główna Pozycja" przydałoby się rozwijane pole z propozycjami pozycji.
32. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się spację a nie prawidłowe dane.
33. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się po jednym znaku, a nie dane w prawidłowym formacie.
34. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się znaki specjalne, np. "&", a nie prawidłowe dane.
35. Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" wpiszę się cyfry, np. "1", a nie dane w prawidłowym formacie.
36. Formularz zapisuje do listy gracza, jeśli w polu "Główna pozycja" wpiszę się cyfry, np. "1", a nie dane w prawidłowym formacie.
37. Formularz zapisuje do listy gracza, jeśli w polu "Data Urodzenia" wpiszę niemożliwą datę, czyli datę z przyszłości, np. 20.02.2023 lub z bardzo dalekiej przeszłości, np. 02.02.0001, brak ogranicznika daty.
38. Formularz zapisuje do listy gracza, nawet jeśli wpiszemy identyczne dane, jak poprzedniego gracza.
39. Formularz zapisuje niemożliwe dane w polu "Waga" i "Wiek", istnieje możliwość dodania minusowych wartości.
40. Formularz zapisuje niemożliwe dane w polu "Telefon", istnieje możliwość dodania znaków specjalnych, np. &, liter, np. a i spacji.
41. Po wpisaniu do formularza w polu "E-mail" maila w nieprawidłowym formacie (bez "@") wyskakuje komunikat "Nie udało się dodać gracza.", ale pole e-mail nie podkreśla się na czerwono, więc nie wiadomo czego dokładnie dotyczy błąd.
42. 16. Po wpisaniu do formularza w polu "DODAJ LINK Z YOUTUBE" danych bez formatu strony internetowej formularz zapisuje błędne dane.
43. Przycisk "CLEAR" pod formularzem edycji gracza nie działa zgodnie z logicznym opisem, po naciśnięciu dane wracają do wersji przed edycją.
44. Przyciski "SUBMIT" i "CLEAR" pod formularzem dodawania gracza powinny być przetłumaczone na język polski.
45. Brak możliwości usunięcia gracza z listy graczy.
46. Pod formularzem dodawania gracza brak przycisku "NIE ZAPISUJ ZMIAN".
47. Po zapisaniu danych gracza strona nie odsyła do zakładki "Gracze" tylko przekierowuje do strony edycji.
48. Dodawanie informacji o meczach i raportów doyczących zawodnika jest nieintuicyjne.
49. Funkcjonalność "Rozpocznij mecz" jest dla mnie nieintuicyjna. Nie ma opisu i nie wiem, jak działa to rozgrywanie meczu. Czy tu się zapisuje rozegrane mecze w formie graficznej czy hipotetyczne? Do tego nie ma opisów nad przyciskami, więc nei wiem czego dotyczą. Nie rozumiem jak działają te funkcjonalności po wciśnięciu przycisku "Play" , nie umiem rozgryść tego bez opisu.
50. Nie mogę wygenerować raportu z meczu bez wpisania danych gracza w polu "Województwo" chociaż w formularzu dodawania gracza nie ma tam gwiazdki. Komunikat: "Brakujące dane gracza. Pole "Województwo" jest wymagane do stworzenia raportu."
51. Przy otwarciu strony z edycją raportu meczowego przycisk "SAVE" rusza się po ekranie razem z przewijaniem strony w dół, często zasłaniając tekst.
52. Przycisk "SAVE" na stronie edycji raportu meczowego nie ejst przetłumaczony na język polski.
53. Strona raport meczowy nie wyświetla się na całym ekranie, żeby zobaczyć pełny raport trzeba przewinąć stronę w prawy bok.
54. w opisach pomocniczych pod nagłówkami w raportach meczowych licznie braki znaków inteprpunkcyjnych.
55. Układ strony głównej jest nielogiczny, dłuższą chwilę zajmuje znalezienie poszczególnych fuunkcjonalności.
56. Wywołanie edycji gracza już istniejącego na liście Gracze nie jest intuicyjna. Po najechaniu na konkretnego gracza nie pojawia się informacja o edycji ani wybrany gracz się nie podświetla. Dopiero naciśnięcie (bez żadnej podpowiedzi) przekierowuje nas do edycji danych gracza.
57. Po wejściu w Devtoolsy pojawia się komunikat - błąd 404 - GEThttps://scouts-test.futbolkolektyw.pl/pl/favicon.ico
58. Strona "Mecze" nie jest responsywna.
59. Strona "Raporty" nie jest responsywna.
60. Strona z edycją raportów nie jest responsywna.
61. Strona z funkcją "Rozpocznij mecz" nie jest responsywna.
62. Na stronie z fucnkją "Rozpocznij mecz" istnieje możliwość dodania nieskończonej ilości połówek, a w meczu mogą być maksymlanie 4 połowy (w przypadku dogrywki).
63. Opisy funkcji na stronie "Gracze" nie zostały przetłumaczone na język polski, tj. Download CSV, Print, View Columns, Filter Table.
64. Na stronie "Gracze" napis w wyszukiwarce nie został przetłumaczony na język polski, tj. Search.
65. Jeśli nie zapiszemy meczu tylko opuścimy stronę, na głównej stronie pojawi się kafelek z tytułem "Niezapisany mecz" z przyciskiem "Wróc do raportu". Po kliknięciu w przycisk nic się nie dzieje, a w Devtools wyskakuje komunikat: Uncaught (in promise) Error: The provided `as` value (/pl/players/6026b48956c79737b3f3c624/reports/start) is incompatible with the `href` value (/players/[id]/reports/start). Read more: https://err.sh/vercel/next.js/incompatible-href-as
66. brak zakładki kontakt.
67. brak przetłumaczenia na polski przycisku "DEV TEAM CONTACT", który przekierowuje do kanału na Slacku.
68. Strona mecze nie mieści się w całym oknie przeglądarki.
69. Pod edycją meczu jest kafelek z nagłówkiem "Lista zdarzeń", podania są opisywane w kolumnie z nagłówkiem "Meta dane". W tych kolumnach opisy kolejnych kroków są podane w niewłaściwym formacie, np. "meta._id, meta.createdAt, meta.updatedAt, meta.match, Głową, Z prowadzenia, W poprzek" lub 	"meta._id, meta.createdAt, meta.updatedAt, meta.match, Faulowany".
70. Poza zapisaniu edycji meczu, nie jesteśmy przekierowywani do strony z listą meczów, tylko zostajemy na stronie edycji.
71. W Filtrach tabeli graczy nie jest przetłumaczony Age and Rate na język polski.

PS. Podczas testowania nie zapomnij z korzystania z poznanych dzisiaj DEVTOOLSÓW
