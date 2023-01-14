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
- Aplikacja nie jest intuicyjna. Miałam problem ze znalezeniem wielu funckjonalności. Niektóre funkcje znalazłam dopiero za 3-4 przeklikiwaniem strony. Niektórych funkcji nie rozumiem nadal. Wielką zagadką jest dla mnie funkcja rozgrywania meczy, próbowałam już kilka razy i dalej w mojej głowie pojawia się wielki pytajnik, gdy próbuję rozegrać mecz. Dość dużo czasu zajęło mi znalezienie funkcji edycji danych gracza oraz znalezienie strony z meczami i raportami. Bardzo brakuje mi przycisku "Dodaj nowego gracza" na stronie z listą graczy. Mój największy zarzut to chyba strona główna aplikacji. Po zalogowaniu się nie miałam pojęcia, co w ogóle mam kliknąć i co robić dalej. Musiałam patrzeć dłuższą chwilę na stronę główną, żeby rozeznać się z możliwościami, jakie daje aplikacja.
- Błędy w aplikacji:
  * STRONA LOGOWANIA
    * Brak opcji rejestracji nowego użytkownika. Do weryfikacji czy to błąd.
    * Nagłówek "Scouts Panel" nie jest przetłumaczony na język polski. 
  * STRONA GŁÓWNA
    * Na granatowym pasku znajdującym się na górze strony - teskt nagłówka strony "Scouts Panel" nie jest przetłumaczony na język polski.
    * W kafelku z tytułem "Scouts Panel" - teskt przycisku "Dev Team Contact" nie jest przetłumaczony na język polski.
    * W nagłówku kafelka "Aktywnosć" jest literówka, kafelek powinien mieć nagłówek "Aktywność".
  * DODAJ GRACZA
    * Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone spacje.
    * Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone pojedyncze znaki, np. A, brak minimalnej ilości znaków.
    * Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone znaki specjalne, np. "&".
    * Formularz zapisuje do listy gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone cyfry, np. 1.
    * Formularz zapisuje do listy gracza, jeśli w polu "Główna pozycja" zostaną wprowadzone cyfry, np. 1.
    * Formularz zapisuje do listy gracza, jeśli w polu "Data Urodzenia" zostanie wprowadzona data z przyszłości, np. 20.02.2023 lub z bardzo dalekiej przeszłości, np. 02.02.0001, brak ogranicznika daty.
    * Formularz zapisuje do listy gracza, jeśli zostaną wprowadzone identyczne dane, jak poprzedniego gracza.
    * Formularz zapisuje do listy gracza, jeśli w polach "Waga" i "Wiek" zostaną wprowadzone minusowe wartości, np. -10.
    * Formularz zapisuje do listy gracza, jeśli w polu "Telefon" zostaną wprowadzone znaki specjalne, np. &, litery, np. a i spacje.
    * Formularz zapisuje do listy gracza, jeśli w polu "Telefon" zostanie wprowadzony jeden znak albo więcej niż dziewięć, brak ogranicznika znaków.
    * Po wprowadzeniu do formularza w polu "E-mail" adresu e-mail w nieprawidłowym formacie (bez "@") wyskakuje komunikat "Nie udało się dodać gracza.", ale pole e-mail nie podkreśla się na czerwono. Brak czytelnego komunikatu czego dotyczy błąd zapisu formularza.
    * Formularz zapisuje do listy gracza, jeśli w polu "Główna pozaycja" zostaną wprowadzone znaki specjalne, np. &, litery, np. a i spacje. W polu "Główna Pozycja" powinno znajdować się rozwijane pole ze wszystkimi możliwymi pozycjami na boisku.
    * Formularz zapisuje do listy gracza, jeśli w polu "DODAJ LINK Z YOUTUBE" zostaną wprowadzone dane w innym formacie niż adres internetowy. Dane powinny być wprowadzane wg wzoru: https://wwww.XXX.XXX
    * Treść przycisku "SUBMIT" nie jest przetłumaczona na język polski.
    * Treść przycisku "CLEAR" nie jest przetłumaczona na język polski.
    * Po zapisaniu danych gracza, strona przekierowuje do strony edycji. Strona powinna odesłać użytkownika do strony "Gracze".
  * EDYCJA GRACZA
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone spacje.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone pojedyncze znaki, np. A, brak minimalnej ilości znaków.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone znaki specjalne, np. "&".
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Imię" i "Nazwisko" zostaną wprowadzone cyfry, np. 1.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Główna pozycja" zostaną wprowadzone cyfry, np. 1.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Data Urodzenia" zostanie wprowadzona data z przyszłości, np. 20.02.2023 lub z bardzo dalekiej przeszłości, np. 02.02.0001, brak ogranicznika daty.
    * Formularz zapisuje edycję danych gracza, jeśli zostaną wprowadzone identyczne dane, jak poprzedniego gracza.
    * Formularz zapisuje edycję danych gracza, jeśli w polach "Waga" i "Wiek" zostaną wprowadzone minusowe wartości, np. -10.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Telefon" zostaną wprowadzone znaki specjalne, np. &, litery, np. a i spacje.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Telefon" zostanie wprowadzony jeden znak albo więcej niż dziewięć, brak ogranicznika znaków.
    * Po wprowadzeniu do formularza w polu "E-mail" adresu e-mail w nieprawidłowym formacie (bez "@") wyskakuje komunikat "Nie udało się dodać gracza.", ale pole e-mail nie podkreśla się na czerwono. Brak czytelnego komunikatu czego dotyczy błąd zapisu formularza.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "Główna pozaycja" zostaną wprowadzone znaki specjalne, np. &, litery, np. a i spacje. W polu "Główna Pozycja" powinno znajdować się rozwijane pole ze wszystkimi możliwymi pozycjami na boisku.
    * Formularz zapisuje edycję danych gracza, jeśli w polu "DODAJ LINK Z YOUTUBE" zostaną wprowadzone dane w innym formacie niż adres internetowy. Dane powinny być wprowadzane wg wzoru: https://wwww.XXX.XXX
    * Po naciśnięciu przycisku "CLEAR" dane wracają do wersji przed edycją, nie są wymazywane całkowicie. Do weryfikacji czy to błąd.
    * Treść przycisku "SUBMIT" nie jest przetłumaczona na język polski.
    * Treść przycisku "CLEAR" nie jest przetłumaczona na język polski.
    * Brak przycisku odpowiadającego za funkcję zapisywania bez zmian.
    * Po edycji danych gracza, pozostajemy na stronie edycji gracza. Strona powinna odesłać użytkownika do strony "Gracze".
  * GRACZE
    * Brak możliwości usunięcia gracza z listy graczy.
    * Opisy funkcji tabeli, tj. Download CSV, Print, View Columns, Filter Table nie są przetłumaczone na język polski.

  
  * Dodawanie informacji o meczach i raportów doyczących zawodnika jest nieintuicyjne.
  * Funkcjonalność "Rozpocznij mecz" jest dla mnie nieintuicyjna. Nie ma opisu i nie wiem, jak działa to rozgrywanie meczu. Czy tu się zapisuje rozegrane mecze w formie graficznej czy hipotetyczne? Do tego nie ma opisów nad przyciskami, więc nei wiem czego dotyczą. Nie rozumiem jak działają te funkcjonalności po wciśnięciu przycisku "Play" , nie umiem rozgryść tego bez opisu.
  * Nie mogę wygenerować raportu z meczu bez wpisania danych gracza w polu "Województwo" chociaż w formularzu dodawania gracza nie ma tam gwiazdki. Komunikat: "Brakujące dane gracza. Pole "Województwo" jest wymagane do stworzenia raportu."
  * Przy otwarciu strony z edycją raportu meczowego przycisk "SAVE" rusza się po ekranie razem z przewijaniem strony w dół, często zasłaniając tekst.
  * Przycisk "SAVE" na stronie edycji raportu meczowego nie ejst przetłumaczony na język polski.
  * Strona raport meczowy nie wyświetla się na całym ekranie, żeby zobaczyć pełny raport trzeba przewinąć stronę w prawy bok.
  * w opisach pomocniczych pod nagłówkami w raportach meczowych licznie braki znaków inteprpunkcyjnych.
  * Po wejściu w Devtoolsy pojawia się komunikat - błąd 404 - GEThttps://scouts-test.futbolkolektyw.pl/pl/favicon.ico
  * Strona "Mecze" nie jest responsywna.
  * Strona "Raporty" nie jest responsywna.
  * Strona z edycją raportów nie jest responsywna.
  * Strona z funkcją "Rozpocznij mecz" nie jest responsywna.
  * Na stronie z fucnkją "Rozpocznij mecz" istnieje możliwość dodania nieskończonej ilości połówek, a w meczu mogą być maksymlanie 4 połowy (w przypadku dogrywki).
  * 
  * Na stronie "Gracze" napis w wyszukiwarce nie został przetłumaczony na język polski, tj. Search.
  * Jeśli nie zapiszemy meczu tylko opuścimy stronę, na głównej stronie pojawi się kafelek z tytułem "Niezapisany mecz" z przyciskiem "Wróc do raportu". Po kliknięciu w przycisk nic się nie dzieje, a w Devtools wyskakuje komunikat: Uncaught (in promise) Error: The provided `as` value (/pl/players/6026b48956c79737b3f3c624/reports/start) is incompatible with the `href` value (/players/[id]/reports/start). Read more: https://err.sh/vercel/next.js/incompatible-href-as
  * brak zakładki kontakt.
  * brak przetłumaczenia na polski przycisku "DEV TEAM CONTACT", który przekierowuje do kanału na Slacku.
  * Strona mecze nie mieści się w całym oknie przeglądarki.
  * Pod edycją meczu jest kafelek z nagłówkiem "Lista zdarzeń", podania są opisywane w kolumnie z nagłówkiem "Meta dane". W tych kolumnach opisy kolejnych kroków są podane w niewłaściwym formacie, np. "meta._id, meta.createdAt, meta.updatedAt, meta.match, Głową, Z prowadzenia, W poprzek" lub 	"meta._id, meta.createdAt, meta.updatedAt, meta.match, Faulowany".
  * Poza zapisaniu edycji meczu, nie jesteśmy przekierowywani do strony z listą meczów, tylko zostajemy na stronie edycji.
  * W Filtrach tabeli graczy nie jest przetłumaczony Age and Rate na język polski.
