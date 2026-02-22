FROM node:20
WORKDIR /opt/server
EXPOSE 8080
COPY package.json .
COPY *.js .
RUN npm install
ENV REDIS_HOST="redis" \
    REDIS_HOST="catalogue" \
    MONGO_URL="8080"
CMD ["node", "server.js"]