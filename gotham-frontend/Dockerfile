FROM node:alpine
RUN mkdir /frontend
WORKDIR /frontend
COPY package.json /frontend/package.json
RUN npm install 
COPY . .
CMD ["npm",  "start" ]