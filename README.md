# Django Social Media Project

A simple social media application built with Django, designed to connect users and allow them to share content.

## Features

- User authentication (registration, login, logout)
- Profile creation and editing
- Post creation, editing, and deletion
- Like and comment on posts
- Follow/unfollow other users
- Responsive design

## Technologies Used

- Django
- Python
- HTML/CSS
- JavaScript
- SQLite (or your preferred database)

## Installation

### Prerequisites

- Python 3.x
- Django
- Git

### Clone the Repository and Set Up the Environment

```bash
git clone https://github.com/yourusername/repo.git
cd repo
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

