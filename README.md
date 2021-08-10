# discordpy-eval
Команда eval для discord.py

## Требования:
- Python 3.6 и выше

## Использование:
### Для начала нужно настроить бота [здесь](https://discord.com/developers/applications)
Нажимаем на кнопку "New Application" справа сверху, придумываем нашему **приложению** название и нажимаем "Create" (окно может немного отличаться). 
*Можно использовать и уже созданное приложение*

![Создаём приложение, окно может немного отличаться](https://cdn.discordapp.com/attachments/859866304395608154/874737298875502632/unknown.png)

Далее переходим на вкладку "Bot", нажимаем "Add Bot", подтверждаем
![Добавляем бота к приложению](https://cdn.discordapp.com/attachments/859866304395608154/874738037878325298/unknown.png)

Копируем токен куда-нибудь при помощии соответствующей кнопки:

![Копируем токен](https://cdn.discordapp.com/attachments/859866304395608154/874739131018792980/unknown.png)

...и ниже включаем эти параметры под заголовком "Priveleged Gateway Intents":

![Интенты и их включение](https://cdn.discordapp.com/attachments/859866304395608154/874740073139171408/unknown.png)

Не забудьте сохраниться!

Пригласим бота на сервер с помощью вкладки OAuth2: перейдём в неё и в поле Scopes выберем "Bot". Ниже появилось ещё одно поле, где мы выбираем только Administrator. Выше появилась ссылка, на которую мы переходим и, как мы это обычно делаем, добавляем бота
![Генерация ссылки-приглашения](https://cdn.discordapp.com/attachments/859866304395608154/874742022110605402/unknown.png)
![Приглашение](https://cdn.discordapp.com/attachments/859866304395608154/874742612307898398/unknown.png)

Можно закрыть браузер

### Установка
Для начала откроем консоль и напишем:
На Windows:
```batch
pip install discord
pip install aeval
```

(можете добавить перед каждым 'pip' python -m)

На Linux/Mac OS:
```bash
pip3 install discord
pip3 install aeval
```
Теперь скачайте файл eval.py (в нём всё подробно расписано), вставьте токен в bot.run (самый конец файла), через ту же консоль перейдите в папку, куда вы его скачали и запустите (просто написав eval.py, или добавив в начало py/python/python3)

## Остались вопросы? Пишите в Discord - Егор Брон#3443, отвечу!