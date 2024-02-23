# LAB - Class 34

## Project: cookie-stand-api

### Author: Errol Vidad
V.1.0.0 (Pr: https://github.com/Code-Fellows-School-Work/cookie-stand-api/pull/1)

### Links and Resources
- Back-end server url (when applicable): None
- Front-end application (when applicable): None

### Setup
- Install ThunderClient extension in VS Code

i.e.

- PORT - Port Number: 8000
- DATABASE_URL - None

### How to initialize/run your application (where applicable)

- git clone https://github.com/Code-Fellows-School-Work/cookie-stand-api
- cd cookie-stand-api
- Run the command: python -m venv .venv
- Activate virtual environment
- Run the command: pip install -r requirements.txt
- Refer to Canvas submission for .env setup and superuser name + password
- Run the command: python -m manage.py runserver
- In the web browser, navigate to http://127.0.0.1:8000/

### How to use your library (where applicable)

### CRUD Routes:

    - [Admin](http://127.0.0.1:8000/admin/)
        - Admin panel
    - [Cookie Stand List](http://127.0.0.1:8000/cookiestands/)
        - Review list of cookie stands
    - [Cookie Stand Detail](http://localhost:8000/cookiestands/<int>)
        - Review detailed info of selected cookie stand
        - Readonly access for non-owners
        - Edit and delete access for owner
    - [About Page](http://127.0.0.1:8000/about)
        - Information not about the author
    - [Token Access](http://127.0.0.1:8000/api/token/)
        - Provides authenticated users an access and refresh token
    - [Token Refresh](http://127.0.0.1:8000/api/token/refresh/)
        - Provides authenticated users a new access token if current access token expired








