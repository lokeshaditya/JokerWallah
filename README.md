# JokerWallah
1. Remove the venv, pycache, .vscode folders.
2. Create your own virtual envirinment using "python -m venv venv"
3. Activate virtual environment
4. Install dependencies mentioned in the requirements.txt file using "pip install -r requirements.txt" command
5. Go to setting.py file in the main project directory and update the database credentials and other detials
6. Execute following commands in terminal/CMD:
7.   python manage.py makemigrations
8.   python manage.py migrate
9.   python manage.py runserver
10. Now the project should be running and the end point "http://localhost:8000/api/fetchjokes/" is ready to serve.
