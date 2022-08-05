# ischool

### To run this project or to contribute:
`` git clone git@github.com:$USERNAME/ischool.git``

replace $USERNAME with your github user name.

###  Initialize Git LFS:
 ``cd ischool``
 
 ``git lfs install``
### Create a virtual enviroment:
``python3 -m venv venv``

### Activate virtual enviromen:
`` venv/bin/activate``
### Install Python dependencies:

`` pip install -r requirements.txt --upgrade``

``pip install -r requirements/dev.txt --upgrade``

``pip install -e .``

#### pip install all requirments:
 ``requests``
 
 ``django``
 
 ``rest framework``

#### Run Application:
`` Python3 manage.py makemigrations``

``python3 manage.py migrate``


``python3 manage.py runserver``

You will  be be able to access the server at ``http://127.0.0.1:8000/``


