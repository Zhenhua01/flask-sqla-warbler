# Warbler App

[Live Demo](https://warbler-zhl.herokuapp.com)

Project: Full stack application for users to create a profile, follow other users, post public messages, and like each other's messages.

## Available Scripts

Initially requires PostgreSQL database created: "warbler" and "warbler_test".
To seed the app database with profile users warbler:

- `python3 seed.py`

App requires a `.env` file in the main directory:
- SECRET_KEY = secret (or any secret key of choice)
- DATABASE_URL = postgresql:///warbler

### In the project directory and venv, you can run:

Install required dependencies from requirements.txt:

- `pip3 install -r requirements.txt`

Run the app in the development mode. Open [http://localhost:5001](http://localhost:5001) to view it in browser:

 - `flask run -p 5001`

Run all tests:

- `python3 -m unittest`
