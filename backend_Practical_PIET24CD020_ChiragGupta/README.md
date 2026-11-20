# Backend Exam

**Name:** Chirag Gupta
**Reg No:** PIET24CD020

## Task 1 - Library Book Management API (A1.js)
REST API using Node.js, Express and MongoDB (Mongoose) with CRUD on books.
Runs on port 3000.

| Method | Route | Description |
|--------|-------|-------------|
| POST | /books | Add a book |
| GET | /books | Get all books |
| GET | /books/:id | Get one book |
| PUT | /books/:id | Update a book |
| DELETE | /books/:id | Delete a book |

## Task 2 - Student Portal with Login (A2.js)
Register, login with JWT, protected routes and basic security (helmet, cors, rate limit).
Runs on port 4000.

| Method | Route | Access |
|--------|-------|--------|
| POST | /register | Public |
| POST | /login | Public |
| GET | /profile | Logged-in user |
| GET | /students | Admin only |

## How to run
1. `npm install`
2. Make sure MongoDB is running and `.env` is set
3. `node file/A1.js` for Task 1
4. `node file/A2.js` for Task 2

## Outputs
Screenshots are in the `outputs` folder (A1.png, A2.png).
