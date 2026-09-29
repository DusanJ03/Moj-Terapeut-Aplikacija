# Moj Terapeut — Full-Stack Web Application

![.NET 8](https://img.shields.io/badge/.NET-8.0-purple)
![C#](https://img.shields.io/badge/Language-C%23-blue)
![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb&logoColor=white)
![REST API](https://img.shields.io/badge/Architecture-REST%20API-orange)

A full-stack mental health and practice management web platform designed to streamline therapist discovery, appointment scheduling, and client-practitioner communication. 

Developed as part of the Software Engineering curriculum at the Faculty of Electronic Engineering, University of Niš.

---

## 🔄 System Overview & Core Features

1. **Role-Based Authentication & Workflows:** Distinct dashboards and permissions tailored across 3 user roles: **Clients**, **Therapists**, and **Administrators**.
2. **Appointment Scheduling Engine:** Interactive session booking, calendar availability tracking, and automated appointment status updates.
3. **Profiles & Feedback System:** Detailed therapist practice listings, specialization filtering, client profiles, and verified service reviews.
4. **Decoupled Architecture:** Modular **ASP.NET Core Web API** backend built with controller-service patterns, persisting data to a flexible **MongoDB NoSQL** database.

---

## 🛠️ Tech Stack

* **Backend:** ASP.NET Core (.NET 8), C#, RESTful Web APIs
* **Frontend:** React.js, JavaScript (ES6+), HTML5, CSS3
* **Database:** MongoDB (NoSQL document store)
* **Configuration & Tools:** Genezio, npm, Git / GitHub

---

## 🚀 How to Run Locally

### Prerequisites
* [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
* [Node.js](https://nodejs.org/) (v16+ recommended) and npm
* [MongoDB](https://www.mongodb.com/) instance running locally or via MongoDB Atlas

---

### 1. Backend Setup (.NET Core Web API)
Open a terminal in the root directory:

```bash
# Restore dependencies and build the backend
dotnet restore

# Configure your MongoDB connection string in appsettings.json
# Then start the API server:
dotnet run
```
The REST API will launch and be accessible at https://localhost:port

### 2. Frontend Setup (React SPA)
Open a second terminal window in the root directory:
```bash
# Install frontend dependencies
npm install

# Start the React development server
npm start
```
The web application will open automatically in your browser at http://localhost:3000
