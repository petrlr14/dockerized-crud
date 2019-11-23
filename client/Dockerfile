FROM node:latest
WORKDIR /client
RUN apt install git -y
RUN git clone https://github.com/petrlr14/Register_Client_PW0219
WORKDIR /client/Register_Client_PW0219
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]