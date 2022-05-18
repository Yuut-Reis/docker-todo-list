FROM node:14-alpine
WORKDIR /todo-app/front-end
COPY . .
EXPOSE 3000
ADD node_modules.tar.gz .
RUN ["npm", "start"]
