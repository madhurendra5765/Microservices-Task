FROM node:26-alpine3.23
WORKDIR /app
COPY . .
RUN npm install
ENV PORT=3000
ENV MONGO_URI=""
EXPOSE 3001
CMD [ "node", "app.js" ]
