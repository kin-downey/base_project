FROM python:latest

COPY ./backend/requirements.txt /run

COPY ./backend/entrypoint.sh /run

WORKDIR /run

RUN pip install -r requirements.txt

CMD [ "sh", "entrypoint.sh" ]