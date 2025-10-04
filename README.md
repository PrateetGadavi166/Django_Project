# Django Polling System 🗳️

A simple web application built with Django that allows users to create polls, vote, and see results in real-time.  

## Features ✨
- Create and manage polls  
- Vote on active polls  
- View poll results with percentages  
- User-friendly interface  

## Project Structure 📁
```bash
django-polling-system/
├── polling_app/ # Main Django app for polls
├── templates/ # HTML templates
├── static/ # CSS, JS, images
├── manage.py # Django management script
├── db.sqlite3 # Default SQLite database
└── README.md # Project documentation
```

## Installation & Setup ⚙️

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd django-polling-system
```
### 2. Create a virtual environment
```bash
python -m venv env
source env/bin/activate   # Linux/Mac
env\Scripts\activate      # Windows
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Apply migrations
```bash
python manage.py migrate
```
### 5. Run the server
```bash
python manage.py runserver
Open http://127.0.0.1:8000 in your browser to access the app.
```
### Acknowledgements 🙏
- 🟢 Django – Web framework
- 🎨 HTML & CSS – Frontend design
- 🐍 Python – Backend logic
- 💻 SQLite – Default database








