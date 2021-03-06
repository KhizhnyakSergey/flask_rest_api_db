
## My second experience with the Flask framework


This is a simple project but with a connected database. 
Model (Task) which has 2 fields 'id' and 'name'.
This project implemented CRUD.


## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/KhizhnyakSergey/flask_rest_api_db
$ cd flask_rest_api_db
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ python -m venv venv
$ venv\Scripts\activate
```

Then install the dependencies:

```sh
(venv)$ pip install -r requirements.txt
```
Note the `(venv)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `venv`.

Once `pip` has finished downloading the dependencies:
```sh
(venv)$ python app.py
```
And navigate to `http://127.0.0.1:5000`.
