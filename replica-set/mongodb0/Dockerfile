FROM mongo:latest

# Volume for mongodb data to persist
VOLUME [ "/mongodb0" ]

ADD ./mongod.conf /etc/mongod.conf

# Entrypoint
CMD [ "mongod", "-f", "/etc/mongod.conf" ]