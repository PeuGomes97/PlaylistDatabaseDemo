### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

Is a Open Relational Database Manage System to store information as tables format

- What is the difference between SQL and PostgreSQL?

SQL is the language used to manage databases while PostgreSQL is a specific implementation of a relational database management system (RDBMS) that supports SQL and offers additional features.

- In `psql`, how do you connect to a database?

\c database

- What is the difference between `HAVING` and `WHERE`?

Having is for groups of data Where applies to individual rows.

- What is the difference between an `INNER` and `OUTER` join?

INNER join is "the middle" join. Catchs the occurrencies in both tables. OUTER join returns all records from at least one of the tables, combining related records when possible.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

 In a LEFT OUTER join, all records from the left table are returned, whereas in a RIGHT OUTER join, all records from the right table are returned.

- What is an ORM? What do they do?

Object-Relational Mapping is a technique that maps objects in code to tables in a database, facilitating interaction between programming languages and relational databases.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

  AJAX allows asynchronous requests from the client-side, while using a library like requests on the server performs synchronous requests to other servers

- What is CSRF? What is the purpose of the CSRF token?

Cross-Site Request Forgery is an attack where a malicious site performs unauthorized actions on a site where the user is authenticated. The CSRF token is used to validate and protect against these attacks, ensuring the request is legitimate

- What is the purpose of `form.hidden_tag()`?

It's used in web forms with Flask to generate a hidden HTML field containing a CSRF security token, safeguarding forms against CSRF attacks.
