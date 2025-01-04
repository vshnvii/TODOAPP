# Simple-To-Do-App
This project is a simple To-Do application developed using Django. It helps users manage their daily tasks effectively by allowing them to add, update, delete, and mark tasks as completed. The app is designed as part of a learning exercise to understand Django's core functionality and follow best practices in web development.


# To-Do App

This is a simple To-Do application built using Django. It allows users to create, update, delete, and manage tasks effectively.

# Features
- Add tasks
- Mark tasks as completed
- Edit tasks
- Delete tasks

# Technologies Used
- Backend: Django
- Frontend: HTML, CSS
- Database: SQLite (default with Django)

# Setup Instructions
Follow these steps to run this project on your local machine:

1. Clone this repository:
   bash
   git clone https://github.com/yourusername/todo-app.git
   cd todo-app
   

2. Set up a virtual environment (optional but recommended):
   bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   

3. Install the dependencies:
   bash
   pip install -r requirements.txt
   

4. Run database migrations:
   bash
   python manage.py migrate
   

5. Start the development server:
   bash
   python manage.py runserver
   

6. Open your browser and go to:
   
   http://127.0.0.1:8000

# How to Use
1. Open the app in your browser.
2. Add tasks by entering their details.
3. Edit or delete tasks as needed.
4. Mark tasks as completed when finished.

# Credits
This project was built following a tutorial on youtube by "Dennis Ivy" https://youtu.be/4RWFvXDUmjo?si=m7xNedjCtF06B21u

# License
This project is for learning purposes only.
