FROM node:latest
WORKDIR /api
RUN apt install git -y
RUN git clone https://github.com/petrlr14/Register_API_PW0219
WORKDIR /api/Register_API_PW0219
RUN npm install
EXPOSE 3500
CMD ["npm", "start"]
