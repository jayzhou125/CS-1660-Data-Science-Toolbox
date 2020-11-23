FROM python:3
# FROM flask:latest

WORKDIR /code

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]

