FROM mongo:3.4

MAINTAINER esteban.esparza@alu.uclm.es

COPY drop/* usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]