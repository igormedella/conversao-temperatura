FROM node:14.17.5

#Criar diretorio da aplicação
WORKDIR /usr/src/app

#Instalar dependências de aplicativos
#Garantir que o package.json e o package-lock.json sejam copiados.
COPY package*.json ./

#Instala pacote npm
RUN npm install

COPY . .

EXPOSE 8080 

CMD ["node", "server.js"]
