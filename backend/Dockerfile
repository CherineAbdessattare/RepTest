
FROM node:14


WORKDIR /usr/src/app

# Copiez les dépendances de build
COPY package*.json ./

# Installez les dépendances
RUN npm install


COPY . .

#  le port
EXPOSE 3030

# Commande de démarrage du backend
CMD ["node", "app.js"]
