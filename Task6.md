# 🚀 **Task 6** 🚀

**:pushpin: SPIS TREŚCI:**
1. [Subtask 1 - Kilka zadań związanych z SQL'em](#Subtask1)
    - [Zad. 11. Znajdź i zastosuj funkcję, która poprawi nazwisko Ani Muler na Miler.](#kropka1)
    - [Zad. 12. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila, który kupił film o id 4.](#kropka2)
    - [Zad. 13. Uzupełnij email klientce Patrycji wpisując: pati@mail.com.](#kropka3)
    - [Zad. 14. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.](#kropka4)
    - [Zad. 15. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.](#kropka5)
    - [Zad. 16. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.](#kropka6)
    - [Zad. 17. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.](#kropka7)
    - [Zad. 18. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.](#kropka8)
    - [Zad. 19. Wyświetl dane klienta, który nie ma podanego adresu email.](#kropka9)
    - [Zad. 20. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.](#kropka10)

##  <a name="Subtask1">Subtask 1 - Kilka zadań związanych z SQL'em 👩‍💻 </a>
### <a name="kropka1">11. Znajdź i zastosuj funkcję, która poprawi nazwisko Ani Muler na Miler.</a>

> UPDATE customers
> 
> SET surname = 'Miler'
> 
> WHERE customer_id = 3

![zadanie 11](https://user-images.githubusercontent.com/122294284/219360740-ddc3b030-31ad-40bb-9b79-0089917eadb9.png)

### <a name="kropka2">12. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila, który kupił film o id 4.</a>

>SELECT sale.movie_id, customers.name, customers.surname, customers.email
>
>FROM customers
>
>JOIN sale ON customers.customer_id=sale.customer_id
>
>WHERE sale.movie_id = 4

![zadanie 12](https://user-images.githubusercontent.com/122294284/219366048-41769051-2835-4459-a7f8-42c1ac6c0613.png)


### <a name="kropka3">13. Uzupełnij email klientce Patrycji wpisując: pati@mail.com.</a>

>UPDATE customers
>
>SET email = 'pati@mail.com'
>
>WHERE name LIKE 'Patrycja'

![zadanie 13](https://user-images.githubusercontent.com/122294284/219372141-d53d5bb3-aef8-422e-a059-fa013fd7a278.png)
