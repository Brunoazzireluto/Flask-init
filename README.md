# Flask Init

An initial model of application in Flask.

### 🔗 Other Versions of this Readme

[Portuguese version](README-pt.md)

### 📖 About

An initial Flask application model using the Factory model.
This template facilitates the creation of initial files saving time and making implementation easier.
The template comes with FlaskSQL-alchemy and Flask-WTF ready to use. having only to configure the database paths.

### 📋 Prerequisites

```
Python 3.8 or superior
Pip 20.0 or superior
virtualenv 20.4 ou or superior
```

### 🔧 Installation

To install the requirements it is necessary to first create a virtual environment so that we can use the app.

**Linux**
virtualenv installation:
```
sudo apt-get install python3-venv
```
creating the virtual environment:
```
python3 -m venv environment_name
```
to activate the virtual environment:
```
source environment_name/bin/activate
```
With the environment properly activated, we install the requirements with the following code:
```
pip3 install -r requirements.txt
```
after installing the frameworks don't forget to change the paths to the databases

## ⚙️ Running the tests

With virtualenv enabled you can run the Application on localhost we use the following code, to run the application in production change the type of environment.

```
flask run
```

## 🛠️ Built with

Tools used in creating this application

 * python

* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
* [Flask-WTF](https://flask-wtf.readthedocs.io/en/stable/)


## ✒️ Developers

* **Bruno Alves** - *Developers Fullstack* - [Bruno Azzireluto](https://github.com/Brunoazzireluto)

---
A project of [Azzireluto](https://github.com/Brunoazzireluto)
