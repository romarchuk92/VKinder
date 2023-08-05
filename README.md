# Командный проект по курсу "Профессиональная работа с Python"
![](https://thumb.cloud.mail.ru/weblink/thumb/xw1/JaaZ/2jdE4F9Bd)
программа-бот для взаимодействия с базами данных социальной сети. Бот предлагает различные варианты людей для знакомств в социальной сети ВКонтакте в виде диалога с пользователем.

## Запуск программы:
1.	Установить необходимые библиотеки:
``` 
    pip install -r requirements.txt
```
2.  [Настроить группу](https://github.com/netology-code/adpy-team-diplom/blob/main/group_settings.md) для взаимодействия с программой и разместить полученный токен в файле tokens.ini:
``` 
    VK_token_GROUP = YOU TOKEN
```
3.  [Получить токен пользователя](https://docs.google.com/document/d/1_xt16CMeaEir-tWLbUFyleZl6woEdJt-7eyva1coT3w/edit) ВКонтакте и разместить полученный токен в файле tokens.ini:
``` 
    VK_token = YOU TOKEN
```  
4.	Создать локальную БД на ПК командой:
``` 
    createdb -U postgres Coursework_2
```
где postgres - имя пользователя БД, Coursework_2 - имя БД.

5.  Настроить DSN для взаимодействия приложения с БД. В файле main.py ввести ваши данные:
``` 
    DSN = 'postgresql://postgres:password@localhost:5432/Coursework_2'
```
где postgres - имя пользователя БД, password - пароль БД, Coursework_2 - имя БД.

6.	Запустить выполнение файла main.py.



