django - python manage.py runserver
rabbitmq - docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:management
reids - docker run -it --rm --name redis -p 6379:6379 redis
flower - celery -A myshop flower
celery - celery -A myshop worker -l info
stripe - stripe listen --forward-to localhost:8000/payment/webhook/