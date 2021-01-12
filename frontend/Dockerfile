FROM node:15-alpine3.10

WORKDIR /src/frontend

COPY package.json /src/frontend
RUN npm install
COPY . /src/frontend

EXPOSE 3000
CMD ["npm", "start"]