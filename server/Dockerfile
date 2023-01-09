FROM node:14-slim 

WORKDIR /sever 

COPY ./package.json ./ 

RUN npm install 

COPY . .

EXPOSE 8000 

CMD [ "npm", "start" ]