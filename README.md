# Grocery-Management-System
This project builds a Python-based grocery store management system with a three-tier architecture, featuring an HTML front-end, a Flask API backend, and a database layer. It enables functionalities like product management, customer checkout, and inventory tracking—all tied together in a full-stack demonstration

# 🛒 Grocery Store Management System

A full-stack **Grocery Store Management System** built using Python, Flask, HTML/CSS, and SQL. The project follows a **3-tier architecture**:  
- **Frontend** (HTML/CSS) for user interaction  
- **Backend API** using Flask for business logic  
- **Database Layer** for product and customer data management  

---

## 🔧 Features

- 🧺 Add, edit, and delete grocery items  
- 📦 Track inventory levels and stock availability  
- 🧾 Customer checkout with automated billing  
- 🧍‍♂️ Manage customer details  
- 🗂️ Real-time updates to the product list  
- 💾 SQLite database integration

---

## 📁 Project Structure

```

grocery-store-management/
├── static/
│   └── styles.css
├── templates/
│   └── index.html
├── app.py
├── database.py
├── models/
│   └── item\_model.py
├── requirements.txt
└── README.md

````

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/hariom-p02/grocery-store-management.git
cd grocery-store-management
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

### 4. Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🛠️ Tech Stack

* **Frontend**: HTML, CSS
* **Backend**: Flask (Python)
* **Database**: SQLite
* **Templating Engine**: Jinja2

## ⚙️ API Endpoints (Sample)

| Method | Endpoint  | Description            |
| ------ | --------- | ---------------------- |
| GET    | /         | Homepage               |
| POST   | /add-item | Add new grocery item   |
| GET    | /checkout | Generate customer bill |
