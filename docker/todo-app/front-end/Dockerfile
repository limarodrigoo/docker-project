FROM node:14-alpine as todofrontend
WORKDIR /
COPY package*.json ./
ADD node_modules.tar.gz ./
COPY . .
EXPOSE 3000
CMD ["npm", "start"]