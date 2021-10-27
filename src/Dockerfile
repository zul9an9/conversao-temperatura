# Contruir a imagem base
FROM node:16

# Criar o diretório
WORKDIR /usr/src/app

# Instalar dependencias
# Copiando os arquivos: package.json e package-lock.json 

COPY ./package*.json ./

# Instalar npm
RUN npm install

# Se vc esta construindo seu código para produção 
# RUN npm ci --only=production

# Copiar seu app
COPY . .
# expor a porta 8080 do app para acessar via browser: localhost:8080 
EXPOSE 8080
# executar o node com o arquivo server.js
CMD [ "node", "server.js" ]
