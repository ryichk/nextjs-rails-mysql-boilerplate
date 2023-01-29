FROM node:18.12

ENV APP /usr/src/app
WORKDIR $APP

COPY package* $APP/
RUN npm install

COPY . $APP/

CMD ["npm", "run", "dev"]
