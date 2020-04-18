FROM node:12.16.1

# Create app directory
RUN mkdir -p /usr/src/smart-brain-server
WORKDIR /usr/src/smart-brain-server

# Install app dependencies
COPY ./ ./
RUN npm install

CMD ["/bin/bash"]