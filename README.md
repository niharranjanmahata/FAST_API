# FastAPI E-Commerce API 🚀

A simple and scalable **E-Commerce REST API** built with **FastAPI** and **Pydantic**.  
This project demonstrates CRUD operations, request validation, JSON-based data storage, environment configuration, and a clean project structure.

## ✨ Features

- 🚀 FastAPI REST API
- 📦 Product management
- ➕ Create products
- 📋 Get all products
- 🔍 Get product by ID
- ✏️ Update product
- 🗑️ Delete product
- ✅ Request validation using Pydantic
- 🔐 Environment variable configuration
- 📄 JSON-based data storage
- 🧩 Modular project structure
- 📚 Automatic API documentation with Swagger UI

## 🛠️ Technologies Used

- **Python**
- **FastAPI**
- **Pydantic**
- **Uvicorn**
- **JSON**
- **Python-dotenv**


## API Architecture
Client
  │
  ▼
FastAPI Router
  │
  ▼
Pydantic Schema
  │
  ▼
Service Layer
  │
  ▼
Data Storage
  │
  ▼
JSON Database

##  Run The Server
uvicorn app.main:app --reload
