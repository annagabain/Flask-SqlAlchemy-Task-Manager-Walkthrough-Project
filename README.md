pip install Flask

pip install SQLAlchemy

pip3 install 'Flask-SQLAlchemy<3' psycopg2

----------

If you get the following error after typing psql in the terminal:
psql: error: could not connect to server: No such file or directory

Please use the following command in the terminal to set an environment variable needed for it to work:

set_pg

And then try the psql command again