1 клонировать
git clone https://github.com/Rasul-1987/Rasul-1987.git
2 создать виртуальное окружение
python -m venv venv
python .venv\Scripts\activate
pip install -r requirements.txt
3 выполнить миграции
python manage.py makemigrations
python manage.py migrate
4 создать суперпользователя
python manage.py createsuperuser
5 запустить
python manage.py runserver