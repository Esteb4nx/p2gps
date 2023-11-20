FROM mongo:3.4

MAINTAINER esteban.esparza@alu.uclm.es

RUN mkdir -p /usr/local/app
COPY drop/MongoRecords.js /usr/local/app/MongoRecords.js

CMD ["mongod", "--smallfiles", "--rest"]