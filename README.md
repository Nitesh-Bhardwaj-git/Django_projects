# Django Todo Project

A simple Django-based Todo application with user authentication, per-user todo lists, and a modern UI using Tailwind CSS.

## Features
- User registration and login
- Each user can only see and manage their own todos
- Create, update, and delete todos
- Dashboard with todo summary
- Responsive design with Tailwind CSS

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Nitesh-Bhardwaj-git/Django_projects.git
   cd YOUR-REPO
   ```

2. **Create a virtual environment and activate it:**
   ```sh
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On Mac/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```sh
   pip install django
   ```

4. **Apply migrations:**
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin access):**
   ```sh
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```sh
   python manage.py runserver
   ```

7. **Access the app:**
   Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Folder Structure
```
Seventh project/
├── Core/
├── Todo/
│   ├── migrations/
│   ├── templates/
│   │   └── Todo/
│   ├── admin.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── manage.py
└── README.md
```

## License
This project is for educational purposes.# Django_projects
