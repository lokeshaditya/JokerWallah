# JokerWallah
**STEPS:**
1. Remove the venv, pycache, .vscode folders.
2. Create your own virtual envirinment using "python -m venv venv"
3. Activate virtual environment.
4. Install dependencies mentioned in the requirements.txt file using "pip install -r requirements.txt" command.
5. This project uses PostgreSQL DB. Go to setting.py file in the project directory and update the database credentials and other detials.
6. Execute following commands in terminal/CMD:
7.   python manage.py makemigrations
8.   python manage.py migrate
9.   python manage.py runserver
10. Now the project should be running and the end point "http://localhost:8000/api/fetchjokes/" is ready to serve.

**Packages**
Package             Version
------------------- ---------
asgiref             3.8.1
certifi             2025.1.31
charset-normalizer  3.4.1
Django              5.1.7
djangorestframework 3.16.0
idna                3.10
pip                 23.2.1
psycopg2            2.9.10
python-dotenv       1.1.0
requests            2.32.3
sqlparse            0.5.3
tzdata              2025.2
urllib3             2.3.0
