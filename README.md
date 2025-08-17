# Bank Management System

A simple bank management system built with Django, HTML, Tailwind CSS, and PostgreSQL. This project allows users to manage their bank accounts with essential features.


## Features

- Create an account
- Login & logout
- Update account details
- Deposit money
- Withdraw money
- Send money to another user
- Take a loan
- Return a loan

## Tech Stack

- **Backend:** Django
- **Frontend:** HTML, Tailwind CSS
- **Database:** PostgreSQL

## Setup Instructions

1. **Clone the repository**
    ```bash
    git clone https://github.com/jahidul17/BitBank.git
    cd BitBank
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```


4. **Create a superuser (As admin login -Optional)**
    ```bash
    python manage.py createsuperuser
    ```

5. **Apply migrations**
    ```bash
    python manage.py migrate
    ```

6. **Run the server**
    ```bash
    python manage.py runserver
    ```

7. **Access the project:**
    Open your browser and go to `http://127.0.0.1:8000/`<br>


