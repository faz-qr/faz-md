FROM fusuf/whatsasena:latest

RUN git clone https://github.com/inrlwabot/Faz /skl/faz
WORKDIR /skl/Faz
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
