# A simple REST API for managing products 

**Version 1.0**

A simple REST API built from the perspective of e-commerce.
Built using PHP Laravel framework and uses MySQL for database. 
It can perform basic CRUD operations of Create Read Update Delete and also has a search functionality.

The API uses Sanctum authentication. A user can login with a name, email and password and a unique token will be provided on logging in, which is destroyed upon logging out.

Following features can be accessed without authorization
~View the list of items on the database
~Search for an item in the database

Following features can only be accessed after authorization with a token
~Creating a new item in the database
~Updating an item on the database
~Removing an item from the database