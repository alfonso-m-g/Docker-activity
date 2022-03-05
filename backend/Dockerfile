FROM node:10.15.3-alpine
WORKDIR /home/node
COPY index.js .
RUN npm init -y
RUN npm install express --save
EXPOSE 5000
CMD ["node" , "index.js"]