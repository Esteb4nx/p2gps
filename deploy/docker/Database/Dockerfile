FROM mongo:3.4

MAINTAINER esteban.esparza@alu.uclm.es

RUN mkdir -p /usr/local/data/db

COPY drop/* /usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]