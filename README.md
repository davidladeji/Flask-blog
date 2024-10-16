# Flask Blog

## About:
This is a single-server blogging web application that allows users to share posts with the entire community. Inspired by Twitter, it facilitates open interaction without a following or follower dynamic. Project was built to gain more experience using Flask framework to build web applications.

This application was built with Python, Flask, SQLAlchemy, and HTML/CSS.

## Steps to Run Locally
1. Clone repo to machine
2. Create virtual environment. `python3 -m venv env` i.e creates virtual enviroment named `env`
3. Activate virtual env `source env/bin/activate` (mac)
4. Install all env requirements `pip3 install -r requirements.txt`
5. set FLASK_APP=run.py `export FLASK_APP=run.py`
6. Initialize the database by using custom command `flask initdb`
7. Run the application `flask --app flaskblog run --debug` (NOTE: debug mode is enabled)
