FROM python:3.9 AS builder
COPY requirements.txt .

RUN pip install -r requirements.txt

COPY ./src .

EXPOSE 5000
CMD [ "python", "./app.py" ]
