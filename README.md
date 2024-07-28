<div align=center>
    
# Приложение Отзывы о фильмах

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/Flask-20232A?style=for-the-badge&logo=flask&logoColor=white)

</div>

## Описание проекта

**Возможности для пользователей сайта:**

- Получить случайное мнение о фильме.
- Перейти на страницу конкретного мнения по прямой ссылке.
- Добавить собственное мнение о фильме.

Так же у проекта есть API:

- GET получить все отзывы:
- POST добавить отзыв:

```python
http://<your_domain>/api/opinions/
```

- GET получить отзыв по id:
- PATCH обновить отзыв по id:
- DELETE удалить отзыв по id:

```
http://<your_domain>/api/opinions/<int:id>/
```

- GET получить случайный отзыв:

```python
http://<your_domain>/api/get-random-opinion/
```

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone
```

```
cd cinema_opinions
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

или для пользователей Windows

```
source env/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Запустить проект:

```
flask run
```

# Автор:

**Форов Александр**

[![Telegram Badge](https://img.shields.io/badge/-Light_88-blue?style=social&logo=telegram&link=https://t.me/Light_88)](https://t.me/Light_88) [![Gmail Badge](https://img.shields.io/badge/forov.py@gmail.com-c14438?style=flat&logo=Gmail&logoColor=white&link=mailto:forov.py@gmail.com)](mailto:forov.py@gmail.com)
