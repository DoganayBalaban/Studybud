
# Studybud

This project is a clone of the "Studybud" application created by following the "Python Django 7 Hours Course" tutorial on the Traversy Media YouTube channel. The primary goal of this project was to learn Django, a high-level Python web framework.

## Table of Contents
- [Studybud](#studybud)
  - [Table of Contents](#table-of-contents)
  - [About the Project](#about-the-project)
  - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Acknowledgements](#acknowledgements)

## About the Project

Studybud is a web application designed to help users manage their study schedules and tasks. It provides functionalities such as user authentication, task management, and a user-friendly interface.

## Built With

- [Django](https://www.djangoproject.com/) - The web framework used
- [SQLite](https://www.sqlite.org/index.html) - The database used for development

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Make sure you have Python and pip installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/DoganayBalaban/Studybud.git
   ```
2. Navigate to the project directory
   ```sh
   cd Studybud
   ```
3. Install the required packages
   ```sh
   pip install -r requirements.txt
   ```
4. Apply the migrations
   ```sh
   python manage.py migrate
   ```
5. Run the server
   ```sh
   python manage.py runserver
   ```

## Usage

To use the application, open your web browser and navigate to `http://127.0.0.1:8000/`. You can register a new user or log in with an existing account to start managing your study tasks.

## Acknowledgements

This project was created by following the tutorial on the Traversy Media YouTube channel. Special thanks to Brad Traversy for providing such a comprehensive and easy-to-follow tutorial.

