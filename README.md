# Task 1
## Subtask 1 
9 punktów
## Subtask 3
*Cześć! 😃 Jestem Ewelina i aktualnie przebranżawiam sie z księgowej na testera manualnego. Udział w tym challengu pozwoli mi sprawdzić zdobytą do tej pory wiedzę z zakresu testowania oraz zdobyć praktyczne umiejętnośći, które będę mogła wykorzystać podczas rekrutacji do mojej pierwszej pracy jako tester. :)* 

*Liczę na to, że dzięki temu projektowi, to czego sie dowiedziałam o testowaniu zacznie układać sie w logiczna całość i doda mi motywacji do dalszych działań. 💪*

*Ewelina*
## Subtask 4

### Tabel of contents
* [Do czego służy aplikacja](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#Do-czego-służy-aplikacja)
* [Główne funkcjonalności aplikacji](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#Główne-funkcjonalności-aplikacji)
  
  [1. Strona główna - Dashbord](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#1-Strona-główna---Dashbord)
  
  [2. Logowanie/Wylogowywanie](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#2-Logowanie/Wylogowywanie)
  
  [3. Dodawanie gracza](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#3-Dodawanie-gracza)
  
  [4. Aktualizacja danych gracza](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#4-Aktualizacja-danych-gracza)
  
  [5. Przeglądanie bazy danych graczy](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#5-przeglądanie-bazy-danych-graczy)
  
  [6. Dodawanie meczu](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#6-Dodawanie-meczu)
  
  [7. Dodawanie raportu](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#7-Dodawanie-raportu)
  
* [Podsumowanie](https://github.com/EwelkaB/challenge_portfolio_Ewelina/#Podsumowanie)
  
  

#### _**Do czego służy aplikacja?**_

Aplikacja jest przeznaczona dla skautów piłki nożnej czyli "łowców talentów", którzy dzięki zebranym tutaj informacjom mogą wyszukać najbardziej wartościowych zawodników. Ta aplikacja umożliwia dodanie nowego gracza do bazy i uzupełnienie kluczowych informacji o nim, jak również wpisanie jego wyników i osiągnięć na boisku. Aplikacja pozwala na filtrowanie zgomadzonych w bazie danych oraz na tworzenie indywidualnych raportów dla każdego z graczy. 

#### _**Główne funkcjonalności aplikacji**_

#### **1. Strona główna - Dashbord**

Strona główna aplikacji na którą przenosimy sie po poprawnym zalogowaniu powinna być przejrzysta i czytela. Z menu łatwo można wybrać główne funkcjonalności, a poruszanie sie po stronie powinno być intuicyjne. Poza tym logo i kafelki powinny być rozmieszczone równomiernie i utrzymane w określonej kolorystyce.  

Wygląd strony nie jest intuicyjny. Jest ona mało czytelna,  trudno jest znaleźć odnośniki do głównych funkcjonalności. Menu główne jest bardzo krótkie i nie ułatwia poruszania się po aplikacji. Kafelki są mocno rozstrzelone po stronie co powoduje, że źle się to ogląda. 
Aplikacja lepiej się prezentuje jeśli wyświetlimy ja na urządzeniu mobilnym (np.  telefon Samsung lub iPhone). Brak udogodnień dla osób słabowidzących ( dopasowanie kontrastu wyświetlanej strony, zmiana wielkości czcionki). 

Zauważone błędy/ proponwane usprawnienia:
* Kafelki są źle rozmieszczone, mocno rozrzucone na stronie.
* Nagłówki poszczególnych kafelków są opisane po polsku i angielsku i zawierają błędy (literówki).  
*	Logo organizacji jest umieszczone w przypadkowym miejscu. 
*	Kliknięcie w kafelki na górze strony nie powoduje żadnej akcji, nie przenosi użytkownika do listy graczy czy bazy meczy.
*	Kafelki u góry strony zawierają bezużyteczne i mało precyzyjne  informacje np. Ilość akcji  - jakich akcji ?? Ilość meczy - rozegranych ? do rozegrania? w sezonie ? w jakim okresie czasu? Ilość akcji – na boisku, na stonce aplikacji???
*	Kafelki na górze strony mają różne kolory. 
*	Opcja wyboru języka została umieszczona w menu głównymm zamiast w prawym górnym rogu, co nie jest intuicyjne. 
*	Z poziomu menu głównego nie mam dostępu do funkcji dodawania meczu czy tworzenia raportu.


#### **2. Logowanie/Wylogowywanie**

Po podaniu poprawnych danych do logowania: loginu i hasła aplikacja przenosi nas na stronę główną. Jeśli nie podamy loginu i/lub hasła pojawia się komunikat, że te pola muszą być uzupełnione. Dostępna jest opcja przypomnienia hasła - w tej sytuacji konieczne jest podanie emaila na który zostaną przesłane dane do edycji hasła. Funkcja wyloguj przenosi nas na stronę do logowania.
Obie funkcjonalności działają poprawnie. 


#### **3. Dodawanie gracza**

Ta funkcjonalność umożliwia dodanie nowego zawodnika do bazy. Po kliknięciu w link Dodaj Gracza otwiera się formularz z polami do uzupełnienia – wpisujemy tu  podstawowe informacje o graczu tj. Imię, Nazwisko, Data Urodzenia, Waga,Pozycja na boisku itp..  

Zauważone błędy/ proponwane usprawnienia:
* Brak walidacji pól: dopuszczalne wartość ujemne w polach Waga, Wzrost, pole Data urodzenia pozwala wpisać datę w przyszłości, rok urodzenia można wpisać dowolny bez żadnych ograniczeń, w polach tekstowych można użyć zarówno liter jak i znaków specjalnych, w polu Telefon można wpisać litery.
* Brak walidacji pól wpływa n abezpieczeństwo aplikacji.
*	Pola tekstowe nie mają graniczonej liczba znaków jakie można wprowadzić w danym polu. 
*	Możliwe jest dodanie gracza do bazy bez kompletu informacji – tylko 3 pola są obowiązkowe ( Imię, Nazwisko, Data urodzenia) 
*	Pola z danymi do kontaktu ( E-mail, Telefon ) nie są wymaganea powinny być. 
*	Pola do podlinkowania różnią się  wyglądem/ wzorcem. Pole do linka z Youtube jest odkrywane i może być dodawane/ usuwane wielokrotnie.
*	Pole Dodaj język jest odkrywane i może być dodawane/ usuwane wielokrotnie.


#### **4. Aktualizacja danych gracza**

Ta funkcjonalność pozwala na aktualizacje wszystkich danych zawodnika istniejącego w bazie. 

Zauważone błędy/ proponwane usprawnienia:
*	Pola obowiązkowe mogą być zmienione w dowolny sposób – brak walidacji.
*	Nie jest wymagane dodatkowe potwierdzenie/ akceptacja przy zatwierdzaniu zmian, wystarczy jedno kliknięcie w SUBMIT i dane zostają zmienione. Można to zrobić przypadkowo. 

#### **5. Przeglądanie bazy danych graczy**

Ta funkcjonalność pozwala na przeglądanie tabeli, w której zapisano dane wszystkich graczy.  Tabela ma możliwość sortowania oraz filtrowania informacji o graczach wg wybranego klucza. Dane zawarte w tabeli możemy exportowac do pliku CSV oraz wydrukować. Dodatkowo wygląd tabeli jest edytowalny i pozwala na wybór kolumn, które bedą wyświetlone w tabeli. 

Zauważone błędy/ proponwane usprawnienia:
*	Wiersze tabeli nie są ponumerowane. Dodanie numerów wierszy znacznie poprawia czytelność tabeli.
*	Na jednej stronie tabeli prezentowanych jest tylko 10 wierszy i nie ma opcji zmiany tej ilości ( tego widoku).
*	Niektóre nagłówki kolumn tabeli są  oznaczone strzałką informująca o możliwości sortowania, inne maja tylko informacje „Sort” która wyświetla się po najechaniu kursorem na nazwę kolumny
*	Po posortowanie kolumny Imię rosnąco, możemy przeklikiwać widok tabeli na kolejne wiersze – przy wierszach 401 do 410  tabela „rozjeżdża” się i kolumny nie sa widoczne  na ekranie. Błąd ten jest  wynikiem dużej ilości znaków wpisanej w pole Imie jednego z graczy .   
*	Sytuacja powtarza się również przy sortowaniu kolumny Wiek i  Pozycja, tu również nie jest możliwe prawidłowe prezentowanie danych w tabeli. Zbyt długie ciągi znaków wpisane w pola z danymi graczy powodują rozciągnięcie tabeli. 
*	Kolumna Mecze i Raporty nie mają opcji sortowania.
*	Drukowanie – nie mamy opcji drukowania widoku tabeli taki jak jest prezentowany na ekranie. Bez względu na to jakie kolumny wybierzemy do prezentacji w tabeli, dane na wydruku się nie zmienią. 
*	Pobieranie danych z tabeli – plik CSV zawiera tylko dane, które były prezentowane na  ekranie  w momencie pobierana. Nie wszystkie dane w pliku są czytelne, zależy to od tego w jakiej postaci były wprowadzone dane do formularza. 
*	W menu głównym w folderze Gracze brakuje opcji podziału na grupy wiekowe ( młodzik, junior, kadet) -a jest to kluczowa informacja.

#### **6. Dodawanie meczu**

Ta funkcjonalność ma pomóc w pokazaniu osiągnięć i predyspozycji poszczególnych zawodników podczas meczu, ich zaangażowanie w grę oraz zdolności komunikacyjne.  Dzięki tej funkcjonalności można tworzyć indywidualne raporty dla poszcególnych graczy. 

Zauważone błędy/ proponwane usprawnienia:
*	Brak walidacji pól: dopuszczalne wartość ujemne w polach Numer i Czas gry, pole Data pozwala wpisać datę w przyszłości, rok można wpisać dowolny bez żadnych ograniczeń, w polach tekstowych można użyć zarówno liter jak i znaków specjalnych, w polu.
*	Pole Kolor koszulki  można wpisać dowolny wymyślony kolor ( nie ma opcji wyboru z listy), pole Liga – również można wpisać dowolny tekst ( powinien być wybór z ograniczonej listy ). 
*	Opisy pól w formularzu są po polsku i angielsku, powinny być dostosowane do wybranego języka. 
*	Pole General  - nie wiadomo co tu wpisać, nazwa jest zagadkowa.
*	Pola tekstowe nie mają graniczonej liczba znaków jakie można wprowadzić w danym polu.
*	Do jednego meczu można dodać kilka raportów dla tego samego gracza, taka opcja. powoduje powstawanie duplikatów i zniekształca dane w raportach/ statystykach.
*	Akcja Rozpocznij mecz dostępna z poziomu Dodawania meczu jest niejasna i  nieintuicyjna, brakuje tutaj instrukcji, która opisze jak prawidłowo przejśc przez ta akcję. ( Niestety zabrakło mi czasu na dokładne sprawdzenie tej funkcjonalności).   

#### **7. Dodawanie raportu**

Dla każdego gracza można utworzyć indywidualny raport po zagranym przez niego meczu, zawierający informacje o kluczowych zagraniach, asystach, golach, faulach posiadaniu piłki itp. Jeden zagrany mecz przez zawodnika to jeden raport.

Zauważone błędy/ proponwane usprawnienia:
*	Do jednego meczu można dodać kilka raportów dla tego samego gracza, taka opcja powoduje powstawanie duplikatów i zniekształca dane w raportach/ statystykach.
*	Opcja wyboru raportów jest dostępna po wcześniejszym wyborze gracza, nie ma tej opcji w menu głównym.
*	Zmiana ilości gwiazdek w recenzji w jednym raporcie powoduje, że w pozostałych raportach ta pozycja również zostaje zmieniona
*	Forma prezentacji raportu po wyświetleniu jest nieestetyczna: logo i nagłówek przesunięte w lewo. 
*	Widoczne w raporcie paski edycji tekstu oraz opisy/ wyjaśnienia  czego dotyczy dana cześć raportu ( powinny się pojawiać przy najechaniu myszką na ikonkę  informacyjną). 
*	Kolejność prezentowanych danych jest nielogiczna, dane statystyczne powinny się znaleźć w raporcie przed podsumowaniem i recenzją. 

#### _**Podsumowanie**_

W mojej ocenie testowana aplikacja jest ciekawym narzędziem do zbierania danych o zawodnikach piłki nożnej i może być pomocna przy poszukiwaniu młodych dobrze zapowiadających się sportowców. Konieczne jest jednak poprawienie  krytycznych blędow związanych z zapewnieniem bezpieczeństwa oraz implementacja szeregu usprawnień zwiazanych z "User Experience"  :blush: 

## Subtask 5

Dołączyłam do ekipy w Jira :smile: 

https://justboat.atlassian.net/jira/software/projects/CPP/boards/1
 





