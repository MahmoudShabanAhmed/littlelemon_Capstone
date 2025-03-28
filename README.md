# LittleLemon Capstone Project

## Overview
Please Read the following instruction to learn more about my project 
and to ease your evolution and grading the project.
thank you for supporting.



## Installation
1. Clone the repository:

    git clone https://github.com/yourusername/littlelemon.git

2. Navigate to the project directory:

    cd littlelemon

3. Activate the virtual environment:

    pipenv shell


## Usage
1. Create Superuser

    python manage.py createsuperuser

2. Apply migrations:

    python manage.py makemigrations
    python manage.py migrate

3. Run the development server:

    python manage.py runserver

4. Access the API at `http://127.0.0.1:8000/`.
     - this will be the Api Root and you can find Links for -Menu and bookings API routes 

## API Endpoints
- **endpoints**:
    you must be authenticated to access the API endpoints.
    - `http://127.0.0.1:8000/auth/users/`: List all users registered. and also you can post new users. 
    - `http://127.0.0.1:8000/auth/users/{username}`: retrieve specific user
    - `http://127.0.0.1:8000/api/booking/`: List all booking registered. and also you can post new. 
    - `http://127.0.0.1:8000/api/booking/{id}`: retrieve specific booking by id.
    - `http://127.0.0.1:8000/api/menu/`: List all menu registered. and also you can post new. 
    - `http://127.0.0.1:8000/api/menu/{id}`: retrieve specific menu by id.

- ** user accounts endpoints**:
    - `http://127.0.0.1:8000/api-auth/login/?next=/`:  Login user with username and password
    - `http://127.0.0.1:8000/auth/token/login/`: Create user Token
    - `http://127.0.0.1:8000/auth/token/logout/`: destroy user Token


    - `http://127.0.0.1:8000/api/api-token-auth/`: you can access user token by username and password need to use insomnia or other tool to test it.

