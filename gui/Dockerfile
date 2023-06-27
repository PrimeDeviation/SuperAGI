FROM node:lts AS deps

WORKDIR /app

COPY package*.json ./
RUN npm ci
RUN npm install react-markdown

COPY . .

CMD ["npm", "run", "dev"]