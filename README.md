# School/College Administration Website

This project is a simple web application built with Flask for managing school or college administration tasks. It includes features such as admission form submission, about page, and a contact form.

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/mann-som/school-administration.git
    cd school-administration
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application:**

    ```bash
    python main.py
    ```

4. Open your browser and navigate to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

## Features

- **Admission Page:**
  - Submit admission forms with name, email, and course selection.
  - View a table of admission details with options to edit and delete entries.

- **About Page:**
  - General information about the school or college.

- **Contact Page:**
  - Contact form to send messages.
  - Form data is displayed in the console (you can extend it to save in a database or send an email).

## Usage

- **Admission Form:**
  - Navigate to the Admission page from the navigation bar.
  - Fill out the form with your details and submit.
  - View submitted entries in the table below the form.

- **About Page:**
  - Navigate to the About page from the navigation bar.

- **Contact Form:**
  - Navigate to the Contact page from the navigation bar.
  - Fill out the form and submit.

## Folder Structure

- **static:** Contains static files like CSS.
- **templates:** Contains HTML templates.
- **main.py:** The main Flask application file.
- **style.css:** Stylesheet for the application.
- **requirements.txt:** Lists the Python dependencies.

## Dependencies

- Flask: Web framework for Python.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
