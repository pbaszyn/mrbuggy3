###Raport błędów dokumentacji
####*Sporządził Przemysław Baszyński*

**Id błędu :** 1
**Tytuł defektu :** “Błędna ilość aplikacji”
**Numer strony na której zlokalizowany jest błąd :** 6
**Akapit :** “Wymagane są cztery wersje aplikacji klienckiej: ”
**Opis defektu :** Na początku akapitu jest informacja o wymaganych czterech wersjach aplikacji, natomiast w opisie poniżej wymieniono jedynie trzy wersje.

**Id błędu :** 2
**Tytuł defektu :** “Literówka w słowie “stwierdzenie””
**Numer strony na której zlokalizowany jest błąd :** 6
**Akapit :** “Wymagane są cztery wersje aplikacji klienckiej:”
**Opis defektu :** W treści opisu wersji demonstracyjnej jest literówka / błąd odmiany. 
***Jest :*** “w celu uruchomienia i zapoznania się z aplikacją oraz stwierdzenie poprawności działania aplikacji na danej konfiguracji sprzętowej uczestnika”
***Powinno być :*** “w celu uruchomienia i zapoznania się z aplikacją oraz stwierdzenia poprawności działania aplikacji na danej konfiguracji sprzętowej uczestnika”

**Id błędu :** 3
***Tytuł defektu :*** “Niezgodna liczba zadań testowych w aplikacji demonstracyjnej”
**Numer strony na której zlokalizowany jest błąd :** 6 i 14
**Akapit :** strona 6 - “Wymagane są cztery wersje aplikacji klienckiej:”, strona 13 - “Opis zadań zamieszczonych w tej wersji:”
**Opis defektu :** W opisie wersji demonstracyjnej jest informacja o tym, że aplikacja powinna zawierać jedno zadanie testowe, opisane poniżej. W opisie zadań testowych w demonstracyjnej wersji aplikacji ( strona 14) znajdują się dwa zadania zamiast jednego.

**Id błędu :** 4
**Tytuł defektu :** “Brak opisu funkcjonalności importu pliku na serwer” 
**Numer strony na której zlokalizowany jest błąd :** 8
**Akapit :** strona 7 - “Dane z części klienckiej dostarczane są do części serwerowej w postaci pliku tekstowego:”
**Opis defektu :** W opisie na stronie 8 jest mowa o opisie eksportu i importu : “W przypadku braku połączenia sieciowego - za pomocą funkcji eksportu z części klienckiej i importu w części serwerowej. Opis tej funkcjonalności zostanie przedstawiony w dalszej części”
Na stronie 10 w opisie “Część kliencka” znajduje się opis eksportu danych do pliku binarnego. W dokumencie brakuje opisu funkcjonalności importu danych z pliku. Opis powinien znajdować się w sekcji “6.2 Część serwerowa“

**Id błędu :** 5
**Tytuł defektu :** “Literówka w słowie “zadanie””
**Numer strony na której zlokalizowany jest błąd :** 8
**Akapit :** “W aplikacji dostępnych ma być nie mniej niż 15 zadań (problemów).”
**Opis defektu :** 
***Jest :*** “W każdym zdaniu ma być dokładnie jeden defekt. Defekty te mogą należeć”
***Powinno być :*** “W każdym zadaniu ma być dokładnie jeden defekt. Defekty te mogą należeć”

**Id błędu :** 6
**Tytuł defektu :** Błąd w opisie pola “Czas”
**Numer strony na której zlokalizowany jest błąd :** 10
**Akapit :** “Okno aplikacji powinno dzielić się na dwie części - okno “Zadania” oraz ”
**Opis defektu :** W punkcie “Pole “Czas”” jest błąd w opisie formatu - z opisu ( gg:mm:ss ) formatu wynika, że pole powinno składać się z trzech elementów - godziny, minut, sekund, podczas gdy w dalszej części opisu pola pojawia się informacja o milisekundach.

