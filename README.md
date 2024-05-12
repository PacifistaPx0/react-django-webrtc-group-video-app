# Group Call App

Inorder to run this project on your local you need to serve two application in two different terminal

## Backend

### Prerequisites

- Python 3.12.1

### Steps to setup
- Open terminal and type `cd backend`
- Run `python -m venv venv` (This sets up a virtual python environment)
- Activate the virtual environment `venv/Scripts/activate` (if you have different terminal like powershell, you will find corresponding script inside `venv/Scripts/`)
- Run `pip install -r requirements.txt` to install all the relevant packages for the backend
- Try running `python manage.py migrate` to setup the database (in this case it will sqlite)
- Finally run `python manage.py runserver`


## Frontend

### Prerequisites

- Node 16.20.2 

### Steps to setup
- Open terminal and type `cd frontend`
- Run `npm i`
- Then finally run `npm start`

