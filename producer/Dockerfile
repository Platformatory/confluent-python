FROM python:3.8-slim-buster

WORKDIR /app

COPY . .
RUN pip install -r requirements.txt

RUN chmod u+x main.py

CMD ["/app/main.py", "broker:29092", "test"]