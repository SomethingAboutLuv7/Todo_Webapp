# Todo Web App

A modern task manager built with Django. Create, manage, edit, and delete
tasks through a clean and interactive interface, with no page reloads
needed for editing.

🔗 **Live demo:** https://luvchau.pythonanywhere.com

## Features
- **View all tasks** in a clear, organized list
- **Add tasks instantly** with a simple input form
- **Edit inline**: update a task right where it is, without leaving the page
- **Delete tasks** individually, or clear all tasks at once
- **Secure by design**: uses POST requests and Django's CSRF protection

## Built With
- Python / Django
- SQLite
- HTML & CSS
- WhiteNoise (static file serving)
- Deployed on PythonAnywhere

## Run Locally
```bash
git clone https://github.com/YOUR-USERNAME/Todo_Webapp.git
cd Todo_Webapp
python -m venv myenv
myenv\Scripts\activate        # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Then open http://127.0.0.1:8000 in your browser.
