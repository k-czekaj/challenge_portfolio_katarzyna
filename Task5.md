# 馃殌 **Task 5** 馃殌

**:pushpin: SPIS TRE艢CI:**
1. [Subtask 1 - Kr贸tki kurs podstaw SQL, lista operator贸w](#subtask1)
2. [Subtask 3 - Kilka zada艅 zwi膮zanych z SQL'em](#subtask3)
    - [Zad. 1. Wy艣wietl tabel臋 actors w kolejno艣ci alfabetycznej sortuj膮c po kolumnie surname.](#kropka1)
    - [Zad. 2. Wy艣wietl film, kt贸ry powsta艂 w 2019 roku.](#kropka2)
    - [Zad. 3. Wy艣wietl wszystkie filmy, kt贸re powsta艂y mi臋dzy 1900, a 1999 rokiem.](#kropka3)
    - [Zad. 4. Wy艣wietl JEDYNIE tytu艂 i cen臋 film贸w, kt贸re kosztuj膮 poni偶ej 7$.](#kropka4)
    - [Zad. 5. U偶yj operatora logicznego AND, aby wy艣wietli膰 aktor贸w o actor_id pomi臋dzy 4-7 (4 i 7 powinny si臋 wy艣wietla膰). NIE U呕YWAJ operatora BETWEEN.](#kropka5)
    - [Zad. 6. Wy艣wietl klient贸w o id 2,4,6 wykorzystaj do tego warunek logiczny.](#kropka6)
    - [Zad. 7. Wy艣wietl klient贸w o id 1,3,5 wykorzystaj do tego operator IN.](#kropka7)
    - [Zad. 8. Wy艣wietl dane wszystkich os贸b z tabeli 鈥榓ctors鈥?, kt贸rych imi臋 zaczyna si臋 od ci膮gu 鈥淎n鈥?.](#kropka8)
    - [Zad. 9. Wy艣wietl dane klienta, kt贸ry nie ma podanego adresu email.](#kropka9)
    - [Zad. 10. Wy艣wietl wszystkie filmy, kt贸rych cena wynosi powy偶ej 9$ oraz ich ID mie艣ci si臋 pomi臋dzy 2 i 8 movie_id.](#kropka10)


## <a name="subtask1">Subtask 1 - Kr贸tki kurs podstaw SQL</a>

### 馃憞 Operatory/zapytania, jakich si臋 nauczy艂am 馃憞

|USE *AdventureWorks2014*<br/>GO|SELECT * <br/>FROM *Person.Person*|SELECT *Name, Color, Size* <br/>FROM *Production.Product*|SELECT *ProductID* AS *ID* <br/>FROM *Production.Product*|
|:- |:- |:- |:- |
|SELECT * <br/>FROM *Production.Product*<br/>ORDER BY *Name*|SELECT * <br/>FROM *Production.Product*<br/>ORDER BY *Color* DESC|SELECT *ProductID* <br/>FROM *Production.Product* <br/>WHERE *ProductID = 707*|SELECT *ProductID, Name, Color* <br/>FROM *Production.Product*<br/>WHERE *ProductID* > *100*|
|SELECT *ProductID* <br/>FROM *Production.Product*<br/>WHERE *ProductID* BETWEEN *13* AND *360*|SELECT *Color* <br/>FROM *Production.Product*<br/>WHERE *Color = 'Red'*|SELECT * <br/>FROM *Production.Product*<br/>WHERE *Name* LIKE *'B%'*|SELECT * <br/>FROM *Production.Product*<br/>WHERE *Name* LIKE *'%Bike%'*|
|SELECT * <br/>FROM *Production.Product*<br/>WHERE *Name* LIKE *'Mountain Bike Socks, _'*|SELECT *Name, Color, Size* <br/>FROM *Production.Product*<br/>WHERE *Color = 'Black'* AND *Size = 'M'*|SELECT *ProductID, Name, Color* <br/>FROM *Production.Product*<br/>WHERE *Color = 'Black'* OR *Color = 'Silver'* OR *Color = 'Blue'*|SELECT * <br/>FROM *Production.Product* <br/>WHERE *Name* LIKE *'%Bike%'* AND *Color = 'White'*|
|SELECT * FROM *Production.Product*<br/>WHERE *Color* IS NULL|SELECT * FROM *Production.Product*<br/>WHERE *Color* IS NOT NULL|SELECT GETDATE() AS *CurrentDateTime*|SELECT DATEDIFF(MONTH, '20190801', '20201201')|
SELECT DATEDIFF(HOUR, '20190801 12:15', '20190801 15:15')|SELECT *ProductID,* UPPER(Name) AS *Name*<br/>FROM *Production.Product*|SELECT COUNT(*) AS *FnCount* FROM *Production.Product*|SELECT *ProductID, Name, Color* AS *Kolor,* <br/>DATEDIFF(DAY, SellStartDate, GETDATE())<br/>FROM *Production.Product*|
|SELECT SUM(ListPrice) AS *FnSum* FROM *Production.Product*|SELECT MIN(ListPrice) AS *FnMIN* FROM *Production.Product*|SELECT *Color,* COUNT(*) AS *Cnt*<br/>FROM *Production.Product*<br/>GROUP BY *Color*|SELECT *ProductID, p.Name, ps.Name, p.ProductSubcategoryID, ps.ProductSubcategoryID*<br/>FROM *Production.Product* AS *p*<br/>JOIN *Production.ProductSubcategory* AS *ps* ON *p.ProductSubcategoryID = ps.ProductSubcategoryID*|


##  <a name="subtask3">Subtask 3 - Kilka zada艅 zwi膮zanych z SQLem 馃懇鈥嶐煉? </a>
### <a name="kropka1"><p align="justify">1. Wy艣wietl tabel臋 actors w kolejno艣ci alfabetycznej sortuj膮c po kolumnie surname.</p></a>

```sql
SELECT * FROM actors
ORDER BY surname
```

![zadanie 1](https://user-images.githubusercontent.com/122294284/218320541-a5f2d476-46e7-4afd-933a-92a171581fe0.png)


### <a name="kropka2"><p align="justify">2. Wy艣wietl film, kt贸ry powsta艂 w 2019 roku.</p></a>

```sql
SELECT * FROM movies
WHERE year_of_production = '2019'
```

![zadanie 2](https://user-images.githubusercontent.com/122294284/218320785-2ea7f22d-35ff-4764-8fa0-8bbde0992fc4.png)


### <a name="kropka3"><p align="justify">3. Wy艣wietl wszystkie filmy, kt贸re powsta艂y mi臋dzy 1900, a 1999 rokiem.</p></a>

```sql
SELECT * FROM movies
WHERE year_of_production BETWEEN '1900' AND '1999'
```

![zadanie 3](https://user-images.githubusercontent.com/122294284/218321022-40aa15de-554f-4734-8153-f86be6b8f01e.png)


### <a name="kropka4"><p align="justify">4. Wy艣wietl JEDYNIE tytu艂 i cen臋 film贸w, kt贸re kosztuj膮 poni偶ej 7$.</p></a>

```sql
SELECT title, price FROM movies
WHERE price <7
```

![zadanie 4](https://user-images.githubusercontent.com/122294284/218321234-845bb2a8-944d-471f-a6b8-e1afc4357ad8.png)


### <a name="kropka5"><p align="justify">5. U偶yj operatora logicznego AND, aby wy艣wietli膰 aktor贸w o actor_id pomi臋dzy 4-7 (4 i 7 powinny si臋 wy艣wietla膰). NIE U呕YWAJ operatora BETWEEN.</p></a>

```sql
SELECT * FROM actors
WHERE actor_id >=4 AND actor_id <=7
```

![zadanie 5](https://user-images.githubusercontent.com/122294284/218321483-db6e822f-c533-41db-956f-bb18e04d3a03.png)


### <a name="kropka6"><p align="justify">6. Wy艣wietl klient贸w o id 2,4,6 wykorzystaj do tego warunek logiczny.</p></a>

```sql
SELECT * FROM customers
WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6
```

![zadanie 6](https://user-images.githubusercontent.com/122294284/218322384-475bb109-ca9c-43eb-af24-0c73630dc52c.png)


### <a name="kropka7"><p align="justify">7. Wy艣wietl klient贸w o id 1,3,5 wykorzystaj do tego operator IN.</p></a>

```sql
SELECT * FROM customers
WHERE customer_id IN (1, 3, 5)
```

![zadanie 7](https://user-images.githubusercontent.com/122294284/218322577-9e4203a4-6aca-4da6-86ac-80ddb32f58b0.png)


### <a name="kropka8"><p align="justify">8. Wy艣wietl dane wszystkich os贸b z tabeli 鈥榓ctors鈥?, kt贸rych imi臋 zaczyna si臋 od ci膮gu 鈥淎n鈥?.</p></a>

```sql
SELECT * FROM actors
WHERE name LIKE 'An%'
```

![zadanie 8](https://user-images.githubusercontent.com/122294284/218322887-30f5ea34-a6c4-41d8-8312-dfcab7ac3db6.png)

### <a name="kropka9"><p align="justify">9. Wy艣wietl dane klienta, kt贸ry nie ma podanego adresu email.</p></a>

```sql
SELECT * FROM customers
WHERE email IS NULL
```

![zadanie 9](https://user-images.githubusercontent.com/122294284/218323052-49ee9aa7-0f8f-4d2d-a85c-9c0b71bba102.png)

### <a name="kropka10"><p align="justify">10. Wy艣wietl wszystkie filmy, kt贸rych cena wynosi powy偶ej 9$ oraz ich ID mie艣ci si臋 pomi臋dzy 2 i 8 movie_id.</p></a>

```sql
SELECT * FROM movies
WHERE price >9 AND movie_id BETWEEN 2 AND 8
```

![zadanie 10](https://user-images.githubusercontent.com/122294284/218323337-d21a4f44-d731-4194-8e60-1e6ec6bf329c.png)






