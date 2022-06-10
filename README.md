# api_final  <img src ="https://img.shields.io/badge/django%20rest-ff1709?style=for-the-badge&logo=django&logoColor=white " />

API для проекта Yatube. Домашняя работа YandexPracticum по теме API.

## Как запустить проект <img src = "https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />

python -m venv env 

source env/bin/activate 

#### Установить зависимость от файла requirements.txt: 

python -m pip install --upgrade pip 

pip install -r requirements.txt 

#### Выполнить выборку: 

python manage.py migrate 

## Примеры. Некоторые примеры файлов к API. <img src ="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/>

#### Получение публикаций 

GET/api/v1/posts/ 

#### Создание публикации 

POST/api/v1/posts/ 

#### Получение комментариев 

GET/api/v1/posts/{post_id}/comments/ 

#### Добавление комментария 

POST/api/v1/posts/{post_id}/comments/ 

#### Получение списка доступных сообществ. 

GET/api/v1/groups/