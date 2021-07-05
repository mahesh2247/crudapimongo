# crudapimongo
A Simple Flask Web API demonstarting CRUD Operations using Postman with MongoDB as backend.

Clone the repo , pip install flask_pymongo dependency for MongoDB , Create a cluster with database name as Users=>user(collection name)
Example URI String: app.config["MONGO_URI"] = "mongodb://localhost:27017/Users"

API Served at:

  http://127.0.0.1:5000/add
  
  http://127.0.0.1:5000/users
  
  http://127.0.0.1:5000/user/id
  
  http://127.0.0.1:5000/delete/id
  
  http://127.0.0.1:5000/update/id
  

