# syntax=docker/dockerfile:1
FROM python:3.13.0a4-alpine3.19
WORKDIR /code
COPY ./shellyserver .
RUN pip install -r requirements.txt
EXPOSE 5500
COPY ./shellyserver .
CMD ["sh","start.sh"]
