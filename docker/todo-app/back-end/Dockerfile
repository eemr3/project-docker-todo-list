FROM node:14-alpine
WORKDIR /back-end
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
ENTRYPOINT ["npm", "start"]