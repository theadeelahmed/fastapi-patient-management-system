# Patient Management System – FastAPI

## 📌 Overview
This is a simple but complete **Patient Management System** built using **FastAPI**, **Pydantic**, and **JSON file storage**.  
The main purpose of this project is to practice real backend development concepts and for better Ai/data engineer, improve API building skills, and understand how CRUD operations work in a real application.

---

## ## 🔧 Technologies Used
- **FastAPI** – for building APIs  
- **Pydantic** – for data validation  
- **JSON** – for storing patient records  
- **Uvicorn** – for running the server  

---

## ## 🩺 Features (CRUD Operations)

### ✔ Create Patient
- New patient added to the JSON file  
- Data validated using Pydantic models  

### ✔ Read Patients
- Get all patients  
- Get a single patient by ID  
- Response returned as structured JSON  

### ✔ Update Patient
- Update fields like name, age, city, email, etc.  
- Input validated before saving  

### ✔ Delete Patient
- Remove patient by ID  
- JSON file auto-updated  

---

## ## 🧠 Pydantic Concepts Used
- Typed fields  
- Optional fields  
- Email validation  
- Field-level validation  
- Model-level validation  
- Serialization for clean API responses  

---

## ## ▶ Running the Project

### Install Dependencies
```
pip install fastapi uvicorn pydantic
```

### Run Server
```
uvicorn main:app --reload
```

### API Documentation
```
http://127.0.0.1:8000/docs
```

---

## 🎯 Purpose
This project is part of my learning journey in:
- Data Science And Ai development  
- FastAPI fundamentals  
- Data validation using Pydantic  
- Working with JSON storage  
- Understanding CRUD patterns  

---

## ⭐ Support
If you find this project helpful, feel free to ⭐ the repo!


