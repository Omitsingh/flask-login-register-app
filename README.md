# Flask Login & Register App

A simple Flask web application with:
- User registration & login
- MySQL database integration
- User management (view & delete users)

## Features
- Secure login & registration
- Styled with CSS
- MySQL backend for user storage

## How to run
1. Clone the repo:
   
   git clone https://github.com/Omitsingh/flask-login-register-app.git
   cd flask-login-register-app

## Install requirements:

--pip install flask mysqlclient
Run the app:

--python app.py
(If mysqlclient gives error, you can instead use:)

--pip install flask
--pip install pymysql

## Project Structure

flask-login-register-app/
│── app.py
│── static/
│   └── style.css
│── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── user.html
│   ├── welcome.html
│   ├── about.html
│   └── contact.html
