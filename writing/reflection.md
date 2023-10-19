# Activity 07

## Title

Using Joins to find errors

### Name

Tuguldurnemekh Gantulga
---

#### Q1

A mistake was made where a name was substituted for another. Use a `left join` in a query of one table over the other to locate the two conflicting names. Inspect the output of your query to determine the switch-up. Please note: part of the solution to this challenge question is the query itself.

* Your query code:

``` SQL
SELECT c.name 
FROM clients c
LEFT JOIN suppliers s ON c.name = s.name
WHERE s.name IS NULL;

```

* What is the conflicting name that appears in one table and not the other?

Name: Curran Evans

#### Q2

Reverse your query from above to complete a `right join` to find the name. Please note: part of the solution to this challenge question is the query itself.

* Your query code:

``` SQL
SELECT s.name 
FROM suppliers s
LEFT JOIN clients c ON s.name = c.name
WHERE c.name IS NULL;

```

* What is the conflicting name that appears in one table and not the other?

Name: Raymond Pratt

#### Q3

Another error was made but this time a telephone number was incorrectly entered. This means that one telephone number for the same person is different in one table. Use joins to determine a `left join` to locate the name of the person who is associated with this conflicting telephone number.

* Your query code:

``` SQL
SELECT c.name 
FROM clients c
LEFT JOIN suppliers s ON c.name = s.name AND c.telephone != s.telephone
WHERE s.telephone IS NOT NULL;

```

* What is the conflicting name that appears in one table and not the other?

Name: Ignatius Chaney

#### Q4

Reverse your query from above to complete a `right join` to locate the name of the other person who is associated with a conflicting telephone number.

* Your query code:

``` SQL
SELECT s.name 
FROM suppliers s
LEFT JOIN clients c ON s.name = c.name AND s.telephone != c.telephone
WHERE c.telephone IS NOT NULL;

```

* What is the conflicting name that appears in one table and not the other?

Name: Abigael Neal
---

Did you remember to place your name to the top of this file?
