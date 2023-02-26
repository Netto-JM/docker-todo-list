FROM node:14-alpine3.17
WORKDIR /frontend
EXPOSE 3000
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT ["npm", "start"]
