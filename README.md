# Приложение "Библиотека" на Django v1

      Django, Sqlite3
      
Описание:

      Приложение — личная библиотека. Это простая система, в которой храниться и отображаться информация о книгах, 
      которые в нее добавлены, а также есть возможность эти данные создавать, удалять и редактировать.

Разворачиваем проект локально:

1. Создайте виртуальное окружение: 

       python3 -m venv env
       
2. Активируйте виртуальное окружение: 

       source env/bin/activate
       
3. Чтобы установить требуемые зависимости выполните команду: 

       pip install -r requirements.txt
       
4. Чтбы запустить сервер введите команду: 

       python manage.py runserver

5. Для входа в администравтивную панель проекта создайте суперпользователя при помощи команды: 

       python manage.py createsuperuser

Список роутов проекта:

1. http://127.0.0.1:8000/admin/ - панель администратора Django

2. http://127.0.0.1:8000/index/ - таблица книг в билиотеке (есть также кнопки позволяющие увеличить/уменьшить колличество экземпляров)

![Список книг в библиотеке](https://github.com/AlenaPliusnina/Django_books_library_v1/blob/master/screenshots/screen_1.png)

3. http://127.0.0.1:8000/publishers/ - вывод списка издательств и их книг

![Список издательств](https://github.com/AlenaPliusnina/Django_books_library_v1/blob/master/screenshots/screen_2.png)

