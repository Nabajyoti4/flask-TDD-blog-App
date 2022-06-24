# Flask Blog APP using TDD pattern 

1. Create a venv and activate it
2. Install the project requirements using `pip install -r requirements.txt`

3. Create a .flaskenv and set the flask_env path

    export FLASK_ENV=development
    export FLASK_APP=blog/app.py
    export FLASK_DEBUG=1

4. Create database with
  `python blog/init_db.py`

5. Now Run tests
   `python -m pytest tests`