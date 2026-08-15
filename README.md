# Online Shop Django

A simple online shop web application built with Django. This project was developed as a learning project to practice Django fundamentals, database models, user authentication, and server-side web development.

## Features

- Browse available products
- Filter products by category
- View individual product details
- User registration
- User login and logout
- Custom Django user model
- Django admin interface
- Product and category image support
- Sample product and category data

## Tech Stack

- Python
- Django 4.1.4
- SQLite
- HTML
- CSS
- Pillow

## Project Structure

```text
Online-Shop-Django/
├── nshop/
│   ├── accounts/          # User model and authentication
│   ├── categories/        # Products and categories
│   ├── media/             # Product and category images
│   ├── nshop/             # Django project configuration
│   ├── static/            # CSS and static files
│   ├── templates/         # Shared templates
│   ├── db.sqlite3         # Sample SQLite database
│   └── manage.py
├── requirements.txt
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/NeginAzadeh/Online-Shop-Django.git
cd Online-Shop-Django
```

### 2. Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Navigate to the Django project

```bash
cd nshop
```

### 5. Run the development server

```bash
python manage.py runserver
```

Then open `http://127.0.0.1:8000/` in your browser.

## Sample Data

The repository includes a sanitized SQLite database with sample products and categories so the application can be explored immediately after setup.

Development user accounts, sessions, and admin activity have been removed from the database.

## Note

This project was developed for educational purposes and is configured for local development rather than production deployment.
