# Airline

A web application built with Django for learning about the framework, how to use the /admin endpoint and the built-in tests.

## 🚀 Features

- User authentication (login, logout, register)
- Admin dashboard

## 🛠️ Tech Stack

- Python 3.12.3
- Django 5.2
- SQLite

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/monicaimendes/airline.git
cd airline
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Create superuser (optional)

```bash
python manage.py createsuperuser
```

### 6. Run the development server

```bash
python manage.py runserver
```

Open your browser at: http://127.0.0.1:8000

## 🧪 Running Tests

```bash
python manage.py test
```

## 📁 Project Structure

```text
airline/
├── flights/
|   ├── admin.py
|   ├── apps.py
|   ├── tests.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── migrations/
│   └── templates/
├── users/
|   ├── admin.py
|   ├── apps.py
|   ├── tests.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── migrations/
│   └── templates/
├── airline/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
├── db.sqlite3
├── requirements.txt
├── .gitignore
└── README.md
```

## ✨ Acknowledgements

- [Django Documentation](https://docs.djangoproject.com/)

