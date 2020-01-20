FROM node:13.6.0

# set work directory
WORKDIR /app

# copy project
COPY . /app/

# install dependencies
RUN npm i npm@6.9.1-next.0
RUN npm install

# build project
RUN npm run build
