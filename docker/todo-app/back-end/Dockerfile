#https://blog.rocketseat.com.br/dockerfile-principais-comandos-para-criar-a-receita-da-imagem/#:~:text=COPY%20e%20ADD&text=Diferen%C3%A7a%20%C3%A9%20que%20ADD%20copia,para%20arquivos%20remotos%20ou%20compactados.
FROM node:14-alpine
WORKDIR /docker/todo-app/back-end
ADD /node_modules.tar.gz ./
COPY . .
RUN npm install
EXPOSE 3001
CMD ["npm", "start"]