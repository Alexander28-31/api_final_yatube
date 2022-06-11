
# api_final  <img src ="https://img.shields.io/badge/django%20rest-ff1709?style=for-the-badge&logo=django&logoColor=white " />
API для проекта Yatube. Домашняя работа YandexPracticum по теме API. 


## Как запустить проект <img src = "https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" /> 

```
python -m venv env  
```
```
source env/bin/activate  
```

#### Установить зависимость от файла requirements.txt: 

```
python -m pip install --upgrade pip 
``` 
```
pip install -r requirements.txt  
```

#### Выполнить выборку:

```
python manage.py migrate  
```

## Примеры. Некоторые примеры файлов к API. <img src ="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/>

#### Получение публикаций 
```
GET http://127.0.0.1:8000/api/v1/posts/1/
```

#### Создание публикации 
```

POST http://127.0.0.1:8000/api/v1/posts/ 
```
```
{
"text": "112"
}
```

#### Получение комментариев 

```
GET http://127.0.0.1:8000/api/v1/posts/1/comments/ 
```

#### Добавление комментария 

```
POST http://127.0.0.1:8000/api/v1/posts/1/comments/1/
```
```
{
"text": "Ты хорош"
}
```

#### Получение списка доступных сообществ.

```
GET http://127.0.0.1:8000/api/v1/groups/
```