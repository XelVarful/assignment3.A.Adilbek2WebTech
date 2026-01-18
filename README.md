# Assignment 3: Book Management System 

##  Project Description
This is my third assignment where I migrated my backend from a simple `data.json` file to a real cloud database — **MongoDB Atlas**. I chose a "Book Management System" as my topic because it fits my Final Project idea. 

The goal of this project was to handle complex object schemas, set up data persistence in the cloud, and build a clean UI to interact with the database.


##  Tech Stack
* **Backend**: Node.js, Express.js
* **Database**: MongoDB Atlas (with Mongoose ODM)
* **Frontend**: HTML5, CSS3
* **Testing**: Postman

##  Database Schema
[cite_start]My `Book` object consists of[cite: 8, 9, 10]:
- `title`: String (Required)
- `author`: String (Required)
- `genre`: String (Required)


##  API Endpoints
| Method | Endpoint | Description | Status Code |
|--------|----------|-------------|-------------|
| POST | `/books` | Add a new book | 201 Created |
| GET | `/books` | Get all books | 200 OK |
| GET | `/books/:id`| Get one book by ID | 200 / 404 |
| PUT | `/books/:id`| Update book info | 200 OK |
| DELETE | `/books/:id`| Delete a book | 200 OK |

## How to run
Run the server: `node server.js`
Open `http://localhost:3000` in your browser.

## Screen site mongodb atlas and postman(1 delete)

<img width="1470" height="875" alt="Снимок экрана 2026-01-18 в 15 35 48" src="https://github.com/user-attachments/assets/290ba9b4-63b0-46c9-ad72-a2eda7cbc71d" />

<img width="1470" height="877" alt="Снимок экрана 2026-01-18 в 15 36 03" src="https://github.com/user-attachments/assets/5238ae8c-cd0e-40f3-bbf0-3432721ef969" />

<img width="1470" height="921" alt="Снимок экрана 2026-01-18 в 15 36 19" src="https://github.com/user-attachments/assets/95f9e80f-327c-4c17-a38a-aed4162f45ea" />

