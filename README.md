# dojos_and_ninjas
***Code Dojo core assignment*** using MySQL Workbench to forward engineer a schema. Then using sql commands to insert, delete, and update queries in the database.

##
I admit I could not find a better way to retrieve the dojo that the last instance of ninja is connected to.

``` SQL
SELECT * FROM ninjas
WHERE dojos.id=1;

SELECT * FROM ninjas
WHERE dojos.id=3;
```
