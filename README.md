# student-management-system-Mini Project

created by: Theertha N K
Institution: Entri

Project Overview

This is a simple Student Management System built using Django.
It allows users to add, view, update, and delete student records.
The project uses SQLite as the database and HTML templates without any CSS frameworks.

This mini-project is designed to understand basic CRUD operations and Django fundamentals.


---

## Features

➕ Add a student (name, age, grade)

📋 View all students in a table

✏️ Update student details

❌ Delete a student

📦 SQLite database included

🧩 Simple HTML templates (no Bootstrap/CSS)



---

## Technologies Used

Python 3

Django

SQLite

HTML



---

🚀 How to Run This Project

Follow these steps:

1️⃣ Clone the GitHub repository

git clone https://github.com/imurmi4/student-management-system.git

2️⃣ Go into the project folder

cd student-management-system

3️⃣ Create a virtual environment

python -m venv .venv

4️⃣ Activate the virtual environment

For Windows PowerShell:

.venv\Scripts\Activate.ps1

5️⃣ Install dependencies

pip install django

6️⃣ Run migrations

python manage.py migrate

7️⃣ Start the server

python manage.py runserver

Your project will run at:
👉 http://127.0.0.1:8000/


---

Screenshots
<img width="367" height="503" alt="student_list" src="https://github.com/user-attachments/assets/826ffae2-96a4-47ee-8c83-31910ad6aee2" />

<img width="312" height="271" alt="edit_student" src="https://github.com/user-attachments/assets/62f27869-c9fe-4fdd-a6f8-759680b3d447" />

<img width="329" height="380" alt="add_student" src="https://github.com/user-attachments/assets/8dcae00f-4286-4cdf-b701-efaa6960842f" />



---

📁 Project Structure

student-management-system/
│
├── student_project/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── students/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/students/
│       ├── student_list.html
│       └── add_student.html
│
├── db.sqlite3
├── manage.py
└── README.md
