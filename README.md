# PostgreSQL database web app with flask
Data Collection Web App using PostGreSQL and Flask  

## Create a python virtual environment:
python -m venv virtual  
*remember to activate the virtual environment by navigating to virtual/Scripts in the terminal and running **activate***

## Dependancies:
**python -m pip install --upgrade pip**  
**pip install flask**  
**pip install psycopg2**  
**pip install sqlalchemy**  
**pip install Flask-SQLAlchemy**

## Objectives:
- HTML
- CSS
- Get user input
- PostgreSQL database model
- Store ther user data into the database
- Email the database values back to the user
- Send statistcs to the user
- Deploy the web application to a live server
- Implement downloading and uploading into the web app  

## Notes
Within the app.py file:  
app.config['SQLALCHEMY_DATABASE_URI']='postgresql://***postgres***:***postgres123***@localhost/***height_collector***'  
- ***postgresql***: enter your PostgreSQL username
- ***postgres123***: enter your PostgreSQL password
- ***height_collector***: database name   

Lessons were learnt from: https://www.udemy.com/course/the-python-mega-cours