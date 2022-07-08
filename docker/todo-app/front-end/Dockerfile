FROM node:14-alpine
WORKDIR /docker/todo-app/front-end
ADD /node_modules.tar.gz ./
COPY . .
# RUN npm install
# RUN docker build -t todobackend ./todo-app/front-end
EXPOSE 3000
CMD ["npm", "start"]
