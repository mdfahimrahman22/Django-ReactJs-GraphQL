FROM python:3
ENV PYTHONUNBUFFERED 1
WORKDIR /todo_app_django

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY .. ..
CMD ["python","manage.py","runserver","0.0.0.0:8000"]