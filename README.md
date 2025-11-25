# Book Store API (Learning Project)
This is a simple Book Store API built using Gorilla Mux in Go.
The project is created only for learning purposes to understand routing, handlers, and building basic REST APIs in Go.
No database is used, all data is stored in-memory.

## What This Project Teaches?
- How to build a basic REST API in Go
- How to use Gorilla Mux for routing
- How to create handlers and models
- How to work with JSON requests and responses
- How to store data in-memory using slices

## Tech Used:
- Go (Golang)
- Gorilla Mux Router
- No database (data stored in Go slice)Book Store API (Learning Project)

  ## API Endpoints
| Method | Endpoint      | Description      |
| ------ | ------------- | ---------------- |
| GET    | `/book`      | Get all books    |
| GET    | `/book/{id}` | Get a book by ID |
| POST   | `/book`      | Add a book       |
| PUT    | `/book/{id}` | Update a book    |
| DELETE | `/book/{id}` | Delete a book    |
