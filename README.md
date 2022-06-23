Django-Celery-Redis simple app

Docker:
-------

	Create new folder "DjangoCeleryRedis" and open it:
	git clone https://github.com/marcin86junior/CeleryRedisDjango.git .
	docker-compose up

    Open cmd on 2nd terminal: (django name in container)
    docker exec it django sh
    python mange.py shell
    from app.tasks import add
    add.delay(2, 2)

    In 1st docker-compose terminal:
    "4"



