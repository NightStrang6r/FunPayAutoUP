<h1 align="center">
    FunPayServer
</h1>

<h4 align="center">
    Консольное приложение для автоматического управления вашим аккаунтом FunPay
</h4>

![FunPayServer](https://i.ibb.co/30BrFGr/Screenshot-107.png "FunPayServer")

[![Downloads][downloads-shield]][downloads-link]
[![Downloads][stars-shield]][stars-link]

## 🤖 **Возможности**

1. Автовыдача товаров.
2. Автоподнятие предложений.
3. Автовосстановление предложений после продажи.
4. Автоответ на сообщения.
5. Автоответ на первые сообщения.
6. Вечный онлайн.
7. Мгновенные уведомления о новых сообщениях.
8. Уведомления о новых заказах.
9. Уведомления о выдаче товара.
10. Уведомления о поднятии лотов.

## 🏆 **Преимущества**

- Хорошая оптимизация <br />
    *Для работы достаточно до 100мб свободного места на диске, 64-разрядная OS, любой процессор, до 250 мб ОЗУ, доступ в Интернет*
- Доступность <br />
    *Программу можно запустить на любой платформе, которую поддерживает NodeJS: от Windows и Linux, до Android, и iOS.*
- Управление через Telegram
- Наличие самого нужного функционала
- Бесплатно

## ⚡ **Установка**

<h3 align="center" >🔷 Windows 🔷</h3>

Данный вид установки подходит для большинства пользователей.

1. Скачайте `FunPayServer.exe` со страницы **[релизов](https://github.com/NightStrang6r/FunPayServer/releases)**.
2. Переместите программу в любую папку.
3. Получите `golden_key` из cookie FunPay. Вы можете использовать расширение [Edit This Cookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg). 
4. Запустите программу и следуйте инструкциям в консоли. Готово!

<h3 align="center" >🔨 Windows (продвинутая установка) 🔨</h3>

Данный вид установки подходит пользователей, которым нужен больший контроль над работой программы.

1. Установите **[Node.JS](https://nodejs.org/en/)**.
2. Скачайте исходный код **[Source code.zip](https://github.com/NightStrang6r/FunPayServer/releases)**.
3. Распакуйте загруженный архив в любую папку.
5. Получите `golden_key` из cookie FunPay. Вы можете использовать расширение [Edit This Cookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg). 
4. Запустите файл `Start.bat`, это установит зависимости для работы программы. После запустите этот файл повторно и следуйте инструкциям в консоли. Готово!

<h3 align="center" >♨️ Linux / Ubuntu ♨️</h3>

Устанавливать можно как на системы с GUI, так и на системы без него. Все версии Ubuntu начиная с 16.04 подходят для установки.
Данный вид установки предусматривает то, что вы будете запускать с source code, инструкцию по установке через .exe файл можно посмотреть в полной статье.
- **[Статья](https://lolz.guru/threads/4287473/)**

Установка NodeJS:
1. После входа в систему пропишите команду `sudo apt update && sudo apt upgrade`
2. Скачайте curl с помощью команды `sudo apt-get install curl`
3. Установите деб-пакет NodeJS при помощи команды `curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -`
4. Установите NodeJS при помощи команды : `sudo apt-get install nodejs`
5. Проверьте версию с помощью команды `node -v`, у вас должна отображаться версия 16, но любая версия выше тоже подойдет.

Включение бота:
1. Пропишите команду `cd (Название папки куда вы загрузили FunPayServer, можно написать часть названия и нажать tab , Linux сам подберет подходящую папку)`
2. Прописываем команду `npm i`, ждем загрузки. 
3. После загрузки прописываем команду `node .`
4. Готово! Бот запущен!

Далее работа с ботом не отличается от Windows версии.
<h3 align="center" >⚫ Termux (Android) ⚫</h3>

1. Установите **Termux** на свой Android одним из вариантов: 
- [Скачать через F-Droid](https://f-droid.org/en/packages/com.termux/) - на странице кнопка "**Download APK**" (рекомендуется)
- [Скачать со страницы релизов Termux](https://github.com/termux/termux-app/releases) - нужен файл `termux-app_v0.118.0+github-debug_universal.apk`, либо более новой версии
- [Скачать через Google Play](https://play.google.com/store/apps/details?id=com.termux) (**важно:** версия Termux из Google Play больше **не обновляется**)
2. Обновите пакеты, выполнив команду `apt update && apt upgrade`.
3. Выполните команду `pkg install nodejs wget unzip`.
4. Выполните команду `wget https://github.com/NightStrang6r/FunPayServer/archive/refs/heads/main.zip && unzip main.zip`.
5. Перейдите в папку проекта, выполнив команду `cd FunPayServer-main`.
6. Выполните команды: `npm i`, `node .` (не пропустите точку!).
7. Следуйте инструкциям консоли. Готово!

<h3 align="center" >🔴 FreeBSD 🔴</h3>

Установка только на системы без GUI через source code. Все версии начиная с 13.1 поддерживаются. Установка на FreeBSD самая простая из всех систем.
Минусы: кириллица не поддерживается, для её отображения вам нужно будет скачивать дополнительные пакеты, в этом гайде их не будет. Без этих пакетов все кириллические символы будут переведены в знаки вопроса.
Установка NodeJS и его компонентов:
1. Установите NodeJS используя команду `pkg install nodejs`
2. Установите npm используя команду `pkg install npm-8.19.1`
3. Перезагрузитесь используя команду `reboot`
Запуск бота (аналогичный запуску на Linux) :
1. Пропишите команду `cd (Название папки куда вы загрузили FunPayServer, можно написать часть названия и нажать tab, FreeBSD сам подберет подходящую папку)`
2. Прописываем команду `npm i`, ждем загрузки. 
3. После загрузки прописываем команду `node .`
4. Готово! Бот запущен!

## 📦 Настройка автовыдачи

1. Проверьте, что в файле `settings.txt` включена настройка автовыдачи: `autoDelivery: 1`.
2. Переходим в папку `data/configs`, открываем файл `delivery.json`.
3. Заполняем необходимыми товарами в формате JSON по примерам:
- Если у вас выдаётся один и тот же товар (к примеру, какая-либо инструкция):
```
[{
    "name": "ТУТ ТОЧЬ В ТОЧЬ НАЗВАНИЕ ТОВАРА НА FUNPAY",
    "message": "Тут сообщение, которое будет выдано после оплаты. Для переноса строки используйте символы \n. Пример: первая строка\nвторая строка"
},
{
    "name": "ТУТ ТОЧЬ В ТОЧЬ НАЗВАНИЕ ТОВАРА НА FUNPAY",
    "message": "Тут другое сообщение, которое будет выдано после оплаты другого лота"
}]
```
- Если у вас выдаются разные товары (например, аккаунты):
```
[{
    "name": "ТУТ ТОЧЬ В ТОЧЬ НАЗВАНИЕ ТОВАРА НА FUNPAY",
    "nodes": [
        "Тут сообщение, которое будет выдано после первой оплаты. Для переноса строки используйте символы \n. Пример: первая строка\nвторая строка ",
        "Тут сообщение, которое будет выдано после второй оплаты данного лота."
    ],
    "name": "ТУТ ТОЧЬ В ТОЧЬ НАЗВАНИЕ ТОВАРА НА FUNPAY",
    "nodes": [
        "Тут сообщение, которое будет выдано после первой оплаты. Для переноса строки используйте символы \n. Пример: первая строка\nвторая строка ",
        "Тут сообщение, которое будет выдано после второй оплаты данного лота."
    ]
}]
```
- Их можно комбинировать:
```
[{
    "name": "ТУТ ТОЧЬ В ТОЧЬ НАЗВАНИЕ ТОВАРА НА FUNPAY",
    "nodes": [
        "Тут сообщение, которое будет выдано после первой оплаты. Для переноса строки используйте символы \n. Пример: первая строка\nвторая строка ",
        "Тут сообщение, которое будет выдано после второй оплаты данного лота."
    ]
},
{
    "name": "ТУТ ТОЧЬ В ТОЧЬ НАЗВАНИЕ ТОВАРА НА FUNPAY",
    "message": "Тут сообщение, которое будет выдано после оплаты. Для переноса строки используйте символы \n. Пример: первая строка\nвторая строка"
}]
```
Для проверки правильности заполнения файла можете использовать сервис http://json.parser.online.fr
Для проверки работы автовыдачи без покупки товара используйте команду в чате: `!автовыдача "НАЗВАНИЕ ПРЕДЛОЖЕНИЯ"`. Для включения данной команды пропишите в файле настроек `settings.txt` `autoIssueTestCommand: 1` и `autoResponse: 1`.

4. Сохраняем и перезапускаем программу.

## 💬 Настройка автоответа

1. Проверьте, что в файле `settings.txt` включена настройка автовыдачи: `autoResponse: 1`.
2. Переходим в папку `data`, открываем файл `autoResponse.json`.
3. Заполняем необходимыми ответами в формате JSON по примерам:

```
[
    {
        "command": "!тест",
        "response": "Тестовое сообщение"
    },
    {
        "command": "!команда",
        "response": "Ответ на команду"
    }
]
```

4. Сохраняем и перезапускаем программу.

## 💲 Функция подсчёта продаж / заработка

*До версии 0.5.0*
Бот может подсчитать количество продаж и сумму заработанных средств с продаж. Для этого запустите файл `FunPayServer.exe` с параметром `--countProfit`, т.е. чтобы получилось `FunPayServer.exe --countProfit`. Запустить файл с параметром можно при помощи командной строки. Если вы использовали продвинутую установку, просто запустите файл `CountTradeProfit.bat`.

## 🌀 Работа с прокси

Бот поддерживает работу с http / https прокси с / без авторизации. Для включения работы через прокси пропишите в файле настроек `settings.txt` настройку `"useProxy": true`, а также данные хоста в поле `host` и порт в поле `port`. Если ваш прокси не требует авторизации, оставьте поля `login` и `pass` пустыми.

## ⚙️ Файл настроек

Бот имеет модульную структуру, что позволяет отключать или подключать необходимые модули, редактируя файл настроек `settings.txt`. Этот файл генерируется автоматически при первом запуске. После редактирования файла не забудьте перезапустить программу.

```
[FunPay]
# Настройки FunPay бота

# Ключ авторизации в FunPay.
# Получите его с помощью расширения Edit This Cookie для браузера.
golden_key: key

# User-agent браузера. Необходимо указывать user-agent именно того браузера, откуда был взят golden_key
# Получить его можно тут: https://wtools.io/ru/check-my-user-agent
user_agent: agent

# Всегда онлайн. [1 - включить, 0 - выключить]
alwaysOnline: 1

# Автоподнятие лотов. [1 - включить, 0 - выключить]
lotsRaise: 1

# Автоактивация лотов после продажи. [1 - включить, 0 - выключить]
goodsStateCheck: 0

# Автовыдача товаров. [1 - включить, 0 - выключить]
autoDelivery: 1

# Автоответ. [1 - включить, 0 - выключить]
autoResponse: 1

# Приветственное сообщение для новых покупателей. [1 - включить, 0 - выключить]
greetingMessage: 1

# Текст приветственного сообщения для новых покупателей.
greetingMessageText: Привет! Продавец скоро ответит на твоё сообщение.

# Команда для проверки работы автовыдачи. [1 - включить, 0 - выключить]
autoDeliveryTestCommand: 0

# Текст, который отправляется в самом начале каждого сообщения бота в чате.
waterMark: [ 🔥NightBot ]


[Telegram]
# Настройки Telegram бота

# Включить бота. [1 - включить, 0 - выключить]
enabled: 0

# Токен бота. Получить его можно у @BotFather
token: key

# Ник (логин) администратора в Telegram без @. Нужен для авторизации в боте.
userName: MyTelegramLogin

# Уведомления о новом сообщении. [1 - включить, 0 - выключить]
newMessageNotification: 1

# Уведомления о новом заказе. [1 - включить, 0 - выключить]
newOrderNotification: 1

# Уведомления о поднятии лотов. [1 - включить, 0 - выключить]
lotsRaiseNotification: 1

# Уведомления о выдаче товара. [1 - включить, 0 - выключить]
deliveryNotification: 1


[Proxy]
# Настройки прокси

# Включить прокси. [1 - включить, 0 - выключить]
enabled: 0

# Хост прокси
host:

# Порт прокси
port:

# Логин прокси (если есть)
login:

# Пароль прокси (если есть)
pass: 

# Тип прокси. [http]
type: http
```

## 🔥 Аналоги
Если по какой-то причине данная версия бота не подходит для вас, попробуйте расширение для браузера - [FunPay Lite Bot](https://chrome.google.com/webstore/detail/funpay-lite-bot/amicfiagmpbgfiiopieeemlkblfeeeip). Функционал расширения будет дополняться со временем.

## 📧 Контакты
Если у вас есть какие-либо вопросы, я буду рад ответить.

Быстрый ответ:

- Telegram - [FunPay Communuty - chat / support](https://t.me/fplite)

Более долгий ответ:

- Lolz.Guru - https://zelenka.guru/threads/4701540/

## 🎉 Понравилось приложение?

Оцените данный репозиторий, поставив звёздчку в верхнем правом углу страницы на GitHub (нужно быть авторизованным в свой аккаунт). Это даёт мне мотивацию развивать данный проект.

![](https://i.ibb.co/x3hFFvf/2022-08-18-132617815.png)

Вы также можете поддержать разработчика материально, чтобы ускорить выход будущих обновлений:

- [Monobank](https://send.monobank.ua/jar/7fiVkcrWYv)
- [DonationAlerts](https://www.donationalerts.com/r/nightstranger)

[downloads-shield]: https://img.shields.io/github/downloads/NightStrang6r/FunPayServer/total?color=purple&logo=GitHub&style=for-the-badge
[downloads-link]: https://github.com/NightStrang6r/FunPayServer/releases/latest

[stars-shield]: https://img.shields.io/github/stars/NightStrang6r/FunPayServer?color=purple&logo=Stars&style=for-the-badge
[stars-link]: https://github.com/NightStrang6r/FunPayServer/
