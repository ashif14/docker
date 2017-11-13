FROM mongo:latest

# Volume for mongodb data to persist
VOLUME [ "/mongodb1" ]

ADD ./mongod.conf /etc/mongod.conf

# Entrypoint
CMD [ "mongod", "-f", "/etc/mongod.conf" ]