### Djangoプロジェクトの作成
docker-compose run django django-admin.py startproject tts_django ./tts_django

### collectstatic
docker-compose run django /project/tts_django/manage.py collectstatic

