# Full Stack Contact Book

* a full stack contact book application featuring a python based flask api for back end data processing and a modular react frontend optimized with vite

## Features

* full CRUD lifecycle capabilities: create, read, update and delete contacts

* cross origin resource sharing (CORS) integration to allow safe communication between the frontend client and backend server

* state driven interface updates, ensuring that modifying or deleting an entry immediately reflects on screen without forcing a browser refresh

## Tech Stack

* backend : python, flask, flask-sqlalchemy(for database object relational mapping), and flask cors

* frontend : react, javascript, vite, and custom css stylesheets for user interface layout design

* database : sqlite

## Local Setup Instructions

* follow these steps to get the application running on your local machine

* # backend setup 

* navigate into the backend directory and setup the python environment:
cd backend

* activate the virtual environment(windows)
venv\Scripts\activate

* install the required python packages
pip install -r requirements.txt

* run the flask server
python main.py

* # frontend setup

* open a new terminal window or tab, then set up the react client:

* change directory to frontend
cd frontend

* install the node modules
npm install

* start the vite development server
npm run dev
