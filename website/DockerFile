FROM node:22-alpine
WORKDIR /website
COPY package*.json ./
RUN npm install
COPY . .
# Maybe build to /website/dist
RUN npm run build
