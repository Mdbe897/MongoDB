# 📦 MongoDB Checkpoint

## 📚 Description

This project is part of a MongoDB checkpoint.
The goal is to practice basic **CRUD operations** using MongoDB.

---

## 🛠️ Technologies Used

* MongoDB
* MongoDB Atlas
* MongoDB Compass

---

## 🧱 Database Structure

* **Database Name:** `contact`
* **Collection Name:** `contactlist`

---

## 📥 Inserted Documents

```json
[
  { "lastName": "Ben", "firstName": "Moris", "email": "ben@gmail.com", "age": 26 },
  { "lastName": "Kefi", "firstName": "Seif", "email": "kefi@gmail.com", "age": 15 },
  { "lastName": "Emilie", "firstName": "brouge", "email": "emilie.b@gmail.com", "age": 40 },
  { "lastName": "Alex", "firstName": "brown", "age": 4 },
  { "lastName": "Denzel", "firstName": "Washington", "age": 3 }
]
```

---

## 🔍 Operations Performed

### ✅ Display all contacts

* Used `find()` to retrieve all documents

### ✅ Display one contact by ID

* Used `findOne()` with `_id`

### ✅ Display contacts with age > 18

* Used `$gt` operator

### ✅ Display contacts with age > 18 and name contains "ah"

* Used `$regex` with `$gt`

### ✅ Update contact

* Updated **Kefi Seif → Kefi Anis** using `$set`

### ✅ Delete contacts with age < 5

* Used `$lt` operator with `deleteMany()`

### ✅ Final display

* Verified remaining data with `find()`

---

## 📸 Screenshots

All required screenshots are included in this repository:

* Data insertion
* Queries results
* Update operation
* Delete operation
* Final data

---

## 🚀 How to Run

1. Connect to MongoDB Atlas
2. Open MongoDB Compass
3. Create database and collection
4. Insert documents
5. Run queries as described above

---

## 👨‍💻 Author

* GitHub: https://github.com/Mdbe897

---
