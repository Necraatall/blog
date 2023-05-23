## from tutorial:

https://realpython.com/python-django-blog/


## create virtual environment .venv
```
python3.9 -m venv .venv
```


## activate/deactivate .venv
in main folder:
```
source .venv/bin/activate
==> (.venv) milan@milan:~/Programy/graphql/blog$ 

deactivate
==> milan@milan:~/Programy/graphql/blog$ 
```


## install all packages for pip3
python3 -m pip install -r requirements.txt

## run django migrations
```
(venv) $ python manage.py migrate

```
## first time or after changing django blog/models.py run
```
(venv) $ python manage.py makemigrations
```

## run django server
```
(venv) $ python manage.py runserver
```

## install vue
by this tutorial:
https://www.google.com/search?q=how+to+make+package.json&oq=how+to+make+package.json&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIICAEQABgWGB4yCAgCEAAYFhgeMggIAxAAGBYYHjIICAQQABgWGB4yCAgFEAAYFhgeMggIBhAAGBYYHjIICAcQABgWGB4yCAgIEAAYFhgeMggICRAAGBYYHtIBCTE0MTYzajBqN6gCALACAA&sourceid=chrome&ie=UTF-8#kpvalbx=_uNBsZN60OsOL9u8PmduS6AQ_38

or:
```
npm init
```

## Install Vue Plugins
on the core project
```
$ npx @vue/cli create frontend --default
```
