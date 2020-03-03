FROM andresvidal/rpi3-mongodb3:latest

RUN rm -f \data\db\mongod.lock && \
    mongod --repair

CMD ["mongod", "--journal"]
