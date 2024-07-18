# Flask Intro Project

This project is a basic Flask web application that demonstrates how to create, read, update, and delete tasks using a SQLite database.

## Table of Contents

- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Important Notes](#important-notes)

## Setup

1. **Clone the Repository**
    ```sh
    git clone https://github.com/s042204/Flask_Intro.git
    cd flask_intro
    ```

2. **Create and Activate Virtual Environment**
    ```sh
    python -m venv env
    # For Windows
    .\env\Scripts\activate
    # For Unix or MacOS
    source env/bin/activate
    ```

3. **Install Dependencies**
    ```sh
    pip install -r requirements.txt
    ```

4. **Initialize the Database**
    ```sh
    python
    >>> from app import db
    >>> db.create_all()
    >>> exit()
    ```

## Usage

1. **Run the Flask Application**
    ```sh
    python app.py
    ```

2. **Open the Application**
    - Open your web browser and go to `http://127.0.0.1:5000`

## Project Structure

- `app.py`: Main application file
- `templates/`: Contains HTML templates
  - `base.html`: Base HTML template
  - `index.html`: Home page template
- `static/css/`: Contains static CSS files
  - `style.css`: Basic styling for the application

## Important Notes

- **Virtual Environment**: Always activate your virtual environment before working on the project.
- **Database**: If you encounter issues with the database, ensure it is initialized properly with `db.create_all()`.
- **Dependencies**: Make sure all dependencies are installed using the provided `requirements.txt`.

---