FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=root
ENV MONGODB_PADDWORD=secret
# VOLUME [ "/app/node_modules" ]

CMD [ "npm", "start" ]