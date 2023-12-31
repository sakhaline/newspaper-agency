# Django Newspaper agency Project

## Description

The Django agency Project is a web application for managing newspapers, redactors, and topics. It provides views for listing, creating, updating, and deleting newspapers, redactors, and topics. The project also includes user authentication features.
![Screenshot from 2023-11-24 05-42-42](https://github.com/sakhaline/newspaper-agency/assets/130174413/2afe5b5a-ac96-463d-beb5-f466e3911b11)
![Screenshot from 2023-11-24 05-43-02](https://github.com/sakhaline/newspaper-agency/assets/130174413/7373e26c-8763-432d-ace8-d1660e0f84d6)

## Installation

1. Clone the repository:
   ```bash
   https://github.com/sakhaline/newspaper-agency
   cd NewspaperAgency
   
2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Apply migrations:
   ```bash
   python manage.py migrate

5. Create a superuser (admin) account:
   ```bash
   python manage.py createsuperuser

Follow the prompts to create a superuser account.

## Usage

1. Start the development server:
   ```bash
   python manage.py runserver
   
3. Open your browser and go to https://newspaper-agency-lmq5.onrender.com to access the application.

4. Log in with the superuser account created during installation to access the admin panel.

5. Explore and use the provided views for manag
ing newspapers, redactors, and topics.

## Author

*Ivanova Olexandra*

## Project Status

Development is ongoing. Feel free to fork the project if needed.
