# bd_spbu
Первый запуск
Команды для первого запуска приложения:
docker-compose build
docker-compose up -d
docker-compose exec web python myshop3/manage.py makemigrations
docker-compose exec web python myshop3/manage.py migrate
docker-compose exec web python myshop3/manage.py createsuperuser

Адрес главной страницы http://0.0.0.0:8000
Панель администратора http://0.0.0.0:8000/admin

Для завершения работы 
docker-compose down

Дальнейшие запуски
Запустить
docker-compose up -d

Завершить
docker-compose down

