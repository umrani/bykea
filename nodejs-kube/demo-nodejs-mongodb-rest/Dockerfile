FROM node:10.13-alpine

RUN mkdir sample-app
COPY . /sample-app
WORKDIR /sample-app
#Install Nodemon Globally
RUN npm install nodemon -g
#Install library
RUN npm install
CMD ["nodemon"]
