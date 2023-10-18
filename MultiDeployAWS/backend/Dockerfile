FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=shjneevn  
ENV MONGODB_PASSWORD=4nhy3u3m
ENV MONGODB_URL=cluster0.yq7rt.mongodb.net
ENV MONGODB_NAME=goals-dev

CMD ["npm", "start"]