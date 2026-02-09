# 📝 Django User Registration Form

A clean and responsive **User Registration Web Application** built using **Django**, **HTML**, **CSS**, and **Bootstrap**.  
The application allows users to fill out a detailed registration form, and the submitted data can be viewed and managed from the **Django Admin Panel**.

---

## 🚀 Features

- 👤 User Registration Form
- 📧 Email & Password validation
- 🧑 Gender selection
- 🎯 Multiple hobbies selection
- 💼 Source of income dropdown
- 💰 Income range slider
- 🖼️ Profile picture upload
- 🎂 Age field
- 📝 Bio section
- 🔐 Django Admin integration to view submitted data
- 🗄️ SQLite database support (default Django DB)

---

## 🖼️ Screenshot

### 🏠 User Registration Page

Displays a complete user registration form with all required fields.

<img width="1340" height="633" alt="Registration Form" src="https://github.com/user-attachments/assets/eb6c6013-05ed-4aa6-afa8-3739131b21a0" />

---

## 🛠️ Tech Stack

### Backend
- Python
- Django

### Frontend
- HTML5
- CSS3
- Bootstrap

### Database
- SQLite3 (Default Django database)

---

## 📂 Project Structure

```text
DJANGO-LOGIN-FORM/
│
├── DJANGO/              # Main Django project folder (settings, urls, wsgi)
│
├── accounts/            # App handling models, views, admin registration
│
├── templates/
│   └── index.html       # User registration form template
│
├── manage.py            # Django project management script
├── requirements.txt     # Project dependencies
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/code2Renovate/Django-login-form.git
cd Django-login-form
```

### 2️⃣ Create a virtual environment
```bash
python -m venv venv
```

### 3️⃣ Activate the virtual environment
- Windows
```bash
venv\Scripts\activate
```
- Mac / Linux
```bash
source venv/bin/activate
```

### 4️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 5️⃣ Apply migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
 
### 6️⃣ Create Superuser (For Admin Access)
```bash
python manage.py createsuperuser
```
Follow the prompts and create your admin credentials.

### 7️⃣ Run the development server
```bash
python manage.py runserver
```

### 8️⃣ Open your browser and visit:
- Homepage:
```bash
http://127.0.0.1:8000/
```
- Admin Panel:
```bash
http://127.0.0.1:8000/admin/
```
