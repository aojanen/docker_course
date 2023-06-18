FROM node:16

WORKDIR /usr/src/app/

COPY ./example-frontend ./

EXPOSE 8686

RUN npm install

RUN npm run build

RUN npm install -g serve

# RUN serve -s -l 8686 build
