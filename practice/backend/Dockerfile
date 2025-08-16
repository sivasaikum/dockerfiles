FROM node:20
WORKDIR /app
COPY package.json /app
COPY *.js /app 
RUN npm install
ENV DB_HOST=mysql
# ENV DB_HOST=localhost
CMD ["node", "index.js"]
