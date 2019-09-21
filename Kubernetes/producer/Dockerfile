FROM node:carbon-alpine
CMD ['npm', 'start']
WORKDIR /app
EXPOSE 2829
COPY package*.json ./
RUN npm install
COPY . .
