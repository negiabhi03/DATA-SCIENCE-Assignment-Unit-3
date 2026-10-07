# Word Counter App using Django

## Project Overview

The **Word Counter App** is a beginner-level web application developed using **Python and Django**. It allows users to enter or paste text and calculates the total number of words in the given text.

This project was selected from the **GeeksforGeeks Django Projects** list and implemented practically to understand the basic concepts of Django web development.

## Features

- Enter or paste text into a text area.
- Count the total number of words.
- Display the word count on the webpage.
- Preserve the entered text after submission.
- Simple and user-friendly interface.
- Purple and white themed design.
- Uses Django POST requests.
- Uses Django CSRF protection.

## Technologies Used

- Python 3.11.3
- Django 5.2.18
- HTML
- CSS
- Git
- GitHub
- Visual Studio Code

## Project Structure

```text
WORDCOUNTER APP/
│
├── counterapp/
│   ├── migrations/
│   ├── templates/
│   │   └── counter.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── wordcounter/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── README.md
└── .gitignore
