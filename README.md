# Python Inventory Logistics MVP 📦

[![Live Demo](https://img.shields.io/badge/Demo-Live-success)](https://sahananeth.onrender.com/)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Framework-Flask-red.svg)](https://flask.palletsprojects.com/)
[![Database](https://img.shields.io/badge/Database-SQLite-green.svg)]()

A lightweight Minimum Viable Product (MVP) for an automated inventory and logistics request system. Built with Python and Flask, this application allows users to request items and automatically routes those requests to the nearest warehouse with sufficient stock using geographical coordinate calculations.

## 🌐 Live Demo & Hosting

You can view and test the current prototype of this project online. It is currently hosted on Render as a simple dummy example for demonstration purposes:

**Live Site:** [https://sahananeth.onrender.com/](https://sahananeth.onrender.com/)

*(Note: Because this is a prototype deployment, any database changes or data entered may be wiped periodically when the server restarts or deploys a new update.)*

---

## ✨ Key Features

* **Role-Based Access Control:** Separate dashboards and permissions for `Users` and `Admins`.
* **Smart Routing Engine:** Uses the **Haversine formula** to automatically calculate the distance between a user's location (Lat/Long) and available warehouses.
* **Automated Processing:** Checks global inventory, finds the closest facility with enough stock, assigns the request, and calculates an ETA.
* **Instant Database Setup:** Uses SQLite and auto-generates dummy data (users, products, and warehouses) on the first run so you can test it immediately locally.

---

## 🛠️ Tech Stack

* **Backend:** Python 3, Flask
* **Database:** SQLite (via Flask-SQLAlchemy)
* **Frontend:** HTML5, CSS3, Bootstrap 5
* **Hosting:** Render (Cloud Application Platform)

---

## 🚀 Local Installation & Setup

If you want to run or develop the project on your own machine, follow these steps:

### 1. Clone the Repository
```bash
git clone [https://github.com/SupunJayawardana/python_Inventory_mvp.git](https://github.com/SupunJayawardana/python_Inventory_mvp.git)
cd python_Inventory_mvp
