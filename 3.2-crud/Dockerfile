FROM python:3.10

WORKDIR /stocks_products

COPY ./stocks_products /stocks_products

RUN pip install -r /stocks_products/requirements.txt

EXPOSE 8000

RUN python manage.py migrate

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
