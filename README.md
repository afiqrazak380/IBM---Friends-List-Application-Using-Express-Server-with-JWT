# Friends List App (Express + JWT)

A simple CRUD REST API for managing a friends list, built with Node.js and
Express, secured with JWT-based session authentication.

Part of IBM's **Developing Back-End Apps with Node.js and Express** course.

## Features

- Register/login users (in-memory user store)
- JWT issued on login, stored in an Express session
- Protected `/friends` routes — only accessible once authenticated
- Add, view, and remove friends from your list

## Tech stack

- Node.js / Express
- `jsonwebtoken` for token-based auth
- `express-session` for session storage

## Running locally

```bash
git clone "https://github.com/afiqrazak380/IBM---Friends-List-Application-Using-Express-Server-with-JWT.git"
cd "IBM---Friends-List-Application-Using-Express-Server-with-JWT"
npm install
npm start
```

## What I learned

Hands-on practice implementing authentication middleware from scratch —
checking session tokens before allowing access to protected routes, a
pattern used throughout real-world Express APIs.
