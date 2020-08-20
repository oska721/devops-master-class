FROM node:8.16.1-alpine
WORKDIR /app
COPY package.json /app
#COPY . /app   #moved to step 7
RUN npm install
EXPOSE 5000
COPY . /app
#CMD node index.js # if index.js doesnt change use ENTRYPOINT
ENTRYPOINT ["node", "index.js"]

#ENTRYPOINT ["node", "index.js"]
#COPY package.json /app
