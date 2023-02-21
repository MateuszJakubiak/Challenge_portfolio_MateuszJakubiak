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
## Task  5

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
![image](https://user-images.githubusercontent.com/122482305/219424081-9d5bb35c-0dcb-43d0-908f-b1a41ee3123c.png)


5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
![image](https://user-images.githubusercontent.com/122482305/219667032-c2b9d158-6e91-4b56-808a-8956747a0ec5.png)


6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny
![image](https://user-images.githubusercontent.com/122482305/219672551-8c5040c5-ee32-4a00-a5cc-5f948c4277dd.png)


7.Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
![image](https://user-images.githubusercontent.com/122482305/219673192-cf08459c-0c37-44a7-98d4-6ffc9d005050.png)

8.Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
![image](https://user-images.githubusercontent.com/122482305/219675937-e2ac3c66-a3d4-47d3-9ec3-c9ccad111a1b.png)


9.Wyświetl dane klienta, który nie ma podanego adresu email.
![image](https://user-images.githubusercontent.com/122482305/219676585-13e6e1f3-07a5-4aa3-ac46-d49959bdc674.png)


10.Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
![image](https://user-images.githubusercontent.com/122482305/219679915-0eebb1ab-32a3-4a4f-8ab1-3b537ea2af87.png)

## Task 6

### Subtask 1 

Ciąg dalszy zadań z SQL.

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈

![image](https://user-images.githubusercontent.com/122482305/220197535-0c84cc58-ecc3-4367-94fd-edbaa5dad005.png)

![image](https://user-images.githubusercontent.com/122482305/220197721-24c998bb-a0bb-4a39-865f-d34b0dd5818b.png)



12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

![image](https://user-images.githubusercontent.com/122482305/220417194-89597d12-6f6e-4210-b300-c1a1731cff66.png)


13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com

![image](https://user-images.githubusercontent.com/122482305/220419754-debfdaca-52e5-419d-9f91-cb14a7f9e05b.png)


14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

![image](https://user-images.githubusercontent.com/122482305/220423982-7aad6b0c-816d-4342-94ee-e99aeefa25ab.png)


15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

![image](https://user-images.githubusercontent.com/122482305/220441320-ff0b72c1-6745-477f-8921-2f9623d0baa6.png)


16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

![image](https://user-images.githubusercontent.com/122482305/220446499-f3a22a66-d37a-479c-8be3-6d2f75856baa.png)


17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

![image](https://user-images.githubusercontent.com/122482305/220448649-432f956a-f29c-4e82-aa59-ff0a3414bae9.png)


18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

![image](https://user-images.githubusercontent.com/122482305/220452451-138ed9bb-25ff-4b35-8ab5-6b2ee4b967b6.png)


19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

![image](https://user-images.githubusercontent.com/122482305/220460169-170deb35-2c5d-4ce5-85eb-578d06de2968.png)


20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

![image](https://user-images.githubusercontent.com/122482305/220460472-47afe16a-9150-4110-b100-368bf26f1320.png)


### Subtask 2 

Test wiedzy ECRU ze strony: http://getistqb.com/ 

Zdjęcie wykonane z 1 podejścia do testu. :)

![image](https://user-images.githubusercontent.com/122482305/220199284-13b05a03-89e6-4760-81da-6210135d694f.png)
