FROM node
RUN mkdir /usr/backoffice
WORKDIR /usr/backoffice
COPY package.json /usr/backoffice
RUN npm install
COPY . /usr/backoffice
EXPOSE 4200
CMD ["npm", "start"]