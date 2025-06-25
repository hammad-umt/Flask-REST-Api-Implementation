# 📝 Flask REST API - ToDo App

This is a simple RESTful API built with **Flask** that manages a basic to-do list using in-memory storage.

---

## 🧪 Curl Commands to Test 

### ➕ To Add a New Task
```bash
curl -X POST http://localhost:5000/add_todo \
     -H "Content-Type: application/json" \
     -d "{\"task\":\"Complete Your Homework\"}"
