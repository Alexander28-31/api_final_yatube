# api_final
Cоздать и активировать окружающую среду:

python -m venv env
source env/bin/activate

Установить зависимость от файла requirements.txt:

python -m pip install --upgrade pip
pip install -r requirements.txt

Выполнить выборку:

python3 manage.py migrate

Запустить проект:

python3 manage.py runserver

Примеры. Некоторые примеры файлов к API.

Получение публикаций

http://127.0.0.1:8000/api/v1/posts/

Создание публикации

http://127.0.0.1:8000/api/v1/posts/

Получение комментариев

http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/

Добавление комментария

http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/

Получение списка доступных сообществ.

http://127.0.0.1:8000/api/v1/groups/


