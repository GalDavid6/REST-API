# Store REST-API

## Description 

REST-API framework for a store.
Including API for Users(Register, Login, Logout & Authentication) and Stores/Items(Add, Update, Remove)

#### Technologies

- Python
- Postman(Optinal) - Not must, I tested the app with Postman you can also doing that using your browser

## Libraries

- Flask 
- Flask-restFUL
- Flask-JWT-Extended
- Flask-SQLAlchemy

#### Project Files

- app.py - the main program.
- db.py - importing and creating SQLAlchemy object.
- blacklist.py - set(object) of blocked user.
- requirements.txt - List of all libraries needed to run the app.
- models(folder) - OOP (Items, Stores, Users).
- resource(folder) - Resources (Items, Stores, Users).

## How To Use

After installing the relevant libraries, run app.py.
It will create your Database and Tables automatically,
Enjoy you are ready to go.

#### Installation

```
pip install Flask
pip install Flask_JWT_extended
pip install flask_restful
pip install flask_sqlalchemy
python app.py
```

## Author Info

- Github - [GalDavid6](https://github.com/GalDavid6)
- Linkedin - [Gal David](https://www.linkedin.com/in/gal-david-22871a182/)
