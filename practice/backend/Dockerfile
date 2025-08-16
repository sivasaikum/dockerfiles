FROM node:20
WORKDIR /app
COPY package.json /app
COPY *.js /app 
RUN npm install
ENV DB_HOST=mysql
CMD ["node", "index.js"]
