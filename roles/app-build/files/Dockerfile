FROM node:14-alpine

# Create app directory
WORKDIR /usr/src

RUN apk add --no-cache git

RUN git clone -b front-only https://github.com/MoiseevDI/pdris-lab1.git app
WORKDIR /usr/src/app
RUN npm install
CMD [ "npm", "run", "build"]
