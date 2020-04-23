# PCToolsBot


Автор не несёт ответсвенности за использование данного скрипта
Данный скрипт создан для упрощенного и защищенного управления СВОИМ ПК


Этот скрипт написан на Python, компилировать его необходимо вам, т.к. внутри скрипта вы указываете API телеграм бота и свой Telegram ID.

Пошаговая Инструкция:
1) Перейдите в телеграм и напишите @BotFather (t.me/BotFather)
2) Напишите команду /newbot в @BotFather
3) Напишите любое имя бота(пример: PC Tools) 
4) Напишите логин бота с окончанием на слово bot, советую писать рандомные символы(пример: nr9dsn6lsh_bot)
5)Вы получите сообщение примера: 
 "Done! Congratulations on your new bot. You will find it at t.me/asdfghjkl_bot.
  You can now add a description, about section and profile picture for your bot, see /help for a list of commands.
  By the way, when you've finished creating your cool bot, ping our Bot Support if you want a better username for it.
  Just make sure the bot is fully operational before you do this.

  Use this token to access the HTTP API:
  1234567:ASDFGHJKLQWERTY
  Keep your token secure and store it safely, it can be used by anyone to control your bot.

  For a description of the Bot API, see this page: https://core.telegram.org/bots/api"
  
  6) Нам необходимо скопировать API(1234567:ASDFGHJKLQWERTY)
  7) Переходим в созданного бота по ссылке из сообщения и нажимаем запустить
  8) Скачиваем с репозитория скрипт бота(PCToolsBot.py) и фaйл(install.txt)
  9) Переходим на офф. сайт https://www.python.org/downloads/ и скачиваем установщик python
  10) Открываем установщик и устанавливаем обязательно поставив галочку на пункте add to path
  11) Запускаем cmd(Win + R и вписываем cmd) 
  12) Пишем в cmd pip install -r путь до файла install.txt (пример: pip install -r C:\download\install.txt)
  13) Открываем через любой текстовый редактор PCToolsBot.py
  14) Вписываем в поле bot_token API бота который мы скопировали
  15) Вписываем в поле my_id ваш TELEGRAM ID(Можно у знать у бота @userinfobot (t.me/userinfobot))
  16) Сохраняем файл и переходим обратно в консоль
  17) пишем cd путь директории где лежит файл PCToolsBot.py
  18) Пишем в консоли pyinstaller -w -F PCToolsBot.py
  19) Перемещаем из папки dist exe-шник в удобну нам папку, создаем ярлык exe-шника
  20) Кидаем ярлык в C:\Users\Username\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
