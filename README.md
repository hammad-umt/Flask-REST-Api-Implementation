# 📝 Flask REST API - ToDo App

This is a simple RESTful API built with **Flask** that manages a basic to-do list using in-memory storage.

### 📌 We've Got the Following Methods:

1. ➕ **Add a Todo** – `POST` Method  
   Endpoint: `/add_todo`

2. 📋 **Get All Todos** – `GET` Method  
   Endpoint: `/get_todos`

3. 🔍 **Get Todo by ID** – `GET` Method  
   Endpoint: `/get_todo/<id>`

4. ✏️ **Update Todo by ID** – `PUT` Method  
   Endpoint: `/update_todo/<id>`

5. ❌ **Delete Todo by ID** – `DELETE` Method  
   Endpoint: `/delete_todo/<id>`

## 🧪 Curl Commands to Test 

### ➕ To Add a New Task
```bash
curl -X POST http://localhost:5000/add_todo \
     -H "Content-Type: application/json" \
     -d "{\"task\":\"Complete Your Homework\"}"
```
### 📋 To Get All Todos
```bash
curl http://localhost:5000/get_todos
```
### 🔍 To Get Todo by ID
```bash
curl http://localhost:5000/get_todo/1
```
### ✏️ To Update Todo by ID
```bash
curl -X PUT http://localhost:5000/update_todo/1 \
     -H "Content-Type: application/json" \
     -d "{\"task\":\"Updated Task Name\"}"
```
### ❌ To Delete Todo by ID
```bash
curl -X DELETE http://localhost:5000/delete_todo/1
```
