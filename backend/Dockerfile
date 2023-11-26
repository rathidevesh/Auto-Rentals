FROM node:current-alpine
WORKDIR /usr/app/backend
COPY package*.json .
RUN npm install
COPY . .
ENV PORT = 5000
EXPOSE 5000
CMD ["node","index.js"]