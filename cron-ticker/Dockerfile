FROM node:19.2-alpine3.16

# cd app
WORKDIR /app

# dest /app
COPY app.js package.json ./

# node package manager
RUN npm install

# comando run de la imagen
CMD [ "node", "app.js" ]

