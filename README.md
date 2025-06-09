# api_final
api final

### О проекте
API-Yatube - социальная сеть, в которой пользователи могут зарегистрироваться, создать, отредактировать или удалить собственный пост, прокомментировать пост другого автора и подписаться на него 

### Как запустить проект
Клонировать репозиторий и перейти в него:

```
git clone https://github.com/Vlad0S1337/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
venv/Scripts/activate
```

Установить зависимости из файла:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py makemigrations
```

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```