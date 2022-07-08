FROM node:alpine
RUN mkdir /backend
WORKDIR /backend
COPY package.json /backend/package.json
RUN npm install 
COPY . .
CMD ["node", "index.js" ]