Book Management System
This is a Book Management System based on a tutorial by freeCodeCamp.org, implemented with Golang and MySQL. This application allows users to manage books by providing CRUD (Create, Read, Update, Delete) operations through a RESTful API.

[IMAGE ALT TEXT HERE
](https://youtu.be/jFfo23yIWac?si=9_E6wFszgf4CzqX7)

Features
•	Create a new book
•	Get all books
•	Get book by id
•	Update a book
•	Delete a book

Installation
To install and run this application, follow these steps:

1.	Clone this repository to your local machine.
         https://github.com/hewageumesha/Book-management-system.git
2.	Install MySQL and make sure it is running on your machine.

3.	Create a new database named bookstore.

4.	Update the MySQL connection string in the Connect() function in the pkg/config/app.go file.

5.	Build and run the application by executing the following command from the project root directory:
        go run cmd/main/main.go

Usage
Once the application is running, you can perform CRUD operations on books by sending HTTP requests to the following endpoints:

Endpoint	          Method		    Description
/api/book	          GET		        Get all books
/api/book/:id	      GET		        Get book by id
/api/book	          POST		      Create a new book
/api/book/:id	      PUT		        Update a book
/api/book/:id	      DELETE		    Delete a book

You can use tools like Postman or cURL to send HTTP requests to the endpoints.

File Structure
book-management-system/
├── cmd/
│   └── main/
│       └── main.go
└── pkg/
    ├── config/
    │   └── app.go
    ├── models/
    │   └── book.go
    ├── controllers/
    │   └── book-controller.go
    ├── routes/
    │   └── bookstore-routes.go
    └── utils/
        └── utils.go
