# PROG_7_Django_4
Lab_7 with poll analytics

## Запуск
1. Открываем консоль в директории с mysite и requirements.txt
2. `py -m venv env`
3. `pip install -r requirements.txt`
4. `py mysite/manage.py runserver`
5. `127.0.0.1:8000` в браузере

## Polls
- `/polls/` - страница с голосованиями

## Analytics
- `/analytics/` - графики результатов голосований
- `/analytics/questions` - вывод данных голосованиях
- `/analytics/questions/<question_id>` - вывод данных конкретного голосования
- `/analytics/choices/` - вывод данных всех ответов на голосования
- `/analytics/choices/<question_id>` - вывод данных ответов на определенное голосование
