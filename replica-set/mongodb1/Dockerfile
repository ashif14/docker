FROM mongo:latest

# Volume for mongodb data to persist
# VOLUME [ "/mongodb0"]
# Volume for log data to persist
# VOLUME [ "/config/mongodb" ]

# Add configuration file for mongod
ADD ./mongod.conf /etc/mongod.conf

# Entrypoint, start with mongod.conf configuration file
CMD [ "mongod", "-f", "/etc/mongod.conf" ]