Prerequisites:
Make sure you have python 3.x for this repository.

Environment setup:
1. Run `python -m venv .venv`
2. Launch your virtual environment with `. .venv/Scripts/activate` or `. .venv/bin/activate`
3. Run `pip install -r requirements.txt`

DB setup:
1. Open up a terminal and type `python` to enter the python shell.
2. Go to the root directory of this project and type the following: `from app import app, db`
3. Then type: `app.app_context().push()`
4. Then type: `db.create_all()`
This will initialize the database (which uses sqlite) in an `instance/` folder. I may convert this step to a script at some point.

Now with your DB ready, you can launch the application locally by running: `python app.py` in the terminal from the root directory.
Have fun!

Credits:
I followed a rough guide from freeCodeCamp.org for this and am going to use this for inspiration to create a chess app in the near future for the fun of it.