# Institution System
A full Institution management System website using flask. Full CRUD( create, read, update, delete ) facility

## How to work in this project
``` 
$ git clone https://github.com/arinetf3321/school_app
```


## How to run this flask app

### Windows
``` bash
> set FLASK_APP=run.py
> set FLASK_ENV=development
> flask run
```

### Mac and Linux
``` shell
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
$ flask run
```

### NEW ###
create .env file with keys.
create .flaskenv file with FLASK_ENV, FLASK_APP as shown above. Alse FLASK_DEBUG=...

To setup a new database run:
$ flask create_tables

This creates all tables in database site.db (conform db-url) with 3 Users records
