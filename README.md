# 🎬 Movie Rating Web App

A Flask-based web application that allows users to search for movies, add them to a personal collection, and rate or review them. The application integrates with **The Movie Database (TMDB) API** to automatically retrieve movie information such as title, release year, description, and poster images.

This project demonstrates full-stack web development concepts including **API integration, database design, CRUD operations, and form handling using Flask**.

---

## 🚀 Features

- Search for movies using the **TMDB API**
- Add movies to a personal movie collection
- Rate movies and write reviews
- Automatically rank movies based on ratings
- Edit or delete movies from the database
- Persistent storage using **SQLite**

---

## 🛠 Tech Stack

**Backend**
- Python
- Flask

**Database**
- SQLite
- SQLAlchemy ORM

**Forms**
- Flask-WTF
- WTForms

**Frontend**
- HTML
- Jinja Templates
- Bootstrap

**API Integration**
- TMDB API

---

## 📂 Project Structure
```
Movie_rating_website
│
├── main.py
├── requirements.txt
├── .gitignore
│
├── templates
│   ├── base.html
│   ├── index.html
│   ├── add.html
│   ├── edit.html
│   └── select.html
│
├── static
│   └── css
│        └── styles.css
│
└── movies.db
```
---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Namdo2465/Movie_rating_website.git
cd Movie_rating_website
```

Create a virtual environment:
```bash
python -m venv .venv
```

Activate the environment:

Mac / Linux
```bash
source .venv/bin/activate
```

Windows
```bash
.venv\Scripts\activate
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

This project uses the TMDB API to fetch movie data.
Set your API key:

Mac / Linux
```bash
export TMDB_API_KEY=your_api_key_here
```
Windows
```bash
set TMDB_API_KEY=your_api_key_here
```

You can obtain a TMDB API key here:
```bash
https://www.themoviedb.org/settings/api
```

## ▶️ Running the Application

Start the Flask server:
```bash
python main.py
```

Then open your browser and go to:
```bash
http://127.0.0.1:5000
```

## 📚 Learning Outcomes

While building this project, I practiced:

- Integrating external APIs into web applications

- Designing relational databases with SQLAlchemy

- Implementing CRUD operations in Flask

- Handling forms and user input with Flask-WTF

- Structuring a Flask project for maintainability

## 🔮 Future Improvements

Potential enhancements include:

- User authentication

- Movie recommendations

- Sorting and filtering options

- Pagination for large movie collections

- Deploying the application to a cloud platform
