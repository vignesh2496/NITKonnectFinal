# NITKonnect

This project has the following basic apps:

* accounts
* profiles
* blog
* qa
* messages

## Installation
Install the latest distribution of virtualenv for Python 3.

### Quick start

To set up a development environment quickly, first install Python 3. It
comes with virtualenv built-in. So, first delete the already existing folder named "venv", and then type the following command in the same directory to
create a new virtual environment and run the project:

    1. `$ virtualenv -p python3 venv
    2. `$ source venv/bin/activate
    3. `$ cd NITKonnect
    4. `$ pip install -r requirements.txt
    5. `$ cd src
    6. `$ cp NITKonnect/settings/local.sample.env NITKonnect/settings/local.env

Run migrations:

    python manage.py migrate
    
Run server:

    python manage.py runserver
    
Open any browser and type '127.0.0.1:8000' in the space for domain name.
The website comes into view :)
