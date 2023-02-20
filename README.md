# Tabel of contents

[Task 1](https://github.com/EwelkaB/challenge_portfolio_Ewelina/blob/main/README.md#task-1)

[Task 2](https://github.com/EwelkaB/challenge_portfolio_Ewelina/blob/main/README.md#task-2)

[Task 3](https://github.com/EwelkaB/challenge_portfolio_Ewelina/blob/main/README.md#task-3)

[Task 4](https://github.com/EwelkaB/challenge_portfolio_Ewelina/blob/main/README.md#task-4)

[Task 5](https://github.com/EwelkaB/challenge_portfolio_Ewelina/blob/main/README.md#task-5)

[Task 6](https://github.com/EwelkaB/challenge_portfolio_Ewelina/blob/main/README.md#task-6)


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

#### **1. Strona główna - Dashboard**

W tej funkcjonalności na stronie głównej aplikacji dostępne są linki, które pozwalaja na dodanie do bazy nowego gracza, śledzenie ostatnich aktywnośći w aplikacji, wybór jezyka w jakim będzie wyświetlana strona. Dodatkowo widoczne są informacje o ilości graczy, ilości meczy i ilości raportów oraz akcji. Na stronie głównej umieszczone jest logo organizacji  oraz link to kontaktu. 

Wygląd strony nie jest intuicyjny. Jest ona mało czytelna, trudno jest znaleźć odnośniki do głównych funkcjonalności. Menu główne jest bardzo krótkie i nie ułatwia poruszania się po aplikacji. Kafelki są mocno rozstrzelone po stronie co powoduje, że źle się to ogląda. 
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

W funkcjonalnoości Logowanie po podaniu poprawnych danych do logowania: loginu i hasła, aplikacja przenosi nas na stronę główną. Jeśli nie podamy loginu i/lub hasła pojawia się komunikat, że te pola muszą być uzupełnione. Dostępna jest opcja przypomnienia hasła - w tej sytuacji konieczne jest podanie emaila, na który zostaną przesłane dane do edycji hasła. Funkcja Wyloguj przenosi nas z aplikacji na stronę do logowania. Aby powrócic do aplikacji konieczne jest ponowne logowanie. 
Obie funkcjonalności Logowanie i Wylogowywanie działają poprawnie. 


#### **3. Dodawanie gracza**

Ta funkcjonalność umożliwia dodanie nowego zawodnika do bazy. Po kliknięciu w link Dodaj Gracza otwiera się formularz z polami do uzupełnienia – wpisujemy tu  podstawowe informacje o graczu tj. Imię, Nazwisko, Data Urodzenia, Waga, Pozycja na boisku itp..  

Zauważone błędy/ proponwane usprawnienia:
* Brak walidacji pól: dopuszczalne wartość ujemne w polach Waga, Wzrost, pole Data urodzenia pozwala wpisać datę w przyszłości, rok urodzenia można wpisać dowolny bez żadnych ograniczeń, w polach tekstowych można użyć zarówno liter jak i znaków specjalnych, w polu Telefon można wpisać litery.
* Brak walidacji pól wpływa na bezpieczeństwo aplikacji.
*	Pola tekstowe nie mają graniczonej liczba znaków jakie można wprowadzić w danym polu. 
*	Możliwe jest dodanie gracza do bazy bez kompletu informacji – tylko 3 pola są obowiązkowe ( Imię, Nazwisko, Data urodzenia) 
*	Pola z danymi do kontaktu ( E-mail, Telefon ) nie są wymaganea powinny być. 
*	Pola do podlinkowania różnią się  wyglądem/ wzorcem. Pole do linka z Youtube jest odkrywane i może być dodawane/ usuwane wielokrotnie.
*	Pole Dodaj język jest odkrywane i może być dodawane/ usuwane wielokrotnie.


#### **4. Aktualizacja danych gracza**

Ta funkcjonalność pozwala na aktualizacje wszystkich danych zawodnika istniejącego już w bazie. 

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
*	Pobieranie danych z tabeli – plik CSV zawiera tylko dane, które były prezentowane na  ekranie  w momencie pobierana. Nie wszystkie dane w pliku są czytelne. 
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

W mojej ocenie testowana aplikacja jest ciekawym narzędziem do zbierania danych o zawodnikach piłki nożnej i może być pomocna przy poszukiwaniu młodych dobrze zapowiadających się sportowców. Konieczne jest jednak poprawienie szeregu blędów ( w tym krytycznych blędow związanych z zapewnieniem bezpieczeństwa aplikacji ) oraz implementacja usprawnień zwiazanych z "User Experience"  :blush: 

## Subtask 5

Dołączyłam do ekipy w Jira :smile: 

https://justboat.atlassian.net/jira/software/projects/CPP/boards/1

# Task 2
## Subtask 1 

https://docs.google.com/spreadsheets/d/1_jV7GjwASGaW7uhVWbbMcC0yWcDtggTtLqbqWk8J-Jo/edit#gid=0

## Subtask 2

https://docs.google.com/spreadsheets/d/14hhGsmBSDINuQ_n9FJ98Itue3VjMqvfR0PEzMA42wfw/edit#gid=0

## Subtask 3

#### _**Po co piszemy test case'y?**_

Test case’y piszemy po to aby:
* dobrze rozplanować to co chcemy przetestować
* wyestymować czas potrzebny do przeprowadzenie testów
* wyłapać brakujące informacje w dostarczonej dokumentacji projektowej 
* mieć dokładny, jasny i czytelny opis funkcjonalności aplikacji zgodnych z oczekiwaniami
* razie problemów kadrowych łatwo wdrożyć nowa osobę która będzie kontynuować testy
* na ich podstawie po zakończonych testach budować raporty z wykonania testów
* upewnić się, że testerzy i deweloperzy jednakowo rozumieją zadanie ( system ) które ma być wykonane
* pokazać co już zostało przetestowane, a co nie i na jakim etapie testów jesteśmy 
* znaleźć defekty i zweryfikować poprawność systemu 
* upewnić się czy system może już być wprowadzony na środowisko produkcyjne
* przy przeprowadzaniu retestów można było sprawdzić czy naprawione błędy już nie występują

## Subtask 4

https://docs.google.com/spreadsheets/d/1Rq8H40srB25dwZM62AmGUczVc_Wvi4qV9mNNtsdvhqw/edit#gid=0

# Task 3
## Subtask 1 

https://docs.google.com/spreadsheets/d/1Dj_u6KK4TmcWMcswV8c-LoGx4mjIfjsEb3Qx4HOyuBs/edit#gid=0

## Subtask 2 

https://docs.google.com/spreadsheets/d/1WzNosK80OIFhVQK_Y3qiNMk-MIub_Juprve9cnlIsb8/edit#gid=250653879
https://docs.google.com/spreadsheets/d/17l4eSsO67av_doPfC72_he-xIuj8uXPDjXvKNiSILzU/edit#gid=1426167314

## Subtask 3 

https://docs.google.com/document/d/1xsqKnYKGjQUD-gGd_atLLBd4oIccjO0jRUEMt2kmdbc/edit

# Task 4
## Subtask 1 

https://docs.google.com/spreadsheets/d/1MrMVrJvJLcItHRkCHet-FsFIdT3WqS6NX9RUebGW8Ak/edit#gid=1749245954

## Subtask 2

https://docs.google.com/spreadsheets/d/1vbcgIpb6ddbJiiroKE15A0F7kA9MB1yJrtsudpbwopI/edit#gid=2052216741

## Subtask 3

#### _**Do czego służy aplikacja OLX?**_

Aplikacja OLX  ma pełnić rolę lokalnej tablicy ogłoszeń. Ma pomagać w łączeniu ze sobą osób, które chcą coś sprzedać, oddać lub zamienić z tymi którzy danej rzeczy lub usługi poszukują. 

Użytkownikiem końcowym aplikacji są osoby szukające okazji do zakupu po atrakcyjnej cenie  rzeczy używanych, tańszych, unikalnych lub staroci.🚗🛴🪑

W moje ocenie aplikacja jest user friendly. 😃 W dolnej części ekranu  widoczne jest menu, które umożliwia łatwe nawigowanie po aplikacji. Strona graficzna jest kolorowa i czytelna. Kolorowe obrazki przy nazwach kategorii ułatwiają wyszukiwanie i są intuicyjne. Pasek wyszukiwania umieszczony  na górze strony jest dobrze widoczny i takie umiejscowienie jest bardzo intuicyjne. Listę wyświetlanych ogłoszeń łatwo się scrolluje. Wszystkie funkcjonalności są bardzo łatwe do opanowania i intuicyjne.

Jako dodatkowe usprawnienie w moje ocenie można dodać funkcję, która spowoduje, że  kliknięcie na ikonę “Szukaj” 🔍 będzie rozwijać  listę z nazwami kategorii. Takie rozwiązanie zapewni szybszy i łatwiejszy wybór kategori, bez klikania w “Zobacz wszystkie” lub scrollowania po ikonach na górze ekranu.

Według mnie testowane aplikacji mobilnej jest bardziej skomplikowane niż testowanie aplikacji desktopowej. Przy testowaniu aplikacji mobilnej  należy  uwzględnić i zasymulować wiele akcji. które mogą wystąpić  na urządzeniu mobilnym w trakcie korzystania z aplikacji ( np. brak lub zmianę sieci, tryb oszczędzania baterii, przychodzące połączenie lub wiadomość).

# Task 5
## Subtask 1 

Done ✔🎧💻

<img width="902" alt="image" src="https://user-images.githubusercontent.com/122117057/219972418-38163e9a-1a58-4128-bf0f-3e6946716667.png">


### Podstawowe zapytania SQL 
* SELECT
* FROM
* WHERE
* BETWEEN / AND 
* ORDER BY ( DESC, ASC ) 
* WHERE  - AND
* WHERE -  OR
* WHERE  - LIKE  


## Subtask 3 
#### _**1.Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**_

SELECT * FROM `actors` ORDER BY surname

<img width="149" alt="image" src="https://user-images.githubusercontent.com/122117057/219970149-6bc4d8b4-21be-4eb8-b138-903776f0a3d6.png">

#### _**2.Wyświetl film, który powstał w 2019 roku.**_

SELECT * FROM `movies` WHERE year_of_production = 2019

<img width="170" alt="image" src="https://user-images.githubusercontent.com/122117057/219970474-5aa6eabd-4d1f-4bff-8bd6-33b6b02f1a6a.png">

#### _**3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**_

SELECT * FROM `movies` WHERE year_of_production BETWEEN 1900 AND 1999

<img width="278" alt="image" src="https://user-images.githubusercontent.com/122117057/219970587-0c121f8b-2fbb-4872-b7f9-38607c246c6b.png">

#### _**4.Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$**_

SELECT title, price FROM `movies` WHERE price < 7

<img width="158" alt="image" src="https://user-images.githubusercontent.com/122117057/219970739-f6ddaf88-b6c7-46f6-8734-f2e9defd7a67.png">

#### _**5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**_

SELECT * FROM `actors` WHERE actor_id >= 4 AND actor_id <= 7

<img width="146" alt="image" src="https://user-images.githubusercontent.com/122117057/219971185-76b0c421-8316-478d-8391-94c8ad64aa67.png">

#### _**6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**_

SELECT * FROM `customers` WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6

<img width="178" alt="image" src="https://user-images.githubusercontent.com/122117057/219971405-70cd80e8-1ddf-452d-bcc0-c712abc2dd61.png">

#### _**7.Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**_

SELECT * FROM `customers` WHERE customer_id IN (1, 3, 5) 

<img width="184" alt="image" src="https://user-images.githubusercontent.com/122117057/219971483-f1e1e109-a900-4662-b46d-2d6128aa32a2.png">

#### _**8.Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**_

SELECT * FROM `actors` WHERE name LIKE "An%"

<img width="128" alt="image" src="https://user-images.githubusercontent.com/122117057/219971773-b1f84c8e-8efa-4a48-9048-8c4973f62ce4.png">

#### _**9.Wyświetl dane klienta, który nie ma podanego adresu email.**_

SELECT * FROM `customers` WHERE email IS Null

<img width="164" alt="image" src="https://user-images.githubusercontent.com/122117057/219971862-9ec26bb1-e1f8-4efb-8d68-574ef35524b4.png">

#### _**10.Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**_

SELECT * FROM `movies` WHERE  ( price > 9)  AND (movie_id BETWEEN 2 and 8) 

<img width="203" alt="image" src="https://user-images.githubusercontent.com/122117057/219972028-68d0b6ee-818d-4713-a3c9-9206dbcec5f6.png">

# Task 6
## Subtask 1 

#### _**11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈**_

UPDATE customers
SET Surname = "Muler"
WHERE Surname= "Miler"

<img width="226" alt="image" src="https://user-images.githubusercontent.com/122117057/220060732-f899273f-0955-40c3-a173-5019c30dbf90.png">

 #### _**12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.**_

SELECT * FROM `sale` JOIN customers ON sale.customer_id = customers.customer_id
WHERE sale.movie_id = 4

<img width="314" alt="image" src="https://user-images.githubusercontent.com/122117057/219977782-4779224b-04b1-472b-a7f0-db204b337db4.png">

#### _**13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com**_

UPDATE customers
SET email  = "pati@mail.com"
WHERE customer_id = 4

<img width="188" alt="image" src="https://user-images.githubusercontent.com/122117057/220097342-44cfed06-7ecc-41da-a209-788aaf195fb3.png">


#### _**14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**_

SELECT sale.sale_date, customers.name, customers.surname, movies.title
FROM sale 
INNER JOIN customers
ON sale.customer_id = customers.customer_id
INNER JOIN movies
ON movies.movie_id = sale.movie_id

<img width="248" alt="image" src="https://user-images.githubusercontent.com/122117057/220173124-1196a674-48db-45ba-b6de-8dd41988ca17.png">


#### _**15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag**_

ALTER TABLE customers
ADD COLUMN pseudonym VARCHAR ( 200)

UPDATE customers SET pseudonym = concat ( LEFT(name,2), RIGHT ( surname,1))

<img width="263" alt="image" src="https://user-images.githubusercontent.com/122117057/220177977-fb71e062-97c0-4f08-a70f-93dfbe7d7ecb.png">



#### _**16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**_

SELECT *
FROM movies
WHERE movie_id IN ( SELECT movie_id from sale) 

<img width="291" alt="image" src="https://user-images.githubusercontent.com/122117057/219980779-4f49bc55-9e1a-4f49-bab7-2524333926d8.png">

#### _**17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)**_

SELECT name FROM actors
UNION
SELECT name FROM customers 
ORDER BY name

<img width="62" alt="image" src="https://user-images.githubusercontent.com/122117057/220063364-b9807112-15aa-4c70-b78d-992d66a4e2dc.png">

#### _**18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).**_

SELECT *, price + 2.5
FROM movies
WHERE year_of_production > 2000

<img width="306" alt="image" src="https://user-images.githubusercontent.com/122117057/219978084-0aa5f576-2e09-4651-9c13-a33e22a2fade.png">

#### _**19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał**_

#### _**20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa**_

## Subtask 2

## Subtask 3 











