# 📚 Online Book Library

[![Django](https://img.shields.io/badge/Django-5.0-green?logo=django)](https://www.djangoproject.com/)    [![SQLite](https://img.shields.io/badge/SQLite-3-blue?logo=sqlite&logoColor=white)](https://www.sqlite.org/)    [![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)   [![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)  

An online library management system built with **Django 5**.  
This web app allows users to **register, browse, borrow, and manage books**, while **admins** can handle users and content from a simple dashboard.

---

## ✨ Features

- 🔐 User authentication & registration  
- 📖 Book management (add, edit, delete)  
- 📚 Borrowing & availability tracking  
- 🖼️ Media support for book images  
- ⚙️ Django Admin interface  

---

## 📂 Project Structure

```
Web-Project/
│── manage.py              # Django management script
│── requirements.txt       # Project dependencies
│── project/               # Django project settings
│── pages/                 # Main app (books & users)
│── media/                 # Uploaded images
│── static/                # CSS, JS, assets
│── templates/             # HTML templates
```

---

## 🚀 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/zinab27/Online_Book_Library.git
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (for admin access)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

---

## 🌐 Usage

- Open the app: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  
- Admin panel: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---

## 🛠️ Tech Stack

- [Django 5](https://www.djangoproject.com/) – Web Framework  
- [SQLite](https://www.sqlite.org/) – Default Database
- HTML , CSS 

---

## 🤝 Contributing

Pull requests and issues are welcome! 🎉
