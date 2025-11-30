# 🌐 HW1 - Express Router

A Node.js Express server that implements RESTful APIs for Users and Products using Express Router.

## 📋 Task Requirements

Create an Express server that uses Router to manage routes.

**Requirements:**
1.  **Server Setup:**
    - Create a server listening on port 3000 (or environment port).
    - Use `express.json()` for parsing request bodies.

2.  **Router Implementation:**
    - Create a Router for Users (`/api/users`).
    - Create a Router for Products (`/api/products`).

3.  **CRUD Operations:**
    For each Router, implement the following routes:
    - `GET /`: Return all items.
    - `GET /:id`: Return item by ID.
    - `POST /`: Add a new item (receives JSON in body).
    - `PUT /:id`: Update an existing item by ID.
    - `DELETE /:id`: Delete an item by ID.

## 🚀 How to Run

1.  Navigate to the project directory:
    ```bash
    cd getPostPutDel
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Start the server:
    ```bash
    node app.js
    ```

## 🔌 API Endpoints

### Users (`/api/users`)
- `GET /` - Get all users
- `GET /:id` - Get user by ID
- `POST /` - Add new user
- `PUT /:id` - Update user
- `DELETE /:id` - Delete user

### Products (`/api/products`)
- `GET /` - Get all products
- `GET /:id` - Get product by ID
- `POST /` - Add new product
- `PUT /:id` - Update product
- `DELETE /:id` - Delete product

## 👥 Students

- Bshara Karkaby [49-2]
- Moner Makhouly [49-2]

---

**Happy coding!** 💻✨
