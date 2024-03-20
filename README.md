# config
# Разработка
#1) Клонировать репозиторий
```
git clone https://github.com/VR48hyukh/config.git
```
2) Создать виртульное окружение 
```
cd pythonProject3

python -m venv venv
```

3) Активировать виртуальное окружение
   
#Linux
```
source venv/bin/activate
```
#Windows 
```
./venv/Scripts/activate
```
4) Установить зависимости:
```
pip install -r req.txt
```
5) Выполнить команду для выполнения миграций 
```
python manage.py migrate
```
6) Создать суперпользователя
```
python manage.py createsuperuser
```
7) Запустить сервер
```
python manage.py runserver
```