**Id błędu :** 7
**Tytuł defektu :** Błąd w opisie przycisków nawigacyjnych
**Numer strony na której zlokalizowany jest błąd :** 10
**Akapit :** “Okno aplikacji powinno dzielić się na dwie części - okno “Zadania” oraz "
**Opis defektu :** W punkcie “Przyciski nawigacyjne” jest następująca informacja - “Przyciski nawigacyjne - “Następne” i “Poprzednie” umożliwiają przeniesienie się do odpowiednio bieżącego, następnego i poprzedniego zadania.”. Prawidłowy opis to “Przyciski nawigacyjne - “Następne” i “Poprzednie” umożliwiają przeniesienie się do odpowiednio następnego i poprzedniego zadania.”

**Id błędu :** 8
**Tytuł defektu :** Błąd w opisie przycisku “Zaraportuj defekt” 
**Numer strony na której zlokalizowany jest błąd :** 10
**Akapit :** “Okno aplikacji powinno dzielić się na dwie części - okno “Zadania” oraz "
**Opis defektu :** W punkcie “Przycisk “Zaraportuj defekt”” jest błąd w opisie - 
***Jest :*** “- pozwala na zaraportowanie defektu aktualnie wyświetlanego w oknie “Zadania””. 
Okno zadanie wyświetla aktualne zadanie w którym ukryty jest defekt a nie sam defekt. 
***Powinno być :*** “- pozwala na zaraportowanie defektu znalezionego w aktualnie wyświetlanym zadaniu w oknie “Zadania””

**Id błędu :** 9
**Tytuł defektu :** Błąd w opisie przycisku “Zaraportuj defekt”
**Numer strony na której zlokalizowany jest błąd :** 10
**Akapit :** “Okno aplikacji powinno dzielić się na dwie części - okno “Zadania” oraz “
**Opis defektu :** W opisie funkcjonalności znajduje się zdanie - “Funkcja ta jest dostępna we wszystkich trybach pracy aplikacji.” - funkcja ta powinna być dostępna w dwóch z trzech trybów pracy aplikacji - w trybie kapitana drużyny oraz w trybie zawodnika. Funkcja nie powinna być dostępna w trybie członka drużyny.

**Id błędu :** 10
**Tytuł defektu :** Błąd w rysunku 1 - Schemat interfejsu użytkownika części klienckiej
**Numer strony na której zlokalizowany jest błąd :** 11
**Akapit :** “Okno aplikacji powinno dzielić się na dwie części - okno “Zadania” oraz “
**Opis defektu :**  Na rysunku znajduje się przycisk z opisem “Znalazłem defekt” podczas gdy w treści dokumentu jest mowa o przycisku z opisem “Zaraportuj defekt”

**Id błędu :** 11
**Tytuł defektu :** Ograniczenie języka oprogramowania serwera do języka Java7
**Numer strony na której zlokalizowany jest błąd :** 11
**Akapit :** Punkt 6.2, “Dostęp do części serwerowej może być zrealizowany poprzez linię ”
**Opis defektu :** W punkcie 4 dokumentu jest mowa o braku określenia języka programowania w którym ma zostać stworzona aplikacja, podczas gdy w punkcie 6.2 jest mowa iż aplikacja serwerowa ma zostać napisana w języku Java7

**Id błędu :** 12
**Tytuł defektu :** unikalność loginów aplikacji klienckiej
**Numer strony na której zlokalizowany jest błąd :** 12
**Akapit :** Punkt 7.2 “ loginy muszą być indywidualne … “
**Opis defektu :** W podpunkcie jest nast. Informacja : “loginy muszą być indywidualne dla każdego użytkownika części serwerowej aplikacji” - nie ma informacji o loginach użytkowników aplikacji klienckiej - te loginy również powinny być unikatowe.

**Id błędu :** 13
**Tytuł defektu :** błędny format loginu
**Numer strony na której zlokalizowany jest błąd :** 12
**Akapit :** Punkt 7.2 “ login musi składać się z 2 do 8 znaków i zawierać przynajmniej jedną ...“
**Opis defektu :** W podpunkcie jest nast. Informacja : “login musi składać się z 2 do 8 znaków i zawierać przynajmniej jedną małą literę, jedną wielką literę, jedną cyfrę i jeden znak specjalny” - aby to wymaganie zostało spełnione login powinien składać się z przynajmniej 4 znaków.
