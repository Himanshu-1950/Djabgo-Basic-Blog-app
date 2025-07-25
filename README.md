
# 📝 Blog App — Django Project

A basic blog application built using Django. This project allows users to register, log in, and view blog posts.

---

## 📁 Project Structure

```
blog_project/
├── blog/                # Django app
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── views.py
│   ├── urls.py
│   └── models.py
├── blog_project/        # Main project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
└── manage.py
```

---

## 🚀 Features

- User registration & login
- Blog home page
- Blog detail view
- Responsive frontend using Bootstrap
- Secure form handling with CSRF protection

---

## ⚙️ Requirements

- Python 3.8+
- Django 4.0+
- pip

---

## 🛠️ Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/blog-app.git
   cd blog-app
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv env
   source env/bin/activate     # Linux/macOS
   env\Scripts\activate      # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Start the development server**
   ```bash
   python manage.py runserver
   ```

6. **Visit the app**
   - Open `http://127.0.0.1:8000` in your browser

---

## 📂 Available URLs

- `/` – Home page
- `/login` – Login page
- `/register` – Registration page
- `/detail` – Blog detail view

---
## ScreenShot

### Home Page
<img width="1919" height="1016" alt="Screenshot 2025-07-25 202824" src="https://github.com/user-attachments/assets/2391af80-d7b5-4b99-b05e-d84220c18864" />

### Login Page
<img width="1919" height="1016" alt="Screenshot 2025-07-25 202846" src="https://github.com/user-attachments/assets/34eb6330-f809-4ee0-8719-6bf7279e5619" />

### Registration Page
<img width="1919" height="1019" alt="Screenshot 2025-07-25 202902" src="https://github.com/user-attachments/assets/b1cb8bdd-7e13-45bf-91ec-036336ace963" />

### Detail Page
<img width="1919" height="668" alt="Screenshot 2025-07-25 202927" src="https://github.com/user-attachments/assets/10b73f58-65f6-4ce0-8f90-563c2aeb3b6a" />
