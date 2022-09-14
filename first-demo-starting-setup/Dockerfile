FROM node:14

# Create app directory

WORKDIR /app

# copy package.json and package-lock.json

COPY package.json .

# Install app dependencies

RUN npm install

# Bundle app source

COPY . .

EXPOSE 3000

CMD [ "node", "app.mjs" ]
