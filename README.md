# JokerWallah
**STEPS:**
1. Remove the venv, pycache, .vscode folders.
2. Create your own virtual environment using "python -m venv venv"
3. Activate virtual environment.
4. Install dependencies mentioned in the requirements.txt file using the "pip install -r requirements.txt" command.
5. This project uses PostgreSQL DB. Go to the setting.py file in the project directory and update the database credentials and other details.
6. Execute the following commands in the terminal/CMD:
7.   python manage.py makemigrations
8.   python manage.py migrate
9.   python manage.py runserver
10. Now the project should be running, and the endpoint "http://localhost:8000/api/fetchjokes/" is ready to serve.


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


**Improvements**
1. JokerAPI cannot fetch more than 10 Jokes at a time. To fetch 100 Jokes, instead of running the loop 10 times, I can implement multithreading to speed up the process.
2. Currently, the program inserts one record at a time into the database in a loop. I can use _bulk_create_ option to reduce the no. of DB calls there by improving the Network efficiency.
3. Admin console can be integrated to check the Jokes in the Database. 
