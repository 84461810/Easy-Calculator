Task 4 has been updated: /task/task4
===

<a href="https://github.com/sjtu-rr-homework/Cloud_native_first_attempt">PROJECT LINK</a>
===

# Easy-Calculator
(This is the name of the first homework; it's actually a homework collection)


Course SE418 since March, 2019.

All tasks, homework and projects will be integrated into this repository.

# Homework 2: Use the calculator with Postman
(The AJAX POST method will be turned to GET method automatically and I don't know why, probably due to misuse of Spring Security)

First, start the Spring Application with an IDE (Intellij IDEA is recommended).

Then, create a POST request with the URL:

<code>localhost:8080/calculator/</code>

and set the request body with raw JSON string:

<code>{
    "expression": "12/24"
}</code>

As a result of the example request, "0.5" will be returned in response.

Of course, the content of expression can be any expression you want to calculate.

Enjoy :)
=======
