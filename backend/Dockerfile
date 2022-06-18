FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=kweyuops
ENV MONGODB_PASSWORD=kweyu_pass
ENV MONGODB_URL=mongodb
ENV MONGODB_NAME=goals-dev

CMD ["npm", "start"]