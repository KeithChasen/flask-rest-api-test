install pip environment
```
pip3 install pipenv
```

Run pipenv shell

```
pipenv shell
```

To create sqlite db
Inside your pipenv

````
python

from app import db

db.create_all()

````

that will create db.sqlite file in you root folder


