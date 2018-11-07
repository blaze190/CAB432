FROM node:6

WORKDIR /graphPlease

COPY package.json /graphPlease

RUN npm install

COPY . /graphPlease

CMD node 2ndass/bin/www

EXPOSE 3001
