Описание проекта:

Проект api_yatube - это API социальной сети yatube.

С помощью api_yatube можно запрашивать данные о постах, группах, комментариях в социальной сети Yatube, а также создавать новые.

Yatube - это учебный проект курса Python-разработчик от Яндекс Практикума.

Автор: Вера Сапожникова

Запуск проекта:

Клонировать репозиторий: git clone git@github.com:VeraSapozhnikova/api_final_yatube.git
Cоздать виртуальное окружение: python -m venv venv
Активировать виртуальное окружение: . venv/Scripts/activate
Установить зависимости: pip install -r requirements.txt
Выполнить миграции: python manage.py migrate
Запустить проект: python manage.py runserver