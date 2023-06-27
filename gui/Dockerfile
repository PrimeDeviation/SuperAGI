FROM node:lts

WORKDIR /app

COPY package*.json ./
COPY . .
RUN npm ci
RUN npm install react-markdown

CMD ["npm", "run", "dev"]