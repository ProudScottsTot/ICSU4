# CalorieCalculator

Example applications for Flask beginners.

## Installation

First, you need to clone this repository:

```bash
$ git clone https://github.com/atwjsw/CalorieCalculator.git
```

Then change into the `CalorieCalculator` folder:

```bash
$ cd CalorieCalculator
```

Now, we will need to create a virtual environment and install all the dependencies:

```bash
$ python3 -m venv venv  # on Windows, use "python -m venv venv" instead
$ . venv/bin/activate  # on Windows, use "venv\Scripts\activate" instead
$ pip install -r requirements.txt
```
## How to Run the Application?

**Before run a specific example application, make sure you have activated the virtual enviroment.**

```bash
python3 run.py # on Windows, user "python run.py"
```bash

## Other useful commands for creating the project

deactivate

pip install flask
pip install flask-sqlalchemy
pip install flask-wtf
pip install wtforms
pip install email_validator
pip install bcrypt
pip install flask_bcrypt
pip install flask_login
pip freeze > requirements.txt
pip install -r requirements.txt

from market import db
db.create_all()
db.drop_all()
from market import Item
item1 = Item(name="IPhone 10", price=500, barcode='846154104831', description='iphone 10 desc')
item2 = Item(name="Laptop", price=600, barcode='846154104832', description='Laptop desc')
u1 = User(username='jsc', password_hash = '123456', email_address = 'jsc@jsc.com')
db.session.add(item2)
db.session.commit()
Item.query.all()
db.session.rollback()

for item in Item.query.all()
for item in Item.query.filter_by(price = 500)

import os
os.system('cls')

import os
os.urandom(12)

## Useful resources
https://github.com/flatcoke/flask-structure
https://www.twilio.com/docs/usage/tutorials/how-to-set-up-your-python-and-flask-development-environment
https://github.com/greyli/flask-examples
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
