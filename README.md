# Bookmarks #
_____________

## User Stories ##


```
    As a user
    So I can quickly access websites I have visited
    I want to see a list of saved urls
```  
```
    As a user   
    So I can visit a site I like again  
    I want to save it so it can be accessed   
```  
```    
    As a user   
    So I organise my favourite sites   
    I want to add tags to their bookmarks  
```
```    
    As a user   
    So I can easily access sites   
    I want to be able to search bookmarks by tags
```
__________

## CRUD ##

- Create
- Read
- Update
- Delete

## SQL ##

- SQL -> Structured Query Language
- A high-level language allowing you to access and maintain data stored in a relational database.

## CRUD -> SQL ##

- Create -> INSERT
  - eg. INSERT INTO *table_name* (*column_name1*) VALUES ("*value1*");
- Read -> SELECT
  - eg. SELECT \* FROM *table_name*

        id |  name
        ----+--------
        1 | James Dix
        (1 row)

- Update -> UPDATE
  - eg. UPDATE *table_name* SET *column_name1* = "*new_value*" WHERE *column_name1* = "*old_value*";

        id |      name
        ----+-----------------
        1 | Courtney Osborn
        (1 row)

- Delete -> DELETE
  - eg. DELETE FROM *table_name* WHERE *column_name1* = "*value*";

        id | name
        ----+------
        (0 rows)
