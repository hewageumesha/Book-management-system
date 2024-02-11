# Book Management System

This is a Book Management System based on a tutorial by [freeCodeCamp.org] (https://github.com/AkhilSharma90/Gola...), implemented with Golang and MySQL. This application allows users to manage books by providing CRUD (Create, Read, Update, Delete) operations through a RESTful API.

## Features
- Create a new book
- Get all books
- Get book by id
- Update a book
- Delete a book

## Installation
To install and run this application, follow these steps:

1.Clone this repository to your local machine.

https://github.com/dinethsiriwardana/Book-Management-System-with-Golang-and-Mysql.git
2.Install MySQL and make sure it is running on your machine.

3.Create a new database named **bookstore**.

4.Update the MySQL connection string in the **Connect()** function in the **pkg/config/app.go** file.

5.Build and run the application by executing the following command from the project root directory:

go run cmd/main/main.go
