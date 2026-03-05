# Django Blog Platform

A simple blog platform built using Django. Users can create blog posts, view posts, and add comments.

## Features

* Create blog posts
* View all blog posts
* View individual post details
* Add comments to posts
* Soft delete functionality for posts/comments
* Admin panel for managing content

## Technologies Used

* Python
* Django
* HTML
* SQLite (default Django database)

## Project Structure

```
blog_platform/
│
├── blog/                # Blog application
├── blog_platform/       # Main Django project settings
├── templates/           # HTML templates
├── manage.py            # Django management script
└── db.sqlite3           # Database file
```

## Installation

1. Clone the repository

```bash
git clone <your-repository-url>
cd blog_platform
```

2. Create virtual environment

```bash
python -m venv venv
```

3. Activate virtual environment

Windows:

```bash
venv\\Scripts\\activate
```

4. Install dependencies

```bash
pip install django
```

5. Apply migrations

```bash
python manage.py migrate
```

6. Run the server

```bash
python manage.py runserver
```

Open your browser and go to:

```
http://127.0.0.1:8000/
```

## Admin Panel

Create a superuser:

```bash
python manage.py createsuperuser
```

Then visit:

```
http://127.0.0.1:8000/admin
```

## Author

Ishika Karbhari
