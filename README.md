# api_yatube
api_yatube

Cоздать и активировать виртуальное окружение:

```
py -3.9 -m venv env
```

```
source env/Scripts/activate

```
py -m pip install --upgrade pip

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
+-  python manage.py makemigrations
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```