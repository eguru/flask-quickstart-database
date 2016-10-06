# Flask Quickstart With Database

The Quickstart With Database project gives a quick setup to a dummy project that has a database. This project only gives bare minimum code required to get started.

For other quickstart projects, refer to the following projects:

* [Flask Quickstart] (https://github.com/eguru/flask-quickstart)
* [Flask Quickstart With Database & Flask-Admin] (https://github.com/eguru/flask-quickstart-database-admin)
* [Flask Quickstart With SSL] (https://github.com/eguru/flask-quickstart-ssl)

# Installation

First, simply get a copy of the project:

```
git clone https://github.com/eguru/flask-quickstart-database.git
```

Now, create a virtual environment, see virtualenv installation [here] (https://virtualenv.pypa.io/en/stable/installation/):

```
cd flask-quickstart-database/
virtualenv venv
```

Activate the virtual environment:

```
source venv/bin/activate
```

Install the Flask framework:

```
pip install flask
```

Install the Flask's SQLAlchemy extension:

```
pip install flask_sqlalchemy
```

Now, simply start the server:

```
python server.py
```

Open up your web browser and enter the following location:

```
http://localhost:8080
```
