#  Aeroplane Ticket Booking App

A full-stack flight booking application with a **React** frontend and **Node.js/Express** backend, using **MySQL** for data persistence.

---

##  Features

- Modern **React** frontend with React Router and Bootstrap UI
- RESTful **Express** backend API
- **MySQL** database integration
- Uses **Axios** for HTTP requests
- Concurrent development of frontend and backend using `concurrently`

---

##  Tech Stack

| Layer     | Technologies                                   |
|-----------|------------------------------------------------|
| Frontend  | React, React-Bootstrap, React Router DOM       |
| Backend   | Node.js, Express                               |
| Database  | MySQL                                          |
| Tooling   | Concurrently, Axios, CORS, Chalk               |

---

##  Getting Started

###  Prerequisites

- Node.js (v18+ recommended)
- npm
- MySQL server

---

###  Installation

1. **Clone the repository**
    ```bash
    git clone <your-repo-url>
    cd flight-app
    ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Setup the database**
    - Create a MySQL database (e.g., `flight_booking`)
    - Update your backend database connection settings (host, user, password, database)
  
**Running the Application**
**To run both frontend and backend concurrently:**
```bash
npm run dev
```
**To run only the backend:**
```bash
npm run backend
```
**To run only the frontend:**
```bash
npm run frontend
```
##  Scripts

| Command             | Description                           |
|---------------------|---------------------------------------|
| `npm run dev`       | Runs frontend and backend together    |
| `npm run frontend`  | Runs only the React frontend          |
| `npm run backend`   | Runs only the Node.js backend         |
| `npm test`          | Placeholder test script               |

---

##  Dependencies

- `axios`
- `bootstrap`
- `chalk`
- `concurrently`
- `cors`
- `express`
- `mysql2`
- `react-bootstrap`
- `react-router-dom`

**Project Structure**
```bash
flight-app/
├── backend/         
│   └── server.js
├── frontend/
│   └── react/       
├── package.json
```

**Notes**

- Make sure your MySQL server is running and accessible.
- Update database credentials in the backend config file.
- Use `npm run dev` for a simplified development workflow.

**License**
ISC

**Author**
Lakshay Mittal
