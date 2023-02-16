# 🚀 **Task 6** 🚀

**:pushpin: SPIS TREŚCI:**
1. [Subtask 1 - Kilka zadań związanych z SQL'em](#Subtask1)
    - [Zad. 11. Znajdź i zastosuj funkcję, która poprawi nazwisko Ani Muler na Miler.](#kropka1)
    - [Zad. 12. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila, który kupił film o id 4.](#kropka2)
    - [Zad. 13. Uzupełnij email klientce Patrycji wpisując: pati@mail.com.](#kropka3)
    - [Zad. 14. Dla każdego zakupu wyświetl imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu.](#kropka4)
    - [Zad. 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag.](#kropka5)
    - [Zad. 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.](#kropka6)
    - [Zad. 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie (wykorzystaj do tego funkcję UNION).](#kropka7)
    - [Zad. 18. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).](#kropka8)
    - [Zad. 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał.](#kropka9)
    - [Zad. 20. Dodaj do tabeli customers nową klientkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa.](#kropka10)

##  <a name="Subtask1">Subtask 1 - Kilka zadań związanych z SQL'em 👩‍💻 </a>
### <a name="kropka1">11. Znajdź i zastosuj funkcję, która poprawi nazwisko Ani Muler na Miler.</a>

```sql
UPDATE customers
SET surname = 'Miler'
WHERE customer_id = 3
```

![zadanie 11](https://user-images.githubusercontent.com/122294284/219360740-ddc3b030-31ad-40bb-9b79-0089917eadb9.png)

### <a name="kropka2">12. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila, który kupił film o id 4.</a>

```sql
SELECT sale.movie_id, customers.name, customers.surname, customers.email
FROM customers
JOIN sale ON customers.customer_id=sale.customer_id
WHERE sale.movie_id = 4
```

![zadanie 12](https://user-images.githubusercontent.com/122294284/219366048-41769051-2835-4459-a7f8-42c1ac6c0613.png)


### <a name="kropka3">13. Uzupełnij email klientce Patrycji wpisując: pati@mail.com.</a>

```sql
UPDATE customers
SET email = 'pati@mail.com'
WHERE name LIKE 'Patrycja'
```

![zadanie 13](https://user-images.githubusercontent.com/122294284/219372141-d53d5bb3-aef8-422e-a059-fa013fd7a278.png)

### <a name="kropka4">14. Dla każdego zakupu wyświetl imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).</a>

```sql
SELECT customers.name, customers.surname, movies.title
FROM sale
INNER JOIN customers ON customers.customer_id = sale.customer_id
INNER JOIN movies ON sale.movie_id = movies.movie_id
```

![zadanie 14](https://user-images.githubusercontent.com/122294284/219392531-ccb3eb55-7922-4250-a7f2-aff9ebd84a3e.png)

### <a name="kropka5">15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag.</a>

Krok 1
```sql
ALTER TABLE customers
ADD pseudonym varchar(3)
```
Krok 2
```sql
UPDATE customers
SET pseudonym = CONCAT(LEFT(name,2), RIGHT(surname,1))
```

![zadanie 15](https://user-images.githubusercontent.com/122294284/219426366-12083c94-31ef-496b-b5b1-a0e22fbb60e7.png)

### <a name="kropka6">16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.</a>

```sql
SELECT DISTINCT movies.movie_id, movies.title
FROM sale
INNER JOIN movies ON sale.movie_id = movies.movie_id
ORDER BY movie_id
```

![zadanie 16](https://user-images.githubusercontent.com/122294284/219416129-fc5675ce-31d1-400a-8b40-ab395c68d3b4.png)

### <a name="kropka7">17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie (wykorzystaj do tego funkcję UNION).</a>

```sql
SELECT name FROM actors
UNION
SELECT name FROM customers
ORDER BY name
```

![zadanie 17](https://user-images.githubusercontent.com/122294284/219456488-cf893b00-209e-4d53-911b-f213e101e497.png)

