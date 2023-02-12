# 🚀 **Task 5** 🚀

## **Subtask 1 - Krótki kurs podstaw SQL**

### *Operatory, jakich się nauczyłam:*

:pushpin: 

### *Zapytania, jakich się nauczyłam:*
:pushpin: 

## **Subtask 3 - Kilka zadań związanych z SQL'em**
### 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

> SELECT * FROM actors
> 
> ORDER BY surname

![zadanie 1](https://user-images.githubusercontent.com/122294284/218320541-a5f2d476-46e7-4afd-933a-92a171581fe0.png)


### 2. Wyświetl film, który powstał w 2019 roku.

>SELECT * FROM movies
>
>WHERE year_of_production = '2019'

![zadanie 2](https://user-images.githubusercontent.com/122294284/218320785-2ea7f22d-35ff-4764-8fa0-8bbde0992fc4.png)


### 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

>SELECT * FROM movies
>
>WHERE year_of_production = '2019'

![zadanie 3](https://user-images.githubusercontent.com/122294284/218321022-40aa15de-554f-4734-8153-f86be6b8f01e.png)


### 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

>SELECT title, price FROM movies
>
>WHERE price <7

![zadanie 4](https://user-images.githubusercontent.com/122294284/218321234-845bb2a8-944d-471f-a6b8-e1afc4357ad8.png)


### 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

>SELECT * FROM actors
>
>WHERE actor_id >=4 AND actor_id <=7

![zadanie 5](https://user-images.githubusercontent.com/122294284/218321483-db6e822f-c533-41db-956f-bb18e04d3a03.png)


6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.


7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.


8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.


9. Wyświetl dane klienta, który nie ma podanego adresu email.


10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.






