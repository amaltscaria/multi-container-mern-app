FROM node

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

ENV PORT=80

EXPOSE $PORT

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret

CMD ["npm","start"]