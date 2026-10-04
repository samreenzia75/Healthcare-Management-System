# 🏥 CarePortal - Healthcare Management System

An enterprise-grade **Healthcare Management System (HMS)** designed to streamline hospital administrative workflows, patient tracking, doctor-patient admissions, and operational resource management.

---

## 🚀 Project Overview & Architecture

CarePortal bridges the gap between front-end user interactions and back-end database operations, providing real-time data sync for hospital staff. 

* **Frontend:** Built with **React.js** featuring a modern, responsive dashboard interface (Overview Dashboard, Patients Registry, Admission Logs, and Clinical Support Helpdesk).
* **Backend:** Powered by **Node.js** and **Express.js**, handling RESTful routing, CORS integration, and robust database middleware.
* **Database:** Connects with **Microsoft SQL Server (MSSQL)** utilizing optimized connection pooling (`mssql` package) for high-speed query handling and data persistence.

---

## 📂 Project Structure & File Manifest

| File Name | Description |
| :--- | :--- |
| `db.js` | Configures the SQL Server connection pool (`sa` user credentials, server connection options, and error handling). |
| `server.js` | Main backend entry point handling HTTP routes (`/patients`, `/dropdowns`, `/admissions`) and database execution. |
| `App.js` | Core React frontend component managing UI layouts, multi-tab navigation, form states, and live dashboard metrics. |
| `package.json` | Contains project metadata and lists core dependencies (`express`, `mssql`, `cors`, `nodemon`). |

---

## ⚙️ Prerequisites & Tech Stack

* **Node.js** (v14+ recommended)
* **Microsoft SQL Server (SQL Server Management Studio / SQLEXPRESS)**
* **npm** (Node Package Manager)

---

## 🛠️ Installation & Setup Instructions

### 1. Clone the Repository & Install Dependencies
Navigate to your project root folder and install the required packages for both the server and client components:
```bash
npm install express mssql cors nodemon

---

## 🛠️ Installation & Setup Instructions

### 1. Clone the Repository & Install Dependencies
Navigate to your project root folder and install the required packages for both the server and client components:
```bash
npm install express mssql cors nodemon

```

### 2. Configure Database Connection

Verify your SQL Server configuration parameters inside **`db.js`**:

* **Server:** `127.0.0.1` (Instance: `SQLEXPRESS`)


* **User:** `sa`

* **Database:** `Healthcare Management System`


### 3. Run the Backend Server

Start the high-speed optimized backend API on port `5000`:

```bash
node server.js
# Or using nodemon for live reloading:
npx nodemon server.js

```

You should see the console message: `🚀 High-Speed Optimized Backend Running on Port 5000`.

### 4. Run the React Frontend

Start your React development application to launch the user interface dashboard.

---

## 🌟 Key Features

* **Overview Dashboard:** Live analytical counters tracking Total Patients, Total Doctors, and Active Admissions.


* **Patients Registry:** Register new patient profiles, filter records via real-time search, and manage or delete existing patient logs.


* **Admission Logs:** Centralized forms to assign doctors, hospitals, insurance providers, medical conditions, billing amounts, and room numbers.


* **Clinical Support Desk:** Emergency hotlines, superintendent contacts, interactive operational FAQs, and an incident coordination alert form.



---

## 👩‍💻 Author

**Samreen Zia**

```

```
