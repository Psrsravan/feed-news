# feed-news
feed/news_django


S C:\sravan\itvedant> base\Scripts\activate
(base) PS C:\sravan\itvedant> python manage.py runserver
C:\Users\shesh\AppData\Local\Programs\Python\Python312\python.exe: can't open file 'C:\\sravan\\itvedant\\manage.py': [Errno 2] No such file or directory
(base) PS C:\sravan\itvedant> cd .\Django-To-Do-list-with-user-authentication-master\
(base) PS C:\sravan\itvedant\Django-To-Do-list-with-user-authentication-master> python manage.py runserver                             
Traceback (most recent call last):
  File "C:\sravan\itvedant\Django-To-Do-list-with-user-authentication-master\manage.py", line 10, in main
    from django.core.management import execute_from_command_line
ModuleNotFoundError: No module named 'django'

The above exception was the direct cause of the following exception:

Traceback (most recent call last):
  File "C:\sravan\itvedant\Django-To-Do-list-with-user-authentication-master\manage.py", line 21, in <module>
    main()
  File "C:\sravan\itvedant\Django-To-Do-list-with-user-authentication-master\manage.py", line 12, in main
    raise ImportError(
ImportError: Couldn't import Django. Are you sure it's installed and available on your PYTHONPATH environment variable? Did you forget to activate a virtual environment?
(base) PS C:\sravan\itvedant\Django-To-Do-list-with-user-authentication-master> pip install django
Collecting django
  Obtaining dependency information for django from https://files.pythonhosted.org/packages/ba/c7/61b02c0ef9e129080a8c2bffefb3cb2b9ddddece4c44dc473c1c4f0647c1/Django-5.0-py3-none-any.whl.metadata
  Downloading Django-5.0-py3-none-any.whl.metadata (4.1 kB)
Collecting asgiref>=3.7.0 (from django)
  Obtaining dependency information for asgiref>=3.7.0 from https://files.pythonhosted.org/packages/9b/80/b9051a4a07ad231558fcd8ffc89232711b4e618c15cb7a392a17384bbeef/asgiref-3.7.2-py3-none-any.whl.metadata
  Using cached asgiref-3.7.2-py3-none-any.whl.metadata (9.2 kB)
Collecting sqlparse>=0.3.1 (from django)
  Using cached sqlparse-0.4.4-py3-none-any.whl (41 kB)
Collecting tzdata (from django)
  Using cached tzdata-2023.3-py2.py3-none-any.whl (341 kB)
Downloading Django-5.0-py3-none-any.whl (8.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.1/8.1 MB 3.2 MB/s eta 0:00:00
Using cached asgiref-3.7.2-py3-none-any.whl (24 kB)
Installing collected packages: tzdata, sqlparse, asgiref, django
Successfully installed asgiref-3.7.2 django-5.0 sqlparse-0.4.4 tzdata-2023.3

[notice] A new release of pip is available: 23.2.1 -> 23.3.1
[notice] To update, run: python.exe -m pip install --upgrade pip
(base) PS C:\sravan\itvedant\Django-To-Do-list-with-user-authentication-master> python manage.py runserver                             
Watching for file changes with StatReloader
Performing system checks...

System check identified some issues:

WARNINGS:
base.Task: (models.W042) Auto-created primary key used when not defining a primary key type, by default 'django.db.models.AutoField'.
        HINT: Configure the DEFAULT_AUTO_FIELD setting or the BaseConfig.default_auto_field attribute to point to a subclass of AutoField, e.g. 'django.db.models.BigAutoField'.

System check identified 1 issue (0 silenced).
December 14, 2023 - 11:12:12
Django version 5.0, using settings 'todo_list.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

[14/Dec/2023 11:12:16] "GET / HTTP/1.1" 302 0
[14/Dec/2023 11:12:16] "GET /login/?next=/ HTTP/1.1" 200 5465
Not Found: /favicon.ico
[14/Dec/2023 11:12:17] "GET /favicon.ico HTTP/1.1" 404 3711
[14/Dec/2023 11:12:22] "POST /login/?next=/ HTTP/1.1" 200 5623
[14/Dec/2023 11:12:26] "GET /register/ HTTP/1.1" 200 5672
[14/Dec/2023 11:13:31] "POST /register/ HTTP/1.1" 200 5707
[14/Dec/2023 11:14:04] "POST /register/ HTTP/1.1" 200 5707
[14/Dec/2023 11:14:09] "GET /login/ HTTP/1.1" 200 5465
[14/Dec/2023 11:14:12] "POST /login/ HTTP/1.1" 200 5623
[14/Dec/2023 11:14:16] "POST /login/ HTTP/1.1" 200 5623
[14/Dec/2023 11:14:36] "POST /login/ HTTP/1.1" 200 5623
[14/Dec/2023 11:14:42] "GET /register/ HTTP/1.1" 200 5672
[14/Dec/2023 11:15:10] "POST /register/ HTTP/1.1" 200 5707
[14/Dec/2023 11:15:28] "POST /register/ HTTP/1.1" 200 5707
[14/Dec/2023 11:16:10] "POST /register/ HTTP/1.1" 200 570
