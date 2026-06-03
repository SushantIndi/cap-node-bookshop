# Welcome to the 1st project attempted by me on SAP BAS(Business Application Studio)

# 📚 SAP CAP Bookshop Backend API

An enterprise-ready backend microservice built using the **SAP Cloud Application Programming Model (CAP)** and Node.js. 

This project transitions standard MERN/Express patterns into a cloud-native database architecture.

---

## 🚀 Key Features

* **Cloud Native:** Developed entirely within SAP Business Application Studio.
* **Declarative Modeling:** Schema definitions built with Core Data Services (CDS).
* **Auto-Routing:** Automated OData V4 REST API endpoint generation.
* **In-Memory Storage:** Instant prototyping using an embedded SQLite engine.
* **Mock Seeding:** Automatic database parsing using native CSV synchronization.

---

## 📂 Project Architecture

* **`db/`** — Database blueprints, tables, and mock CSV datasets.
* **`srv/`** — Core business logic services and endpoint paths.
* **`app/`** — Workspace placeholder for future frontend UI integration.

---

## 🛠️ Tech Stack

* **Runtime:** Node.js
* **Framework:** SAP CAP (@sap/cds)
* **Database:** SQLite (In-Memory)
* **IDE Platform:** SAP Business Application Studio (Linux Container)

---

## 💻 Quick Start

### 1. Initialize the Environment
Open your SAP BAS terminal and clone the repository:
```bash
git clone https://github.com
cd sap-cap-bookshop
npm install
```

### 2. Launch the Development Server
Run the hot-reloading development engine:
```bash
cds watch
```

### 3. Preview the API
The application will launch automatically on your exposed cloud environment:
* **Welcome Dashboard:** `http://localhost:4004`
* **JSON Metadata Service:** `http://localhost:4004/odata/v4/catalog/$metadata`
* **Live Books Endpoint:** `http://localhost:4004/odata/v4/catalog/Books`
*
