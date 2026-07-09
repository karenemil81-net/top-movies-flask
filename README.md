# Top Movies Flask Application

## Project Overview

Top Movies is a Flask web application that allows users to build and manage a personal movie collection. Users can search for movies using The Movie Database (TMDB) API, add movies to their collection, rate them, write reviews, and manage their favorite films.

This project demonstrates building a complete CRUD application using Flask, SQLAlchemy, Flask-WTF, Bootstrap, and SQLite.

## Features

- Search for movies using the TMDB API
- Add movies to a personal movie database
- Display saved movies in a collection
- Edit movie ratings and reviews
- Delete movies from the collection
- Store movie information using SQLite
- Use Flask-WTF forms with validation
- Create database models using SQLAlchemy ORM
- Build a responsive interface using Bootstrap

## Technologies Used

- Python
- Flask
- Flask-SQLAlchemy
- SQLAlchemy ORM
- Flask-WTF
- Bootstrap
- Bootstrap-Flask
- SQLite
- TMDB API
- HTML
- CSS

## Project Structure

```text
top-movies-flask/
│
├── main.py                     # Main Flask application
├── movies.db                   # SQLite database
├── requirements.txt            # Project dependencies
├── .env                        # Environment variables
├── .gitignore                  # Ignored files
│
├── static/                     # Static files such as CSS
│   └── css/
│       └── styles.css          # Custom styling
│
└── templates/                  # HTML templates
    ├── index.html              # Home page displaying movies
    ├── add.html                # Add movie search page
    ├── edit.html               # Edit movie rating and review page
    └── select.html             # Select movie from API results

