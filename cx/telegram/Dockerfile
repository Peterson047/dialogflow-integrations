FROM node:16

# Define o diretório de trabalho dentro do contêiner
WORKDIR /app

# Copia os arquivos do projeto para o contêiner
COPY . .

# Instala as dependências do projeto
RUN npm install

# Expõe a porta que o servidor Node.js vai usar
EXPOSE 3000

# Comando para iniciar o servidor
CMD ["node", "server.js"] 
