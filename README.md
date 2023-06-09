## Описание
Проект представляет собой коллекцию для сбора данных из сети Интернет

Функционал:

* Получить список репозиториев для конкретного пользователя GitHub, с сохранением в файле *.json;

* Получить список всех сообществ на которые вы подписаны вконтакте;

* Поиск вакансий с заработной платой используя сервис hh.ru, 
  с выводом информации в DataFrame и сохранением в базе данных MongoDB;

* Парсинг новостей с сайта lenta.ru, с сохранением в базе данных MongoDB;

* Сбор входящих писем из своего почтового ящика, с сохранением в базе данных MongoDB;

* Сбор данных о книгах с сайта labirint.ru с использованием библиотеки Scrapy 
  и сохранением в базе данных MongoDB.


## Как запустить проект:
1. Клонировать репозиторий и перейти в папку (каталог) в командной строке:
```
git clone git@github.com:matrosovmn/GB_Scraping.git
```
```
cd GB_Scraping/
```
2. Cоздать и активировать виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```
3. Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
4. Cоздать файл .env в корневой папке проекта:
```
touch .env
```
5. Открыть файл .env, добавить в него логины и пароли в следующем формате:
```
USER_ID=ваш_user_id
LOGIN=ваш_логин
PASSWORD=ваш_пароль
```
6. Развернуть у себя на компьютере/виртуальной машине/хостинге MongoDB
https://www.mongodb.com/try/download/community
7. Скорректировать для MongoDB host (пример для локальной машины):
mongodb://localhost:27017
иначе
mongodb://127.0.0.1:27017/

## Об авторе
Начинающий разработчик Михаил Матросов. С моими другими работами вы можете ознакомится по ссылке: https://github.com/matrosovmn


![Jokes Card](https://readme-jokes.vercel.app/api)

