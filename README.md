For start:
```cmd
python manage.py runserve
```
Port: 8000

Requests:
  Post:
      for register: 
      ```
      {
      "email":"ex@gmail.com",
      "username":"asdff",
      "password":"обязательно длиннее 6 символов"
      }
      ```
      for login:
      ```
      {
      "email":"",
      "password":""
      }
      ``` 
Считай что скопировал код с репо ниже.
При регистрации также испольуются cookie, пример подключения фронта:
https://github.com/dotja/authentication_app_react_django_rest
      
   
