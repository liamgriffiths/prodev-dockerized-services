FROM rackspacedot/python37

# Create app directory
WORKDIR /usr/src/ghi


# Bundle app source
COPY . .

EXPOSE 8080
CMD [ "python3", "server.py" ]