# Canteen Management System
Canteen management system is a web application built using Django.

## Functionalities Implemented
* User Registration/Login
* Cart functionality
* Registered users can add to cart and checkout
* Guest users can add to cart and checkout
* Admin dashboard
* Admin can view and update/place orders
* Admin can add and update meals

## Software used
* [Visual Studio Code](https://code.visualstudio.com/download)

## Running the application

- To run the Django app on your local computer, set up a Python development environment, including Python, `pip`, and `virtualenv`.
- Create an isolated Python environment, and install dependencies:
  ```
  virtualenv env
  ```
  > To activate your virtual environment use this command(windows):
  ```
  env\scripts\activate
  ```
  > To install all the requirements for the project:
  ```
  pip install -r requirements.txt
  ```
- Run the Django migrations to set up your models:
  ```
  python manage.py makemigrations
  python manage.py migrate
  ```
- Start a local web server:
  ```
  python manage.py runserver
  ```
- In your browser, go to [http://localhost:8000](http://localhost:8000).
- Press `Control+C` to stop the local web server.


