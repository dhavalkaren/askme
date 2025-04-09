# 🧠 Quora-Lite Django App

A simple Q&A platform inspired by Quora, built with Django.  
This project allows users to register, ask questions, answer questions, and like answers — with full login/logout functionality.

---

## 🚀 Features

### 🔐 User Authentication
- **Register** as a new user
- **Login** securely
- **Logout** when done

### ❓ Questions
- **Create a question**
- **View all questions** on the homepage

### 💬 Answers
- **Post answers** to questions
- **View answers** for each question
- **Like answers** (only once per user)

---


## ⚙️ Tech Stack

- Python 3.x
- Django 4.x
- SQLite3 (default Django DB)

---

## 🛠️ Setup Instructions (Run Locally)

### 1. Clone the Repository
```bash
git clone https://github.com/dhavalkaren/askme.git
````
```bash
cd askme
``` 
```bash
python -m venv env
```
```bash
source env/bin/activate
```
```bash
pip install -r requirements.txt
```
```bash
python manage.py makemigrations
python manage.py migrate
```
```bash
python manage.py runserver
```
### 2. Visit in Browser
 
Visit http://127.0.0.1:8000/ on your browser.

---