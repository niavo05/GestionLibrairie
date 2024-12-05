# Library Management API

This project contains the OpenAPI specification for managing books and authors in a library system.  

---


### Endpoints
#### Books
- **GET /books**  
  Retrieve a list of books with optional filters:  
  - `bookName` (string)  
  - `releaseDate` (date interval: `startDate` and `endDate`)  

- **POST /books**  
  Add a new book.  

- **PUT /books**  
  Update an existing book. This is an idempotent operation.  

- **DELETE /books**  
  Delete a book by its ID.  

#### Authors
- **GET /authors**  
  Retrieve a list of authors with an optional filter:  
  - `authorName` (string)  

- **POST /authors**  
  Add a new author.  

- **PUT /authors**  
  Update an existing author. This is an idempotent operation.  

- **DELETE /authors**  
  Delete an author by their ID.
