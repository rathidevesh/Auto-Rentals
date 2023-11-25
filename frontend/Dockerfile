FROM node:current-alpine
WORKDIR /usr/app/frontend
COPY . .
RUN npm install
RUN npm run build
EXPOSE 3000
ENV NODE_ENV PRODUCTION
CMD ["npx","serve","build"]