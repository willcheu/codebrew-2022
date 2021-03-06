# codebrew-2022

## Setup instructions

Install:
- [Python3](https://www.python.org/downloads/)
- [Git](https://www.atlassian.com/git/tutorials/install-git)

## Setup Project
To clone project
```bash
git clone https://github.com/willcheu/codebrew-2022.git
cd codebrew-2022
```

Run these scripts in terminal in the project directory
```bash
pip3 install virtualenv --user
python3 -m virtualenv venv
# Activate virtualenv
source venv/bin/activate
# Install Python requirements
pip install -r requirements.txt
```

## Run project

If you have changed models file run
```bash
python3 manage.py makemigration
python3 manage.py migrate
```

To run web server
```
python3 manage.py runserver
```

Open the web app in your browser
```
http://localhost:8000
```

