
# Simple CRUD Application using Flask and SQLAlchemy

This project is a simple CRUD (Create, Read, Update, Delete) application built with Flask and SQLAlchemy. It allows users to perform basic CRUD operations on a database.

## Installation

1. **Clone this repository** to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. **Navigate into the project directory**:

   ```bash
   cd <project-directory>
   ```

3. **Create a virtual environment**:

   ```bash
   python -m venv venv
   ```

4. **Activate the virtual environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

5. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have a database set up and configured in the `config.py` file. Modify the SQLAlchemy URI as needed.

2. **Initialize the database**:

   ```bash
   flask db init
   ```

3. **Create the necessary migrations**:

   ```bash
   flask db migrate
   ```

4. **Apply the migrations**:

   ```bash
   flask db upgrade
   ```

5. **Run the Flask application**:

   ```bash
   flask run
   ```

6. **Access the application** in your web browser.

## Technologies Used

   - **Flask**: Lightweight web application framework in Python, known for simplicity and flexibility.
   - **SQLAlchemy**: SQL toolkit and Object-Relational Mapping (ORM) library for Python, simplifies database interaction.
   - **HTML**: Standard markup language for creating web pages, defining structure and content.
   - **CSS**: Style sheet language for controlling web page presentation and enhancing user experience.
