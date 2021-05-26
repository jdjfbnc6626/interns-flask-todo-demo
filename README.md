# Flask/Python-centric, not strict AWS
- https://www.python-engineer.com/posts/flask-todo-app/
- Better https://github.com/python-engineer/flask-todo
- https://flask-sqlalchemy.palletsprojects.com/en/2.x/

## Notes
- Nice virtual environment setup - compare to npm, and not polluting global python
jjtu:~/DEV-OPS-PRO/flask-todo$ python3 -m venv venv
jjtu:~/DEV-OPS-PRO/flask-todo$ . venv/bin/activate
(venv) jjtu:~/DEV-OPS-PRO/flask-todo$
- SQLite just does everything local via SQLalchemy. Created a db.sqlite binary file here.

## Run app
- spin up virtual environment '. venv/bin/activate'
- from root folder 'python3 app.py' OR 'python app.py'
- now availalbe at localhost:5000 BUT FOR C9
- flask run -h localhost -p 8080
- to 8080

## Quick python demo within venv
- cars = ['car', car, 12, 1.3] - will error on car, not a string
- math 2+3
- print()
- cars.append('string')
- cars.pop(0) - index
- https://www.w3schools.com/python/python_getstarted.asp
- https://wiki.python.org/moin/BeginnersGuide