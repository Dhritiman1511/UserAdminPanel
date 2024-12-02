
# UserAdminPanel

UserAdminPanel is a simple CRUD application for user management. It allows you to add, update, delete, and read user information. The application is built using **Node.js**, **Express**, and **MongoDB**.

---

## Features

- **Create Users**: Add new users to the database.
- **Read Users**: View the list of all users.
- **Update Users**: Modify existing user information.
- **Delete Users**: Remove users from the database.

---

## Tech Stack

- **Backend**: Node.js, Express
- **Database**: MongoDB

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Dhritiman1511/UserAdminPanel.git
   ```

2. Navigate to the project directory:
   ```bash
   cd UserAdminPanel
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `config.env` file in the root directory and add the following:
   ```
   MONGO_URI=your_mongodb_connection_string
   PORT=3000
   ```

5. Start the server:
   ```bash
   npm start
   ```

---

## API Endpoints

### Base URL: `http://localhost:3000`

| Method | Endpoint        | Description             |
|--------|-----------------|-------------------------|
| GET    | `/users`        | Fetch all users         |
| POST   | `/users`        | Create a new user       |
| PUT    | `/users/:id`    | Update a user by ID     |
| DELETE | `/users/:id`    | Delete a user by ID     |

---
## How to Contribute

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature-name"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.