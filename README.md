 # User REST API

A RESTful CRUD API built with Node.js, Express.js and MongoDB.

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv
- cors

## Features
- Create a user
- Get all users
- Get a single user by ID
- Update a user
- Delete a user

## API Routes

| Method | Route | Description |
|--------|-------|-------------|
| GET | /api/users | Get all users |
| GET | /api/users/:id | Get one user |
| POST | /api/users | Create a user |
| PUT | /api/users/:id | Update a user |
| DELETE | /api/users/:id | Delete a user |

## How to Run Locally

1. Clone the repo
2. Run `npm install`
3. Add `.env` file with `PORT` and `MONGO_URI`
4. Run `nodemon server.js`
5. Test with Postman
```
