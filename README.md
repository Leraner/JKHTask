### Этот репозиторий содержит тестовое задание

### Установка
```bash
# Убедиться, что активировано виртуальное окружение с python 3.7.6 и запущен redis

git clone https://github.com/Leraner/TestTaskJKH.git # копировать проект локально
pip install -r requirements.txt  # установка зависимостей python
python manage.py migrate # миграция (подготовка) базы данных
python manage.py prepare_finance # создать тестовые данные
python manage.py  prepare_account # создать список проверенных почтовых ящиков
```

### Запуск
```bash
python manage.py runserver
```

### Pytest
```bash
pytest
```

# 🌟
