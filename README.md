# 🧪 Besmoke Inventory Tracker

This project is a full-stack inventory tracking system designed as a take-home assignment for Bio X Cell. It helps track and manage the stock of scientific products, with clear visualization for low inventory.

---

## 🚀 Tech Stack

- **Frontend**: React.js, Axios, Bootstrap
- **Backend**: ASP.NET Core Web API (C#)
- **Database**: SQL Server (LocalDB)
- **ORM**: Entity Framework Core
- **API Documentation**: Swagger

---

## 📸 Features

- 📦 View a full list of scientific products
- 📊 Inventory Report with live quantities
- 🟥 Low inventory (less than 50) highlighted in red
- 🔁 Backend-frontend integration using REST APIs
- ✅ Clean, responsive user interface
- 🌐 Swagger API testing and demo

---

## 🧰 Project Structure

```
BesmokeInventory/
├── BesmokeInventoryAPI/      # Backend .NET Core API
├── client/                   # Frontend React App
├── README.md                 # Project overview
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 🔧 Backend Setup (.NET Core API)

1. Open `BesmokeInventory.sln` in Visual Studio
2. Update database:
   - Open **Package Manager Console**
   - Run:
     ```
     Update-Database
     ```
3. Run the project (F5)
4. Verify Swagger is live at:
   ```
   http://localhost:5192/swagger
   ```

---

### 🌐 Frontend Setup (React)

1. Open terminal and go to frontend folder:
   ```
   cd client
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Start React app:
   ```
   npm start
   ```
4. Access app at:
   ```
   http://localhost:3000
   ```

---

## 🧪 API Endpoints (via Swagger)

| Method | Endpoint                  | Description                      |
|--------|---------------------------|----------------------------------|
| GET    | `/api/products`           | Get all products                 |
| POST   | `/api/products`           | Add a new product                |
| GET    | `/api/inventory/report`   | Get current inventory report     |
| POST   | `/api/inventory/update`   | Add/subtract product inventory   |

---

## ✅ Test Cases Performed

- Product list loads on page open
- Inventory report reflects backend quantities
- Added new products through API
- Inventory updates reflected in UI
- Rows show red for inventory < 50
- All APIs tested via Swagger
- UI tested for responsiveness

---

## 👤 Author

**Anjali**  
Software Engineer – Full Stack  
Bio X Cell Assignment  
April 2025