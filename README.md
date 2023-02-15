# Challenge_portfolio_MateuszJakubiak
## Subtask 1 
Punkty: 5 
### Subtask 3 
Hej, jestem Mateusz biorę udział w projekcie aby poszerzyć swoją wiedzę na temet testowania oraz po to żeby znależć pracę jako tester oprogramowania. Ludzie którymi się otaczam to programiści, Web deweloperzy, testerzy i to właśnie oni zarazili mnie środowiskiem IT.
##### Subtask 4
**1.** Aplikacja służy do szerokopojętej specyfikacji zawodnika. Pozwala ona na stworzenie karty zawodnika w której możemy zapisywać takie statystyki jak gole, czas gry, którą nogą strzelił, z jakiej pozycji ( generuje się obraz boiska na którym możemy to zaznaczyć ), z jakiego jest klubu i wiele wiele innych. Aplikacja pozwala na sprawdzanie innych zawodników co ułatwia sprawdzanie mocnych oraz słabych stron danego piłkarza.
**2.** Fukncjonalności w aplikacji jest wiele: - logowanie się za pomocą e-mail oraz hasła, - zapisanie wpisanych danych, - Automatyczne oblicznie procentowej skuteczności, - pobieranie statystyk graczy, - edycja, - zmiana jezyka strony. Cała strona jest intuicyjna ze wszystkim trzeba się obeznać ale łatwo jest ją obsługiwać. W mojej opini nie każdy powinien mieć dostę do zmiany statystyk innych zawodników, tylko osoba która stworzyła danego zawodnika powinna mieć dostęp do jego edycji.
**3.** Interfejs mogłby być bardziej urozmaicony strona jest intuicyjna, prosta w obsłudze lecz surowa. Powinny znajdować sie tam motywy piłki nożnej nawet minimalistyczne. 
**4.** *Zaloguj się ----> Kliknij Gracze -----> Kliknij pierwszy wiersz -----> Zmień dowolny parametr -----> Kliknij zastosuj.*
Rezultat: Aplikacja zapisuje zmiany jakiegokolwiek zaznaczonego zawodnika.
Oczekiwany rezultat: Aplikacja nie pozwala na zapisanie zmian dowolnego zawodnika tylko na dodanych samodzielnie lub osób które dostały dostęp do przypisanego konta.
##### Mateusz 😊
## Task 2 
### Subtask 1 
https://drive.google.com/drive/folders/1zjh6dp18sHAk1FyhLbPm5sjpORlrrrL9
### Subtask 2 
https://drive.google.com/drive/folders/1zjh6dp18sHAk1FyhLbPm5sjpORlrrrL9
### Subtask 3 
Przypadki testowe są tworzone w określonym celu lub dla warunku testowego, jakim jest wykonanie danej ścieżki w programie lub zweryfikowanie zgodności z wymaganiem.
## Task 3 
### Subtask 1 
https://drive.google.com/drive/folders/1zamCQbRf0d-BuKtvudeN3K8eYrf7Go36
## Subtask 2 
https://drive.google.com/drive/folders/1zamCQbRf0d-BuKtvudeN3K8eYrf7Go36
## Subtask 3 
https://drive.google.com/drive/folders/1zamCQbRf0d-BuKtvudeN3K8eYrf7Go36
## Task 4
### Subtask 1 
https://drive.google.com/drive/folders/1gYDxBMEjppDIy-Sk8KkOWQVjT39-O51C
### Subtask 2
https://drive.google.com/drive/folders/1gYDxBMEjppDIy-Sk8KkOWQVjT39-O51C
### Subtask 3
https://drive.google.com/drive/folders/1gYDxBMEjppDIy-Sk8KkOWQVjT39-O51C
## Zadanie  5

                                                                  SQL


### Subtask 1 
|Zapytania   | Operatory  |
|---|---|
|  SELECT - wybierz  |  BEETWEEN - w jakim zakresie pozwalamy na występowanie wartości. |
|  GO - odgrodzenie | = - równości  |
|  FROM - z |  < - mniejszości |
| AS - jako  | > - większości  |
|  ORDER BY - jest zawsze po SELECT oraz FROM | <> - różny niż  |
|  DESC - descending, dotyczy tej kolumny po której ją wprowadziliśmy | LIKE - operator dla wartości tekstowych  |
|   |  AND - i |
|   | OR - lub  |
|   | IS - jest  |


 Wybieranie kolumn:
SELECT ProductID, Name, Color, Size 
FROM Production.Product

Malejąco wg koloru i rosnąco wg nazwy:
SELECT * FROM Production.Product
ORDER BY Color DESC, Name
### Subtask 2 
Konfiguracja środowiska i wgranie bazy danych.
### Subtask 3
1.Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
![image](https://user-images.githubusercontent.com/122482305/219127136-8c321407-7085-4e49-9aac-d136935578e2.png)

2.Wyświetl film, który powstał w 2019 roku.
![image](https://user-images.githubusercontent.com/122482305/219128870-6b28261b-ad79-4a20-8268-ab3b7ae5b0a0.png)


3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
![image](https://user-images.githubusercontent.com/122482305/219130668-c08f3344-d9bd-460d-a313-f14aa8a79d6d.png)


4.Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny

7.Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

8.Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

9.Wyświetl dane klienta, który nie ma podanego adresu email.

10.Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
