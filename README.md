# Hashflix
___

## About the Project
This is a complete web project, developed with the Django framework, which simulates a movie and series streaming platform. The application allows users to create an account, log in, and access a movie catalog with detailed information, a view count system, and a history of watched films.

## Features
- **User Authentication:** A robust system for logging in, account registration, and profile editing.
- **Movie Catalog:** Displays a list of movies and highlights the most popular one, with a search option.
- **Detail Pages:** Each movie has its own page with information, view counts, and the option to watch episodes.
- **Watch History System:** The application records which movies a user has watched.

## Technologies
The following technologies were used: Python, Django, HTML, CSS, Tailwind, Bootstrap, SQLite, and SQLAlchemy.

## How to Run
To run this project, you need to have Python and `pip` installed. After cloning the repository, install the dependencies listed in the `requirements.txt` file.

**Remember to apply the migrations to create the database before running the application:**
```bash
python manage.py makemigrations
python manage.py migrate