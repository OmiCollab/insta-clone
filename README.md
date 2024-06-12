# Instagram Clone with Django

This is an Instagram clone built using Django. Follow the steps below to set up the project on your local machine.

## Prerequisites

- Python 3.x installed on your machine
- Git installed on your machine

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/insta-clone.git
cd insta-clone
```

### 2. Set Up a Virtual Environment
A virtual environment helps to manage project-specific dependencies. Here's how to create and activate a virtual environment:

#### For macs and linux (For WSL2 as well):
```bash
python3 -m venv insta_clone_env
source insta_clone_env/bin/activate
```

#### For Windows:
``` bash
python -m venv insta_clone_env
insta_clone_env\Scripts\activate
```
### 3. Install Dependencies
With the virtual environment activated, install Django and other dependencies:

```bash
pip install django
```

### 4. Verfying the Install
To confirm that Django is installed correctly, run the following command:

```bash
python -m django --version
```

with this you should see a django version number printed on the screen.

### 5. To run the Development Server
```bash
python manage.py runserver
```

This will output some result where in there will be the local host mentioned in it. 
Like this: http://127.0.0.1:8000/
Click on that link or copy and paste it to get to your web server.

