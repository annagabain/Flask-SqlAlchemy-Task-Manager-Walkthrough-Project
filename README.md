# Deployed App:

## https://task-manager-walkthrough-pr.herokuapp.com/

In Terminal:

pip3 install 'Flask-SQLAlchemy<3' psycopg2

----------

If you get the following error after typing psql in the terminal:
psql: error: could not connect to server: No such file or directory

Please use the following command in the terminal to set an environment variable needed for it to work:

set_pg

And then try the psql command again


----------

CREATE DATABASE taskmanager;

to exit:  \q

----------

python3

from taskmanager import db

db.create_all()

to exit:  exit()

----------

Run the programme:

### python3 run.py
