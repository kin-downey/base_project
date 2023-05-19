FROM node:16

COPY ./frontend/entrypoint.sh /app/

RUN npm install -g @vue/cli

WORKDIR /app

CMD [ "sh", "entrypoint.sh" ]