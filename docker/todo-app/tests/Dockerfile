FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests
ADD /node_modules.tar.gz ./
COPY . .
# RUN npm install
# RUN docker build -t todobackend ./todo-app/front-end
EXPOSE 3000
CMD ["npm", "test"]
