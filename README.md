# Photo Share <!-- omit from toc -->

## Table of Contents <!-- omit from toc -->
- [Features](#features)
- [Installation and Setup](#installation-and-setup)

## Features
- User registration and authentication
- Photo upload and deletion
- Album creation and deletion
- User profile with uploaded images and albums

## Installation and Setup

Fallow these instructions to setup the project locally on your machine.

1. Clone the repo

```shell
git clone https://github.com/IT-Mzk/Software-Project.git
```

2. Create a virtual environment

```shell
python -m venv venv
```

3. Activate the virtual environment

    1. Unix

    ```shell
    source venv/bin/activate
    ```

    2. Windows

    ```shell
    .\venv\Scripts\Activate
    ```

4. Install required packages

```shell
pip install -r requirements.txt
```

5. Apply database migrations

```shell
python manage.py migrate
```

6. Create a superuser for admin access

```shell
python manage.py createsuperuser
```

7. Run the development server

```shell
python manage.py runserver
```

8. In your web browser go to `http://localhost:8000`

9. Browse the front facing features by clicking on the links in the navigation bar.

10. Visit the admin panel at `http://localhost/admin`, login with the credentials you used when creating the superuser.

