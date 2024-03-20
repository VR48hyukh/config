# config

# Разработка
# Клонировать репозиторий
```
git clone https://github.com/VR48hyukh/config.git
```
Создать виртульное окружение 
```
cd pythonProject3

python -m venv venv
```

Активировать виртуальное окружение
Linux
```
source venv/bin/activate
```
Windows 
```
./venv/Scripts/activate
```
Устанавливить зависимости:
```
pip install -r req.txt
```
Выполнить команду для выполнения миграций 
```
python manage.py migrate
```
Создать суперпользователя
```
python manage.py createsuperuser
```
Запустить сервер
```
python manage.py runserver
```




