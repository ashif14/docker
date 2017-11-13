FROM mongo:latest

# Volume for mongodb data to persist
VOLUME [ "/mongodb" ]

# Volume for log data to persist
# VOLUME [ "/config/mongodb" ]

ADD ./mongod.conf /etc/mongod.conf

# Entrypoint
CMD [ "mongod", "-f", "/etc/mongod.conf" ]