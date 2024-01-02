![Capture](https://i.ytimg.com/vi/lFNsZWzdyAM/maxresdefault.jpg)

# Cuvette - Django Authentication Project
---

Contents
---

* [Overview](#overview)
* [Features](#features)
* [Getting Started](#getting-started)
* [Built With](#built-with)
* [Author](#author)
* [Demo Video](#demo-video)



### Overview 
---
This project is a simple Django web application implementing basic user authentication including features like user registration (sign up), login, logout, and profile management.


### Features
---

<ol>
  <li>User Registration</li>
  <li>User Login</li>
  <li>User Logout</li>
  <li>Dashboard Access upon Login</li>
</ol>

### Getting Started
---

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#### Prerequisites

Before you begin, ensure you have met the following requirements:

<ol>
  <li>Python 3.x</li>
  <li>pip</li>
  <li>Virtualenv (optional but recommended)</li>
</ol>

### Setting Up the Project

Clone the repository

```
git clone https://github.com/gouravmohanty7070/Authentication_Page
cd Authentication_Page
```

Setup Virtual Environment

To ensure a clean and isolated environment for your application, it's recommended to use a virtual environment. Here's how you can set it up:

```
python3 -m virtualenv venv
```

Activating the Virtual Environment
- On Windows:
```
venv\Scripts\activate
```

- On macOS and Linux:

```
source venv/bin/activate
```

Install Dependencies
With the virtual environment activated, install the required dependencies using pip and the requirements.txt file:
```
pip install -r requirements.txt
```

Start the Application
Navigate to the "auth_page" directory, which contains the application code:
```
cd auth_page
```

Run Migrations
```
python manage.py makemigrations
python manage.py migrate
```

Run the following command to start the application:
```
python manage.py runserver
```

Access the Application

```
Open your web browser and go to http://127.0.0.1:8000/accounts/signup/
```
Using the Application

To Register:
Navigate to ```/accounts/signup/``` to create a new user account.

To Login:
Navigate to ```/accounts/login/``` to log in to an existing account.

To View Dashboard:
After logging in, you will be redirected to the dashboard.

To Logout:
Click the logout link in the dashboard.


### Built With
---

<ol>
  <li>Django - The web framework used</li>
  <li>SQLite - The database engine used</li>
</ol>

### Author

Made with ❤️ by Gourav Mohanty

### Demo Video
---


