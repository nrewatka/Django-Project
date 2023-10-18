# Django Poll Application

This README provides an overview of the Django Poll Application, an open-source web framework for Python. This repository encompasses the entire codebase for the Django project's tutorial polls application. The code here should closely resemble the code of all Part 8. For comprehensive information, tutorials, and the latest updates, please visit the [Django 4.2 Official Documentation](https://docs.djangoproject.com/en/4.2/).

![Django Logo](https://www.djangoproject.com/s/img/logos/django-logo-negative.png)

## Appendix

By following these steps, you can setup a local copy of the project for use in testing and development.

## Table of Contents

- [What is Django?](#what-is-django)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [License](#license)
- [Screenshots](#screenshots)
- [Authors](#authors)
## What is Django?

Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design. It follows the "batteries-included" philosophy, providing everything needed to build web applications, from simple to complex. Django takes care of much of the hassle of web development, so you can focus on writing your app without needing to reinvent the wheel.

For more information about Django and its features, check out the [official Django website](https://www.djangoproject.com/).

## Prerequisites

Assuming you have Django installed, you can verify its presence and version by entering the following command in a terminal :

$ python -m django --version

If Django is correctly installed, this command will display the installed version. In case it's not installed, you'll receive an error indicating 'No module named django.'

This tutorial is tailored for Django 4.2, which is compatible with Python 3.8 and newer versions

## Installation

**Importing Code**

Open terminal, navigate to folder where you want to keep the project by:

$ cd (\folderpath)

Clone the code by typing:

$ git clone https://github.com/nrewatka/Django-Project/tree/master


**Run Migration**

To migrate the database type in terminal in project directory:

$ python manage.py migrate


**Create Admin**

To access the admin panel, you are required to generate a superuser by executing the following command:

$ python manage.py createsuperuser


**Run the Server**

To access the program in local server use the following command:

$ python manage.py runserver

Visit http://127.0.0.1:8000/admin/ to create a poll using the admin credential

Visit http://127.0.0.1:8000/polls/ to participate in the poll.







## License

[MIT](https://choosealicense.com/licenses/mit/)

## License

Django 4.2 is released under the [Django Software Foundation License](https://docs.djangoproject.com/en/4.2/internals/contributing/licenses/). Please review it to understand the terms and conditions.

For the most up-to-date and detailed information, visit the [official Django 4.2 documentation](https://docs.djangoproject.com/en/4.2/).

Happy coding with Django 4.2!

## Project Screenshots

***Admin Login Page***
![App Screenshot](https://raw.githubusercontent.com/nrewatka/Django-Project/2b2bc132777b88c98fa4695c0da5923176dc9ca1/admin%20login%20page.png)

***Admin site-Administrator  Page***
![App Screenshot](https://raw.githubusercontent.com/nrewatka/Django-Project/2b2bc132777b88c98fa4695c0da5923176dc9ca1/admin_site%20administration%20page.png)

***Admin Question List Page***
![App Screenshot](https://raw.githubusercontent.com/nrewatka/Django-Project/2b2bc132777b88c98fa4695c0da5923176dc9ca1/admin%20question%20page.png)

***Admin Add Question Page***
![App Screenshot](https://raw.githubusercontent.com/nrewatka/Django-Project/846dac64785f4f4bde057664166c970216232194/Add%20quenstion%20page.png)

***Poll List Page***
![App Screenshot](https://raw.githubusercontent.com/nrewatka/Django-Project/2b2bc132777b88c98fa4695c0da5923176dc9ca1/poll%20page.png)

***Polling Page***
![App Screenshot](https://raw.githubusercontent.com/nrewatka/Django-Project/2b2bc132777b88c98fa4695c0da5923176dc9ca1/vote%20page.png)
## Authors

-Noopur Rewatkar

Email: nrewatka@cbu.edu

ID: 899491297

