# Task 1
## Subtask 1 
9 punktów
## Subask 3
*Cześć! Jestem Ewelina i aktualnie przebranżawiam sie z księgowej na testera manualnego. Udział w tym challengu pozwoli mi sprawdzić zdobyta do tej pory wiedzę z zakresu testowania oraz zdobyć praktyczne umiejętnośći, które będę mogła wykorzystać podczas rekrutacji do mojej pierwszej pracy jako tester. :)* 

*Liczę na to, że dzięki temu projektowi, to czego sie dowiedziałam o testowaniu zacznie układać sie w logiczna całość i doda mi motywacji do dalszych działań.*

*Ewelina*
## Subtask 4
_**Do czego służy aplikacja?**_

Aplikacja jest przeznaczona dla skautów piłi nożnej, czyli łowców talentów, którzy dzięki zebranym tutaj informacja mogą łatwo wyszukać najbardziej wartościowych zawodników.

_**Funkcjonalności**_

**1. Strona głóna - Dashbord**

Wygląd strony nie jest intuicyjny. Jest ona mało czytelna,  trudno jest znaleźć odnośniki do głównych funkcjonalności. Menu główne jest bardzo krótkie i nie ułatwia poruszania się po aplikacji. Kafelki są mocno rozstrzelone po stronie co powoduje, że źle się to ogląda. 
Aplikacja lepiej się prezentuje jeśli wyświetlimy ja na urządzeniu mobilnym (np.  telefon Samsung lub iPhone). Brak udogodnień dla osób słabowidzących ( dopasowanie kontrastu wyświetlanej strony, zmiana wielkości czcionki). 

Zauważone blędy:
* Kafelki są źle rozmieszczone, mocno rozrzucone na stronie.
* Nagłówki poszczególnych kafelków są opisane po polsku i angielsku i zawierają błędy ( literówki).  
*	Logo organizacji jest umieszczone w przypadkowym miejscu. 
*	Kliknięcie w kafelki na górze strony nie powoduje żadnej akcji, nie przenosi użytkownika do listy graczy czy bazy meczy.
*	Kafelki u góry strony zawierają bezużyteczne i mało precyzyjne  informacje np. Ilość akcji  - jakich akcji ?? Ilość meczy - rozegranych ? do rozegrania? w sezonie ? w jakim okresie czasu? Ilość akcji – na boisku, na stonce aplikacji???
*	Kafelki na górze strony mają różne kolory, a informacje w nich zawarte są bezużyteczne. 
*	Opcja wyboru języka została umieszczona w Menu łównymm zamiast w prawym górnym rogu, co nie jest intuicyjne. 
*	Z poziomu Menu głównego nie mam dostępu do funkcji dodawania meczu czy tworzenia raportu


**2. Logowanie/Wylogowywanie**

Po podaniu poprawnych danych do logowania: loginu i hasła aplikacja przenosi nas na stronę główną. Jeśli nie podamy loginu i/lub hasła pojawia się komunikat, że te pola muszą być uzupełnione. Dostępna jest opcja przypomnienia hasła -  tej sytuacji konieczne jest podanie emaila na który zostaną przesłane dane do edycji hasła. Funkcja wyloguj przenosi nas na stronę do logowania. Obie funkcjonalności działają poprawnie 


**3. Dodawanie gracza**

Po kliknięciu w link Dodaj gracza otwiera się formularz z polami do uzupełnienia – są to podstawowe informacje o graczu. 

Zauważone blędy:
* Brak walidacji pól: dopuszczalne wartość ujemne w polach Waga, Wzrost, pole Data urodzenia pozwala wpisać datę w przyszłości, rok urodzenia można wpisać dowolny bez żadnych ograniczeń, w polach tekstowych można użyć zarówno liter jak i znaków specjalnych, w polu Telefon można wpisać litery
*	Pola tekstowe nie mają graniczonej liczba znaków jakie można wprowadzić w danym polu 
*	Możliwość dodania gracza do bazy bez kompletu informacji – tylko 3 pola są obowiązkowe ( Imię, Nazwisko, Data Urodzenia) 
*	Pola z danymi do kontaktu ( E-mail, Telefon ) nie są wymagane 
*	Pola do podlinkowania różnią się  wyglądem/ wzorcem. Pole do linka z Youtube jest odkrywane i może być dodawane/ usuwane wielokrotnie.
*	Pole Dodaj język jest odkrywane i może być dodawane/ usuwane wielokrotnie.


