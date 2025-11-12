# 💻 SQL Interface

A **web-based SQL query execution interface** built with React, Node.js, Express, and Microsoft SQL Server.  
This project allows users to execute SQL queries directly from the frontend, with the backend securely processing the query and returning results from the connected database.  
It’s a simple yet powerful tool for interacting with databases without needing a separate SQL client.

---

## 🚀 Features

- Execute any valid SQL query directly from the browser.
- View query results instantly on the frontend.
- Supports **SELECT, INSERT, UPDATE, DELETE**, and other standard SQL operations.
- Backend securely handles queries using Sequelize ORM.
- User-friendly and minimal UI for running and testing SQL commands.
- Handles error responses gracefully (e.g., syntax or permission errors).

---

## 🧠 Tech Stack

**Frontend:** React.js  
**Backend:** Node.js, Express.js  
**Database:** Microsoft SQL Server (MSSQL)  
**ORM:** Sequelize ORM  

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   
   ```bash
   git clone https://github.com/Dev-Garg-1/SQL-Interface.git
   cd SQL-Interface

2. **Install Dependencies**
   
   ```bash
   # For backend
   cd backend
   npm install

   # For frontend
   cd ../frontend
   npm install
   
3. **Configure environment variables**
   
    Create a .env file in the backend folder and include:
     ```bash
     DATABASE_NAME=
     DATABASE_USERNAME=
     PASSWORD=
     SERVER_HOSTNAME=
    ```
  
    Create a .env file in the frontend folder and include:
     ```bash
     VITE_BACKEND_URL=
     ```

4. **Run the development servers**

    ```bash
    # Backend
    npm run dev
    
    # Frontend
    npm run dev
    ```
