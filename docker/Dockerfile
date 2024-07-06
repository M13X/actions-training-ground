FROM node:16

ENV MONGODB_CONNECTION_PROTOCOL mongodb+srv
ENV MONGODB_DB_NAME database_demo
ENV MONGODB_CLUSTER_ADDRESS learning-cluster.aecfiri.mongodb.net
ENV MONGODB_USERNAME name
ENV MONGODB_PASSWORD v145m-8902v6iftajnh68

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm", "start"]