**4. Aktualizacja danych gracza**

Możliwa jest aktualizacja wszystkich pól z danymi gracza.

Zauważone blędy:
*	Pola obowiązkowe również mogą być zmienione w dowolny sposób – brak walidacji.
*	Nie jest wymagane dodatkowe potwierdzenie / akceptacja przy zatwierdzaniu zmian, wystarczy jedno kliknięcie, można to zrobić przypadkowo. 

**5. Przeglądanie bazy danych graczy**

Ta funkcjonalność pozwala na przeglądanie tabeli, w której zapisano dane wszystkich graczy.  Tabela ma możliwość sortowania oraz filtrowania informacji o graczach wg wybranego klucza.

Zauważone blędy:
*	Wiersze tabeli nie są ponumerowane
*	Na jednej stronie tabeli prezentowanych jest tylko 10 wierszy i nie ma opcji zmiany tej ilości
*	Niektóre nagłówki kolumn tabeli są  oznaczone strzałką informująca o możliwości sortowania, inne maja tylko informacje „Sort” która wyświetla się po najechaniu kursorem na nazwę kolumny
*	Po posortowanie kolumny Imię rosnąco możemy przeklikiwać widok tabeli na kolejne wiersze – przy wierszach 401 do 410  tabela „rozjeżdża” się i kolumny nie sa widoczne  na ekranie. Błąd ten jest  wynikiem dużej ilości znaków wpisanej w pole Imie jednego z graczy .   
*	Sytuacja powtarza się również przy sortowaniu kolumny Wiek i  Pozycja i również nie jest możliwe prawidłowe prezentowanie danych w tabeli. Zbyt długie ciągi znaków wpisane w pola z danymi graczy powodują rozciągnięcie tabeli. 
*	Kolumna Mecze i Raporty nie mają opcji sortowania
*	Drukowanie – nie mamy opcji drukowania widoku tabeli taki jak jest prezentowany na ekranie. Bez względu na to jakie kolumny wybierzemy do prezentacji w tabeli dane na wydruku się nie zmienią. 
*	Pobieranie danych z tabeli – plik CSV zawiera tylko dane, które były prezentowane na  ekranie  w momencie pobierana. Nie wszystkie dane w pliku są czytelne, zależy to od tego w jakiej postaci były wprowadzone dane do formularza. 
*	W menu głównym w folderze gracze brakuje opcji podziału na grupy wiekowe ( młodzik, junior, kadet) 

**6. Dodawanie meczu**

Ta funkcjonalność ma pomóc w pokazaniu osiągnięć i predyspozycji poszczególnych zawodników oraz ich zaangażowanie w meczu.  Dzięki tej funkcjonalności można tworzyć raporty. 

Zauważone blędy:
*	Brak walidacji pól: dopuszczalne wartość ujemne w polach Numer i Czas gry, pole Data pozwala wpisać datę w przyszłości, rok można wpisać dowolny bez żadnych ograniczeń, w polach tekstowych można użyć zarówno liter jak i znaków specjalnych, w polu.
*	Pole Kolor koszulki  można wpisać dowolny wymyślony kolor ( nie ma opcji wyboru z listy), pole Liga – również można wpisać dowolny tekst ( powinien być wybór z ograniczonej listy ). 
*	Opisy pól w formularzu są po polsku i angielsku, powinny być dostosowane do wybranego języka. 
*	Pole General  - nie wiadomo co tu wpisać, nazwa jest zagadkowa
*	Pola tekstowe nie mają graniczonej liczba znaków jakie można wprowadzić w danym polu.
*	Do jednego meczu można dodać kilka raportów dla tego samego gracza, taka opcja. powoduje powstawanie duplikatów i zniekształca dane w raportach/ statystykach
*	Akcja Rozpocznij mecz dostępna z poziomu Dodawania meczu jest niejasna i  nieintuicyjna. 

**7. Dodawanie raportu**






