FROM node:14-alpine3.17
WORKDIR /server
EXPOSE 3001
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT ["npm", "start"]
