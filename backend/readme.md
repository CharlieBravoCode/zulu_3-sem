# Flask CRUD App

This is a backend CRUD app using flask-python with an external database. The APIs are done with the Flask-SQLAlchemy extension by using a direct SQL query. The template engine used is Jinja2.

The authentication is done via the SSO Keycloak. The SSO Keycloak is a third party service that provides authentication and authorization. The SSO Keycloak is used to authenticate the user and provide the token to the backend. The backend uses the token to authorize the user.

## Requirements


## Core features

1. Render a template with a list of items from the database.
2. Render a template with a form to add a new item to the database.
3. Add a new item to the database.
4. Render a template with a form to edit an item in the database.
5. Edit an item in the database.
6. Delete an item from the database.
7. Display data from the on a map.


## How to run

1. Clone the repository
2. Create a virtual environment
    - `python3 -m venv env`
    - `source env/bin/activate`

3. Install the requirements
    - `pip install -r requirements.txt`
4. Run the app
    - `python app.py`

